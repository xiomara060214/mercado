# mercado
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MULTI-MARKET | Tu Tienda Digital</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background: #222;
            color: white;
            padding: 15px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header .logo {
            height: 60px;
        }

        nav ul {
            display: flex;
            gap: 20px;
            list-style: none;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        /* HERO */
        .hero {
            padding: 60px;
            text-align: center;
            background: lightgray;
        }

        /* GRID PRODUCTOS */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }

        .card {
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 10px;
            text-align: center;
            background: white;
            box-shadow: 0 2px 6px rgba(0,0,0,0.1);
        }

        .card img {
            width: 100%;
            aspect-ratio: 1/1;
            object-fit: cover;
            border-radius: 10px;
        }

        .card button {
            margin-top: 10px;
            padding: 10px 15px;
            background: #0078ff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        .servicios, .contacto {
            padding: 40px;
            text-align: center;
        }

        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 15px;
        }

        input, textarea {
            width: 80%;
            padding: 8px;
            margin: 8px;
        }
    </style>



        <img src="logo.png" alt="Logo Multi-Market" class="logo">

        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
   

    <!-- HERO -->
    <section id="inicio" class="hero">
        <h1>Bienvenido a MULTI-MARKET</h1>
        <p>Tu plataforma confiable para comprar de todo en un solo lugar.</p>
        <a href="#productos" class="btn">Ver Productos</a>
    </section>

    <!-- PRODUCTOS -->
    <section id="productos">
        <h2 style="text-align:center;">Nuestros Productos</h2>

        <div class="grid">

            <div class="card">
                <img src="imagen1.jpg" alt="Producto 1">
                <h3>Producto 1</h3>
                <p>Set de cucharones</p>
                <button>Comprar</button>
            </div>

            <div class="card">
                <img src="imagen2.webp" alt="Producto 2">
                <h3>Producto 2</h3>
                <p>Set de cucharones y cuchillos</p>
                <button>Comprar</button>
            </div>

            <div class="card">
                <img src="imagen3.jpeg" alt="Producto 3">
                <h3>Producto 3</h3>
                <p>Espejo flexible</p>
                <button>Comprar</button>
            </div>

            <div class="card">
                <img src="imagen4.jpg" alt="Producto 4">
                <h3>Producto 4</h3>
                <p>Espejo forma lunar</p>
                <button>Comprar</button>
            </div>

            <div class="card">
                <img src="imagen5.jpg" alt="Producto 5">
                <h3>Producto 5</h3>
                <p>Set de jardinería</p>
                <button>Comprar</button>
            </div>

        </div>
    </section>

    <!-- SERVICIOS -->
    <section id="servicios" class="servicios">
        <h2>¿Qué Ofrecemos?</h2>
        <ul style="list-style:none; padding:0;">
            <li>✔ Entregas rápidas y seguras</li>
            <li>✔ Atención al cliente 24/7</li>
            <li>✔ Productos de alta calidad</li>
            <li>✔ Precios competitivos</li>
        </ul>
    </section>

    <!-- CONTACTO -->
    <section id="contacto" class="contacto">
        <h2>Contáctanos</h2>
        <form>
            <input type="text" placeholder="Tu nombre" required>
            <br>
            <input type="email" placeholder="Correo electrónico" required>
            <br>
            <textarea placeholder="Escribe tu mensaje"></textarea>
            <br>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <!-- FOOTER -->
    <footer>
        <p>© 2025 MULTI-MARKET — Todos los derechos reservados.</p>
    </footer>
</head>
</body>
</html>
