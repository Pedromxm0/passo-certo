# passo-certo
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Passo Certo</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; background: #f9f9f9; color: #333; }
    header { background: #1f1f1f; color: white; padding: 1.5rem; text-align: center; }
    nav a { margin: 0 1rem; color: white; text-decoration: none; font-weight: bold; }
    section { padding: 2rem; max-width: 1000px; margin: auto; }
    h1, h2 { color: #1f1f1f; }
    .products { display: flex; gap: 1rem; flex-wrap: wrap; justify-content: center; }
    .product-card { background: white; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); padding: 1rem; width: 220px; text-align: center; }
    .product-card img { max-width: 100%; border-radius: 8px; }
    .qr-code { text-align: center; margin-top: 2rem; }
    form { display: flex; flex-direction: column; gap: 0.5rem; max-width: 400px; margin: auto; }
    input, textarea { padding: 0.75rem; border: 1px solid #ccc; border-radius: 5px; }
    button { padding: 0.75rem; background: #1f1f1f; color: white; border: none; border-radius: 5px; cursor: pointer; }
    footer { background: #1f1f1f; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
  </style>
</head>
<body>
  <header>
    <h1>Passo Certo</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#produtos">Produtos</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section id="sobre">
    <h2>Sobre Nós</h2>
    <p>A Passo Certo é uma marca dedicada a criar calçados que aliam conforto, saúde e estilo. Especialistas em tênis ortopédicos e modelos casuais para o dia a dia.</p>
  </section>

  <section id="produtos">
    <h2>Produtos</h2>
    <div class="products">
      <div class="product-card">
        <img src="https://sdmntprwestus.oaiusercontent.com/files/00000000-4634-6230-80cc-97a42f2b31e8/raw?se=2025-05-24T22%3A34%3A09Z&sp=r&sv=2024-08-04&sr=b&scid=c49245b3-b026-5ec3-8ca9-159857c3c9e9&skoid=61180a4f-34a9-42b7-b76d-9ca47d89946d&sktid=a48cca56-e6da-484e-a814-9c849652bcb3&skt=2025-05-24T01%3A39%3A48Z&ske=2025-05-25T01%3A39%3A48Z&sks=b&skv=2024-08-04&sig=XYL%2B7sKNU9MR9x%2BdGYwve8itury0shYP6mGfPKWZ6Y4%3D=Tenis+Ortopedico" alt="Tênis Ortopédico">
        <h3>Tênis Ortopédico</h3>
        <p>Conforto e suporte para sua saúde.</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200x150.png?text=Tenis+Casual" alt="Tênis Casual">
        <h3>Tênis Casual</h3>
        <p>Estilo e leveza para o seu dia a dia.</p>
      </div>
      <div class="product-card">
        <img src="https://via.placeholder.com/200x150.png?text=Tenis+Esportivo" alt="Tênis Esportivo">
        <h3>Tênis Esportivo</h3>
        <p>Desempenho e resistência para seus treinos.</p>
      </div>
    </div>
  </section>

  <section id="contato">
    <h2>Fale Conosco</h2>
    <form action="#" method="POST">
      <input type="text" name="nome" placeholder="Pedro Moreira" required>
      <input type="email" name="email" placeholder="pedromoreiramxm@gmail.com" required>
      <textarea name="mensagem" rows="5" placeholder="Obrigado" required></textarea>
      <button type="submit">Enviar</button>
    </form>
  </section>

  <section class="qr-code">
    <h2>Acesse Nosso Site</h2>
    <p>Escaneie o QR Code abaixo para visitar nosso site:</p>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://www.passocerto.com" alt="QR Code para Passo Certo">
  </section>

  <footer>
    <p>&copy; 2025 Passo Certo. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
