<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Móveis planejados com qualidade, rapidez e design sob medida. Neto Pontual Móveis transforma seu ambiente!">
  <title>Neto Pontual Móveis Planejados</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body { font-family: 'Inter', sans-serif; background: #f9f9f9; color: #333; }
    header { background: #2C3E50; color: white; padding: 2rem; text-align: center; }
    header h1 { font-size: 2rem; }
    section { padding: 2rem; max-width: 1000px; margin: auto; }
    h2 { color: #2C3E50; margin-bottom: 1rem; }
    p { margin-bottom: 1rem; line-height: 1.6; }
    .gallery { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; margin: 2rem 0; }
    .gallery img { width: 100%; border-radius: 10px; box-shadow: 0 2px 5px rgba(0,0,0,0.1); }
    form { background: #fff; padding: 2rem; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
    input, textarea, button { width: 100%; padding: 1rem; margin-top: 1rem; border: 1px solid #ccc; border-radius: 5px; }
    button { background: #2C3E50; color: white; border: none; cursor: pointer; transition: background 0.3s ease; }
    button:hover { background: #1A252F; }
    footer { background: #2C3E50; color: white; text-align: center; padding: 1rem; margin-top: 2rem; }
  </style>
</head>
<body>
  <header>
    <h1>Neto Pontual Móveis Planejados</h1>
    <p>Soluções sob medida para sua casa ou empresa</p>
  </header>

  <section>
    <h2>Por que escolher a Neto Pontual?</h2>
    <p>Trabalhamos com projetos personalizados de móveis planejados, com entrega rápida de 30 a 45 dias úteis. Nossa missão é transformar ambientes com qualidade, pontualidade e beleza.</p>
    <p>Pagamento facilitado: 50% na entrada e 50% na entrega. Aceitamos cartões de crédito, débito e Pix.</p>
  </section>

  <section class="gallery">
    <img src="img1.jpg" alt="Cozinha planejada">
    <img src="img2.jpg" alt="Quarto moderno">
    <img src="img3.jpg" alt="Home office planejado">
    <img src="img4.jpg" alt="Closet personalizado">
  </section>

  <section>
    <h2>Peça seu orçamento</h2>
    <form action="#" method="POST">
      <label for="nome">Seu nome</label>
      <input type="text" id="nome" name="nome" required>

      <label for="email">E-mail</label>
      <input type="email" id="email" name="email" required>

      <label for="mensagem">Mensagem</label>
      <textarea id="mensagem" name="mensagem" rows="5" required></textarea>

      <button type="submit">Enviar orçamento</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 Neto Pontual Móveis. Todos os direitos reservados.</p>
    <p>Atendemos Teresina e região.</p>
  </footer>
</body>
</html>
