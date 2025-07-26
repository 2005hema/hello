<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Simple Shop</title>
  <style>
    /* Minimal inline styles for basic layout */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f5f5f5;
    }
    header {
      background-color: #007bff;
      color: white;
      padding: 15px 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    .products {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      padding: 20px;
      gap: 20px;
    }
    .product {
      background-color: white;
      border: 1px solid #ddd;
      border-radius: 5px;
      width: 200px;
      padding: 15px;
      box-shadow: 0 0 5px #ccc;
    }
    .product h3 {
      margin-top: 0;
    }
    .price {
      font-weight: bold;
      color: #28a745;
    }
    button {
      background-color: #007bff;
      color: white;
      border: none;
      padding: 10px;
      width: 100%;
      cursor: pointer;
      font-size: 16px;
      border-radius: 4px;
      margin-top: 10px;
    }
    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

<header>
  <h1>Simple Shop</h1>
</header>

<section class="products">
  <div class="product">
    <h3>Product 1</h3>
    <p>High-quality item perfect for your needs.</p>
    <p class="price">$19.99</p>
    <button>Add to Cart</button>
  </div>
  
  <div class="product">
    <h3>Product 2</h3>
    <p>Reliable and affordable, a great choice.</p>
    <p class="price">$29.99</p>
    <button>Add to Cart</button>
  </div>

  <div class="product">
    <h3>Product 3</h3>
    <p>Top-rated and loved by many customers.</p>
    <p class="price">$39.99</p>
    <button>Add to Cart</button>
  </div>
</section>

</body>
</html>
