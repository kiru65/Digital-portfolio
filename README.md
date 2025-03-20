# Digital-<!DOCTYPE html>
<html>
<head>
    <title>Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: deeppink;
        }

        header {
            background-color: purple;
            color: #fff;
            text-align: center;
            padding: 2rem 0;
            position: relative; /* Add this */
        }

        .header-content h1 {
            font-size: 2.5rem;
        }

        /* Add styles for the round profile picture */
        .profile-picture {
            width: 100px; /* Adjust the size as needed */
            height: 100px;
            border-radius: 75%; /* Create a circular shape */
            object-fit: cover; /* To ensure the image fills the circular area */
            position: absolute; /* Add this */
            top: 75px; /* Adjust top position as needed */
            left: 75px; /* Adjust left position as needed */
        }

        nav {
            background-color: #333;
            color: #fff;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 20px;
        }

        nav ul li a {
            text-decoration: none;
            color: #fff;
        }

        .section-content {
            background-color:pink;
            padding: 2rem;
            margin: 1rem;
            border-radius: 20px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: justify;
        }

        .download-button {
            background-color: #333;
            color: #fff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 20px;
            display: inline-block;
            margin-top: 10px;
            align-self: center;
        }

        .download-button:hover {
            background-color: #555;
        }

        footer {
            text-align: center;
            padding: 1rem 0;
            background-color: #333;
            color: #fff;
        }

        ul {
            list-style-type: disc;
            padding-left: 20px;
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <!-- Add your profile picture here -->
            <img src=" https://assets.onecompiler.app/43c9b5n2j/43c9cgkem/WhatsApp%20Image%202025-03-19%20at%203.34.15%20PM.jpeg" class="profile-picture">
            <h1>kiruthika.D</h1>
            <p> Department of computer application</p>
        </div>
    </header>

    <nav>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#resume">Resume</a></li>
           
        </ul>
    </nav>

    <section id="about">
        <div class="section-content">
            <h2>About Me</h2>
            <p>I'm a <b></b> I am D.kiruthika, a Bachelor of Computer Applications (BCA) student at Alpha Arts and Science College, graduating in 2026. Passionate about technology, I enjoy coding, problem-solving, and exploring software development. I have experience with programming languages like Python, Java, and C++, and I actively participate in workshops and projects to enhance my technical skills. Beyond academics, I engage in extracurricular activities that improve my communication and teamwork abilities. My goal is to establish a successful career in the IT industry, specializing in software development or data science, and contribute to innovative technological solutions that make a positive impact.


        </div>
    </section>

    <section id="education">
        <div class="section-content">
            <h2>Education</h2>
            <p>Alpha art and science  - Bca</p>
            
            
        </div>
    </section>

    <section id="skills">
        <div class="section-content">
            <h2>Skills</h2>
            <ul>
          
                <li>Python</li>
                <li> AI</li>
                <li>java</li>
                <li>c++</li>
                <li> Html</li>
                <li>css</li>
            </ul>
        </div>
    </section>

    <section id="projects">
        <div class="section-content">
            <h2>Project</h2>
            <ul>
                <li><a href="#">Facial emotion recognition using AI</a></li>
               
                <!-- Add more project links here -->
            </ul>
        </div>
    </section>

    <section id="resume">
    
        <div class="section-content">
            <center>
            <h2>Resume</h2>
            <a href="file.pdf" target="_blank" class="download-button">Download CV</a>
        </center>
        </div>
        
    </section>

    <footer>
        <p>&copy; 2025 D.kiruthika</p>
    </footer>

    <script>
        // Smooth scrolling to section when clicking on navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();

                const targetId = this.getAttribute('href').substring(1);
                const targetElement = document.getElementById(targetId);

                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>portfolio
