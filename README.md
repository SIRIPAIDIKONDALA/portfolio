<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background-color: #666;
            padding: 10px 0;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 10px 20px;
        }
        main {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            padding: 20px;
        }
        .sidebar {
            flex: 1;
            padding: 20px;
        }
        .content {
            flex: 3;
            background-color: #fff;
            padding: 20px;
            margin-bottom: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 20px;
        }
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 0 auto;
            display: block;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Portfolio</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#resume">Resume</a>
        <a href="#certifications">Certifications</a>
        <a href="#contact">Contact Us</a>
        <a href="#skills">Skills</a>
    </nav>
    <main>
        <div class="sidebar">
            <img class="profile-pic" src="subbupic.jpg" alt="Profile Picture">
        </div>
        <div class="content" id="about">
            <h2>About Me</h2>
            <p> I am a passionate web developer student with a keen interest in front-end development.
        I have experience working with HTML, CSS, and JavaScript, and I love creating
        beautiful and interactive user interfaces. In my free time, I enjoy learning
        new technologies and expanding my skill set. I am also a team player and thrive
        in collaborative environments where I can contribute my creativity and problem-solving
        skills. Feel free to explore my portfolio and get in touch with me if you have
        any questions or opportunities for collaboration.</p>
        </div>
        <div class="content" id="resume">
            <h2>Resume</h2>
            <p>Add your resume content here.</p>
        </div>
        <div class="content" id="certifications">
            <h2>Certifications</h2>
            <p>Add your certifications here.</p>
        </div>
        <div class="content" id="contact">
            <h2>Contact Us</h2>
            <p>Add your contact information here.</p>
        </div>
        <div class="content" id="skills">
            <h2>Skills</h2>
            <p>Add your skills here.</p>
        </div>
    </main>
    <footer>
        &copy; 2024 My Portfolio. All rights reserved.
    </footer>
</body>
</html>