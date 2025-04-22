<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>J&J Dining Restaurant - Services</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header {
      background-color: #2e2e2e;
      color: white;
      padding: 10px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      display: flex;
      align-items: center;
      font-size: 24px;
      font-weight: bold;
    }
    .logo img {
      height: 40px;
      margin-right: 10px;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin-left: 20px;
      font-size: 16px;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .hero {
      background-image: url('https://via.placeholder.com/1200x400');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    .section {
      padding: 40px 20px;
      max-width: 1200px;
      margin: auto;
    }
    .services, .store {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .card {
      background: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }
    .store-item img {
      width: 100%;
      border-radius: 8px;
    }
    footer {
      background-color: #2e2e2e;
      color: white;
      text-align: center;
      padding: 20px;
    }
    footer a {
      color: #fff;
      text-decoration: underline;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">
      <img src="https://via.placeholder.com/40x40?text=J&J" alt="J&J Logo">
      J&J Dining Restaurant
    </div>
    <nav>
      <a href="#services">Services</a>
      <a href="#store">Store</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <div class="hero">
    <h2>Welcome to J&J Dining</h2>
    <p>Savor the Taste of Excellence</p>
  </div>

  <section class="section" id="services">
    <h2>Our Services</h2>
    <div class="services">
      <div class="card">
        <h3>Dine-In</h3>
        <p>Enjoy a comfortable, modern dining atmosphere with top-quality service.</p>
      </div>
      <div class="card">
        <h3>Takeaway & Delivery</h3>
        <p>Order your favorites to-go or have them delivered right to your door.</p>
      </div>
      <div class="card">
        <h3>Catering</h3>
        <p>Perfect for events, parties, and corporate gatherings.</p>
      </div>
    </div>
  </section>

  <section class="section" id="store">
    <h2>Online Store</h2>
    <div class="store">
      <div class="card store-item">
        <img src="https://via.placeholder.com/300x200" alt="Dish 1">
        <h3>Grilled Chicken</h3>
        <p>$12.99</p>
        <button>Add to Cart</button>
      </div>
      <div class="card store-item">
        <img src="https://via.placeholder.com/300x200" alt="Dish 2">
        <h3>Veggie Pasta</h3>
        <p>$10.99</p>
        <button>Add to Cart</button>
      </div>
    </div>
  </section>

  <footer id="contact">
    <p>Contact us: info@jandjdining.com | Open Daily 10am - 10pm</p>
    <p>Follow us on <a href="https://facebook.com/YourPageName" target="_blank">Facebook</a></p>
  </footer>
</body>
</html>
