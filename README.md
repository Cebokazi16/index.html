<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>My Portfolio</title>
<meta name="author" content="name">
<meta name="description" content="description here">
<meta name="keywords" content HTML, CSS, JAVASCRIPT ="keywords,here">
<link rel="stylesheet" href="stylesheet.css" type="text/css">
<style>
<style>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: mistyrose;
}
li {
    float: left;
}

li a {
     display: block;
     color: indianred;
     text-align: centre;
     padding: 14px 16px;
     text-decoration: none;
}

li a:hover:not(.active) {
          background-color: none;
}

.active {
     background-color: steelblue;
     }
     
{
 box-sizing: border-box;
}
* {
 box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial;
  margin: 0;
}

/* Header/logo Title */
.header {
  padding: 60px;
  text-align: center;
  background: #1abc9c;
  color: white;
}

/* Style the top navigation bar */
.navbar {
  display: flex;
  background-color: #333;
}

/* Style the navigation bar links */
.navbar a {
  color: white;
  padding: 14px 20px;
  text-decoration: none;
  text-align: center;
}

/* Change color on hover */
.navbar a:hover {
  background-color: white;
  color: black;
}

/* Column container */
.row {  
  display: flex;
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: #ddd;
}

/* Responsive layout - when the screen is less than 700px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 700px) {
  .row, .navbar {   
    flex-direction: column;
  }
}
</style>
</head>
<body>

<!-- Note -->
<font color="MistyRose"><div style="background:black;padding:5px">
  <h4 style="text-align:center">Cebo's Page😎.</h4>
</div></font>

<!-- Header -->
<div class="header">
  <h1>My Portfolio</h1>
  <p>The<b> Solution</b> to your Web Designing.</p>
</div>

<!-- Navigation Bar -->
<div class="navbar">
  <a href="/">Home</a>
  <a href="#about">About</a>
  <a href="#hobbies">Hobbies</a>
  <a href="#projects">Projects</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
</div>

<!-- The flexible grid (content) -->
<div class="row">
  <div class="side">
    <h2>About Me</h2>
    <ol><img src="/storage/emulated/0/SHAREit/pictures/snapchat/Snapchat-322907985.jpg" height="300" width="200"></ol>
    <p><h5>Hi there! My name is Cebokazi Makasi and welcome to my portfolio page. Feel free to look around!</h5></p>
    <p>About two weeks ago I started the Codetelligent classes where I was introduced to 'coding' for the first time. When I heard about these classes I thought to myself "aarg... I just want to be busy" because I was just sitting at home doing nothing(since I'm fresh from high school).</p>
    <p>I was not really excited about this because I heard someone saying coding and interneting is extremely difficult. I then tried building my first page using HTML and as I familiarised myself with HTML languages my feeling of excitement revived😅! It is, though, a challenging path to take but what's better than trying? I cannot wait to experience and do more and finally going to a higher institution to study the fields of Web Development further!</p>
    <h2>Hobbies</h2>
    <p><h6>Besides learning to become a professional Web Designer,I do enjoy : </h6></p>
    <li>Singing</li>
    <li>Cooking</li>
    <li>Playing Rugby (though I don't look like I play but heeeeyyyy I do!).</li> 
    <ol><img src="/storage/emulated/0/Pictures/facebook/FB_IMG_15984510937612675.jpg" height="300" width="200"></ol>
  </div>
  </div>
  <div class="main">
    <h2>Projects</h2>
    <h5>Project 1</h5>
    <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout...</p>
     <p><a href="Lorem Ipsum is that it has a more-or-less">See more</a></p>
    <br>
    <h5>Project 2</h5>
    <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution...</p>
    <p><a href="Lorem Ipsum is that it has a more-or-less">See more</a></p>
    <h5>Project 3</h5>
    <p>It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution.</p>
    <h2>Skills</h2>
    <li>Applying HTML and CSS</li>
  </div>
</div>

<!-- Footer -->
<div class="footer">
  <ul>
  <h2>Contact</h2>
  <p>Cell : <a href="cell:071 268 8511">0712688511</a></p>
  
  <p>Email : <a href="mail to: cebokazimakasi@gmail.com">cebokazimakasi@gmail.com</a></p>
  </li>
  </ul>
  <ul>
  <p>WhatsApp: <a href="https://wa.link/uo3p7">WhatsApp</a></p>
  <p>Facebook: <a href="m.facebook.com">Cebo Kazee</a></p>
  <h3>Address</h3>
  <p>12123 Flat 49 Mpunzi Crescent</p>
  <p>Lower Cross Roads</p>
  <p>Cape Town</p>
  <p>7750</p>
  </li>
  </ul>
  <p>&copy; 2020-Cebokazi Makasi-All rights reserved</p>
</div>

</body>
</html>
