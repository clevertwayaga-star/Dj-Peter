# Dj-Peter<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>DJ Peter 256</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, Helvetica, sans-serif;
      background: #0b0b0b;
      color: #fff;
    }
    header {
      height: 100vh;
      background: linear-gradient(135deg, #ff0000, #0033ff);
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
    }
    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
    }
    header p {
      font-size: 1.2rem;
    }
    nav {
      position: fixed;
      top: 0;
      width: 100%;
      background: rgba(0,0,0,0.8);
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      z-index: 1000;
    }
    nav a {
      color: #fff;
      margin-left: 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 60px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .card {
      background: #1a1a1a;
      padding: 20px;
      border-radius: 12px;
      margin-bottom: 20px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.5);
    }
    .music iframe {
      width: 100%;
      height: 120px;
      border: none;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #000;
      font-size: 0.9rem;
    }
    button {
      background: red;
      border: none;
      padding: 12px 20px;
      border-radius: 25px;
      color: #fff;
      font-size: 1rem;
      cursor: pointer;
    }
    button:hover {
      opacity: 0.8;
    }
  </style>
</head>
<body>  <nav>
    <strong>DJ Peter 256</strong>
    <div>
      <a href="#about">About</a>
      <a href="#music">Music</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
      <a href="https://www.tiktok.com/@djpeter256" target="_blank">TikTok</a>
    </div>
  </nav>  <header>
    <div>
      <h1>DJ Peter 256</h1>
      <p>Dancehall • Afrobeat • Club Vibes</p>
      <button onclick="document.getElementById('music').scrollIntoView({behavior:'smooth'})">Listen Now</button>
    </div>
  </header>  <section id="about">
    <div class="card">
      <h2>About Me</h2>
      <p>I am DJ Peter 256, bringing heavy dancehall, afrobeat and party vibes. Available for clubs, events, weddings and online mixes.</p>
    </div>
  </section>  <section id="music" class="music">
    <div class="card">
      <h2>Latest Mix</h2>
      <p>Listen to my latest mixes on YouTube.</p>
      <iframe src="https://www.youtube.com/embed?listType=search&list=DJ+Peter+256" allowfullscreen></iframe>
      <p style="margin-top:10px;">
        <a href="https://youtube.com/@twayaga-166" target="_blank" style="color:#ff0000;font-weight:bold;">▶ Visit my YouTube Channel</a>
      </p>
    </div>
  </section>  <section id="gallery">
    <div class="card">
      <h2>Photo Gallery</h2>
      <p>Event moments, club nights & DJ vibes.</p>
      <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(150px,1fr));gap:12px;">
        <div style="background:#333;height:150px;border-radius:10px;display:flex;align-items:center;justify-content:center;">Photo 1</div>
        <div style="background:#333;height:150px;border-radius:10px;display:flex;align-items:center;justify-content:center;">Photo 2</div>
        <div style="background:#333;height:150px;border-radius:10px;display:flex;align-items:center;justify-content:center;">Photo 3</div>
        <div style="background:#333;height:150px;border-radius:10px;display:flex;align-items:center;justify-content:center;">Photo 4</div>
      </div>
    </div>
  </section>  <section id="contact">
    <div class="card">
      <h2>Contact & Bookings</h2>
      <p>Phone / WhatsApp: +256 XXX XXX XXX</p>
      <p>Email: djpeter256@email.com</p>
    </div>
  </section>  <footer>
    © 2026 DJ Peter 256. All Rights Reserved.
  </footer>  <!-- WhatsApp Floating Button -->  <a href="https://wa.me/256704453743" target="_blank" style="position:fixed;bottom:20px;right:20px;background:#25D366;color:#fff;padding:14px 18px;border-radius:50px;text-decoration:none;font-weight:bold;box-shadow:0 10px 25px rgba(0,0,0,0.4);z-index:2000;">
    💬 Book on WhatsApp
  </a></body>
</html>
