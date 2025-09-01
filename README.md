# Namma_deals-
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Namma Deals - Online Shopping</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #f4f4f4;
    }
    header {
      background: #e40046;
      color: #fff;
      padding: 15px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      margin: 0;
      font-size: 24px;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
    }
    .search-box {
      flex: 1;
      margin: 0 20px;
    }
    .search-box input {
      width: 100%;
      padding: 8px;
      border-radius: 5px;
      border: none;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product-card {
      background: white;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0px 2px 6px rgba(0,0,0,0.2);
      text-align: center;
    }
    .product-card img {
      width: 100%;
      height: 180px;
      object-fit: contain;
    }
    .product-card h3 {
      margin: 10px 0;
      font-size: 18px;
    }
    .product-card p {
      color: green;
      font-weight: bold;
    }
    .btn {
      display: inline-block;
      margin-top: 10px;
      padding: 8px 12px;
      background: #e40046;
      color: white;
      border-radius: 5px;
      text-decoration: none;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #222;
      color: #fff;
      margin-top: 20px;
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <h1># Namma_deals</h1>
    <div class="search-box">
      <input type="text" placeholder="Search for products...">
    </div>
    <nav>
      <a href="#">Home</a>
      <a href="#">Cart 🛒</a>
      <a href="#">Login</a>
    </nav>
  </header>

  <!-- Products Section -->
  <section class="products">
    <div class="product-card">
      <img src="https://via.placeholder.com/200" alt="Product 1">
      <h3>Smart Watch</h3>
      <p>₹599</p>
      <a href="#" class="btn">Add to Cart</a>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/200" alt="Product 2">
      <h3>Mini Bluetooth Speaker</h3>
      <p>₹499</p>
      <a href="#" class="btn">Add to Cart</a>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/200" alt="Product 3">
      <h3>Display Earbuds</h3>
      <p>₹849</p>
      <a href="#" class="btn">Add to Cart</a>
    </div>

    <div class="product-card">
      <img src="https://via.placeholder.com/200" alt="Product 4">
      <h3>LED Ring Light</h3>
      <p>₹499</p>
      <a href="#" class="btn">Add to Cart</a>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <p>© 2025 Namma_deals | All Rights Reserved</p>
  </footer>

</body>
</html>
