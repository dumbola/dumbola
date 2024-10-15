<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>Loja Online - Compre Agora!</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Cabeçalho com barra de navegação -->
  <header>
    <nav class="navbar">
      <div class="logo">
        <a href="#"><img src="logo.png" alt="Logo da Loja"></a>
      </div>
      <ul class="nav-links">
        <li><a href="#produtos">Produtos</a></li>
        <li><a href="#sobre">Sobre Nós</a></li>
        <li><a href="#contato">Contato</a></li>
        <li><a href="#carrinho">Carrinho</a></li>
      </ul>
    </nav>
  </header>

  <!-- Banner de destaque -->
  <section class="banner">
    <h1>Promoção Especial!</h1>
    <p>Compre agora com descontos imperdíveis</p>
    <a href="#produtos" class="btn">Ver Produtos</a>
  </section>

  <!-- Seção de produtos -->
  <section id="produtos" class="produtos">
    <h2>Produtos em Destaque</h2>
    <div class="grid-container">
      <div class="produto">
        <img src="produto1.jpg" alt="Produto 1">
        <h3>Produto 1</h3>
        <p>R$ 150,00</p>
        <button class="btn">Adicionar ao Carrinho</button>
      </div>
      <div class="produto">
        <img src="produto2.jpg" alt="Produto 2">
        <h3>Produto 2</h3>
        <p>R$ 200,00</p>
        <button class="btn">Adicionar ao Carrinho</button>
      </div>
      <div class="produto">
        <img src="produto3.jpg" alt="Produto 3">
        <h3>Produto 3</h3>
        <p>R$ 250,00</p>
        <button class="btn">Adicionar ao Carrinho</button>
      </div>
      <div class="produto">
        <img src="produto4.jpg" alt="Produto 4">
        <h3>Produto 4</h3>
        <p>R$ 300,00</p>
        <button class="btn">Adicionar ao Carrinho</button>
      </div>
    </div>
  </section>

  <!-- Seção sobre nós -->
  <section id="sobre" class="sobre">
    <h2>Sobre Nós</h2>
    <p>Somos uma loja dedicada a oferecer os melhores produtos com os melhores preços. Nosso objetivo é proporcionar uma experiência de compra fácil e segura.</p>
  </section>

  <!-- Seção de contato -->
  <section id="contato" class="contato">
    <h2>Entre em Contato</h2>
    <form action="#" method="POST">
      <label for="nome">Nome:</label>
      <input type="text" id="nome" name="nome" required>
      <label for="email">E-mail:</label>
      <input type="email" id="email" name="email" required>
      <label for="mensagem">Mensagem:</label>
      <textarea id="mensagem" name="mensagem" required></textarea>
      <button type="submit" class="btn">Enviar</button>
    </form>
  </section>

  <!-- Rodapé -->
  <footer>
    <p>&copy; 2024 Loja Online. Todos os direitos reservados.</p>
  </footer>

  <script src="app.js"></script>
</body>
</html>


  <!DOCTYPE css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
  }
  
  header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
  }
  
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
  }
  
  .nav-links {
    list-style: none;
    display: flex;
  }
  
  .nav-links li {
    margin-left: 20px;
  }
  
  .nav-links a {
    color: #fff;
    text-decoration: none;
    font-size: 1.1rem;
  }
  
  .banner {
    background: url('banner.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 100px 20px;
  }
  
  .banner h1 {
    font-size: 3rem;
    margin-bottom: 20px;
  }
  
  .btn {
    padding: 10px 20px;
    background-color: #ff5a5f;
    color: #fff;
    border: none;
    cursor: pointer;
    font-size: 1rem;
    border-radius: 5px;
  }
  
  .produtos {
    padding: 50px 20px;
    background-color: #fff;
  }
  
  .grid-container {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
    max-width: 1200px;
    margin: 0 auto;
  }
  
  .produto {
    background-color: #fff;
    border: 1px solid #ddd;
    padding: 20px;
    text-align: center;
  }
  
  .produto img {
    max-width: 100%;
    height: auto;
  }
  
  .produto h3 {
    font-size: 1.2rem;
    margin: 10px 0;
  }
  
  .produto p {
    font-size: 1.1rem;
    color: #888;
    margin-bottom: 10px;
  }
  
  .sobre, .contato {
    padding: 50px 20px;
    text-align: center;
    background-color: #f9f9f9;
  }
  
  footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 20px;
  }
  
