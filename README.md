<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Design Responsivo</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
header {
      background-color: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }

   .nav {
      display: flex;
      justify-content: space-around;
      background-color: #444;
      padding: 1rem;
    }
    .nav a {
      color: #fff;
      text-decoration: none;
    }
    .content {
      padding: 2rem;
    }
    .grid-container {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
      gap: 1rem;
    }
    .card {
      background-color: #f4f4f4;
      padding: 1rem;
      text-align: center;
    }
    /* Media Queries */
    @media (max-width: 600px) {
      .nav {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>
<body>

<header>
  <h1>Meu Site Responsivo</h1>
</header>

<nav class="nav">
  <a href="#">Home</a>
  <a href="#">Sobre</a>
  <a href="#">Contato</a>
</nav>

<section class="content">
  <h2>Bem-vindo ao meu site!</h2>
  <div class="grid-container">
    <div class="card">
      <h3>Produto 1</h3>
      <p>Descrição do produto</p>
    </div>
    <div class="card">
      <h3>Produto 2</h3>
      <p>Descrição do produto</p>
    </div>
    <div class="card">
      <h3>Produto 3</h3>
      <p>Descrição do produto</p>
    </div>
  </div>
</section>

</body>
</html>
