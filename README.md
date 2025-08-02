# Tienda HT Global
ROPA HT
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Tienda HT Global - Ecommerce</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f6f6f6;
    }
    header {
      background-color: #333;
      color: white;
      padding: 15px;
      text-align: center;
    }
    nav {
      background-color: #555;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 10px;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: #ddd url('https://via.placeholder.com/1200x300?text=Bienvenido+a+Tienda+Global') no-repeat center center;
      background-size: cover;
      height: 300px;
    }
    .container {
      padding: 20px;
    }
    .product {
      background-color: white;
      border: 1px solid #ccc;
      border-radius: 5px;
      margin: 10px;
      padding: 15px;
      width: calc(33% - 40px);
      box-sizing: border-box;
      float: left;
    }
    .product img {
      max-width: 100%;
      height: auto;
    }
    .product h3 {
      margin: 10px 0;
    }
    .product p {
      font-size: 14px;
    }
    .product button {
      background-color: #28a745;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }
    footer {
      clear: both;
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
  <header>
    <h1>Tienda Global</h1>
    <p>Tu mercado online de confianza</p>
  </header>
  <nav>
    <a href="#">Inicio</a>
    <a href="#">Productos</a>
    <a href="#">Ofertas</a>
    <a href="#">Contacto</a>
  </nav>
  <div class="hero"></div>
  <div class="container">
    <div class="product">
      <img src="https://via.placeholder.com/300x200?text=Producto+1" alt="Producto 1">
      <h3>Producto 1</h3>
      <p>Descripción breve del producto.</p>
      <p><strong>$19.99</strong></p>
      <button>Agregar al carrito</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x200?text=Producto+2" alt="Producto 2">
      <h3>Producto 2</h3>
      <p>Descripción breve del producto.</p>
      <p><strong>$29.99</strong></p>
      <button>Agregar al carrito</button>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x200?text=Producto+3" alt="Producto 3">
      <h3>Producto 3</h3>
      <p>Descripción breve del producto.</p>
      <p><strong>$39.99</strong></p>
      <button>Agregar al carrito</button>
    </div>
  </div>
  <footer>
    <p>&copy; 2025 Tienda Global - Todos los derechos reservados</p>
  </footer>
</body>
</html>
