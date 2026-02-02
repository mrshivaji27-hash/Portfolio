# Ex01 Portfolio
## Date: 2/2/2026
## Developed by: k.shivaji
## Reg no: 212224233002


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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Portfolio</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
        }

        nav a {
            margin-right: 15px;
            text-decoration: none;
            color: blue;
            cursor: pointer;
        }

        section {
            display: none;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<h1>My Portfolio</h1>

<nav>
    <a onclick="openSection('home')">Home</a>
    <a onclick="openSection('about')">About</a>
    <a onclick="openSection('projects')">Projects</a>
    <a onclick="openSection('contact')">Contact</a>
</nav>

<section id="home">
    <h2>Home</h2>
    <p>
        Welcome to my portfolio website. This page gives a short overview
        about who I am and what I do.
    </p>
</section>

<section id="about">
    <h2>About Me</h2>
    <p>
        I am a student who is learning web development. I enjoy creating
        simple websites using HTML, CSS, and basic JavaScript.
    </p>
</section>

<section id="projects">
    <h2>Projects</h2>
    <p>
        Below are some of the projects I have worked on:
    </p>
    <ul>
        <li>Personal portfolio website</li>
        <li>Simple calculator</li>
        <li>Basic form validation project</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>
        You can contact me using the information below:
    </p>
    <p>Email: sivaji69@gmail.com</p>
</section>

<script>
    function openSection(id) {
        document.getElementById("home").style.display = "none";
        document.getElementById("about").style.display = "none";
        document.getElementById("projects").style.display = "none";
        document.getElementById("contact").style.display = "none";

        document.getElementById(id).style.display = "block";
    }

    openSection("home");
</script>

</body>
</html>
```

## OUTPUT
<img width="1920" height="1200" alt="Screenshot 2026-02-02 134613" src="https://github.com/user-attachments/assets/0b6ab633-0500-4651-a979-0b87bb05e5fe" />
<img width="1920" height="1200" alt="Screenshot 2026-02-02 134629" src="https://github.com/user-attachments/assets/e0cf884c-a9c7-4ec9-a0b2-575ffe91de2a" />
<img width="1920" height="1200" alt="Screenshot 2026-02-02 134638" src="https://github.com/user-attachments/assets/9f042787-5def-499c-bbd8-d33af3f53137" />
<img width="1920" height="1200" alt="Screenshot 2026-02-02 134649" src="https://github.com/user-attachments/assets/a9188abd-2f2a-4f68-802f-32e7b1b39962" />



 RESULT
The program for creating Portfolio using HTML and CSS is executed successfully.
