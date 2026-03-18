<!DOCTYPE html>
<html>
<head>
  <title>Mini Online Store</title>
  <style>
    body {
      margin: 0;
      font-family: Arial;
    }

    header {
      background: #333;
      color: white;
      padding: 15px;
      text-align: center;
    }

    .container {
      display: flex;
      min-height: 80vh;
    }

    /* EMPTY SIDEBAR (from Student 1) */
    .sidebar {
      width: 200px;
      background: #444;
      color: white;
      padding: 15px;
    }

    .content {
      flex: 1;
      padding: 20px;
      background: #f4f4f4;
    }

    /* STUDENT 2 FEATURE */
    .products {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }

    .item {
      background: white;
      padding: 15px;
      border-radius: 10px;
      width: 150px;
      text-align: center;
    }

    footer {
      background: #333;
      color: white;
      text-align: center;
      padding: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>Mini Online Store</h1>
</header>

<div class="container">

  <!-- EMPTY SIDEBAR -->
  <div class="sidebar">
    <h3>Categories</h3>
    <p>Categories here</p>
  </div>

  <!-- STUDENT 2 FEATURE -->
  <div class="content">
    <h2>Products</h2>

    <div class="products">
      <div class="item">
        <h3>T-Shirt</h3>
        <p>₱250</p>
      </div>

      <div class="item">
        <h3>Shoes</h3>
        <p>₱1200</p>
      </div>

      <div class="item">
        <h3>Bag</h3>
        <p>₱500</p>
      </div>
    </div>

  </div>

</div>

<footer>
  <p>© 2026 Mini Online Store</p>
</footer>

</body>
</html>