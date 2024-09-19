<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kristian Troy Eakins</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <h1>Kristian Troy Eakins</h1>
        <p>Dedicated high school student with a passion for finance, accounting, and community service</p>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#achievements">Achievements</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I'm Kristian, a high school student passionate about finance, accounting, and community service. My journey includes leadership roles in my school's golf team and founding a club to support young patients...</p>
        <img src="your-photo.jpg" alt="Kristian Troy Eakins">
    </section>

    <!-- Experience Section -->
    <section id="experience">
        <h2>Experience</h2>
        <div class="experience-item">
            <h3>Co-Captain, High School Golf Team</h3>
            <p>American Heritage High School, August 2024 – Present</p>
            <p>Led team practices and organized tournaments...</p>
        </div>
        <!-- Repeat for other experiences -->
    </section>

    <!-- Education Section -->
    <section id="education">
        <h2>Education</h2>
        <div class="education-item">
            <h3>American Heritage School</h3>
            <p>August 2021 - Present</p>
            <p>GPA: 3.8, 4.4 weighted</p>
        </div>
        <!-- Repeat for other education entries -->
    </section>

    <!-- Achievements Section -->
    <section id="achievements">
        <h2>Achievements and Awards</h2>
        <ul>
            <li>ISSOS Outdoor Leadership Achievement Award (2023)</li>
            <li>ISSOS Clan Spirit Award (2023)</li>
            <li>Geometry Award (2022)</li>
        </ul>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills & Certifications</h2>
        <p>QuickBooks Certification, Photography, Communication, Team Motivation...</p>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>Email: Pl221971@ahschool.com | kristian.teakins@gmail.com</p>
        <form action="submit_form.php" method="post">
            <input type="text" name="name" placeholder="Your Name">
            <input type="email" name="email" placeholder="Your Email">
            <textarea name="message" placeholder="Your Message"></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Kristian Troy Eakins</p>
    </footer>
</body>
</html>
/* General Styles */
body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Header Styles */
header {
    background: #333;
    color: #fff;
    padding: 20px 0;
    text-align: center;
}

header h1 {
    margin: 0;
    font-size: 2.5em;
}

header p {
    margin-top: 10px;
    font-size: 1.2em;
}

/* Navigation Styles */
nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 10px;
}

nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1em;
}

nav ul li a:hover {
    text-decoration: underline;
}

/* Section Styles */
section {
    padding: 20px;
    margin: 20px auto;
    max-width: 800px;
    background: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}

section h2 {
    font-size: 2em;
    margin-bottom: 15px;
    color: #333;
    border-bottom: 2px solid #333;
    padding-bottom: 10px;
}

section p {
    font-size: 1.1em;
    line-height: 1.6;
}

/* About Section */
#about img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
    margin-top: 20px;
}

/* Experience and Education Sections */
.experience-item, .education-item {
    margin-bottom: 20px;
}

.experience-item h3, .education-item h3 {
    font-size: 1.5em;
    margin: 10px 0;
    color: #007acc;
}

.experience-item p, .education-item p {
    margin: 5px 0;
}

/* Achievements and Skills Sections */
ul {
    list-style-type: none;
    padding: 0;
}

ul li {
    background: #f4f4f4;
    margin: 5px 0;
    padding: 10px;
    border-left: 4px solid #007acc;
}

/* Contact Section */
#contact form {
    display: flex;
    flex-direction: column;
}

#contact input, #contact textarea {
    margin: 10px 0;
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

#contact button {
    padding: 10px;
    background: #007acc;
    color: #fff;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    font-size: 1.1em;
}

#contact button:hover {
    background: #005b99;
}

/* Footer Styles */
footer {
    text-align: center;
    padding: 20px;
    background: #333;
    color: #fff;
    margin-top: 20px;
}

/* Media Queries for Responsiveness */
@media (max-width: 768px) {
    nav ul li {
        display: block;
        margin: 10px 0;
    }

    header h1 {
        font-size: 2em;
    }

    header p {
        font-size: 1em;
    }

    section {
        margin: 10px;
        padding: 15px;
    }
}
