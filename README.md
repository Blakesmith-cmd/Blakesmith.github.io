<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blake Smith | Portfolio</title>
  <style>
    :root {
      --bg-color: #121212;
      --text-color: #e0e0e0;
      --accent-color: #00bcd4;
      --card-bg: #1e1e1e;
    }

    body {
      font-family: 'Segoe UI', Arial, sans-serif;
      margin: 0;
      background: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
    }

    header {
      background: #000;
      color: var(--accent-color);
      padding: 3rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      letter-spacing: 2px;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      color: #aaa;
    }

    nav {
      background: #1e1e1e;
      padding: 1rem;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    nav a {
      color: var(--text-color);
      margin: 0 1rem;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: var(--accent-color);
    }

    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }

    h2 {
      color: var(--accent-color);
      border-bottom: 2px solid var(--accent-color);
      padding-bottom: 0.5rem;
    }

    .projects img {
      width: 100%;
      max-width: 500px;
      border-radius: 8px;
      margin-bottom: 1rem;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .projects img:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px rgba(0, 188, 212, 0.7);
    }

    .skills ul {
      list-style: none;
      padding: 0;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 1rem;
    }

    .skills li {
      background: var(--card-bg);
      padding: 1rem;
      border-radius: 6px;
      text-align: center;
      transition: background 0.3s ease, transform 0.3s ease;
    }

    .skills li:hover {
      background: var(--accent-color);
      color: #000;
      transform: translateY(-5px);
    }

    footer {
      background: #000;
      color: #aaa;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    footer a {
      color: var(--accent-color);
      text-decoration: none;
    }

    footer a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

<header>
  <h1>Blake Smith</h1>
  <p>Web Designer | UX/UI | Responsive Design</p>
</header>

<nav>
  <a href="#summary">Summary</a>
  <a href="#projects">Projects</a>
  <a href="#experience">Experience</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
</nav>

<section id="summary">
  <h2>Summary</h2>
  <p>With over six years of experience in web design, Blake brings expertise in UX/UI and responsive design to create impactful websites. Known for blending innovative design with functionality, enhancing user engagement and satisfaction. Notable achievement includes leading a team to boost a client's conversion rates by 40%.</p>
</section>

<section id="projects" class="projects">
  <h2>Projects</h2>
  <h3>Interactive NGO Website Design</h3>
  <img src="images/ngo-website.jpg" alt="NGO Website Project">
  <p>Designed an engaging website for a local NGO, enhancing user engagement and mobilizing community resources.</p>

  <h3>E-Commerce Platform Redesign</h3>
  <img src="images/ecommerce-redesign.jpg" alt="E-Commerce Redesign Project">
  <p>Revitalized the user interface of a growing online retailer, improving navigation and customer satisfaction metrics.</p>
</section>

<section id="experience">
  <h2>Experience</h2>
  <h3>Senior Web Designer | Canvas Creative (2023 - Present)</h3>
  <p>Led a team to revamp a client’s e-commerce site, increasing conversion rates by 40%. Developed 25+ responsive designs and implemented user testing sessions that improved satisfaction scores by 20%.</p>

  <h3>UX/UI Designer | BrightWave Agency (2021 - 2022)</h3>
  <p>Redesigned a client’s website, boosting traffic by 50%. Collaborated with developers to shorten timelines by 15% and designed marketing collateral that increased lead generation by 30%.</p>

  <h3>Visual Designer | PixelWorks Interactive (2020 - 2021)</h3>
  <p>Created 15+ client websites with strong aesthetic appeal and usability. Strengthened clients’ visual identities and market positioning.</p>
</section>

<section id="skills" class="skills">
  <h2>Skills</h2>
  <ul>
    <li>Adobe Creative Suite</li>
    <li>Figma</li>
    <li>HTML/CSS</li>
    <li>Wireframing & Prototyping</li>
    <li>User Testing</li>
  </ul>
</section>

<section id="contact">
  <h2>Contact</h2>
  <p>📍 Dallas, Texas</p>
  <p>📞 +1-(234)-555-1234</p>
  <p>🔗 <a href="https://www.linkedin.com">LinkedIn</a> | <a href="https://www.behance.net/">Behance</a></p>
</section>

<footer>
  <p>&copy; 2026 Blake Smith | Portfolio Website</p>
</footer>

</body>
</html>
https://github.com/pages-themes/architect.git
