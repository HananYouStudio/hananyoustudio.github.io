# hananyoustudio.github.io
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi Web Fluida</title>
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body, html {
      font-family: Arial, sans-serif;
      scroll-behavior: smooth;
      color: #512012;
    }
    a { color: #512012; text-decoration: none; }

    /* HEADER */
    header {
      width: 100%;
      background-color: #fbf4e8;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 10px 30px;
      position: fixed;
      top: 0;
      z-index: 1001;
    }

    .logo { font-weight: bold; font-size: 1.4em; }

    nav {
      display: flex;
      gap: 30px;
    }

    nav a {
      font-size: 1em;
      padding: 8px 12px;
    }

    .contacto {
      border: 1px solid #000;
      padding: 8px 12px;
      border-radius: 4px;
      font-weight: bold;
    }

    /* HERO PARALLAX */
    .hero {
      background-image: url('https://via.placeholder.com/1600x900');
      height: 100vh;
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding-top: 60px;
    }

    .hero h1 {
      font-size: 3em;
      text-shadow: 2px 2px 4px #000;
    }

    /* CONTENIDO */
    .content {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }

    .content p {
      margin-bottom: 20px;
      line-height: 1.6;
    }

    /* SWITCH DE IDIOMA */
    #language-switcher {
      position: fixed;
      top: 20px;
      right: 20px;
      z-index: 999;
    }

    #language-switcher img {
      width: 40px;
      cursor: pointer;
    }

    /* RESPONSIVE */
    @media screen and (max-width: 768px) {
      .hero h1 {
        font-size: 2em;
      }

      header {
        flex-direction: column;
        align-items: flex-start;
        gap: 10px;
      }

      nav {
        flex-wrap: wrap;
        gap: 15px;
      }
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">HananYou Studio</div>
    <nav>
      <a href="#">Inicio</a>
      <a href="#">Servicios</a>
      <a href="#">Proyectos</a>
      <a href="#" class="contacto">Contacto</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Bienvenido a HananYou Studio</h1>
  </section>

  <section class="content">
    <p>Diseño gráfico fluido, creativo y 100% adaptado a tu estilo.</p>
    <p>Desde branding completo hasta campañas visuales para redes y streaming.</p>
  </section>
</body>
</html>
