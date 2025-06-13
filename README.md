# convite-aniversario
convite do aniversário de joão






<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Convite de Aniversário</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: #000;
      color: #fff;
      text-align: center;
      background-image: url('sua-imagem.jpg'); /* Substitua pela URL da imagem */
      background-size: cover;
      background-position: center;
      height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      padding: 20px;
    }

    .convite {
      background-color: rgba(0, 0, 0, 0.6);
      padding: 30px;
      border-radius: 20px;
    }

    h1 {
      font-size: 2.5em;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.2em;
      margin-bottom: 20px;
    }

    .botoes a {
      display: inline-block;
      margin: 10px;
      padding: 15px 30px;
      background-color: #ffcc00;
      color: #000;
      font-weight: bold;
      border-radius: 10px;
      text-decoration: none;
      transition: background-color 0.3s;
    }

    .botoes a:hover {
      background-color: #ffc107;
    }

    @media (max-width: 600px) {
      h1 { font-size: 2em; }
      p { font-size: 1em; }
      .botoes a { padding: 12px 24px; }
    }
  </style>
</head>
<body>
  <div class="convite">
    <h1>Você está convidado!</h1>
    <p>Venha comemorar o aniversário de <strong>João Lucas</strong> conosco!<br>
    🎉 13 de Julho de 2025 às 17h<br>
    📍 Joy Kids</p>

    <div class="botoes">
      <a href="https://forms.gle/DEieYRQDC56e1GtV8" target="_blank">Confirmar Presença</a>
      <a href="https://maps.app.goo.gl/STAyHTPubyAzCEUp6" target="_blank">Ver Local no Mapa</a>
    </div>
  </div>
</body>
</html>
