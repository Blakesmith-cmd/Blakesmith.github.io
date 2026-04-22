
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Blake Smith | Futuristic Portfolio</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');

    :root {
      --bg-color: #0a0f1c;
      --text-color: #e0e0ff;
      --accent-color: #00aaff;
      --highlight-color: #ff0044;
      --card-bg: rgba(17, 26, 43, 0.85);
    }

    body {
      font-family: 'Orbitron', sans-serif;
      margin: 0;
      background: var(--bg-color) url('images/redbull-car-logo.jpg') no-repeat center center fixed;
      background-size: cover;
      color: var(--text-color);
      line-height: 1.6;
      position: relative;
      overflow-x: hidden;
    }

    /* Neon animation overlay */
    body::before {
      content: "";
      position: fixed;
      top: 0;
      left: 0;
      width: 200%;
      height: 200%;
      background: repeating-linear-gradient(
        45deg,
        rgba(0, 170, 255, 0.15),
        rgba(0, 170, 255, 0.15) 10px,
        transparent 10px,
        transparent 20px
      );
      animation: moveNeon 10s linear infinite;
      z-index: 0;
    }

    @keyframes moveNeon {
      from { transform: translate(0,0); }
      to { transform: translate(-200px,-200px); }
    }

    header, nav, section, footer {
      position: relative;
      z-index: 1; /* keeps content above animation */
    }

    header {
      background: rgba(0, 0, 0, 0.7);
      color: var(--accent-color);
      padding: 3rem;
      text-align: center;
      text-shadow: 0 0 15px var(--accent-color);
    }

    header h1 {
      margin: 0;
      font-size: 3rem;
      letter-spacing: 3px;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      color: var(--highlight-color);
    }

    nav {
      background: rgba(13, 20, 36, 0.9);
      padding: 1rem;
      text-align: center;
      position: sticky;
      top: 0;
      z-index: 1000;
      border-bottom: 2px solid var(--accent-color);
    }

    nav a {
      color: var(--text-color);
      margin: 0 1rem;
      text-decoration: none;
      transition: color 0.3s ease, text-shadow 0.3s ease;
    }

    nav a:hover {
      color: var(--accent-color);
      text-shadow: 0 0 10px var(--accent-color);
    }

    section {
      padding: 2rem;
      max-width: 1100px;
      margin: auto;
      background: var(--card-bg);
      border-radius: 12px;
      margin-top: 2rem;
    }

    h2 {
      color: var(--accent-color);
      border-bottom: 2px solid var(--highlight-color);
      padding-bottom: 0.5rem;
      text-shadow: 0 0 10px var(--accent-color);
    }

    .projects img {
      width: 100%;
      max-width: 600px;
      border-radius: 12px;
      margin-bottom: 1rem;
      transition: transform 0.4s ease, box-shadow 0.4s ease;
      box-shadow: 0 0 20px rgba(0, 170, 255, 0.6);
    }

    .projects img:hover {
      transform: scale(1.08) rotate(1deg);
      box-shadow: 0 0 40px rgba(255, 0, 68, 0.8);
    }

    .skills ul {
      list-style: none;
      padding: 0;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 1rem;
    }

    .skills li {
      background: var(--card-bg);
      padding: 1rem;
      border-radius: 8px;
      text-align: center;
      transition: background 0.3s ease, transform 0.3s ease, box-shadow 0.3s ease;
    }

    .skills li:hover {
      background: var(--highlight-color);
      color: #fff;
      transform: translateY(-8px);
      box-shadow: 0 0 20px var(--highlight-color);
    }

    footer {
      background: rgba(0, 31, 63, 0.9);
      color: #aaa;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
      border-top: 2px solid var(--accent-color);
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
  <p>Web Designer | UX/UI | Futuristic Design</p>
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
  <p>Blake Smith is a web designer blending futuristic aesthetics with functional UX/UI. With six years of experience, Blake has boosted conversion rates, enhanced user satisfaction, and delivered designs that feel as bold and energetic as a Red Bull racing campaign.</p>
</section>

<section id="projects" class="projects">
  <h2>Projects</h2>
  <h3>Interactive NGO Website Design</h3>
  <img src="images/ngo-futuristic.jpg" alt="Futuristic NGO Website">
  <p>Designed an engaging futuristic NGO platform with glowing accents and immersive visuals.</p>

  <h3>E-Commerce Platform Redesign</h3>
  <img src="images/ecommerce-futuristic.jpg" alt="Futuristic E-Commerce Redesign">
  <p>Revamped an online retailer’s interface with neon blue highlights, boosting navigation and satisfaction.</p>
</section>

<section id="experience">
  <h2>Experience</h2>
  <h3>Senior Web Designer | Canvas Creative (2023 - Present)</h3>
  <p>Led futuristic redesigns that increased conversion rates by 40% and satisfaction scores by 20%.</p>

  <h3>UX/UI Designer | BrightWave Agency (2021 - 2022)</h3>
  <p>Boosted traffic by 50% with bold, high-energy designs inspired by modern branding aesthetics.</p>
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
  <p>📞 +1-(234)-555-765
