index.html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hospital General del Oriente Chiricano Dr. Francisco Pérez</title>
  <style>
    body {
      margin: 0;
      font-family: "Segoe UI", Arial, sans-serif;
      background-color: #f4f9f9;
    }
    header {
      background-color: #0073e6;
      color: white;
      padding: 20px 0;
      text-align: center;
    }
    nav {
      background-color: #0066cc;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      padding: 14px 20px;
      text-decoration: none;
      text-transform: uppercase;
      font-weight: bold;
    }
    nav a:hover {
      background-color: #004c99;
    }
    section {
      padding: 40px;
      text-align: center;
    }
    .hero {
      background-color: #e6f0ff;
      padding: 50px 20px;
    }
    .hero h1 {
      color: #0073e6;
      font-size: 2em;
    }
    .gallery img {
      width: 320px;
      height: auto;
      margin: 10px;
      border-radius: 10px;
      box-shadow: 0 0 8px rgba(0,0,0,0.1);
    }<img src="miimagen.jpg" alt="IMG_20251014_090130.jpg">
    form {
      max-width: 500px;
      margin: 0 auto;
      text-align: left;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      border: 1px solid #ccc;
      border-radius: 6px;
    }
    button {
      background-color: #0073e6;
      color: white;
      border: none;
      padding: 10px 15px;
      margin-top: 10px;
      border-radius: 6px;
      cursor: pointer;
    }
    button:hover {
      background-color: #005bb5;
    }
    iframe {
      width: 100%;
      height: 350px;
      border: none;
      border-radius: 10px;
      margin-top: 20px;
    }
    footer {
      background-color: #004c99;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 30px;
    }
  </style>
</head>
<body>
<header style="background-image:url('banner.jpg'); background-size:cover; background-position:center; color:white; padding:100px 20px;">
  <h1 style="background-color:rgba(0,0,0,0.5); display:inline-block; padding:20px; border-radius:10px;">
    Hospital General del Oriente Chiricano<br>Dr. Francisco Pérez
  </h1>
  <p style="font-size:1.2em; background-color:rgba(0,0,0,0.4); display:inline-block; padding:10px 20px; border-radius:10px;">
    Comprometidos con la salud y el bienestar de nuestra comunidad
  </p>
</header>

  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#buzones">Buzones</a>
    <a href="#conferencias">Conferencias</a>
    <a href="#talleres">Talleres</a>
    <a href="#mapa">Mapa</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="inicio" class="hero">
    <h1>Bienvenidos al Hospital General del Oriente Chiricano</h1>
    <p>Brindamos atención médica integral y servicios de calidad a toda la región oriental de Chiriquí.</p>

    <div class="gallery">
      <img src="IMG-20251008-WA0007.jpg" alt="Equipo del hospital">
      <img src="qwqww.PNG" alt="Instalaciones del hospital">
    </div>
  </section>

  <section id="buzones">
    <h2>Buzones de Sugerencias</h2>
    <p>En el Hospital contamos con buzones físicos y virtuales para recibir sus comentarios y sugerencias.</p>

    <form>
      <label for="nombre">Nombre:</label>
      <input type="text" id="nombre" name="nombre" placeholder="Tu nombre...">

      <label for="correo">Correo electrónico:</label>
      <input type="email" id="correo" name="correo" placeholder="tu@correo.com">

      <label for="mensaje">Mensaje o sugerencia:</label>
      <textarea id="mensaje" name="mensaje" rows="4" placeholder="Escribe aquí tu mensaje..."></textarea>

      <button type="submit">Enviar</button>
    </form>
  </section>

  <section id="conferencias">
    <h2>Conferencias</h2>
    <p>El hospital realiza conferencias educativas dirigidas al personal de salud y la comunidad.</p>
    <p>Próximas conferencias se anunciarán en nuestras redes y carteleras institucionales.</p>
  </section>

  <section id="talleres">
    <h2>Talleres y Capacitaciones</h2>
    <p>Fomentamos la formación continua del personal mediante talleres prácticos y programas de actualización.</p>
    <p>Temas recientes incluyen salud cardiovascular, emergencias médicas y gestión de calidad hospitalaria.</p>
  </section>

  <section id="mapa">
    <h2>Ubicación</h2>
    <p>Encuéntranos fácilmente a través de Google Maps:</p>
    <iframe 
      src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3923.3421395928473!2d-82.59626722529126!3d8.352833991728891!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8fa5f3a82b28b68b%3A0x356d25e5021c9c78!2sHospital%20General%20del%20Oriente%20Chiriqu%C3%A1no%20Dr.%20Francisco%20P%C3%A9rez!5e0!3m2!1ses!2spa!4v1700000000000!5m2!1ses!2spa"
      allowfullscreen=""
      loading="lazy">
    </iframe>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p><strong>Dirección:</strong> Oriente de Chiriquí, Panamá</p>
    <p><strong>Teléfono:</strong> (000) 000-0000</p>
    <p><strong>Email:</strong> hospitaloriente@minsa.gob.pa</p>
  </sec
