<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Hiram Pessoa</title>

  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;

      background-image: url("fundo.jpg");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      background-attachment: fixed;

      color: white;
    }

    .conteudo {
      background-color: rgba(0, 0, 0, 0.7);
      padding: 30px;
      min-height: 100vh;
      max-width: 900px;
      margin: auto;
      border-radius: 10px;
    }

    h1 {
      margin-bottom: 5px;
      text-align: center;
    }

    .subtitulo {
      margin-top: 0;
      color: #ccc;
      text-align: center;
    }

    h2 {
      margin-top: 40px;
      border-bottom: 2px solid #ffcc00;
      padding-bottom: 5px;
    }

    p {
      line-height: 1.6;
    }

    ul {
      padding: 0;
    }

    li {
      list-style: none;
      margin-bottom: 40px;
    }

    a {
      display: inline-block;
      margin: 10px 0;
      padding: 10px 15px;
      background-color: #ffcc00;
      color: black;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: 0.3s;
    }

    a:hover {
      background-color: #e6b800;
      transform: scale(1.05);
    }

    iframe {
      width: 100%;
      height: 500px;
      border: none;
      border-radius: 10px;
      margin-top: 10px;
    }

    .contato a {
      display: block;
      width: fit-content;
    }

    @media (max-width: 600px) {
      iframe {
        height: 300px;
      }

      .conteudo {
        padding: 15px;
      }
    }
  </style>
</head>

<body>

<div class="conteudo">

  <!-- TOPO -->
  <h1>Hiram Pessoa</h1>
  <p class="subtitulo">Estudante de Tecnologia / Desenvolvedor</p>

  <!-- SOBRE -->
  <h2>Sobre mim</h2>
  <p>
    Sou estudante de tecnologia com interesse em desenvolvimento de sistemas e projetos práticos.
    Busco constantemente evoluir minhas habilidades e criar soluções úteis e eficientes.
  </p>

  <!-- CURRÍCULO -->
  <h2>Currículo</h2>
  <ul>
    <li>
      <a href="hiram-curriculo.pdf" target="_blank">Abrir Currículo</a>
      <iframe src="hiram-curriculo.pdf"></iframe>
    </li>
  </ul>

  <!-- PORTFÓLIO -->
  <h2>Portfólio</h2>
  <ul>
    <li>
      <a href="portifolio.pdf" target="_blank">Abrir Portfólio</a>
      <iframe src="portifolio.pdf"></iframe>
    </li>
  </ul>

  <!-- CONTATO -->
  <h2>Contato</h2>
  <div class="contato">
    <a href="https://github.com/" target="_blank">GitHub</a>
    <a href="https://linkedin.com/" target="_blank">LinkedIn</a>
    <a href="mailto:seuemail@email.com">Email</a>
  </div>

</div>

</body>
</html>
