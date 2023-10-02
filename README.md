<!DOCTYPE html>
<html lang="pt-br">
  <head>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500&display=swap"
      rel="stylesheet"
    />

    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Documento</title>
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div id="container">
      <div id="profile">
        <img
          src="./assets/avatar.png"
          alt="Foto de Mayk Brito Sorrindo, usando óculos e camisa preta, barba e fundo amarelo."
        />
        <p>@maykbrito</p>
      </div>
      <div id="switch" onclick="toggleMode()">
        <button></button>
        <span></span>
      </div>
      <ul>
        <li>
          <a href="#">Inscrever-se no NLW</a>
        </li>

        <li>
          <a href="#">Baixar meu e-book</a>
        </li>

        <li>
          <a href="https://github.com/maykbrito">Ver meu portifólio</a>
        </li>

        <li>
          <a href="https://rocketseat.com.br/explorer" target="_blank"
            >Conheça o Explorer</a
          >
        </li>
      </ul>
      <div id="social-links">
        <a href="https://github.com/maykbrito" target="_blank">
          <ion-icon name="logo-github"></ion-icon>
        </a>

        <a href="https://instagram.com/maykbrito" target="_blank">
          <ion-icon name="logo-instagram"></ion-icon>
        </a>

        <a href="https://youtube.com/maykbrito" target="_blank">
          <ion-icon name="logo-youtube"></ion-icon>
        </a>
        <a href="https://linkedin.com/in/maykbrito" target="_blank">
          <ion-icon name="logo-linkedin"></ion-icon>
        </a>
      </div>
      <footer>
        Feito com S2 pela <a href="https://rocketseat.com.br">Rockeseat</a>
      </footer>
    </div>

    <script
      type="module"
      src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.esm.js"
    ></script>
    <script
      nomodule
      src="https://unpkg.com/ionicons@7.1.0/dist/ionicons/ionicons.js"
    ></script>

    <script src="./script.js"></script>
  </body>
</html>
