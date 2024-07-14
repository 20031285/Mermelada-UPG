<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mermeladas UPG</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Mermeladas UPG</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#producto">Producto</a></li>
                <li><a href="#cotizaciones">Cotizaciones</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="inicio">
            <h2>Bienvenido a Mermeladas UPG</h2>
            <p>Descubre nuestra deliciosa mermelada de fresa, producida en el hermoso estado de Guanajuato.</p>
        </section>
        <section id="producto">
            <h2>Producto</h2>
            <p>Ofrecemos mermelada de fresa en frascos de 500 gramos, ideal para acompañar tus comidas favoritas.</p>
            <img src="mermelada.jpg" alt="Frasco de mermelada de fresa">
        </section>
        <section id="cotizaciones">
            <h2>Cotizaciones</h2>
            <form action="submit-quote" method="post">
                <label for="nombre">Nombre:</label>
                <input type="text" id="nombre" name="nombre" required>
                <label for="email">Correo Electrónico:</label>
                <input type="email" id="email" name="email" required>
                <label for="mensaje">Mensaje:</label>
                <textarea id="mensaje" name="mensaje" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
        <section id="contacto">
            <h2>Contacto</h2>
            <p>Para más información, contáctanos en:</p>
            <p>Email: info@mermeladasupg.com</p>
            <p>Teléfono: +52 411 197 0191 </p>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Mermeladas UPG. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
