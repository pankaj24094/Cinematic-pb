
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Cinematic Pankyaa</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: linear-gradient(to bottom, #000, #4B0082);
      color: white;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px;
      background-color: #111;
    }

    nav a, #toggleMode {
      color: pink;
      text-decoration: none;
      font-weight: bold;
    }

    .brand-section {
      background: linear-gradient(to right, #000, #4B0082);
      padding: 30px 0;
      text-align: center;
    }

    .brand-section h1 {
      color: hotpink;
      font-size: 3em;
      margin: 0;
      font-weight: bold;
    }

    .brand-profile-pic {
      margin-top: 20px;
    }

    .brand-profile-pic img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid hotpink;
      object-fit: cover;
    }

    .brand-buttons {
      margin-top: 20px;
    }

    .brand-buttons button {
      background-color: pink;
      color: black;
      border: none;
      padding: 10px 20px;
      font-size: 1em;
      font-weight: bold;
      cursor: pointer;
      margin: 0 10px;
      border-radius: 5px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .brand-buttons button:hover {
      transform: scale(1.1);
      box-shadow: 0 0 10px pink;
    }

    hr {
      border: 0;
      height: 2px;
      background: linear-gradient(to right, #ff69b4, #fff, #ff69b4);
      margin: 40px 0;
    }

    section {
      text-align: center;
      padding: 40px 20px;
    }

    h2 {
      color: pink;
    }

    .card-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }

    .card {
      background-color: #222;
      color: white;
      padding: 20px;
      border-radius: 10px;
      width: 250px;
      transition: transform 0.3s ease, opacity 0.3s ease;
      opacity: 0;
      transform: translateY(30px);
      animation: fadeInUp 1s forwards;
    }

    .card:nth-child(1) { animation-delay: 0.2s; }
    .card:nth-child(2) { animation-delay: 0.4s; }
    .card:nth-child(3) { animation-delay: 0.6s; }
    .card:nth-child(4) { animation-delay: 0.8s; }

    @keyframes fadeInUp {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    iframe {
      margin: 10px;
      border: none;
      border-radius: 10px;
    }

    #contact form {
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 15px;
      max-width: 400px;
      margin: auto;
    }

    #contact input, #contact button {
      width: 100%;
      padding: 10px;
      border: none;
      border-radius: 5px;
      font-size: 1em;
    }

    #contact input {
      background-color: #333;
      color: white;
    }

    #contact button {
      background-color: hotpink;
      color: black;
      font-weight: bold;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    #contact button:hover {
      background-color: #ff85b4;
    }

    .contact-profile {
      text-align: center;
      margin-bottom: 20px;
    }

    .contact-profile img {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid hotpink;
      object-fit: cover;
      margin-bottom: 10px;
    }

{
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }

    .button {
      padding: 12px 20px;
      font-size: 16px;
      border: none;
      border-radius: 6px;
      cursor: pointer;
      color: white;
      text-decoration: none;
      display: inline-block;
      margin: 10px 0;
      width: 220px;
      text-align: center;
    }

    .whatsapp {
      background-color: #25D366; /* WhatsApp green */
    }

    .email {
      background-color: #FF69B4; /* Pink */
    }

    .button:hover {
      opacity: 0.9;
    }
  </style>
</head>

<body>
  <nav>
    <button id="toggleMode">🌙 Toggle Mode</button>
    <a href="#about">About Me</a>
    <a href="#work">Work</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="brand-section">
    <h1>Cinematic Pankyaa</h1>

    <!-- 👇 Profile Picture Below Brand Name -->
    <div class="brand-profile-pic">
      <img src="C:\Users\Pankaj\Downloads\WhatsApp Image 2025-07-26 at 11.10.57 PM.jpeg" alt="Profile Picture" />
    </div>

    <div class="brand-buttons">
      <button onclick="document.getElementById('work').scrollIntoView({ behavior: 'smooth' })">View Work</button>
      <button onclick="document.getElementById('contact').scrollIntoView({ behavior: 'smooth' })">Hire Me</button>
    </div>
  </div>

  <hr />

  <section id="about">
    <h2>About Me</h2>
    <p style="max-width: 600px; margin: auto;">I'm a passionate video editor and content creator with a knack for storytelling. With years of experience, I bring moments to life using visuals and sound.</p>
  </section>

  <hr />

  <section id="work">
    <h2>Work Experience</h2>
    <div class="card-container">
      <div class="card">Video Editing - 4 Years</div>
      <div class="card">Shooting - 4 Years</div>
      <div class="card">Post Production - 4 Years</div>
      <div class="card">YouTube Management - 4 Years</div>
    </div>
  </section>

  <hr />

  <section id="portfolio">
    <h2>Portfolio</h2>
    <br>
    <video width="250" height="300" controls><source src="C:\Users\Pankaj\Downloads\WhatsApp Video 2025-07-26 at 8.13.11 PM.mp4" type="video/mp4"></video>
    <video width="250" height="300" controls><source src="C:\Users\Pankaj\Downloads\WhatsApp Video 2025-07-26 at 12.50.38 AM.mp4" type="video/mp4"></video>
    <video width="250" height="300" controls><source src="C:\Users\Pankaj\Downloads\WhatsApp Video 2025-07-26 at 10.49.12 PM.mp4" type="video/mp4"></video><br> <br>
    <video width="250" height="300" controls><source src="C:\Users\Pankaj\Downloads\WhatsApp Video 2025-07-26 at 10.49.01 PM.mp4" type="video/mp4"></video>
    <video width="250" height="300" controls><source src="C:\Users\Pankaj\Downloads\WhatsApp Video 2025-07-26 at 10.59.22 PM.mp4" type="video/mp4"></video>
    <video width="250" height="300" controls><source src="C:\Users\Pankaj\Downloads\WhatsApp Video 2025-07-26 at 11.07.51 PM.mp4" type="video/mp4"></video>


  </section> 

  <hr />

  <section id="services">
    <h2>Services We Offer</h2>
    <div class="card-container">
      <div class="card">Video Shooting<br />High-quality production</div>
      <div class="card">Video Editing<br />Creative and dynamic cuts</div>
      <div class="card">Social Media Creator<br />Optimized for engagement</div>
    </div>
  </section>

  <hr />

  <section id="contact">
    <h2>Contact Us</h2>

    <div class="contact-profile">
<img src="C:\Users\Pankaj\Downloads\d67df532-4b02-46cf-a9f7-8e8a1e5c908e.jpg" alt="Profile Picture" />
      <p><strong>Cinematic Pankyaa</strong><br />Video Editor & Creator</p>
    </div>

  </section>

<center><a href="https://wa.me/1234567890" class="button whatsapp">Chat on WhatsApp</a></center>
 <center> <a href="mailto:someone@example.com" class="button email">Send Email</a>
</center>
</body>
</html>
