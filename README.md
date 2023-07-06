<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>My Profile README</title>
<style>
body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
    color: #333;
    margin: 0;
    padding: 0;
}

.container {
    max-width: 800px;
    margin: 0 auto;
    padding: 40px;
    background-color: #fff;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.header {
    text-align: center;
    margin-bottom: 40px;
}

.header h1 {
    color: #ff5722;
    font-size: 32px;
    margin-bottom: 10px;
}

.header p {
    font-size: 18px;
}

.section {
    margin-bottom: 40px;
}

.section h2 {
    color: #333;
    font-size: 24px;
    margin-bottom: 20px;
}

.skills-list,
.projects-list,
.interests-list,
.contacts-list {
    list-style-type: disc;
    margin-left: 20px;
}

.contacts-list {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

.contacts-list li {
    display: inline;
    margin-right: 10px;
}

.contacts-list li:last-child {
    margin-right: 0;
}

.footer {
    text-align: center;
    margin-top: 40px;
}
</style>
</head>
<body>
<div class="container">
<div class="header">
    <h1>Hello, I'm [Your Name]</h1>
    <p>Welcome to my GitHub profile README! Here you'll find information about my skills, projects, and contact details.</p>
</div>

<div class="section">
    <h2 styles={{color: "red"}}>🔧 Skills</h2>
    <ul class="skills-list">
    <li>React.js</li>
    <li>TypeScript</li>
    <li>C#</li>
    <li>Python</li>
    <li>ASP.NET Core</li>
    <li>Django</li>
    </ul>
</div>

<div class="section">
    <h2>💼 Projects</h2>
    <ul class="projects-list">
    <li><a href="project-link">Project 1</a> - Brief description of project 1.</li>
    <li><a href="project-link">Project 2</a> - Brief description of project 2.</li>
    </ul>
</div>

<div class="section">
    <h2>🌱 Interests</h2>
    <ul class="interests-list">
    <li>Artificial Intelligence and Machine Learning</li>
    <li>Game Development</li>
    <li>Data Analysis and Visualization</li>
    </ul>
</div>

<div class="section">
    <h2>📫 Contact</h2>
    <ul class="contacts-list">
    <li>Email: <a href="mailto:example@example.com">example@example.com</a></li>
    <li>LinkedIn: <a href="linkedin-link">Your LinkedIn Profile</a></li>
    </ul>
</div>

<div class="footer">
    <p>Thank you for visiting my profile README! If you have any questions or suggestions, feel free to contact me. I'm open to collaborations and discussions.</p>
    <p>Have a great day!</p>
</div>
</div>
</body>
</html>
