<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Davenmar Bioagro</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f9f4;
      color: #333;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #388E3C;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      display: inline-block;
    }
    nav a:hover {
      background-color: #2E7D32;
    }
    section {
      padding: 40px;
    }
    .product {
      border: 1px solid #ccc;
      padding: 16px;
      margin: 16px 0;
      border-radius: 8px;
      background-color: white;
    }
    .product img {
      max-width: 100%;
      height: auto;
    }
    footer {
      background-color: #2E7D32;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .contact-form {
      max-width: 500px;
      margin: auto;
    }
    .contact-form input, .contact-form textarea {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
  </style>
</head>
<body>

<header>
  <h1>Davenmar Bioagro</h1>
  <p>Productos Orgánicos y Herbicidas Naturales</p>
</header>

<nav>
  <a href="#inicio">Inicio</a>
  <a href="#tienda">Tienda</a>
  <a href="#educacion">Educación</a>
  <a href="#contacto">Contáctanos</a>
</nav>

<section id="inicio">
  <h2>Bienvenido a Davenmar Bioagro</h2>
  <p>Proveemos soluciones orgánicas y sostenibles para tu finca, hogar o cultivo.</p>
</section>

<section id="tienda">
  <h2>Nuestros Productos</h2>
  <div class="product">
    <h3>Fertilizante Orgánico Davenmar</h3>
    <img src="https://via.placeholder.com/400x200" alt="Fertilizante Orgánico">
    <p>Hecho 100% con ingredientes naturales. Ideal para cultivos orgánicos.</p>
    <a href="https://wa.me/50712345678" target="_blank">Comprar por WhatsApp</a>
  </div>
  <div class="product">
    <h3>Herbicida Natural</h3>
    <img src="https://via.placeholder.com/400x200" alt="Herbicida Natural">
    <p>Controla malezas sin afectar tu suelo ni la salud de tus plantas.</p>
    <a href="https://wa.me/50712345678" target="_blank">Comprar por WhatsApp</a>
  </div>
</section>

<section id="educacion">
  <h2>Educación</h2>
  <p>Conoce las ventajas de los productos orgánicos, aprende a usarlos y mejora tus cultivos.</p>
</section>

<section id="contacto">
  <h2>Contáctanos</h2>
  <div class="contact-form">
    <form action="mailto:tucorreo@example.com" method="post" enctype="text/plain">
      <input type="text" name="name" placeholder="Tu nombre" required>
      <input type="email" name="email" placeholder="Tu correo" required>
      <textarea name="message" rows="4" placeholder="Tu mensaje" required></textarea>
      <input type="submit" value="Enviar">
    </form>
  </div>
</section>

<footer>
  <p>&copy; 2025 Davenmar Bioagro. Todos los derechos reservados.</p>
</footer>

</body>
</html>
