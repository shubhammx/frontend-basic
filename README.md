# frontend-basic
# 🌐 Personal Portfolio (HTML &amp; CSS)  This is my personal portfolio website created using only HTML and CSS to showcase my skills and projects.📌 Purpose This project is built to practice frontend basics and create a personal online presence.link: http://127.0.0.1:5500/personal%20porfolio.html
HTML CODE:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MY portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!--header-->
    <h1><center>shubham sahay's portfolio</center></h1> 
    <p><center>welcome to my personal portfolio website</center></p>
    <hr>
    <!--about me-->
    <h2><center>ABOUT ME</center></h2>
    <img src="shubham.jpg" class="profile-img" alt="profile-img">
    <p><center>Hello my name is shubham sahay.i am learning web development.
        i am intrested in html,css,java and javascript and want to become a perofesional web developer.
    </center></p>
    <hr>
    <!-- skills-->
    <h2> my skills</h2>
    <ul>
        <li>html</li>
        <li>basic css</li>
        <li>c programing</li>
        <li>problem solving</li>   
    </ul>
    <hr>
    <!--projects-->
    <h2>projects</h2>
    <ol>
        <li>google homepage clone</li>
        <li>student registration form</li>
        <li>resturant menu page</li>
    </ol>
    <hr>
    <!--education-->
    <h2>education</h2>
    <table border="1">
        <tr>
            <th>year</th>
            <th>course</th>
            <th>institute</th>
        </tr>
        <tr>
            <td>2026</td>
            <td>btech</td>
            <td>haldia institute of technology</td>
        </tr>
        <tr>
            <td>2022</td>
            <td>12th</td>
            <td>dps</td>
        </tr>
    </table>
    <hr> 
    <!--contact-->
    <h2>contact me</h2>
    <form>
        name:<br>
        <input type="name"placeholder='write your name here'><br><br>
        e-mail:<br>
        <input type="email"placeholder='your email address'><br><br>
        message:<br>
        <textarea rows="5"cols="30"placeholder='write something here'></textarea><br><br>
        <input type="submit" value="send message">
    </form>
    <hr>
    <!--footer-->
    <p>@ 2026 shubham sahay| All rights reserved.</p>

CSS code:
.profile-img{
    width:150px;
    height:150px;
    border-radius:50%;
    object-fit:cover;
    display:block;
    margin:20px auto;
    border:3px solid black;
}
body{
    background-color:skyblue;
    h1{
        color:blue;
    }
    p{
        font-size:18px;
        color:rgb(15, 15, 180);
    }
}
</body>

</html>
