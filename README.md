# Web-Development-Capstone-Project

 
<!DOCTYPE html>
<html>
<head>
    <title>My Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

    <!-- Navigation Bar -->
    <nav>
        
        <h2>My Portfolio</h2>

        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
        
    </nav>

    <!-- Home Section -->
    <section id="home">

        <div class="intro">
            <h1>Hi, I'm Devansh Gupta</h1>
            <h3>B.Tech CSE (AI & ML) Student</h3>
            <p>Welcome to my personal portfolio website.</p>
        </div>
        <img src ="Image/WhatsApp Image 2026-11-17 at 1.19.27 PM.jpeg" alt="My Profile Photo" class="profile-photo">

    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>
            I am Devansh Gupta, a first-year B.Tech student
            pursuing Computer Science Engineering with
            Artificial Intelligence and Machine Learning
            from KR Mangalam University.

            I am interested in learning programming
            and new technologies.
        </p>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>My Skills</h2>
        <p>HTML</p>
        <p>CSS</p>
        <p>Python (Beginner)</p>
    </section>

    <!-- Education Section -->
    <section id="education">
        <h2>Education</h2>
        <h3>B.Tech CSE (AI & ML)</h3>
        <p>KR Mangalam University</p>
        <p>Currently pursuing 1st Year</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: your-devansh@gmail.com</p>
        <p>GitHub: github.com/devansh</p>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2026 Devansh Gupta | My Portfolio</p>
    </footer>

</body>
</html>




/* Body */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background-color: #f4f4f4;
}

/* Navigation Bar */
nav {
    background-color: #222;
    color: white;
    padding: 15px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin:15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

/* Home Section */
#home {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 60px;
    background-color: #dbeafe;
}

/* Introduction */
.intro {
    text-align: center;
}

/* Profile Photo */
.profile-photo {
    width: 200px;
    height: 200px;
    object-fit: cover;
}

/* Other Sections */
section {
    background-color: white;
    margin: 20px;
    padding: 30px;
    border-radius: 10px;
}

/* Headings */
h2 {
    color: #2563eb;
}

/* Footer */
footer {
    background-color: #222;
    color: white;
    text-align: center;
    padding: 15px;
}

