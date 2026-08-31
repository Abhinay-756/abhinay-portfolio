<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Gubbala Abhinay | Portfolio</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #f5f7fb;
      color: #1f2937;
      line-height: 1.6;
    }

    /* NAVBAR */
    nav {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: #111827;
      padding: 15px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    nav .logo {
      color: white;
      font-size: 22px;
      font-weight: bold;
    }

    nav ul {
      display: flex;
      list-style: none;
      gap: 25px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-size: 15px;
    }

    nav a:hover {
      color: #60a5fa;
    }

    /* HERO */
    .hero {
      min-height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 50px 20px;
      background: linear-gradient(135deg, #111827, #1e3a8a);
      color: white;
    }

    .hero-content {
      max-width: 800px;
    }

    .hero h1 {
      font-size: 55px;
      margin-bottom: 10px;
    }

    .hero h2 {
      color: #93c5fd;
      font-size: 25px;
      margin-bottom: 20px;
    }

    .hero p {
      font-size: 18px;
      color: #e5e7eb;
      margin-bottom: 30px;
    }

    .btn {
      display: inline-block;
      padding: 12px 25px;
      background: #2563eb;
      color: white;
      text-decoration: none;
      border-radius: 8px;
      margin: 5px;
      transition: 0.3s;
    }

    .btn:hover {
      background: #1d4ed8;
      transform: translateY(-2px);
    }

    .btn-outline {
      background: transparent;
      border: 1px solid white;
    }

    .btn-outline:hover {
      background: white;
      color: #111827;
    }

    /* SECTIONS */
    section {
      padding: 75px 8%;
    }

    .section-title {
      text-align: center;
      font-size: 32px;
      margin-bottom: 40px;
      color: #111827;
    }

    .section-title::after {
      content: "";
      display: block;
      width: 60px;
      height: 4px;
      background: #2563eb;
      margin: 10px auto;
      border-radius: 5px;
    }

    .about {
      max-width: 900px;
      margin: auto;
      text-align: center;
      font-size: 17px;
      color: #4b5563;
    }

    /* CARDS */
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
    }

    .card {
      background: white;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.08);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h3 {
      color: #1d4ed8;
      margin-bottom: 12px;
    }

    .card p {
      color: #6b7280;
    }

    /* SKILLS */
    .skills {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 12px;
    }

    .skill {
      background: #dbeafe;
      color: #1e40af;
      padding: 10px 18px;
      border-radius: 25px;
      font-weight: bold;
    }

    /* EXPERIENCE */
    .timeline {
      max-width: 850px;
      margin: auto;
    }

    .experience {
      background: white;
      padding: 30px;
      margin-bottom: 20px;
      border-left: 5px solid #2563eb;
      border-radius: 8px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.06);
    }

    .experience h3 {
      color: #111827;
    }

    .experience .date {
      color: #2563eb;
      font-weight: bold;
      margin: 5px 0 15px;
    }

    .experience ul {
      padding-left: 20px;
      color: #4b5563;
    }

    /* CONTACT */
    .contact {
      text-align: center;
      background: #111827;
      color: white;
    }

    .contact .section-title {
      color: white;
    }

    .contact-info {
      font-size: 18px;
      margin: 15px;
    }

    .contact a {
      color: #93c5fd;
      text-decoration: none;
    }

    /* FOOTER */
    footer {
      text-align: center;
      padding: 20px;
      background: #030712;
      color: #9ca3af;
      font-size: 14px;
    }

    /* MOBILE */
    @media (max-width: 700px) {
      nav {
        flex-direction: column;
        gap: 10px;
      }

      nav ul {
        gap: 12px;
        flex-wrap: wrap;
        justify-content: center;
      }

      .hero h1 {
        font-size: 38px;
      }

      .hero h2 {
        font-size: 20px;
      }

      section {
        padding: 55px 5%;
      }
    }
  </style>
</head>

<body>

  <!-- NAVIGATION -->
  <nav>
    <div class="logo">Abhinay</div>

    <ul>
      <li><a href="#about">About</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>


  <!-- HERO -->
  <header class="hero">
    <div class="hero-content">

      <h1>Gubbala Abhinay</h1>

      <h2>Operations Support | Data Management | Customer Support</h2>

      <p>
        Motivated and detail-oriented professional with experience in
        operations support, data management and customer support.
      </p>

      <a href="#contact" class="btn">Contact Me</a>

      <a href="#about" class="btn btn-outline">View Portfolio</a>

    </div>
  </header>


  <!-- ABOUT -->
  <section id="about">

    <h2 class="section-title">About Me</h2>

    <div class="about">

      <p>
        I am a motivated and detail-oriented professional based in
        Hyderabad, Telangana. I have experience in operations support,
        customer support, data management and administrative tasks.
      </p>

      <br>

      <p>
        I am trained in Microsoft Excel and Power BI, with an interest in
        data management, operations, back-office and administrative roles.
        I am a quick learner with strong problem-solving, teamwork,
        communication and organizational skills.
      </p>

    </div>

  </section>


  <!-- EXPERIENCE -->
  <section id="experience">

    <h2 class="section-title">Experience</h2>

    <div class="timeline">

      <div class="experience">

        <h3>Customer Support / Information Technology Intern</h3>

        <div class="date">August 2025 – Present</div>

        <ul>
          <li>Handled customer queries through calls and messages.</li>
          <li>Coordinated with internal teams to resolve customer issues.</li>
          <li>Maintained accurate customer and order data.</li>
          <li>Ensured timely responses and customer satisfaction.</li>
        </ul>

      </div>

    </div>

  </section>


  <!-- SKILLS -->
  <section id="skills">

    <h2 class="section-title">Skills</h2>

    <div class="skills">

      <span class="skill">Data Entry</span>
      <span class="skill">Data Management</span>
      <span class="skill">Microsoft Excel</span>
      <span class="skill">MS Word</span>
      <span class="skill">Power BI</span>
      <span class="skill">Problem Solving</span>
      <span class="skill">Teamwork</span>
      <span class="skill">Coordination</span>
      <span class="skill">Time Management</span>
      <span class="skill">Communication</span>
      <span class="skill">Adaptability</span>
      <span class="skill">Quick Learning</span>

    </div>

  </section>


  <!-- TRAINING -->
  <section>

    <h2 class="section-title">Training</h2>

    <div class="cards">

      <div class="card">
        <h3>Microsoft Excel</h3>
        <p>
          Data entry, formulas, sorting, filtering and basic data analysis.
        </p>
      </div>

      <div class="card">
        <h3>Power BI</h3>
        <p>
          Dashboards, data visualization and basic reporting.
        </p>
      </div>

    </div>

  </section>


  <!-- EDUCATION -->
  <section id="education">

    <h2 class="section-title">Education</h2>

    <div class="cards">

      <div class="card">

        <h3>ZPHS Saroonagar</h3>

        <p><strong>Intermediate – CEC</strong></p>

        <p>Commerce, Economics & Civics</p>

        <p><strong>Completed:</strong> April/May 2024</p>

      </div>

    </div>

  </section>


  <!-- LANGUAGES -->
  <section>

    <h2 class="section-title">Languages</h2>

    <div class="skills">

      <span class="skill">Telugu</span>
      <span class="skill">English</span>
      <span class="skill">Hindi</span>

    </div>

  </section>


  <!-- CONTACT -->
  <section id="contact" class="contact">

    <h2 class="section-title">Contact Me</h2>

    <div class="contact-info">
      📍 Hyderabad, Telangana
    </div>

    <div class="contact-info">
      📞 <a href="tel:7569051805">7569051805</a>
    </div>

    <div class="contact-info">
      ✉ <a href="mailto:gubbalaabhinay267@gmail.com">
        gubbalaabhinay267@gmail.com
      </a>
    </div>

    <br>

    <a href="mailto:gubbalaabhinay267@gmail.com" class="btn">
      Send Me an Email
    </a>

  </section>


  <!-- FOOTER -->
  <footer>
    © 2026 Gubbala Abhinay. All Rights Reserved.
  </footer>

</body>
</html>
