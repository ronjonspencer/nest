<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Nest Garden Furniture</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f9f9f9;
      color: #333;
    }

    header {
      background: #2f5d3a;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      background: #3e7b4f;
    }

    nav a {
      color: white;
      padding: 1rem 1.5rem;
      text-decoration: none;
      font-weight: bold;
    }

    nav a:hover {
      background: #2f5d3a;
    }

    .hero {
      background: url('https://images.unsplash.com/photo-1598300053653-1f7f3c7eca21') no-repeat center/cover;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }

    .hero h1 {
      font-size: 3rem;
      margin-bottom: 1rem;
    }

    .btn {
      background: #ff914d;
      color: white;
      padding: 12px 25px;
      text-decoration: none;
      border-radius: 5px;
      display: inline-block;
      margin-top: 10px;
    }

    .container {
      padding: 2rem;
      max-width: 1100px;
      margin: auto;
    }

    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }

    .card {
      background: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
      text-align: center;
    }

    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }

    .card h3 {
      margin: 10px 0;
    }

    footer {
      background: #2f5d3a;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2rem;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Nest Garden Furniture</h1>
  <p>Stylish Outdoor Living Starts Here</p>
</header>

<nav>
  <a href="#">Home</a>
  <a href="#products">Products</a>
  <a href="#about">About</a>
  <a href="#contact">Contact</a>
</nav>

<section class="hero">
  <h1>Transform Your Garden</h1>
  <p>Premium outdoor furniture for comfort and style</p>
  <a href="#products" class="btn">Shop Now</a>
</section>

<div class="container" id="products">
  <h2>Our Collection</h2>
  <div class="products">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1616628182506-3bcb35c0a4d4" alt="Garden Sofa">
      <h3>Luxury Garden Sofa</h3>
      <p>Comfortable and weather-resistant seating.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1598300042247-d088f8ab3a91" alt="Dining Set">
      <h3>Outdoor Dining Set</h3>
      <p>Perfect for summer meals and gatherings.</p>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c" alt="Sun Lounger">
      <h3>Sun Lounger</h3>
      <p>Relax and enjoy the sunshine in style.</p>
    </div>

  </div>
</div>

<div class="container" id="about">
  <h2>About Us</h2>
  <p>Nest Garden Furniture brings you high-quality, stylish outdoor pieces designed to make your garden a place you love to spend time in.</p>
</div>

<div class="container" id="contact">
  <h2>Contact</h2>
  <p>Email: hello@nest.github.io</p>
</div>

<footer>
  <p>&copy; 2026 Nest Garden Furniture</p>
</footer>

</body>
</html>
