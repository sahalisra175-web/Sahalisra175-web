<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Isra Sahal | Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
</head>
<body>

    <header>
        <nav>
            <div class="logo">ISRA<span>SAHAL</span></div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h3>Welcome to my Profile! 👋</h3>
            <h1>I'm <span>Isra Sahal Ibrahim</span></h1>
            <p class="subtitle">Visual Storyteller | Graphic Designer & Web Developer 🎨💻</p>
            <p class="description">
                I specialize in creating professional logos, brand identities, 
                and building modern, responsive websites that stand out.
            </p>
            <a href="mailto:SAHALISRA@GMAIL.COM" class="btn">Get In Touch</a>
        </div>
    </section>

    <section id="skills" class="skills-section">
        <h2>My Technical <span>Skills</span></h2>
        <div class="skills-grid">
            <div class="skill-card">
                <i class="fab fa-adobe"></i>
                <h3>Design</h3>
                <p>Photoshop & Illustrator</p>
            </div>
            <div class="skill-card">
                <i class="fas fa-code"></i>
                <h3>Development</h3>
                <p>HTML5 & CSS3</p>
            </div>
        </div>
        
        <div class="badges">
            <img src="https://img.shields.io/badge/photoshop-%2331A8FF.svg?style=for-the-badge&logo=adobephotoshop&logoColor=white" alt="Photoshop">
            <img src="https://img.shields.io/badge/illustrator-%23FF9A00.svg?style=for-the-badge&logo=adobeillustrator&logoColor=white" alt="Illustrator">
            <img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
            <img src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
        </div>
    </section>

    <footer>
        <p>© 2026 Isra Sahal. All Rights Reserved.</p>
    </footer>

</body>
</html>
@import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Inter', sans-serif;
}

body {
    background-color: #0b0f1a;
    color: #ffffff;
    line-height: 1.6;
    scroll-behavior: smooth;
}

/* Navigation */
header {
    padding: 20px 10%;
    background: rgba(11, 15, 26, 0.95);
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 1000;
}

nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.logo {
    font-size: 22px;
    font-weight: 700;
}

.logo span {
    color: #31A8FF;
}

nav ul {
    display: flex;
    list-style: none;
}

nav ul li {
    margin-left: 30px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: 500;
    transition: 0.3s;
}

nav ul li a:hover {
    color: #31A8FF;
}

/* Hero Section */
.hero {
    height: 100vh;
    display: flex;
    align-items: center;
    padding: 0 10%;
    background: radial-gradient(circle at top right, #1e293b, #0b0f1a);
}

.hero-content h3 {
    color: #31A8FF;
    font-size: 1.2rem;
    margin-bottom: 10px;
}

.hero-content h1 {
    font-size: 3.5rem;
    margin-bottom: 10px;
}

.hero-content h1 span {
    color: #31A8FF;
}

.subtitle {
    font-size: 1.5rem;
    font-weight: 600;
    color: #94a3b8;
    margin-bottom: 20px;
}

.description {
    max-width: 600px;
    margin-bottom: 30px;
    color: #cbd5e1;
}

.btn {
    padding: 12px 35px;
    background: #31A8FF;
    color: white;
    text-decoration: none;
    border-radius: 8px;
    font-weight: 600;
    transition: 0.3s;
    display: inline-block;
}

.btn:hover {
    background: #0084ff;
    transform: translateY(-3px);
    box-shadow: 0 5px 15px rgba(49, 168, 255, 0.4);
}

/* Skills Section */
.skills-section {
    padding: 100px 10%;
    text-align: center;
}

.skills-section h2 {
    font-size: 2.5rem;
    margin-bottom: 40px;
}

.skills-section h2 span {
    color: #31A8FF;
}

.skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    margin-bottom: 40px;
}

.skill-card {
    background: #161e2d;
    padding: 30px;
    border-radius: 15px;
    transition: 0.3s;
}

.skill-card:hover {
    background: #1e293b;
}

.skill-card i {
    font-size: 40px;
    color: #31A8FF;
    margin-bottom: 15px;
}

.badges {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;
}

footer {
    text-align: center;
    padding: 40px;
    background: #080b13;
    color: #64748b;
    font-size: 0.9rem;
}
