<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Name | Portfolio</title>

<style>
:root {
    --bg: #0f172a;
    --card: #1e293b;
    --accent: #3b82f6;
    --text: #f1f5f9;
    --subtext: #94a3b8;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Segoe UI', sans-serif;
}

body {
    background: var(--bg);
    color: var(--text);
    line-height: 1.6;
}

header {
    text-align: center;
    padding: 80px 20px;
}

header h1 {
    font-size: 3rem;
    margin-bottom: 10px;
}

header p {
    color: var(--subtext);
    font-size: 1.2rem;
}

button {
    margin-top: 20px;
    padding: 12px 24px;
    border: none;
    background: var(--accent);
    color: white;
    font-size: 1rem;
    border-radius: 8px;
    cursor: pointer;
    transition: 0.3s;
}

button:hover {
    opacity: 0.8;
}

section {
    padding: 60px 20px;
    max-width: 1000px;
    margin: auto;
}

h2 {
    text-align: center;
    margin-bottom: 40px;
    font-size: 2rem;
}

.projects {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
}

.card {
    background: var(--card);
    padding: 20px;
    border-radius: 12px;
    transition: 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

.card h3 {
    margin-bottom: 10px;
}

.card p {
    color: var(--subtext);
    font-size: 0.9rem;
}

footer {
    text-align: center;
    padding: 30px;
    color: var(--subtext);
    border-top: 1px solid #334155;
}
</style>
</head>

<body>

<header>
    <h1>Your Name</h1>
    <p>Creative Developer • Designer • Builder</p>
    <button onclick="document.getElementById('contact').scrollIntoView({behavior:'smooth'})">
        Contact Me
    </button>
</header>

<section>
    <h2>About Me</h2>
    <p style="text-align:center; max-width:600px; margin:auto; color:var(--subtext);">
        I'm a passionate creator who builds modern, clean, and user-friendly digital experiences.
        I love turning ideas into reality through code and design.
    </p>
</section>

<section>
    <h2>Projects</h2>
    <div class="projects">
        <div class="card">
            <h3>Project One</h3>
            <p>A short description of your project goes here.</p>
        </div>

        <div class="card">
            <h3>Project Two</h3>
            <p>A short description of your project goes here.</p>
        </div>

        <div class="card">
            <h3>Project Three</h3>
            <p>A short description of your project goes here.</p>
        </div>
    </div>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p style="text-align:center; color:var(--subtext);">
        Email: your@email.com <br>
        GitHub: github.com/yourusername
    </p>
</section>

<footer>
    © 2026 Your Name. All rights reserved.
</footer>

</body>
</html>
