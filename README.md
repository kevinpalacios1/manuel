<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Manuel's Painting Co</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background-color: #f5f1e9;
      color: #333;
    }
    header, footer {
      background-color: #e6ddce;
      padding: 20px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #333;
      font-weight: bold;
    }
    .container {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    .logo {
      max-width: 150px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 8px;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      max-width: 400px;
    }
    input, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: #333;
      color: #fff;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
  </style>
</head>
<body>
  <header>
    <img src="/mnt/data/ChatGPT Image Jun 14, 2025, 12_00_19 PM.png" alt="Logo" class="logo" />
    <h1>Manuel's Painting Co</h1>
    <p>Commercial and Residential Painting in South Florida</p>
    <nav>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="home" class="container">
    <h2>Welcome to Manuel's Painting Co</h2>
    <p>We provide top-quality commercial and residential painting services in South Florida. Our team is committed to delivering clean, efficient, and beautiful work on every project.</p>
  </section>

  <section id="about" class="container">
    <h2>About Us</h2>
    <p>Manuel's Painting Co is a trusted name in South Florida. We specialize in both interior and exterior painting for homes and businesses. With a focus on detail, professionalism, and customer satisfaction, we make sure every job is done right.</p>
  </section>

  <section id="gallery" class="container">
    <h2>Gallery</h2>
    <div class="gallery">
      <!-- Add your project images here -->
      <img src="https://via.placeholder.com/300x200" alt="Project 1">
      <img src="https://via.placeholder.com/300x200" alt="Project 2">
      <img src="https://via.placeholder.com/300x200" alt="Project 3">
    </div>
  </section>

  <section id="contact" class="container">
    <h2>Contact Us</h2>
    <p>Phone: <strong>951-422-4346</strong></p>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="4" placeholder="Your Message" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Manuel's Painting Co. All rights reserved.</p>
  </footer>
</body>
</html>
