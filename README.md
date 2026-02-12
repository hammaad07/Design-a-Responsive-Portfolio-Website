<!DOCTYPE html>
<html>
<head>
    <title>Simple Portfolio</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial;
            text-align: center;
        }

        header {
            background: #333;
            color: rgb(0, 187, 255);
            padding: 15px;
        }

        nav a {
            color: rgb(255, 255, 255);
            margin: 0 10px;
            text-decoration: none;
        }

        section {
            padding: 40px 20px;
        }

        .skills span {
            display: inline-block;
            background: rgb(0, 119, 182);
            color: white;
            padding: 5px 10px;
            margin: 5px;
            border-radius: 5px;
        }

        .project {
            background: rgb(181, 201, 198);
            margin: 10px auto;
            padding: 15px;
            width: 80%;
            border-radius: 5px;
        }

        footer {
            background: rgb(51, 51, 51);
            color: white;
            padding: 10px;
        }

        @media (max-width: 600px) {
            .project {
                width: 95%;
            }
        }
    </style>
</head>

<body>

<header>
    <h2>HAMMAAD KHAN I</h2>
    <p>Portfolio</p>
    <img src="download.jpg" alt="photo">

    <nav>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#contact">Contact</a>
    </nav>
</header>


<section id="about">
    <h3>About Me</h3>
    <p>Currently exploring the world of web development and loving every step</p>
</section>
<hr>
<section id="skills" class="skills">
    <h3>Skills</h3>
    <span>HTML</span>
    <span>CSS</span>
    <span>JavaScript</span>
</section>
<hr>
<section id="projects">
    <h3>Projects</h3>
    <div class="project">Portfolio Website</div>
    
</section>
<hr>

<h2>Contact me</h2>

 
         <p>
            Email:
            <a href="hammaadkhani.cs25@bitsathy.ac.in">
                hammaadkhani.cs25@bitsathy.ac.in
            </a>
         </p>
         Phone Number:
            <a href="8825459173">
                8825459173

            </a>
        </p>


</body>
</html>
