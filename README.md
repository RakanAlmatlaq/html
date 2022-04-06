# <!DOCTYPE html>
<html>
    <head>
<title>Academy Tuwaiq</title>
<style>
    table, th, td {
        border: 2px solid blue;
    }
</style>
    </head>
<body dir="rtl">

    <h1>H1</h1><!--comment-->
    <h2>H2</h2>
<p>
    <b>HTML</b> HTML is the <i> standard </i>standard <em> markup </em>markup language 
    for creating <strong> Web</strong> pages
</p>
<p>
    <b>
From 12:00<sub>pm</sub> to 4:00 <sub>pm</sub><br>
From 1:00<sub>pm</sub> to 2:00 <sub>pm</sub>
    </b><br>
</p>

<p>
1<sup>st</sup> level<br>
2<sup>nd</sup> level
</p><hr><hr>

<h2>W3school</h2>
<ol type="A">
    <li>First</li>
    <li>Second</li>
    <li>Third</li>
</ol>

<h2>What is HTML?</h2>
<ul type="circle">
    <li>HTML stands for Hyper Text Markup Language</li>
    <li>HTML consists of a series of elements</li>
    <li>HTML elements tell the browser how to display the content</li>
</ul>
    
<p>Click to open Google
    <a href="https://www.google.com/"> HERE</a> 
</p>

<h1>Picture</h1>
<img src="html.PNG" height="150" width="150" alt="html picture"> 

<H1>Video</H1>
<video width="500" height="500" controls>
    <source src="" type="video/mp4">
    Sorry can't play the video 
</video>

<h1>Audio</h1>
<audio controls>
    <source src="" type="audio/mp3">
</audio>

<h1>Table</h1>
<table>
    <caption>Learning</caption>
    <tr>
        <th>Day</th>
        <th>Place</th>
    </tr>
    <tr>
        <td>Sun & Mon</td>
        <td>Class A</td>
    </tr>
    <tr>
        <td>Tu & Wed</td> 
        <td>Class B</td>
    </tr>
    <tr>
        <td colspan="2">Th 
        Online</td>
    </tr>
</table><hr><hr>

<h2>Sign up</h2>
<form>
    <label for="name">User Name</label>
    <input type="text" id="name">

    <p>Gender</p>
    <input type="radio" id="male" name="gender">
    <label for="male">Male</label>
    <input type="radio" id="female" name="gender">
    <label for="female">Female</label>

    <p>Where do you hear about us:</p>
    <input type="checkbox" id="friend" name="friend">
    <lable for="friend">Friend</lable><br>
    <input type="checkbox" id="google" name="google">
    <lable for="google">Google</lable><br>
    <input type="checkbox" id="facebook" name="facebook">
    <lable for="facebook">Facebook</lable><br>

    <label for="city">Choose your city : </label>
    <select id="city" name="city">
        <option value="Riyadh">Riyadh</option>
        <option value="Jeddah">Jeddah</option>
        <option value="Dammam">Dammam</option>
    </select><br><br>

    <input type="submit" value="Submit">

</form>

</body>
    </html>
