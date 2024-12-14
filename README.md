<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Aakash Kumar</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            position: relative;
            background: url('aakash.jpg') no-repeat center center/cover;
            color: black;
            text-align: center;
            padding: 4rem 2rem;
            box-shadow: inset 0 0 0 1000px rgba(255, 255, 255, 0.7);
        }

        header .profile-picture {
            display: block;
            margin: 2rem auto 1rem;
            border-radius: 50%;
            width: 200px;
            height: 200px;
            object-fit: cover;
            border: 4px solid #333;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0.5rem 0;
        }

        header p {
            font-size: 1.2rem;
            margin: 0;
        }

        .container {
            max-width: 1200px;
            margin: 2rem auto;
            padding: 2rem;
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }

        .section {
            margin-bottom: 2rem;
        }

        .skills, .projects {
            display: flex;
            flex-wrap: wrap;
            gap: 1rem;
        }

        .skill, .project {
            background: #f0f0f0;
            border: 1px solid #ddd;
            border-radius: 8px;
            padding: 1rem;
            flex: 1 1 calc(33.333% - 2rem);
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            text-align: center;
        }

        .skill h3, .project h3 {
            margin: 0.5rem 0;
        }

        .skill:hover, .project:hover {
            background: #e3f2fd;
            border-color: #64b5f6;
            transform: translateY(-5px);
            transition: 0.3s ease;
        }

        footer {
            background-color: #f0f0f0;
            color: #666;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        a {
            color: #1e88e5;
            text-decoration: none;
        }

        a:hover {
            text-decoration: underline;
        }

        .contact-links a {
            display: inline-block;
            margin: 0.5rem;
            padding: 0.5rem 1rem;
            background-color: #e0e0e0;
            color: #333;
            border-radius: 5px;
            text-decoration: none;
            border: 1px solid #ccc;
            transition: 0.3s;
        }

        .contact-links a:hover {
            background-color: #64b5f6;
            color: white;
            transform: scale(1.1);
        }

        @media (max-width: 768px) {
            .skill, .project {
                flex: 1 1 100%;
            }

            header {
                padding: 2rem;
            }

            header h1 {
                font-size: 2rem;
            }

            header p {
                font-size: 1rem;
            }

            header .profile-picture {
                width: 150px;
                height: 150px;
            }
        }
    </style>
</head>
<body>
    <header>
        <img src="pro1.jpg" alt="Aakash Kumar" class="profile-picture">
        <h1>Aakash Kumar</h1>
        <p>B.Tech CSE | KIET Ghaziabad (2024 - 2028)</p>
    </header>

    <div class="container">
        <section class="section">
            <h2>About Me</h2>
            <p>Hi, I am Aakash Kumar. I am a Computer Science student proficient in multiple programming languages and 3D design. I am fluent in Hindi, English, and French.</p>
        </section>

        <section class="section">
            <h2>Skills</h2>
            <div class="skills">
                <div class="skill">
                    <h3>C Language</h3>
                </div>
                <div class="skill">
                    <h3>Python</h3>
                </div>
                <div class="skill">
                    <h3>HTML & CSS</h3>
                </div>
                <div class="skill">
                    <h3>JavaScript</h3>
                </div>
                <div class="skill">
                    <h3>3D Design Autodesk Inventor </h3>
                </div>
                <div class="skill">
                    <h3>My SQL </h3>
                </div>
               
            </div>
        </section>

        <section class="section">
            <h2>Projects</h2>
            <div class="projects">
                <div class="project">
                    <h3>Campus Bazar Website</h3>
                    <a href="#" target="_blank">View Project</a>
                </div>
                <div class="project">
                    <h3>360 Degree Rotate Mobile Stand Design</h3>
                    <a href="#" target="_blank">View Design</a>
                </div>
            </div>
        </section>

        <section class="section">
            <h2>Contact Me</h2>
            <p>You can reach out to me on the following platforms:</p>
            <div class="contact-links">
                <a href="linkedin.com/in/aakash-kumar-6a3222314">LinkedIn</a>
                <a href="#">Instagram</a>
                <a href="#">WhatsApp</a>
                <h3 >Phone no. : +917505278027 <br> Email id : aakash.2428cse2420@kiet.edu <br>Email id    : 2020aakashbaghel@gmail.com</h3>
            </div>
        </section>
    </div>

   
</body>
</html>
