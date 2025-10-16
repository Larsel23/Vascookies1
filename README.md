<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vascookies - Galletas</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #f8f8f5;
    }
    header {
      background-color: #650002;
      color: white;
      padding: 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 32px;
    }
    .container {
      padding: 40px;
      max-width: 1200px;
      margin: auto;
    }
    .productos {
      display: flex;
      flex-wrap: wrap;
      gap: 30px;
      justify-content: center;
    }
    .producto {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      width: 220px;
      text-align: center;
      padding-bottom: 20px;
      transition: transform 0.2s;
    }
    .producto:hover {
      transform: translateY(-5px);
    }
    .producto img {
      width: 100%;
      border-top-left-radius: 10px;
      border-top-right-radius: 10px;
      height: 180px;
      object-fit: cover;
    }
    .producto h3 {
      margin: 10px 0 5px 0;
      font-size: 18px;
      color: #333;
    }
    .producto p {
      color: #555;
    }
    footer {
      text-align: center;
      padding: 20px;
      background: #8D0004;
      color: white;
      margin-top: 40px;
    }
    body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  background: url('fondo-navidad.png') no-repeat top center, #f8f8f5;
  background-size: cover;
  background-attachment: fixed;
}

  </style>
</head>
<body>

  <header>
    <h1>Vascookies</h1>
    <p>Deliciosas galletas artesanales y caseras</p>
  </header>

  <div class="container">
    <h2 style="text-align:center;">Galletas</h2>
    <div class="productos">
      
      <div class="producto">
        <img src="https://nodashofgluten.com/wp-content/uploads/2025/10/Pfeffernusse-Cookies-Recipe-German-Spice-2.webp" alt="Macarrones">
        <h3><!-- Macarrones Sabores Surtidos -->Sugar Rush cookie</h3>
        <p>S/. 17.50</p>
      </div>

      <div class="producto">
        <img src="https://annaspasteleria.com/images/_imageBlock/DSC_1311web.jpg" alt="Brownie">
        <h3><!-- Brownie -->Galleta glaseada</h3>
        <p>S/. 10.00</p>
      </div>

      <div class="producto">
        <img src="https://tse2.mm.bing.net/th/id/OIP.CsURvBPJ7i-jo0r6OpVKGAHaHa?cb=12&rs=1&pid=ImgDetMain&o=7&rm=3" alt="ChocoChip">
        <h3><!-- Galleta Chocochip con Almendras -->Chispigalletas</h3>
        <p>Desde S/. 8.00</p>
      </div>

      <div class="producto">
        <img src="https://i.pinimg.com/originals/ff/7b/e2/ff7be2e68203e100c08c9b0031461a1c.jpg" alt="Box Macarrones">
        <h3><!-- Box Macarrones x16 -->Covigalletas</h3>
        <p><del>S/. 40.00</del> S/. 32.00</p>
      </div>

      <div class="producto">
        <img src="https://i1.wp.com/thehappening.com/wp-content/uploads/2019/12/galletas-jengibre.jpg?resize=1024%2C694&ssl=1" alt="Galletón">
        <h3><!-- Galletón de Nutella -->Navigalleta</h3>
        <p>S/. 9.00</p>
      </div>

      <div class="producto">
        <img src="https://bocatus.com/wp-content/uploads/2022/10/foto1_1920x1080-5-800x450.jpg" alt="Galleta Pistacho">
        <h3><!-- Galleta de Pistacho -->Chocogalleta</h3>
        <p>S/. 9.50</p>
      </div>

    </div>
  </div>
  <style>
  .snowflake {
    position: fixed;
    top: -10px;
    z-index: 9999;
    color: white;
    font-size: 1em;
    user-select: none;
    pointer-events: none;
    animation: fall linear infinite;
  }

  @keyframes fall {
    0% {
      transform: translateY(0) rotate(0deg);
      opacity: 1;
    }
    100% {
      transform: translateY(100vh) rotate(360deg);
      opacity: 0;
    }
  }
</style>

<script>
  function crearCopoNieve() {
    const snowflake = document.createElement('div');
    snowflake.classList.add('snowflake');
    snowflake.textContent = '❄';

    // Estilo aleatorio
    snowflake.style.left = Math.random() * 100 + 'vw';
    snowflake.style.fontSize = (Math.random() * 10 + 10) + 'px';
    snowflake.style.animationDuration = (Math.random() * 5 + 5) + 's';

    document.body.appendChild(snowflake);

    // Eliminar después de caer
    setTimeout(() => {
      snowflake.remove();
    }, 10000);
  }

  // Crear muchos copos
  setInterval(crearCopoNieve, 300);
</script>


  <footer>
    &copy; 2025 Vascookies. Todos los derechos reservados por economia.
  </footer>

</body>
</html>
