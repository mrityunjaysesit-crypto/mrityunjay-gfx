<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mrityunjay_GFX | Creative Designer</title>
  <style>
    :root {
      --bg: #0f172a;
      --card: #111827;
      --accent: #38bdf8;
      --text: #e5e7eb;
      --muted: #9ca3af;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: linear-gradient(120deg, #020617, #0f172a);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      padding: 40px 20px;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      letter-spacing: 1px;
    }

    header span {
      color: var(--accent);
    }

    header p {
      margin-top: 10px;
      color: var(--muted);
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      margin-top: 20px;
    }

    nav a {
      color: var(--text);
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover { color: var(--accent); }

    section {
      max-width: 1100px;
      margin: 60px auto;
      padding: 0 20px;
    }

    .section-title {
      font-size: 1.8rem;
      margin-bottom: 20px;
      border-left: 4px solid var(--accent);
      padding-left: 10px;
    }

    .about {
      background: var(--card);
      padding: 30px;
      border-radius: 16px;
    }

    .services, .portfolio {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: var(--card);
      padding: 25px;
      border-radius: 18px;
      transition: transform 0.3s, box-shadow 0.3s;
    }

    .card:hover {
      transform: translateY(-6px);
      box-shadow: 0 10px 30px rgba(0,0,0,0.4);
    }

    .card h3 {
      margin-bottom: 10px;
      color: var(--accent);
    }

    .portfolio img {
      width: 100%;
      border-radius: 14px;
      margin-bottom: 10px;
    }

    .contact {
      background: var(--card);
      padding: 30px;
      border-radius: 18px;
      text-align: center;
    }

    .contact a {
      display: inline-block;
      margin-top: 15px;
      padding: 12px 28px;
      background: var(--accent);
      color: #020617;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 30px 20px;
      color: var(--muted);
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Mrityunjay<span>_GFX</span></h1>
    <p>Graphic Designer • Creative Visuals • Branding</p>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <h2 class="section-title">About Me</h2>
    <div class="about">
      <p>
        Hi, I’m <strong>Mrityunjay</strong>, a creative graphic designer known as <strong>Mrityunjay_GFX</strong>. 
        I design modern, eye‑catching visuals for social media, brands, and digital platforms.
      </p>
    </div>
  </section>

  <section id="services">
    <h2 class="section-title">Services</h2>
    <div class="services">
      <div class="card">
        <h3>Social Media Designs</h3>
        <p>Instagram posts, YouTube thumbnails, banners, and ads.</p>
      </div>
      <div class="card">
        <h3>Branding</h3>
        <p>Logos, brand identity, color palettes, and typography.</p>
      </div>
      <div class="card">
        <h3>Photo Manipulation</h3>
        <p>Creative edits, retouching, and cinematic effects.</p>
      </div>
    </div>
  </section>

  <section id="portfolio">
    <h2 class="section-title">Portfolio</h2>
    <div class="portfolio">
      <div class="card">
        <img src="https://via.placeholder.com/400x250" alt="Work 1" />
        <p>Creative Poster Design</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x250" alt="Work 2" />
        <p>YouTube Thumbnail</p>
      </div>
      <div class="card">
        <img src="https://via.placeholder.com/400x250" alt="Work 3" />
        <p>Brand Identity</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2 class="section-title">Contact</h2>
    <div class="contact">
      <p>Want to work together or need custom designs?</p>
      <a href="mailto:mrityunjaygfx@email.com">Contact Me</a>
    </div>
  </section>

  <footer>
    <p>© 2026 Mrityunjay_GFX. All rights reserved.</p>
  </footer>

</body>
</html>
