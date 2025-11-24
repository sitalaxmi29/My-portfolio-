/* Reset some default browser styles */
body, h1, h2, h3, h4, h5, h6, p, ul, li {
    margin: 0;
    padding: 0;
}

/* Base styles */
body {
    font-family: "Segoe UI", Arial, sans-serif;
    background: #f6f8fa;
    color: #333;
    line-height: 1.6;
    min-height: 100vh;
}

header {
    background: #5A189A;
    color: #fff;
    padding: 2rem 0 1rem 0;
    text-align: center;
}

header h1 {
    font-size: 2.5rem;
    margin-bottom: 0.5rem;
}

header .bio {
    font-size: 1.2rem;
    font-weight: 400;
    margin-bottom: 1rem;
}

main {
    max-width: 700px;
    margin: 2rem auto 0 auto;
    padding: 0 1.5rem;
    background: #fff;
    box-shadow: 0 0 12px rgba(143, 122, 188, 0.08);
    border-radius: 12px;
}

section {
    margin-bottom: 2rem;
}

section h2 {
    color: #5A189A;
    font-size: 1.5rem;
    margin-bottom: 0.75rem;
    border-bottom: 1px solid #ddd;
    padding-bottom: 0.4rem;
}

ul {
    list-style: disc inside;
    margin-left: 1rem;
}

li {
    margin-bottom: 0.75rem;
}

strong {
    color: #9D4EDD;
}

a {
    color: #5A189A;
    text-decoration: none;
    transition: color 0.2s;
}

a:hover {
    text-decoration: underline;
    color: #3C096C;
}

footer {
    margin-top: 3rem;
    text-align: center;
    color: #999;
    padding: 1rem 0;
    background: #eee;
    border-radius: 0 0 12px 12px;
    font-size: 0.95rem;
}

/* Responsive adjustments */
@media (max-width: 600px) {
    main {
        padding: 0 0.7rem;
    }
    header h1 {
        font-size: 2rem;
    }
}
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sitalaxmi Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Sitalaxmi</h1>
        <p class="bio">A passionate developer dedicated to creating impactful solutions.</p>
    </header>
    <main>
        <section id="about">
            <h2>About Me</h2>
            <p>
                I am a web developer with a strong foundation in front-end and back-end technologies. I enjoy tackling challenging problems and learning new skills.
            </p>
        </section>
        <section id="skills">
            <h2>Skills</h2>
            <ul>
                <li>HTML5, CSS3, JavaScript</li>
                <li>React, Node.js</li>
                <li>Python, Django</li>
                <li>Git & GitHub</li>
                <li>Responsive Design</li>
            </ul>
        </section>
        <section id="education">
            <h2>Education</h2>
            <ul>
                <li>Bachelor of Technology in Computer Science (2022)</li>
                <li>Certified Web Developer - FreeCodeCamp (2023)</li>
            </ul>
        </section>
        <section id="experience">
            <h2>Experience</h2>
            <ul>
                <li>
                    <strong>Frontend Developer</strong>, XYZ Corp (2024-Present)<br>
                    Building modern web applications and maintaining company websites.
                </li>
                <li>
                    <strong>Intern</strong>, ABC Tech (2023)<br>
                    Gained hands-on experience in web development and project collaboration.
                </li>
            </ul>
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <ul>
                <li>Email: <a href="mailto:sitalaxmi@example.com">sitalaxmi@example.com</a></li>
                <li>LinkedIn: <a href="https://www.linkedin.com/in/sitalaxmi" target="_blank">linkedin.com/in/sitalaxmi</a></li>
                <li>GitHub: <a href="https://github.com/sitalaxmi29" target="_blank">github.com/sitalaxmi29</a></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>© 2025 Sitalaxmi. All rights reserved.</p>
    </footer>
</body>
</html>
