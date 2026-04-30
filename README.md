<!-- index.html -->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Creative Portfolio</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <!-- Navigation -->
    <header>
        <div class="logo">My Portfolio</div>

        <nav>
            <a href="#about">About</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <div class="hero-text">
            <h1>Hello, I'm <span>Kryle</span></h1>
            <h2>Future Web Developer</h2>
            <p>
                I create clean, modern, and user-friendly websites
                with passion and creativity.
            </p>
        </div>
    </section>

    <!-- About -->
    <section id="about" class="section">
        <h2>About Me</h2>
        <p>
           I am a new Information Technology student who is learning how to make websites, study programming, and create simple digital projects.
        </p>
    </section>

    <!-- Skills -->
    <section id="skills" class="section">
        <h2>My Skills</h2>

        <div class="skills-container">
            <div class="skill-box">HTML</div>
            <div class="skill-box">CSS</div>
            <div class="skill-box">JavaScript</div>
            <div class="skill-box">Web Design</div>
        </div>
    </section>

    <!-- Projects -->
    <section id="projects" class="section">
        <h2>Projects</h2>

        <div class="project-grid">
            <div class="project-box">
                <h3>Landing Page</h3>
                <p>A simple homepage design created using HTML and CSS.</p>
            </div>

            <div class="project-box">
                <h3>Student Portal</h3>
                <p>A basic student dashboard for school information and activities.</p>
            </div>

            <div class="project-box">
                <h3>Portfolio Site</h3>
                <p>A personal website to show my skills, projects, and contact details.</p>
            </div>
        </div>
    </section>

    <!-- Contact -->
    <section id="contact" class="section">
        <h2>Contact Me</h2>

        <form>
            <input type="text" placeholder="Enter your name">
            <input type="email" placeholder="Enter your email">
            <textarea placeholder="Write your message"></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

</body>
</html>