# neon.github.io
<!-- ======================= index.html ======================= --><!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Student Digital Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body><!-- Navbar -->
<header>
    <h2 class="logo">My Portfolio</h2>
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#achievements">Achievements</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#gallery">Gallery</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    <button onclick="toggleDarkMode()" class="dark-btn">🌙</button>
</header>

<!-- Home Section -->
<section id="home" class="section">
    <img src="images/photo.jpg" class="profile">
    <h1>Shravan Nanaware</h1>
    <p>Computer Engineering Student | Web Developer | Programmer</p>
</section>

<!-- About Section -->
<section id="about" class="section">
    <h2>About Me</h2>
    <p><b>Education:</b> BTech Computer Engineering</p>
    <p><b>Interests:</b> Coding, Web Development, Programming</p>
    <p><b>Goals:</b> Become a Software Engineer</p>
    <p><b>Strengths:</b> Problem Solving, Teamwork, Creativity</p>
</section>

<!-- Achievements -->
<section id="achievements" class="section">
    <h2>Achievements</h2>
    <ul>
        <li>AI4A Project Completed</li>
        <li>Design Thinking Project</li>
        <li>ACE Project</li>
        <li>Coursera Certificate</li>
        <li>NetAcad Certificate</li>
        <li>Yuva AI Certificate</li>
    </ul>
</section>

<!-- Projects -->
<section id="projects" class="section">
    <h2>Projects</h2>
    <div class="project">
        <img src="images/project1.png">
        <h3>Student Portfolio Website</h3>
        <p>Created using HTML, CSS, JavaScript</p>
    </div>
</section>

<!-- Gallery -->
<section id="gallery" class="section">
    <h2>Gallery</h2>
    <div class="gallery">
        <img src="images/cert1.jpg">
        <img src="images/cert2.jpg">
        <img src="images/photo.jpg">
    </div>
</section>

<!-- Contact -->
<section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: shravan@gmail.com</p>
    <p>GitHub: github.com/shravan</p>
    <p>LinkedIn: linkedin.com/shravan</p>
</section>

<script src="script.js"></script>

</body>
</html><!-- ======================= style.css ======================= --><style>
body {
    margin: 0;
    font-family: Arial;
    background: #f4f4f4;
    text-align: center;
}

header {
    display: flex;
    justify-content: space-between;
    background: #333;
    color: white;
    padding: 15px;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin: 10px;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.section {
    padding: 40px;
}

.profile {
    width: 150px;
    border-radius: 50%;
}

.project img {
    width: 200px;
}

.gallery img {
    width: 150px;
    margin: 10px;
}

.dark-btn {
    background: black;
    color: white;
    border: none;
    padding: 10px;
    cursor: pointer;
}

.dark-mode {
    background: black;
    color: white;
}
</style><!-- ======================= script.js ======================= --><script>
function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
}
</script>
