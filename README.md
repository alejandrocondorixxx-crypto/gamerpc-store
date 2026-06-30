<!DOCTYPE html>
<html lang="es">
<head>

<meta charset="UTF-8">

<title>GAMER PC STORE</title>

<link rel="stylesheet" href="css/styles.css">

</head>

<body>

<header>

<h1>🎮 GAMER PC STORE</h1>

<nav>

<a href="#inicio">Inicio</a>

<a href="#productos">Productos</a>

<a href="#promociones">Promociones</a>

<a href="#nosotros">Nosotros</a>

<a href="#contacto">Contacto</a>

</nav>

</header>

<section id="inicio">

<h2>Bienvenido</h2>

<img src="assets/images/banner.jpg" width="700">

<p>

Las mejores computadoras gamer al mejor precio.

</p>

</section>

<section id="productos">

<h2>Productos</h2>

<div class="producto">

<img src="assets/images/pc1.jpg">

<h3>PC Gamer RTX 4070</h3>

<p>Procesador Ryzen 7</p>

<h4>$1500</h4>

<button onclick="comprar()">Comprar</button>

</div>

<div class="producto">

<img src="assets/images/pc2.jpg">

<h3>Laptop ASUS ROG</h3>

<p>Intel Core i7</p>

<h4>$1800</h4>

<button onclick="comprar()">Comprar</button>

</div>

</section>

<section id="promociones">

<h2>Promociones</h2>

<p>

20% de descuento durante esta semana.

</p>

</section>

<section id="nosotros">

<h2>Nosotros</h2>

<p>

Somos una tienda especializada en computadoras gamer.

</p>

</section>

<section id="contacto">

<h2>Contacto</h2>

<form>

<input type="text" id="nombre" placeholder="Nombre">

<input type="email" id="correo" placeholder="Correo">

<textarea id="mensaje"></textarea>

<button type="button" onclick="enviar()">

Enviar

</button>

</form>

</section>

<script src="js/main.js"></script>

</body>

</html>
