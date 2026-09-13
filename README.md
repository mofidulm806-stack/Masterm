<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name | Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      background: #0f172a;
      color: #f8fafc;
      line-height: 1.6;
    }

    header {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(15, 23, 42, 0.9);
      backdrop-filter: blur(10px);
      z-index: 1000;
      border-bottom: 1px solid #334155;
    }

    nav {
      max-width: 1100px;
      margin: auto;
      padding: 18px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 24px;
      font-weight: bold;
      color: #38bdf8;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 25px;
    }

    nav a {
      color: #f8fafc;
      text-decoration: none;
      transition: 0.3s;
    }

    nav a:hover {
      color: #38bdf8;
    }

    section {
      max-width: 1100px;
      margin: auto;
      padding: 100px 20px;
    }

    #home {
      min-height: 100vh;
      display: flex;
      align-items: center;
    }

    .hero h1 {
      font-size: clamp(45px, 8vw, 80px);
      margin-bottom: 10px;
    }

    .hero h1 span {
      color: #38bdf8;
    }

    .hero h2 {
      color: #94a3b8;
      font-size: 28px;
      margin-bottom: 20px;
    }

    .hero p {
      max-width: 650px;
      color: #cbd5e1;
      font-size: 18px;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      padding: 12px 25px;
      background: #38bdf8;
      color: #0f172a;
      text-decoration: none;
      border-radius: 8px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      transform: translateY(-3px);
      background: #7dd3fc;
    }

    .section-title {
      font-size: 40px;
      margin-bottom: 40px;
      color: #38bdf8;
    }

    .about p {
      max-width: 750px;
      color: #cbd5e1;
      font-size: 18px;
    }

    .skills {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      margin-top: 25px;
    }

    .skill {
      padding: 10px 18px;
      background: #1e293b;
      border: 1px solid #334155;
      border-radius: 20px;
    }

    .projects {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 25px;
    }

    .project {
      background: #1e293b;
      padding: 25px;
      border-radius: 12px;
      border: 1px solid #334155;
      transition: 0.3s;
    }

    .project:hover {
      transform: translateY(-7px);
      border-color: #38bdf8;
    }

    .project h3 {
      margin-bottom: 10px;
      color: #38bdf8;
    }

    .project p {
      color: #cbd5e1;
      margin-bottom: 15px;
    }

    .project a {
      color: #7dd3fc;
      text-decoration: none;
    }

    .contact p {
      color: #cbd5e1;
      margin-bottom: 10px;
    }

    .contact a {
      color: #38bdf8;
    }

    footer {
      text-align: center;
      padding: 25px;
      border-top: 1px solid #334155;
      color: #94a3b8;
    }

    @media (max-width: 650px) {
      nav {
        flex-direction: column;
        gap: 10px;
      }

      nav ul {
        gap: 12px;
        font-size: 14px;
      }

      section {
        padding: 80px 20px;
      }
    }
  </style>
</head>

<body>

  <header>
    <nav>
      <div class="logo">YourName</div>

      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <!-- HOME -->
  <section id="home">
    <div class="hero">
      <h1>Hi, I'm <span>Your Name</span></h1>
      <h2>Web Developer & Designer</h2>

      <p>
        I create modern, responsive and user-friendly websites
        using HTML, CSS and JavaScript.
      </p>

      <a href="#projects" class="btn">View My Work</a>
    </div>
  </section>

  <!-- ABOUT -->
  <section id="about" class="about">
    <h2 class="section-title">About Me</h2>

    <p>
      Hello! I'm Your Name. I'm passionate about technology,
      web development and creating beautiful digital experiences.
      I enjoy learning new technologies and building useful projects.
    </p>

    <div class="skills">
      <div class="skill">HTML</div>
      <div class="skill">CSS</div>
      <div class="skill">JavaScript</div>
      <div class="skill">Responsive Design</div>
      <div class="skill">UI/UX</div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects">
    <h2 class="section-title">My Projects</h2>

    <div class="projects">

      <div class="project">
        <h3>Project One</h3>
        <p>
          A modern responsive website built with HTML, CSS and JavaScript.
        </p>
        <a href="#" target="_blank">View Project →</a>
      </div>

      <div class="project">
        <h3>Project Two</h3>
        <p>
          A creative web application designed to provide a simple
          and enjoyable user experience.
        </p>
        <a href="#" target="_blank">View Project →</a>
      </div>

      <div class="project">
        <h3>Project Three</h3>
        <p>
          A responsive portfolio or business website optimized
          for mobile and desktop devices.
        </p>
        <a href="#" target="_blank">View Project →</a>
      </div>

    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="contact">
    <h2 class="section-title">Contact Me</h2>

    <p>Email:
      <a href="mailto:your@email.com">your@email.com</a>
    </p>

    <p>GitHub:
      <a href="#" target="_blank">Your GitHub</a>
    </p>

    <p>LinkedIn:
      <a href="#" target="_blank">Your LinkedIn</a>
    </p>
  </section>

  <footer>
    <p>© 2026 Your Name. All rights reserved.</p>
  </footer>

</body>
</html>
