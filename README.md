# Ex01 Portfolio
## Date:26/072026

## AIM
To create a Portfolio using HTML and CSS.

## ALGORITHM
### STEP 1
Create an HTML file (index.html)

### STEP 2
Create a CSS file (style.css)

### STEP 3
Include a navigation bar with links to different sections.

### STEP 4
Add structured sections for introduction, about, projects, and contact details.

### STEP 5
Define global styles for fonts, colors, and layout.

### STEP 6
Style the header, navigation bar, and sections.

### STEP 7
Use Flexbox or CSS Grid for layout design.

### STEP 8
Add hover effects and transitions for interactivity.

### STEP 9
Add Images and Media.

### STEP 10
Use optimized images for a professional look.

### STEP 11
Open the HTML file in a browser to check layout and functionality.

### STEP 12
Fix styling issues and refine content placement.

### STEP 13
Deploy the Portfolio.

### STEP 14
Upload to GitHub Pages for free hosting.

## PROGRAM
```
!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio</title>
<link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <nav>
        <h2>My Portfolio</h2>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section id="home" class="home">
    <img src="profile.jpg" alt="Profile">
    <h1>Hello, I'm <span>kavyareddy</span></h1>
    <p>Web Developer | Student | Programmer</p>
    <button onclick="showMessage()">Hire Me</button>
</section>

<section id="about">
    <h2>About Me</h2>
    <p>
        I am a passionate web developer interested in HTML, CSS,
        JavaScript, Python, and Machine Learning. I enjoy creating
        responsive and user-friendly websites.
    </p>
</section>

<section id="skills">
    <h2>Skills</h2>
    <div class="cards">
        <div class="card">HTML</div>
        <div class="card">CSS</div>
        <div class="card">JavaScript</div>
        <div class="card">Python</div>
        <div class="card">C Programming</div>
        <div class="card">Machine Learning</div>
    </div>
</section>

<section id="projects">
    <h2>Projects</h2>

    <div class="project">
        <h3>Portfolio Website</h3>
        <p>Responsive personal portfolio using HTML, CSS & JavaScript.</p>
    </div>

    <div class="project">
        <h3>Weather App</h3>
        <p>Weather application using JavaScript API.</p>
    </div>

    <div class="project">
        <h3>Student Management System</h3>
        <p>Python project for managing student records.</p>
    </div>

</section>

<section id="contact">
    <h2>Contact</h2>
    <p>Email: kavyareddy@gmail.com</p>
    <p>Phone: +91 7337329602</p>
</section>

<footer>
    <p>© 2026 kavya reddy | All Rights Reserved</p>
</footer>

<script src="script.js"></script>
</body>
</html>
```
```
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
scroll-behavior:smooth;
}

body{
background:#f4f4f4;
color:#333;
}

header{
background:#0d47a1;
padding:15px;
position:fixed;
width:100%;
top:0;
}

nav{
display:flex;
justify-content:space-between;
align-items:center;
width:90%;
margin:auto;
}

nav h2{
color:white;
}

nav ul{
display:flex;
list-style:none;
}

nav ul li{
margin-left:20px;
}

nav ul li a{
text-decoration:none;
color:white;
font-weight:bold;
}

section{
padding:90px 10%;
}

.home{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
background:#1976d2;
color:white;
}

.home img{
width:180px;
height:180px;
border-radius:50%;
border:5px solid white;
margin-bottom:20px;
object-fit:cover;
}

.home span{
color:yellow;
}

button{
padding:12px 30px;
margin-top:20px;
background:white;
color:#1976d2;
border:none;
border-radius:5px;
font-size:16px;
cursor:pointer;
}

button:hover{
background:yellow;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(150px,1fr));
gap:20px;
margin-top:20px;
}

.card{
background:white;
padding:20px;
text-align:center;
border-radius:10px;
box-shadow:0 5px 10px rgba(0,0,0,.2);
transition:.3s;
}

.card:hover{
transform:scale(1.05);
background:#1976d2;
color:white;
}

.project{
background:white;
padding:20px;
margin-top:20px;
border-radius:10px;
box-shadow:0 5px 10px rgba(0,0,0,.2);
}

footer{
background:#0d47a1;
color:white;
text-align:center;
padding:20px;
}
```
```
function showMessage(){
    alert("Thank you for visiting my portfolio!");
}
```
## OUTPUT
<img width="1792" height="900" alt="image" src="https://github.com/user-attachments/assets/e7205e3c-fc71-4a30-acf5-f5e9c852b6f0" />
<img width="1787" height="795" alt="image" src="https://github.com/user-attachments/assets/43d46587-40c9-4859-bcb0-664b1529a973" />
<img width="1781" height="871" alt="image" src="https://github.com/user-attachments/assets/6b2e5515-df77-4f8a-b507-f233871dae40" />
<img width="1815" height="898" alt="image" src="https://github.com/user-attachments/assets/e1af84be-28ca-46f1-8dc1-c4df68a8b91a" />

## RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
