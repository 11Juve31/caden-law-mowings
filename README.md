<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Canden Lawn Mowing</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
      color: #333;
    }
    header, nav, footer {
      background-color: #2e7d32;
      color: white;
      text-align: center;
      padding: 1em;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
    }
    .container {
      padding: 20px;
      max-width: 900px;
      margin: auto;
      background: white;
      margin-top: 20px;
      border-radius: 8px;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    .contact-form button {
      background-color: #2e7d32;
      color: white;
      padding: 10px 20px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    .hero {
      text-align: center;
    }
    .hero img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Canden Lawn Mowing</h1>
    <p>Reliable Lawn Care in McKinney, Texas</p>
  </header>
  <nav>
    <a href="#home">Home</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="container" id="home">
    <div class="hero">
      <h2>Welcome to Canden Lawn Mowing</h2>
      <p>Affordable and professional lawn care for your home or business.</p>
      <img src="https://via.placeholder.com/800x400?text=Lawn+Mowing+Service" alt="Lawn Mowing" />
    </div>
  </div>

  <div class="container" id="about">
    <h2>About Us</h2>
    <p>At Canden Lawn Mowing, we take pride in keeping McKinney lawns neat, green, and healthy. Our team is committed to excellent service, timely appointments, and affordable prices. Whether it’s a one-time cut or a regular schedule, we’ve got you covered!</p>
  </div>

  <div class="container" id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form">
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </div>

  <footer>
    <p>&copy; 2025 Canden Lawn Mowing - McKinney, TX</p>
  </footer>
</body>
</html>
