<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Jamaine | Web Developer Portfolio</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <!-- Header -->
  <header>
    <div class="logo">
      <h1>Jamaine</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- Hero Section -->
  <section id="home" class="hero">
    <div class="hero-content">
      <h2>Hi, I'm Jamaine — Web Developer</h2>
      <p>I build modern, responsive websites that bring ideas to life.</p>
      <a href="#contact" class="cta-button">Let's Connect</a>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="about">
    <h2>About Me</h2>
    <p>Hello! I'm Jamaine, a passionate web developer with experience in building responsive and modern websites. I enjoy turning creative ideas into clean, functional code.</p>
  </section>

  <!-- Skills Section -->
  <section id="skills" class="skills">
    <h2>Skills</h2>
    <div class="skill">HTML</div>
    <div class="skill">CSS</div>
    <div class="skill">JavaScript</div>
    <div class="skill">PHP</div>
    <div class="skill">SQL</div>
  </section>

  <!-- Projects Section -->
  <section id="projects" class="projects">
    <h2>Projects</h2>
    <div class="project">
      <h3>Portfolio Website</h3>
      <p>My personal portfolio site built with HTML, CSS, and a touch of JavaScript. Showcases my skills, projects, and contact information.</p>
    </div>
    <div class="project">
      <h3>Blog CMS</h3>
      <p>A content management system developed using PHP and MySQL to post and manage articles easily.</p>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="contact">
    <h2>Contact</h2>
    <p>Email: Jamainemalabanan@gmail.com</p>
    <p>Phone: 09234686512</p>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Jamaine | Web Developer Portfolio</p>
  </footer>
</body>
</html>













css
/* General Styles */
body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #101010;
    color: #fff;
  }
  
  /* Header and Navigation */
  header {
    background-color: #222;
    color: #fff;
    padding: 20px;
    text-align: center;
  }
  
  header .logo h1 {
    font-size: 36px;
    letter-spacing: 3px;
    color: #f1c40f;
  }
  
  nav ul {
    list-style-type: none;
    padding: 0;
    margin: 0;
  }
  
  nav ul li {
    display: inline;
    margin: 0 20px;
  }
  
  nav ul li a {
    color: #fff;
    text-decoration: none;
    font-size: 18px;
    text-transform: uppercase;
    letter-spacing: 1px;
    transition: color 0.3s ease;
  }
  
  nav ul li a:hover {
    color: #f1c40f;
  }
  
  /* Hero Section */
  .hero {
    background: url('itbg.JPG') no-repeat center center;
    background-size: cover;
    height: 700px;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    color: white;
    position: relative;
  }
  
  .hero .hero-content {
    z-index: 2;
  }
  
  .hero h2 {
    font-size: 48px;
    font-weight: bold;
    margin: 0;
    text-shadow: 3px 3px 5px rgba(0, 0, 0, 0.7);
  }
  
  .hero p {
    font-size: 22px;
    margin: 10px 0;
  }
  
  .cta-button {
    background-color: #f1c40f;
    color: #fff;
    padding: 15px 30px;
    font-size: 20px;
    border-radius: 30px;
    text-decoration: none;
    margin-top: 30px;
    transition: background-color 0.3s ease;
  }
  
  .cta-button:hover {
    background-color: #e67e22;
  }
  
  /* About Section */
  .about {
    background-color: #1a1a1a;
    padding: 50px 20px;
    text-align: center;
  }
  
  .about h2 {
    font-size: 36px;
    color: #f1c40f;
  }
  
  .about p {
    font-size: 18px;
    line-height: 1.6;
    max-width: 800px;
    margin: 20px auto;
  }
  
  /* Skills Section */
  .skills {
    background-color: #1a1a1a;
    padding: 50px 20px;
    text-align: center;
  }
  
  .skills h2 {
    font-size: 36px;
    color: #f1c40f;
    margin-bottom: 20px;
  }
  
  .skill {
    display: inline-block;
    background-color: #2c3e50;
    color: #f1c40f;
    font-weight: bold;
    margin: 10px;
    padding: 10px 20px;
    border-radius: 20px;
    box-shadow: 0 5px 10px rgba(0, 0, 0, 0.3);
  }
  
  /* Projects Section */
  .projects {
    background-color: #1a1a1a;
    padding: 50px 20px;
    text-align: center;
  }
  
  .projects h2 {
    font-size: 36px;
    color: #f1c40f;
    margin-bottom: 20px;
  }
  
  .project {
    background-color: #34495e;
    padding: 30px;
    margin: 20px auto;
    max-width: 600px;
    border-radius: 10px;
    box-shadow: 0 5px 15px rgba(0, 0, 0, 0.3);
    transition: transform 0.3s ease;
  }
  
  .project:hover {
    transform: scale(1.05);
  }
  
  .project h3 {
    color: #f1c40f;
  }
  
  .project p {
    color: #bdc3c7;
  }
  
  /* Contact Section */
  .contact {
    padding: 50px 20px;
    background-color: #2c3e50;
    text-align: center;
  }
  
  .contact h2 {
    font-size: 36px;
    color: #f1c40f;
  }
  
  .contact p {
    font-size: 18px;
    color: #bdc3c7;
    margin: 10px 0;
  }
  
  /* Footer */
  footer {
    background-color: #222;
    color: #fff;
    padding: 20px;
    text-align: center;
  }
  
  footer p {
    font-size: 16px;
  }
  
