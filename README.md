Frontend Developer Portfolio – Code Sample

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Segoe UI', sans-serif; background: #f4f4f4; color: #333; }
    header { background: #111; color: #fff; padding: 2rem; text-align: center; }
    nav a { margin: 0 1rem; color: #fff; text-decoration: none; font-weight: bold; }
    section { padding: 2rem; }
    .hero { text-align: center; margin-top: 1rem; }
    .hero h1 { font-size: 2.5rem; }
    .hero p { margin: 1rem 0; font-size: 1.2rem; }
    .btn { background: #007bff; color: white; padding: 0.7rem 1.5rem; border: none; border-radius: 5px; cursor: pointer; }
    .projects, .services { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; }
    .card { background: white; padding: 1rem; border-radius: 10px; box-shadow: 0 0 10px rgba(0,0,0,0.1); }
    footer { background: #222; color: #eee; text-align: center; padding: 1rem; margin-top: 2rem; }
  </style>
</head>
<body>
  <header>
    <h1>Your Name</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#projects">Projects</a>
      <a href="#services">Services</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Frontend Developer & UI/UX Enthusiast</h1>
    <p>I build modern, responsive websites and apps. Let’s bring your idea to life!</p>
    <button class="btn">View Projects</button>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I’m a frontend developer with 4+ years of experience. I build user-friendly websites, e-commerce platforms, and interactive tools like live code editors.</p>
  </section>

  <section id="projects">
    <h2>Projects</h2>
    <div class="projects">
      <div class="card">
        <h3>Live Code Editor</h3>
        <p>HTML/CSS/JS editor with real-time preview.</p>
        <a href="#">Live Demo</a> | <a href="#">GitHub</a>
      </div>
      <div class="card">
        <h3>E-commerce Website</h3>
        <p>Fully responsive shopping site with cart and checkout features.</p>
        <a href="#">Live Demo</a> | <a href="#">GitHub</a>
      </div>
    </div>
  </section>

  <section id="services">
    <h2>Services</h2>
    <div class="services">
      <div class="card">Frontend Development</div>
      <div class="card">Responsive Web Design</div>
      <div class="card">E-commerce Development</div>
      <div class="card">Website Redesign & Fixing</div>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <p>Email: yourname@example.com</p>
    <p>Phone: +234-000-0000</p>
    <p>WhatsApp / LinkedIn / GitHub</p>
  </section>

  <footer>
    &copy; 2025 Your Name. All rights reserved.
  </footer>
</body>
</html>
