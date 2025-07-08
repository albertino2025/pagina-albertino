# pagina-albertino
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>¿Qué es una Página Web? | Aprende Internet</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f9;
      color: #333;
    }
    header {
      background: #0077cc;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 40px 20px;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #0077cc;
    }
    img, iframe {
      max-width: 100%;
      height: auto;
      display: block;
      margin: 20px auto;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 20px;
    }
    table, th, td {
      border: 1px solid #ccc;
    }
    th, td {
      padding: 12px;
      text-align: center;
    }
    .interactivo {
      margin-top: 40px;
      text-align: center;
    }
    button {
      padding: 10px 20px;
      background: #0077cc;
      color: white;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background: #005fa3;
    }
  </style>
</head>
<body>

<header>
  <h1>Explorando el Mundo Web</h1>
  <p>Comprende qué es una página web, la diferencia entre Internet y la Web, y cómo funciona el protocolo IP.</p>
</header>

<section>
  <h2>🌐 ¿Qué es una Página Web?</h2>
  <p>Una página web es un documento digital que se accede mediante un navegador y está alojado en un servidor. Contiene texto, imágenes, enlaces y otros elementos multimedia.</p><a href="https://fernandoarciniega.com/wp-content/uploads/2016/02/diagrama-de-funcionamiento.jpg" target="_blank">DIAGRAMA DE UNA PAGINA WEB</a> /<p>
  <a href="https://youtu.be/okcaF_WGZGU" target="_blank">DIFERENCIAS ENTRE UNA PAGINA WEB Y EL INTERNET</a>

<section>
  <h2>🌍 Internet vs Web</h2>
  <p><strong>Internet:</strong> Es la infraestructura que conecta millones de computadoras alrededor del mundo.</p>
  <p><strong>Web (WWW):</strong> Es un sistema de acceso a la información usando Internet como medio.</p>
  
  <table>
    <tr>
      <th>Característica</th>
      <th>Internet</th>
      <th>Web</th>
    </tr>
    <tr>
      <td>Definición</td>
      <td>Red global de computadoras</td>
      <td>Sistema de documentos interconectados</td>
    </tr>
    <tr>
      <td>Protocolo</td>
      <td>TCP/IP</td>
      <td>HTTP/HTTPS</td>
    </tr>
    <tr>
      <td>Función</td>
      <td>Transmisión de datos</td>
      <td>Presentación de información</td>
    </tr>
  </table>
</section>

<section>
  <h2>📡 ¿Cómo Funciona el Protocolo IP?</h2>
  <p>El protocolo IP permite el envío de información entre dispositivos en una red. Cada dispositivo tiene una dirección IP única.</p>
  <ol>
    <li>La información se divide en paquetes.</li>
    <li>Los paquetes viajan a través de diferentes rutas por Internet.</li>
    <li>Se reensamblan en el destino.</li>
  </ol>
<a href="https://youtu.be/801xu7tGEfA" target="_blank"> VIDEO ACERCA DE LOS PROTOCOLO IP</a>
<section class="interactivo">
  <h2>🧪 Actividad Interactiva</h2>
  <p>Haz clic en el botón para abrir un editor de HTML y crear tu propia página web básica:</p>
  <a href="https://codepen.io/pen" target="_blank">
    <button>¡Crea tu Página Web!</button>
  </a>
</section>

<footer style="text-align:center; padding:20px; background:#eee;">
  <p>Creado por Valencia la 10 | 2025</p>
</footer>
<section class="interactivo">
  <h2>📝 Cuestionario Rápido</h2>
  <p>Responde: ¿Cuál es la diferencia principal entre Internet y la Web?</p>
  <input type="text" id="respuesta" placeholder="Escribe tu respuesta aqui" style="padding:10px; width:80%; max-width:400px;">
  <br><br>
  <button onclick="verificarRespuesta()">Verificar</button>
  <p id="feedback" style="margin-top:15px; font-weight:bold;"></p>
</section>

<script>
  function verificarRespuesta() {
    const resp = document.getElementById('respuesta').value.toLowerCase();
    const feedback = document.getElementById('feedback');
    
    if (resp.includes('internet') && resp.includes('web')) {
      feedback.innerHTML = '✅ ¡Correcto! Internet es la infraestructura, y la Web es un sistema de informacion que funciona sobre ella.';
      feedback.style.color = 'green';
    } else {
      feedback.innerHTML = '❌ Intenta de nuevo. Pista: la Web funciona sobre Internet.';
      feedback.style.color = 'red';
    }
  }
</script>

</body>
</html>
