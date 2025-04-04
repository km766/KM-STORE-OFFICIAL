<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>KM STORE</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #000;
      color: #fff;
    }
    header {
      background-color: #111;
      padding: 20px;
      text-align: center;
      color: gold;
      font-size: 2rem;
      font-weight: bold;
    }
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .product {
      background-color: #1a1a1a;
      border: 1px solid gold;
      border-radius: 10px;
      padding: 15px;
      text-align: center;
    }
    .product img {
      max-width: 100%;
      border-radius: 10px;
    }
    .product h3 {
      color: gold;
      margin: 10px 0 5px;
    }
    .product p {
      font-size: 0.9rem;
      color: #ccc;
    }
    .whatsapp {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: gold;
      color: #000;
      padding: 10px 20px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 0 10px gold;
    }
    .whatsapp:hover {
      background-color: #ffd700;
    }
    footer {
      text-align: center;
      padding: 15px;
      background-color: #111;
      color: #888;
    }
  </style>
</head>
<body>
  <header>KM STORE</header>

  <section class="products">
    <div class="product">
      <img src="https://via.placeholder.com/300x300?text=Produto+1" alt="Produto 1">
      <h3>Produto 1</h3>
      <p>Descrição do produto 1</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x300?text=Produto+2" alt="Produto 2">
      <h3>Produto 2</h3>
      <p>Descrição do produto 2</p>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/300x300?text=Produto+3" alt="Produto 3">
      <h3>Produto 3</h3>
      <p>Descrição do produto 3</p>
    </div>
  </section>

  <a class="whatsapp" href="https://wa.me/5599999999999" target="_blank">Fale conosco</a>

  <footer>© 2025 KM STORE - Todos os direitos reservados</footer>
</body>
</html>
