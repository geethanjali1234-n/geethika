<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Geethanjali's Portfolio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
</head>
<body>

    <!-- Navigation Section -->
    <header>
        <nav>
            <div class="logo">Geethanjali</div>
            <ul class="nav-links">
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="hero">
        <div class="hero-content">
            <h1>Hello, I'm <span>Geethanjali</span></h1>
            <p>Aspiring Software Developer | Master’s in Applied Computer Science</p>
            <a href="#projects" class="btn">View My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About Me</h2>
        <p>I'm a passionate software developer with a background in Electronics and Communication Engineering. I specialize in web development, database systems, and graph algorithms. Currently pursuing my Master’s in Applied Computer Science, I aim to build innovative solutions for real-world problems.</p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-grid">
            <div class="project-card">
                <h3>Neo4j Graph Algorithms</h3>
                <p>Analyzed social network data using PageRank, Betweenness Centrality, and other algorithms to find key influencers.</p>
            </div>
            <div class="project-card">
                <h3>Personalized Shopping Platform</h3>
                <p>Collaborated with a team to build a sustainable e-commerce platform with product recommendations and community features.</p>
            </div>
            <div class="project-card">
                <h3>SQL Database Management</h3>
                <p>Created advanced SQL queries for BoatsPG database, handling multi-table joins, aggregate functions, and view creation.</p>
            </div>
            <div class="project-card">
                <h3>Redis Data Structures</h3>
                <p>Worked on geospatial indexing, streams, and transactions using Redis, with Lua scripting for automation.</p>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
        <h2>Skills</h2>
        <div class="skills-list">
            <span>Python</span>
            <span>SQL</span>
            <span>JavaScript</span>
            <span>Cypher</span>
            <span>Neo4j</span>
            <span>Redis</span>
            <span>Git</span>
            <span>HTML/CSS</span>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Me</h2>
        <p>If you're interested in collaborating or just want to say hi, feel free to drop me a message!</p>
        <a href="mailto:geethanjalinalla58@gmail.com" class="btn">Send an Email</a>
    </section>

    <footer>
        <p>© 2024 Geethanjali. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
