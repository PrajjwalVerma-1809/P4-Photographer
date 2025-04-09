# P4-Photographer
My Wedding Photography Website
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>P4 Photographer | Wedding Photography</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Montserrat&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Montserrat', sans-serif;
      background-color: #111;
      color: #fff;
    }
    header {
      background: url('https://images.unsplash.com/photo-1524253482453-3fed8d2fe12b') no-repeat center center/cover;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      margin: 0;
    }
    header p {
      font-size: 1.2rem;
      margin-top: 10px;
    }
    nav {
      background: #000;
      display: flex;
      justify-content: center;
      padding: 15px;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .section-title {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      margin-bottom: 20px;
      text-align: center;
    }
    footer {
      background: #000;
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
    }
    .contact-button {
      display: inline-block;
      padding: 10px 20px;
      background: #e91e63;
      color: #fff;
      text-decoration: none;
      border-radius: 5px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>P4 Photographer</h1>
    <p>Capturing Your Forever Moments</p>
  </header>

  <nav>
    <a href="#about">About</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <section id="about">
    <h2 class="section-title">About Me</h2>
    <p>Hello! I'm Prajjwal Verma, the artist behind P4 Photographer. Specializing in wedding photography, I believe in capturing the most genuine and emotional moments of your big day. My goal is to tell your love story through timeless and elegant photographs.</p>
  </section>

  <section id="portfolio">
    <h2 class="section-title">Portfolio</h2>
    <p>Gallery Coming Soon... (You can add image grids or lightbox here)</p>
  </section>

  <section id="services">
    <h2 class="section-title">Services & Packages</h2>
    <ul>
      <li>Pre-Wedding Shoots</li>
      <li>Wedding Day Coverage</li>
      <li>Candid Photography</li>
      <li>Traditional & Cinematic Videography</li>
    </ul>
  </section>

  <section id="contact">
    <h2 class="section-title">Get In Touch</h2>
    <p>Want to book a shoot or discuss your wedding? Reach out anytime!</p>
    <a class="contact-button" href="https://wa.me/6396250573" target="_blank">Message on WhatsApp</a>
  </section>

  <footer>
    &copy; 2025 P4 Photographer | All rights reserved.
  </footer>
</body>
</html>

