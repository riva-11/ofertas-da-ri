<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ofertas Especiais - Shopee</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0; padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background: #f9f9f9;
      color: #333;
      padding: 20px;
    }

    header {
      text-align: center;
      padding: 30px 0;
      background: linear-gradient(to right, #ff5722, #ff9800);
      color: white;
    }

    h1 {
      font-size: 2em;
    }

    .container {
      max-width: 1000px;
      margin: 40px auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 30px;
    }

    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
      overflow: hidden;
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card img {
      width: 100%;
      height: 250px;
      object-fit: cover;
    }

    .card-content {
      padding: 20px;
    }

    .card-content h2 {
      font-size: 1.1em;
      margin-bottom: 10px;
    }

    .card-content p {
      font-size: 0.9em;
      margin-bottom: 15px;
      color: #666;
    }

    .btn {
      display: block;
      text-align: center;
      padding: 12px 20px;
      background: #ff5722;
      color: white;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
      transition: background 0.3s;
    }

    .btn:hover {
      background: #e64a19;
    }

    footer {
      text-align: center;
      margin-top: 60px;
      color: #999;
      font-size: 0.85em;
    }
  </style>
</head>
<body>

  <header>
    <h1>🌟 Ofertas Imperdíveis na Shopee 🌟</h1>
    <p>Aproveite descontos incríveis clicando nos produtos abaixo!</p>
  </header>

  <section class="container">
    <!-- Produto 1 -->
    <div class="card">
      <img src="https://down-br.img.susercontent.com/file/sg-11134201-23030-wzkvxy1tbknv30" alt="Babá Eletrônica">
      <div class="card-content">
        <h2>Babá Eletrônica com Visão Noturna</h2>
        <p>Acompanhe seu bebê em tempo real com segurança e praticidade.</p>
        <a href="https://s.shopee.com.br/5L1MCkFhpK" class="btn" target="_blank">Ver na Shopee</a>
      </div>
    </div>

    <!-- Produto 2 -->
    <div class="card">
      <img src="https://down-br.img.susercontent.com/file/br-11134207-7r98o-lqf95kqoejqb31" alt="Robô Aspirador Xiaomi">
      <div class="card-content">
        <h2>Robô Aspirador Inteligente Xiaomi</h2>
        <p>Limpeza automática, ideal para quem busca praticidade no dia a dia.</p>
        <a href="https://s.shopee.com.br/5L1MCkFhpK" class="btn" target="_blank">Ver na Shopee</a>
      </div>
    </div>

    <!-- Produto 3 -->
    <div class="card">
      <img src="https://down-br.img.susercontent.com/file/br-11134207-7qukw-lgeuklsc4h1t82" alt="Air Fryer">
      <div class="card-content">
        <h2>Air Fryer 5L Inox</h2>
        <p>Prepare receitas deliciosas e saudáveis sem óleo.</p>
        <a href="https://s.shopee.com.br/5L1MCkFhpK" class="btn" target="_blank">Ver na Shopee</a>
      </div>
    </div>
  </section>

  <footer>
    Página feita com ❤️ por Rivanete • Link de afiliado Shopee
  </footer>
</body>
</html>
