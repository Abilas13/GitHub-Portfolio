<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Abilash13 Portfolio</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet"/>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      background-color: #f4f6f8;
      color: #333;
      line-height: 1.6;
    }

    /* Navbar */
    nav {
      background: #1e88e5;
      padding: 15px 20px;
      display: flex;
      justify-content: center;
      gap: 20px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }

    /* Header */
    header {
      background: linear-gradient(135deg, #1e88e5, #1565c0);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }
    header p {
      font-size: 1.2rem;
    }

    /* Section styling */
    section {
      max-width: 1000px;
      margin: 50px auto;
      padding: 0 20px;
    }
    h2 {
      border-bottom: 3px solid #1e88e5;
      display: inline-block;
      padding-bottom: 5px;
      margin-bottom: 25px;
    }

    /* Skills, Projects, Contact */
    .skills, .projects, .contact {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }
    .skill, .project, .contact-card {
      background-color: white;
      padding: 20px;
      border-radius: 12px;
      flex: 1 1 250px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
    }
    .skill:hover, .project:hover, .contact-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.15);
    }

    .project a {
      display: inline-block;
      margin-top: 10px;
      color: #1e88e5;
      text-decoration: none;
      font-weight: bold;
    }
    .project a:hover {
      text-decoration: underline;
    }

    /* GitHub stats */
    .github-stats {
      margin-top: 30px;
      text-align: center;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 30px;
      background: #1e88e5;
      color: white;
    }

    @media (max-width: 600px) {
      nav {
        flex-direction: column;
        align-items: center;
      }
      .skills, .projects, .contact {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>

  <!-- Navbar -->
  <nav>
    <a href="#about">About</a>
    <a href="#skills">Skills</a>
    <a href="#projects">Projects</a>
    <a href="#github-stats">GitHub Stats</a>
    <a href="#contact">Contact</a>
  </nav>

  <!-- Header -->
  <header>
    <h1>Hi, I'm Abilash13 👋</h1>
    <p>Undergraduate Data Science student passionate about Python, Machine Learning & Data Visualization.</p>
  </header>

  <!-- About -->
  <section id="about">
    <h2>About Me</h2>
    <p>🎓 Currently pursuing a degree in Data Science<br>
       🐍 Skilled in Python and its data ecosystem<br>
       💡 Interested in Machine Learning, AI, and Data Visualization<br>
       ⚡ Always eager to learn and collaborate on exciting projects</p>
  </section>

  <!-- Skills -->
  <section id="skills">
    <h2>Skills</h2>
    <div class="skills">
      <div class="skill">Python</div>
      <div class="skill">SQL</div>
      <div class="skill">Pandas</div>
      <div class="skill">NumPy</div>
      <div class="skill">Matplotlib</div>
      <div class="skill">Scikit-learn</div>
      <div class="skill">Data Analysis</div>
      <div class="skill">Machine Learning</div>
      <div class="skill">Data Visualization</div>
    </div>
  </section>

  <!-- Projects -->
  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="project">
        <h3>ChatOn</h3>
        <p>Interactive chatbot project built with Python and modern data science tools.</p>
        <a href="#">Live Demo</a> | <a href="#">Code</a>
      </div>
      <div class="project">
        <h3>Sales Data Analysis</h3>
        <p>Analyzed and visualized sales data to provide actionable business insights.</p>
        <a href="#">Live Demo</a> | <a href="#">Code</a>
      </div>
      <div class="project">
        <h3>ML Prediction Model</h3>
        <p>Built predictive model to forecast outcomes based on historical data.</p>
        <a href="#">Live Demo</a> | <a href="#">Code</a>
      </div>
    </div>
  </section>

  <!-- GitHub Stats -->
  <section id="github-stats" class="github-stats">
    <h2>GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=Abilas13&show_icons=true&theme=radical" alt="GitHub Stats">
  </section>

  <!-- Contact -->
  <section id="contact">
    <h2>Contact Me</h2>
    <div class="contact">
      <div class="contact-card">
        <i class="fas fa-envelope"></i>
        <p>Email: <a href="mailto:y.abilash13@gmail.com">y.abilash13@gmail.com</a></p>
      </div>
      <div class="contact-card">
        <i class="fab fa-linkedin"></i>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/yourprofile" target="_blank">Abilash</a></p>
      </div>
      <div class="contact-card">
        <i class="fab fa-github"></i>
        <p>GitHub: <a href="https://github.com/Abilas13" target="_blank">Abilas13</a></p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    &copy; 2025 Abilash13 | Built with ❤️ and GitHub Pages
  </footer>

</body>
</html>
