-<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Just Sweets Sugar!!</title>
  <style>
    /* Basic reset */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      color: #333;
      background-color: #f9f9f9;
    }

    /* Header styling */
    header {
      background: #ff6f61;
      color: #fff;
      padding: 1rem 0;
      text-align: center;
    }

    header h1 {
      font-size: 2.5rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.2rem;
    }

    /* Navigation styling */
    nav {
      background: #333;
    }

    nav ul {
      display: flex;
      justify-content: center;
      list-style: none;
    }

    nav ul li {
      margin: 0;
    }

    nav ul li a {
      display: block;
      padding: 1rem 1.5rem;
      color: #fff;
      text-decoration: none;
      transition: background 0.3s;
    }

    nav ul li a:hover {
      background: #555;
    }

    /* Main sections styling */
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: 0 auto;
      background: #fff;
      margin-bottom: 1rem;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    section h2 {
      color: #ff6f61;
      margin-bottom: 1rem;
    }

    section p {
      margin-bottom: 1rem;
      font-size: 1rem;
    }

    /* Contact form styling */
    form {
      display: flex;
      flex-direction: column;
      max-width: 500px;
    }

    form label {
      margin: 0.5rem 0 0.2rem;
    }

    form input,
    form textarea {
      padding: 0.5rem;
      border: 1px solid #ccc;
      border-radius: 3px;
      margin-bottom: 1rem;
      font-size: 1rem;
    }

    form button {
      padding: 0.7rem;
      border: none;
      background: #ff6f61;
      color: #fff;
      font-size: 1rem;
      border-radius: 3px;
      cursor: pointer;
      transition: background 0.3s;
    }

    form button:hover {
      background: #e65b50;
    }

    /* Footer styling */
    footer {
      background: #333;
      color: #fff;
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
    }

    /* Responsive navigation */
    @media (max-width: 600px) {
      nav ul {
        flex-direction: column;
      }
    }
  </style>
</head>
<body>
  <!-- Header Section -->
  <header>
    <h1>Just Sweets Sugar!!</h1>
    <p>Delicious Cheesecakes and More to Come!</p>
  </header>

  <!-- Navigation Menu -->
  <nav>
    <ul>
      <li><a href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#products">Products</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>

  <!-- Home Section -->
  <section id="home">
    <h2>Welcome to Just Sweets Sugar!!</h2>
    <p>
      Located at 1300 Marketplace in Failane Mall, Dearborn, Michigan, we specialize in mouthwatering cheesecakes made with the freshest ingredients. Our treats are crafted with love and designed to delight your taste buds.
    </p>
  </section>

  <!-- About Section -->
  <section id="about">
    <h2>About Us</h2>
    <p>
      At Just Sweets Sugar!!, our passion for baking shines through every slice of our cheesecake. Our journey started with a simple goal: to bring a smile to every customer's face through our sweet creations. While our specialty is cheesecakes, we’re excited to expand our menu with more baked goods in the near future.
    </p>
    <p>
      We believe that every treat should not only taste amazing but also be a work of art that celebrates the joy of life.
    </p>
  </section>

  <!-- Products Section -->
  <section id="products">
    <h2>Our Products</h2>
    <p>
      Our signature cheesecake is a customer favorite—rich, creamy, and bursting with flavor. We use the finest ingredients and time-honored recipes to ensure every bite is a delight.
    </p>
    <p>
      Stay tuned as we introduce new baked goods to our menu. From cookies to cupcakes, we’re continuously working to bring more sweetness into your life!
    </p>
  </section>

  <!-- Contact Section -->
  <section id="contact">
    <h2>Contact Us</h2>
    <p>
      Have a question or want to place an order? Reach out to us!
    </p>
    <p>
      <strong>Address:</strong> 1300 Marketplace, Failane Mall, Dearborn, Michigan
    </p>
    <form action="#" method="post">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" placeholder="Your name" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" placeholder="Your email" required>

      <label for="message">Message:</label>
      <textarea id="message" name="message" placeholder="Your message" rows="5" required></textarea>

      <button type="submit">Send Message</button>
    </form>
  </section>

  <!-- Footer -->
  <footer>
    <p>&copy; 2025 Just Sweets Sugar!!. All rights reserved.</p>
  </footer>
</body>
</html>
--
title: Just Sweets Sugar!!
---

