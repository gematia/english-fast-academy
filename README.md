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
        text-align: center; /* Centrando el título de la sección */
      }
      .course-card {
        background-color: #E1F5FE;
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
      .img-left {
        float: left;
        margin-right: 20px;
        width: 30%; /* Tamaño de la imagen izquierda */
      }
      .image-container {
  text-align: center;
  margin-top: 20px;
}

.img-medium {
  display: inline-block;
  width: 25%;
  margin: 0 10px;
}

.clearfix {
  clear: both;
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
        var url = "https://wa.me/" + numero + "?text=" + texto;
        window.open(url, "_blank");
        return false;
      }
    </script>
  </head>
  <body>
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

    <nav>
      <a href="#inicio">Inicio</a>
      <a href="#cursos">Cursos</a>
      <a href="#contacto">Contacto</a>
      <a href="https://www.facebook.com/share/1AfLaNygJ8/" target="_blank" class="facebook-link">Facebook</a>
    </nav>

    <main>
      <section id="inicio">
        <h2>Bienvenido a English Fast Academy</h2>
        <img src="imgvertical.jpeg" alt="Descripción de la imagen" class="img-left" />
        <p>
          <strong>English Fast Academy</strong> es una academia moderna enfocada
          en acelerar tu aprendizaje del idioma inglés con métodos interactivos,
          profesores nativos y herramientas digitales adaptadas a tus necesidades.
        </p>
        <p>¿Por qué elegirnos?</p> 
        <ul>
          <li>✅ Clases online, presenciales y a domicilio</li>
          <li>✅ Profesores certificados</li>
          <li>✅ Planes personalizados para cada alumno</li>
        </ul>
       <section id="inicio">

  <div class="image-container">
    <img src="imgver.jpeg" alt="Descripción de la imagen mediana" class="img-medium">
    <img src="imghr.jpeg" alt="Descripción de la imagen mediana" class="img-medium">
  </div>
  <div class="clearfix"></div>


      </section>

      <section id="cursos">
        <h2>Nuestros Cursos</h2>
        <div class="course-card">
          <h3>🟢 Inglés Básico para Principiantes</h3>
          <p>
            Ideal para quienes están comenzando. Aprende vocabulario esencial,
            gramática básica y frases comunes para comunicarte desde el primer día.
          </p>
        </div>

        <div class="course-card">
          <h3>🔵 Conversación Intermedia</h3>
          <p>
            Practica con profesores nativos y mejora tu fluidez oral. Clases
            dinámicas con situaciones reales para ganar confianza al hablar.
          </p>
        </div>

        <div class="course-card">
          <h3>🟣 Preparación para TOEFL/IELTS</h3>
          <p>
            Entrena para obtener certificaciones internacionales. Simulacros de
            examen, estrategias y tips para aprobar con éxito.
          </p>
        </div>

        <div class="course-card">
          <h3>🟠 Inglés para Negocios</h3>
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

    <footer>
      &copy; 2025 English Fast Academy | Síguenos en
      <a href="https://www.facebook.com/share/1AfLaNygJ8/" target="_blank" style="color: #fff; text-decoration: underline;">Facebook</a>
    </footer>
  </body>
</html> 
