# Juwon-
Food and drinks 
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Juwon Foods</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff8f0;
      scroll-behavior: smooth;
    }
    header {
      background-color: #ff6347;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #ffa07a;
      padding: 10px;
      text-align: center;
    }
    nav a {
      margin: 0 15px;
      color: white;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }
    nav a:hover {
      color: #333;
    }
    .menu {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 40px 20px;
    }
    .item {
      background: white;
      padding: 15px;
      border-radius: 10px;
      text-align: center;
      box-shadow: 0 0 10px #ccc;
      transition: transform 0.3s, box-shadow 0.3s;
    }
    .item:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
    }
    .item img {
      max-width: 100%;
      border-radius: 8px;
    }
    .price {
      color: green;
      font-weight: bold;
      margin: 10px 0;
    }
    .order-btn {
      display: inline-block;
      padding: 10px 20px;
      background-color: #ff6347;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-weight: bold;
      text-decoration: none;
      transition: background 0.3s;
    }
    .order-btn:hover {
      background-color: #e5533d;
    }
    .contact {
      background: #ffe4c4;
      padding: 40px 20px;
      text-align: center;
    }
    .contact h2 {
      margin-bottom: 15px;
    }
    .contact p {
      margin: 5px 0;
    }
    footer {
      background-color: #ff6347;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Juwon Foods</h1>
    <p>Delicious meals delivered to your door!</p>
  </header>

  <nav>
    <a href="#">Home</a>
    <a href="#menu">Menu</a>
    <a href="#contact">Contact</a>
  </nav>

  <div class="menu" id="menu">
    <div class="item">
      <img src="https://images.unsplash.com/photo-1604908177371-68df8c878b43" alt="Jollof Rice">
      <h3>Jollof Rice</h3>
      <p class="price">₦1500</p>
      <a href="https://wa.me/2347045839776?text=I%20want%20to%20order%20Jollof%20Rice" class="order-btn">Order Now</a>
    </div>
    <div class="item">
      <img src="https://images.unsplash.com/photo-1630851840639-802d7ed2b71a" alt="Fried Rice">
      <h3>Fried Rice</h3>
      <p class="price">₦1800</p>
      <a href="https://wa.me/2347045839776?text=I%20want%20to%20order%20Fried%20Rice" class="order-btn">Order Now</a>
    </div>
    <div class="item">
      <img src="https://images.unsplash.com/photo-1617196039897-3e64c1cc0a0e" alt="Efo Riro">
      <h3>Efo Riro</h3>
      <p class="price">₦2000</p>
      <a href="https://wa.me/2347045839776?text=I%20want%20to%20order%20Efo%20Riro" class="order-btn">Order Now</a>
    </div>
    <div class="item">
      <img src="https://images.unsplash.com/photo-3B27OmEt5qtLDs9fh"alt="whiterice and veggies ">
      <h3>whiterice and veggies  </h3>
      <p class="price">₦3500</p>
      <a href="https://wa.me/2347045839776?text=I%20want%20to%20order%20White%20Rice%20and%20Veggies" class="order-btn">Order Now</a>
    </div>
  </div>

  <section class="contact" id="contact">
    <h2>Contact Us</h2>
    <p>📍 Address: 123 Food Street, Lagos, Nigeria</p>
    <p>📞 Phone: +234 7045839776</p>
    <p>📧 Email: support@juwonfoods.com</p>
  </section>

  <footer>
    &copy; 2025 Juwon Foods. All rights reserved.
  </footer>
</body>
</html>
