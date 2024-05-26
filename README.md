# Maderamaestra
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artesanía en Madera</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">Tu Marca</div>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#galeria">Galería</a></li>
                <li><a href="#testimonios">Testimonios</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="inicio" class="hero">
        <h1>Artesanía en Madera de Alta Calidad</h1>
        <p>Descubre la belleza de lo natural</p>
        <a href="#productos" class="btn">Explorar Colección</a>
    </section>

    <section id="destacados" class="destacados">
        <h2>Productos Destacados</h2>
        <div class="productos">
            <div class="producto">
                <img src="producto1.jpg" alt="Producto 1">
                <h3>Producto 1</h3>
                <p>Descripción breve del producto 1.</p>
            </div>
            <div class="producto">
                <img src="producto2.jpg" alt="Producto 2">
                <h3>Producto 2</h3>
                <p>Descripción breve del producto 2.</p>
            </div>
            <div class="producto">
                <img src="producto3.jpg" alt="Producto 3">
                <h3>Producto 3</h3>
                <p>Descripción breve del producto 3.</p>
            </div>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Tu Marca. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header .logo {
    font-size: 1.5rem;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

header nav ul li {
    margin-left: 1rem;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

.hero {
    background: url('hero.jpg') no-repeat center center/cover;
    color: #fff;
    text-align: center;
    padding: 5rem 1rem;
}

.hero h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}

.hero p {
    font-size: 1.2rem;
    margin-bottom: 2rem;
}

.hero .btn {
    background: #ff5722;
    color: #fff;
    padding: 0.75rem 1.5rem;
    text-decoration: none;
    border-radius: 5px;
}

.destacados {
    padding: 2rem 1rem;
    text-align: center;
}

.destacados h2 {
    font-size: 2rem;
    margin-bottom: 1.5rem;
}

.destacados .productos {
    display: flex;
    justify-content: center;
    gap: 2rem;
}

.destacados .producto {
    width: 30%;
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 1rem;
    text-align: center;
}

.destacados .producto img {
    max-width: 100%;
    border-radius: 5px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem;
    position: absolute;
    bottom: 0;
    width: 100%;
}
