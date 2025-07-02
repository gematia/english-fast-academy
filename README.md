
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>English Fast Academy</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
    }

    header {
      background-color: #ffffff;
      color: #003366;
      padding: 20px 30px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      box-shadow: 0 2px 4px rgba(0, 0, 0, 0.05);
    }

    .header-text {
      max-width: 70%;
    }

    .header-logo img {
      height: 120px;
      object-fit: contain;
    }

    nav {
      background-color: #0055a5;
      padding: 10px;
      text-align: center;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }

    nav a:hover {
      text-decoration: underline;
    }

    main {
      padding: 30px;
      max-width: 900px;
      margin: auto;
    }

    section {
      margin-top: 50px;
    }

    h2 {
      color: #003366;
    }

    .course-card {
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      margin-bottom: 20px;
      padding: 20px;
    }

    form {
      background-color: white;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    input,
    textarea {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1em;
      box-sizing: border-box;
    }

    button {
      background-color: #0055a5;
      color: white;
      border: none;
      padding: 10px 20px;
      margin-top: 15px;
      border-radius: 5px;
      font-size: 1em;
      cursor: pointer;
    }

    button:hover {
      background-color: #003366;
    }

    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    nav a.facebook-link {
      color: white;
      text-decoration: underline;
    }

    @media (max-width: 600px) {
      header {
        flex-direction: column;
        text-align: center;
      }

      .header-text,
      .header-logo {
        max-width: 100%;
      }

      nav a {
        display: block;
        margin: 10px 0;
      }

      main {
        padding: 15px;
      }
    }
  </style>

  <script>
    function enviarWhatsApp(numero) {
      var nombre = document.getElementById("nombre").value.trim();
      var mensaje = document.getElementById("mensaje").value.trim();

      if (nombre === "" || mensaje === "") {
        alert("Por favor, completa todos los campos.");
        return false;
      }

      var texto = "Hola, mi nombre es *" + nombre + "*.%0A";
      texto += "Quisiera comentar lo siguiente:%0A" + mensaje;

      var telefono = numero; // número enviado desde el botón clickeado

      var url = "https://wa.me/" + telefono + "?text=" + texto;
      window.open(url, "_blank");
      return false;
    }
  </script>
</head>
<body>

  <!-- ENCABEZADO -->
  <header>
    <div class="header-text">
      <h1>English Fast Academy</h1>
      <p>Aprende inglés de forma rápida y efectiva</p>
    </div>
    <div class="header-logo">
      <img
        src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSbwtJXjwdesUIdbGiY7JgHFLHE_bQJYKzEOg&s"
        alt="Logo English Fast Academy"
      />
    </div>
  </header>

  <!-- NAVEGACIÓN -->
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#cursos">Cursos</a>
    <a href="#contacto">Contacto</a>
    <a href="https://www.facebook.com/share/1AfLaNygJ8/" target="_blank" class="facebook-link"
      >Facebook</a
    >
  </nav>

  <!-- CONTENIDO -->
  <main>
    <section id="inicio">
      <h2>Bienvenido a English Fast Academy</h2>
      <p>
        <strong>English Fast Academy</strong> es una academia moderna enfocada
        en acelerar tu aprendizaje del idioma inglés con métodos interactivos,
        profesores nativos y herramientas digitales adaptadas a tus necesidades.
      </p>
      <p>¿Por qué elegirnos?</p>
      <ul>
        <li>✅ Clases online,presenciales y a domicilio</li>
        <li>✅ Profesores certificados</li>
        <li>✅ Planes personalizados para cada alumno</li>
      </ul>
    </section>

    <section id="cursos">
      <h2>Nuestros Cursos</h2>
      <p>
        Ofrecemos <strong>cursos personalizados</strong> según tu nivel y
        objetivos. Podés elegir clases <strong>virtuales</strong> desde cualquier
        lugar o <strong>a domicilio</strong> si preferís atención presencial en
        tu zona.
      </p>

      <div class="course-card" style="background-color: #E1F5FE;">
        <h3>🔵 Inglés Básico para Principiantes</h3>
        <p>
          Ideal para quienes están comenzando. Aprende vocabulario esencial,
          gramática básica y frases comunes para comunicarte desde el primer día.
        </p>
      </div>

      <div class="course-card" style="background-color: #E1F5FE;">
        <h3>🔵 Conversación Intermedia</h3>
        <p>
          Practica con profesores nativos y mejora tu fluidez oral. Clases
          dinámicas con situaciones reales para ganar confianza al hablar.
        </p>
      </div>


<div class="course-card" style="background-color: #E1F5FE;">
  <h3>🔵 Preparación para TOEFL/IELTS</h3>
  <p>
    Entrena para obtener certificaciones internacionales. Simulacros de
    examen, estrategias y tips para aprobar con éxito.
  </p>
       </div>



      <div class="course-card" style="background-color: #E1F5FE;">
        <h3>🔵 Inglés para Negocios</h3>
        <p>
          Enfocado en vocabulario empresarial, presentaciones, reuniones y
          escritura profesional. Perfecto para ejecutivos y emprendedores.
        </p>
      </div>
    </section>

    <section id="contacto">
      <h2>Contacto</h2>
      <p>¿Tienes preguntas o quieres inscribirte? ¡Envíanos un mensaje por WhatsApp!</p>

      <form onsubmit="return false;">
        <label for="nombre">Nombre:</label><br />
        <input type="text" id="nombre" name="nombre" required /><br /><br />

        <label for="mensaje">Mensaje:</label><br />
        <textarea id="mensaje" name="mensaje" rows="5" required></textarea><br /><br />

        <button onclick="return enviarWhatsApp('593985737117');">Enviar a WhatsApp 0985 737117</button>
        <button onclick="return enviarWhatsApp('593978820507');">Enviar a WhatsApp 0978 820507</button>
      </form>
    </section>
  </main>

   


  <!-- PIE DE PÁGINA -->
  <footer>
    &copy; 2025 English Fast Academy | Síguenos en
    <a href="https://www.facebook.com/share/1AfLaNygJ8/" target="_blank" style="color: #fff; text-decoration: underline;">Facebook</a>
  </footer>
</body>
</html>
