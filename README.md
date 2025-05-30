<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Gift Bracelets - Unique Gift Bracelets</title>
  <!-- Google Fonts for a modern look -->
  <link href="https://fonts.googleapis.com/css?family=Montserrat:400,700|Open+Sans:400,600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Open Sans', sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f4f4f4;
    }
    header {
      background: #ffffff;
      padding: 20px 0;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }
    .container {
      width: 90%;
      max-width: 1200px;
      margin: auto;
    }
    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 1.8em;
      font-weight: 700;
      font-family: 'Montserrat', sans-serif;
      color: #333;
    }
    .nav-links {
      list-style: none;
      display: flex;
    }
    .nav-links li {
      margin-left: 20px;
    }
    .nav-links a {
      text-decoration: none;
      color: #333;
      font-weight: 600;
      transition: color 0.3s ease;
    }
    .nav-links a:hover {
      color: #007BFF;
    }
    .hero {
      background: url('https://source.unsplash.com/1600x900/?bracelet') no-repeat center center/cover;
      height: 70vh;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #fff;
      text-align: center;
    }
    .hero h1 {
      font-size: 3em;
      font-family: 'Montserrat', sans-serif;
    }
    section {
      padding: 60px 0;
    }
    .section-title {
      text-align: center;
      font-size: 2em;
      margin-bottom: 20px;
      font-family: 'Montserrat', sans-serif;
    }
    .about, .products {
      background: #ffffff;
      padding: 40px 0;
    }
    .about p, .products p {
      max-width: 800px;
      margin: auto;
      text-align: center;
      font-size: 1.1em;
      color: #555;
    }
    .product-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      margin-top: 30px;
    }
    .product-item {
      background: #fff;
      border: 1px solid #ddd;
      border-radius: 4px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .product-item:hover {
      transform: translateY(-5px);
    }
    .product-img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .product-info {
      padding: 15px;
      text-align: center;
    }
    .contact {
      background: #ffffff;
      padding: 40px 0;
    }
    form {
      max-width: 600px;
      margin: auto;
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ddd;
      border-radius: 4px;
    }
    form button {
      background: #007BFF;
      color: #fff;
      border: none;
      padding: 10px 20px;
      border-radius: 4px;
      cursor: pointer;
      font-size: 1em;
    }
    form button:hover {
      background: #0056b3;
    }
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 20px 0;
    }
    @media (max-width: 768px) {
      .hero { height: 50vh; }
      .hero h1 { font-size: 2.5em; }
    }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <nav>
        <div class="logo">Gift Bracelets</div>
        <ul class="nav-links">
          <li><a href="#home">Home</a></li>
          <li><a href="#about">About</a></li>
          <li><a href="#products">Products</a></li>
          <li><a href="#contact">Contact</a></li>
        </ul>
      </nav>
    </div>
  </header>

  <section class="hero" id="home">
    <div class="container">
      <h1>Unique Gift Bracelets</h1>
      <p>The perfect gift for that special someone.</p>
    </div>
  </section>

  <section class="about" id="about">
    <div class="container">
      <h2 class="section-title">About Us</h2>
      <p>We believe that a gift carries meaning and emotion. Our bracelets are designed with attention to detail, crafted to express love and special moments. Enjoy our unique designs, perfect for any occasion—from birthdays to meaningful celebrations shared with loved ones.</p>
    </div>
  </section>

  <section class="products" id="products">
    <div class="container">
      <h2 class="section-title">Our Products</h2>
      <p>Explore our collection of stylish gift bracelets – the perfect present for you and your loved ones.</p>
      <div class="product-grid">
        <div class="product-item">
          <img class="product-img" src="https://source.unsplash.com/400x300/?bracelet,red" alt="Bracelet 1">
          <div class="product-info">
            <h3>Bracelet 1</h3>
            <p>Sophisticated and elegant for those special moments.</p>
          </div>
        </div>
        <div class="product-item">
          <img class="product-img" src="https://source.unsplash.com/400x300/?bracelet,blue" alt="Bracelet 2">
          <div class="product-info">
            <h3>Bracelet 2</h3>
            <p>A modern take combining elegance and classic style.</p>
          </div>
        </div>
        <div class="product-item">
          <img class="product-img" src="https://source.unsplash.com/400x300/?bracelet,gold" alt="Bracelet 3">
          <div class="product-info">
            <h3>Bracelet 3</h3>
            <p>Glimmer and sophistication in every detail.</p>
          </div>
        </div>
        <div class="product-item">
          <img class="product-img" src="https://source.unsplash.com/400x300/?bracelet,silver" alt="Bracelet 4">
          <div class="product-info">
            <h3>Bracelet 4</h3>
            <p>Unique design made for the modern individual.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <div class="container">
      <h2 class="section-title">Contact Us</h2>
      <form action="#" method="post">
        <input type="text" name="name" placeholder="Name" required>
        <input type="email" name="email" placeholder="Email" required>
        <textarea name="message" rows="5" placeholder="Your message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    <div class="container">
      <p>&copy; 2025 Gift Bracelets. All rights reserved.</p>
    </div>
  </footer>
</body>
</html>
