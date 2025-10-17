<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ella’s Accessories Shop</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #fafafa;
      color: #333;
    }

    header {
      background-color: #f5d0c5;
      text-align: center;
      padding: 2.5rem 1rem;
    }

    header h1 {
      font-size: 2rem;
      margin-bottom: 0.5rem;
    }

    header p {
      font-size: 1.1rem;
      color: #555;
    }

    .container {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
      padding: 2rem;
      max-width: 1100px;
      margin: auto;
    }

    .product {
      background-color: white;
      border-radius: 12px;
      box-shadow: 0 3px 8px rgba(0, 0, 0, 0.1);
      overflow: hidden;
      transition: transform 0.2s ease;
    }

    .product:hover {
      transform: translateY(-4px);
    }

    .product img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }

    .info {
      padding: 1rem;
      text-align: center;
    }

    .info h3 {
      margin: 0.5rem 0;
      font-size: 1.2rem;
    }

    .info p {
      color: #777;
      margin: 0.5rem 0 1rem 0;
    }

    .price {
      font-weight: bold;
      color: #c15a41;
      font-size: 1.1rem;
    }

    .btn {
      background-color: #c15a41;
      color: white;
      padding: 0.6rem 1.2rem;
      border-radius: 25px;
      border: none;
      cursor: pointer;
      text-decoration: none;
      font-size: 0.9rem;
    }

    .btn:hover {
      background-color: #a84834;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background-color: #f5d0c5;
      color: #333;
      margin-top: 3rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Ella’s Accessories</h1>
    <p>Chic & Simple | Handmade with love 💖</p>
  </header>

  <main class="container">
    <div class="product">
      <img src="https://images.unsplash.com/photo-1618354691120-7b8d6a97cebc?auto=format&fit=crop&w=800&q=80" alt="Necklace">
      <div class="info">
        <h3>Gold Charm Necklace</h3>
        <p class="price">$22.90</p>
        <a href="https://m.me/yourfacebook" class="btn">Order via Messenger</a>
      </div>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1612817159949-1cfaf69cb761?auto=format&fit=crop&w=800&q=80" alt="Bracelet">
      <div class="info">
        <h3>Minimalist Bracelet</h3>
        <p class="price">$14.50</p>
        <a href="https://m.me/yourfacebook" class="btn">Order via Messenger</a>
      </div>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1600180758890-6d8d4d2a7b84?auto=format&fit=crop&w=800&q=80" alt="Earrings">
      <div class="info">
        <h3>Pearl Drop Earrings</h3>
        <p class="price">$18.00</p>
        <a href="https://m.me/yourfacebook" class="btn">Order via Messenger</a>
      </div>
    </div>

    <div class="product">
      <img src="https://images.unsplash.com/photo-1618354690555-d5b3f7322f24?auto=format&fit=crop&w=800&q=80" alt="Rings">
      <div class="info">
        <h3>Stackable Rings Set</h3>
        <p class="price">$16.90</p>
        <a href="https://m.me/yourfacebook" class="btn">Order via Messenger</a>
      </div>
    </div>
  </main>

  <footer>
    © 2025 Ella’s Accessories · Handmade with ❤️ · <a href="https://www.instagram.com/" style="color:#c15a41;text-decoration:none;">@ellas.accessories</a>
  </footer>
</body>
</html>
