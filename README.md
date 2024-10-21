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
        <p>Dedicated and ambitious student with a strong passion for finance, accounting, and community service</p>
        <nav>
            <ul>
                <li><a href="#about">About Me</a></li>
                <li><a href="#experience">Experience</a></li>
                <li><a href="#education">Education</a></li>
                <li><a href="#internships">Internships</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <img src="profile-photo.jpg" alt="Kristian Troy Eakins">
        <p>As a dedicated high school student passionate about finance and accounting, I’ve spent most of my academic journey exploring business and leadership in and out of school. Through hands-on internships and taking leadership roles in organizations like the Joe DiMaggio All-Stars and Fairplay Sports for all, I’ve developed many skills in accounting, financial modeling, and community impact. With a GPA of 3.84 in the Business & Entrepreneurship Program at American Heritage School, I’m eager to continue my education in any and all environments that I can learn and grow as a person and business man.</p>
    </section>

    <!-- Experience Section -->
    <section id="experience">
        <h2>Experience</h2>
        <div class="experience-item">
            <h3>Co-Captain, High School Golf Team</h3>
            <p>American Heritage High School, August 2024 – Present</p>
            <p>Led team practices and organized tournaments, resulting in a 9th place finish in regional competition. Mentored new team members to develop their skills and managed scheduling and communications between team members and coaching staff.</p>
        </div>
        <div class="experience-item">
            <h3>Co-Founder, Joe DiMaggio All-Stars Club</h3>
            <p>American Heritage High School, October 2023 – Present</p>
            <p>Established a student-led initiative to raise funds and collect supplies for young patients of Joe DiMaggio Children’s Hospital. Organized fundraising events, raising over $6,000, including a Mini-Golf event in partnership with Fair Play Sports 4 All.</p>
        </div>
    </section>

    <!-- Education Section -->
    <section id="education">
        <h2>Education</h2>
        <div class="education-item">
            <h3>American Heritage School</h3>
            <p>August 2021 - Present</p>
            <p>GPA: 3.8 (Unweighted), 4.4 (Weighted)</p>
            <p>Relevant Coursework: Business Essentials, Entrepreneurship, Finance & Accounting, Marketing, Business Management, Architecture 1 & 2, Computer Science.</p>
        </div>
        <div class="education-item">
            <h3>Cambridge University - Business/Entrepreneurship</h3>
            <p>July 2023 - August 2023</p>
            <p>Earned college credit in entrepreneurship. Created and presented a business idea to investors.</p>
        </div>
    </section>

    <!-- Internships Section -->
    <section id="internships">
        <h2>Internships</h2>
        <div class="experience-item">
            <h3>Accounting Intern, Seal Aftermarket Products</h3>
            <p>Hollywood, FL | June 2022 - August 2022, June 2023 - August 2023</p>
            <p>Assisted in managing accounts receivable and payable reconciliations, providing valuable insights into the financial health of the company. Performed trend analysis of accounts payable and receivable aging reports, contributing to the optimization of cash flow management.</p>
        </div>
        <div class="experience-item">
            <h3>Golf Ambassador, Fair Play Sports 4 All</h3>
            <p>Pembroke, FL | October 2023 – Present</p>
            <p>Organized used golf club events, obtaining used golf clubs from local golf clubs and individuals. Coordinated with Keiser University representatives to provide equipment for disadvantaged youth groups and veteran's golf programs, promoting inclusivity in sports.</p>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">

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
