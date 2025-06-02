<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Atención Psicológica</title>
  <link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville&display=swap" rel="stylesheet" />
  <style>
    body {
      margin: 0;
      font-family: 'Libre Baskerville', serif;
      background-image: url('im4.jpg');
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
      color: #2d2d2d;
    }

    header {
      background-color: rgba(255, 255, 255, 0.9);
      padding: 2rem;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }

    header h1 {
      font-size: 2.8rem;
      margin: 0;
    }

    nav {
      background-color: #8a7f6f;
      padding: 1rem;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 1.5rem;
      font-size: 1.1rem;
    }

    section {
      padding: 3rem 2rem;
      max-width: 1000px;
      margin: auto;
      background-color: rgba(255, 255, 255, 0.9);
      margin-top: 2rem;
      border-radius: 12px;
    }

    section h2 {
      font-size: 2rem;
      margin-bottom: 1rem;
      text-align: center;
    }

    .servicio-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 1.5rem;
      justify-content: center;
      margin-top: 2rem;
    }

    .servicio-item {
      background-color: #f4f1ed;
      padding: 1.5rem;
      border-radius: 10px;
      width: 200px;
      text-align: center;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.3s;
    }

    .servicio-item:hover {
      transform: translateY(-5px);
    }

    .servicio-item span {
      font-size: 2rem;
      display: block;
      margin-bottom: 0.5rem;
    }

    .servicio-item p {
      margin: 0;
      font-size: 1.1rem;
    }

    .perfil {
      display: flex;
      gap: 2rem;
      align-items: center;
      flex-wrap: wrap;
    }

    .perfil img {
      max-width: 280px;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
    }

    .perfil-info {
      flex: 1;
      background-color: #fdfcfa;
      padding: 1.5rem;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.05);
    }

    .perfil-info h2 {
      margin-top: 0;
      color: #4a4a4a;
    }

    .perfil-info p {
      font-size: 1.1rem;
      line-height: 1.7;
      color: #333;
    }

    .contacto {
      text-align: center;
    }

    .contacto a {
      display: block;
      margin: 1rem auto;
      color: #8a7f6f;
      font-size: 1.2rem;
      text-decoration: none;
      padding: 0.8rem 1.2rem;
      border: 2px solid #8a7f6f;
      border-radius: 8px;
      width: fit-content;
      transition: background-color 0.3s, color 0.3s;
    }

    .contacto a:hover {
      background-color: #8a7f6f;
      color: white;
    }

    .contacto form {
      margin-top: 2rem;
      display: flex;
      flex-direction: column;
      gap: 1rem;
      max-width: 500px;
      margin-left: auto;
      margin-right: auto;
    }

    .contacto input,
    .contacto textarea {
      padding: 0.8rem;
      border-radius: 8px;
      border: 1px solid #ccc;
      font-size: 1rem;
      font-family: 'Libre Baskerville', serif;
    }

    .contacto button {
      background-color: #8a7f6f;
      color: white;
      padding: 0.8rem;
      border: none;
      border-radius: 8px;
      font-size: 1.1rem;
      cursor: pointer;
    }

    .contacto button:hover {
      background-color: #6e6558;
    }

    footer {
      text-align: center;
      padding: 1.5rem;
      background-color: #8a7f6f;
      color: white;
      margin-top: 3rem;
    }

    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      padding: 12px 16px;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.2);
      font-family: sans-serif;
    }
  </style>
</head>
<body>

  <header>
    <h1>Atención Psicológica</h1>
    <p>CADA CRISIS ES UNA OPORTUNIDAD DE ENCONTRARSE CON UNO MISMO.</p>
  </header>

  <nav>
    <a href="#contacto">Contacto</a>
    <a href="#servicios">Ofrecemos</a>
    <a href="#perfil">Sobre mí</a>
  </nav>

  <section id="servicios" class="servicios">
    <h2>Ofrecemos</h2>
    <div class="servicio-grid">
      <div class="servicio-item">
        <span>🧠</span>
        <p>Atención integral</p>
      </div>
      <div class="servicio-item">
        <span>🏠</span>
        <p>Espacio cómodo y seguro</p>
      </div>
      <div class="servicio-item">
        <span>🎨</span>
        <p>Actividades terapéuticas</p>
      </div>
      <div class="servicio-item">
        <span>⏰</span>
        <p>Horario flexible</p>
      </div>
      <div class="servicio-item">
        <span>💬</span>
        <p>Pregunta sin compromiso</p>
      </div>
    </div>
  </section>

  <section id="perfil" class="perfil">
    <img src="im100.jpg" />
    <div class="perfil-info">
      <h2>Sobre mí</h2>
      <p>
        Soy <strong>Scarlet Escamilla</strong>, psicóloga en Querétaro. Brindo atención personalizada, tanto presencial como online. Mi enfoque se centra en ofrecer un espacio digno, seguro y respetuoso, donde puedas expresar con libertad tus pensamientos y emociones. Trabajo con diversas técnicas adaptadas a tus necesidades, para ayudarte a alcanzar un equilibrio entre las distintas áreas de tu vida y así lograr tu bienestar emocional.
      </p>
    </div>
  </section>

  <section id="contacto" class="contacto">
  

    <h2>Contacto</h2>
  <h3 style="margin-top:2.5rem;">Agenda tu cita</h3>
    <a href="tel:+524426204179">📞 Llamar al 442 620 4179</a>
    <a href="https://wa.me/524426204179" target="_blank">💬 Enviar mensaje por WhatsApp</a>
    <a href="mailto:salud.mental100.atencionpsi@gmail.com">📧 Enviar correo: salud.mental100.atencionpsi@gmail.com</a>

      
    </form>
  </section>

  <footer>
    &copy; 2025 Atención Psicológica. Todos los derechos reservados.
  </footer>

  <a href="https://wa.me/524426204179" target="_blank" class="whatsapp-float">💬 WhatsApp</a>

</body>
</html>
