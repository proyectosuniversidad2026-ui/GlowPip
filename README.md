/* Estilos Generales para GlowPip */
body {
    font-family: 'Montserrat', sans-serif;
    background-color: #FFF9FB;
    color: #2D2D2D;
    margin: 0;
    line-height: 1.6;
}

h1, h2, .logo {
    font-family: 'Playfair Display', serif;
}

/* Encabezado y Navegación */
header {
    background-color: white;
    padding: 1rem 5%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 2px 10px rgba(0,0,0,0.05);
    position: sticky;
    top: 0;
    z-index: 1000;
}

.logo {
    font-size: 1.8rem;
    color: #FF69B4;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 20px;
    margin: 0;
    padding: 0;
}

nav a {
    text-decoration: none;
    color: #2D2D2D;
    transition: color 0.3s;
}

nav a:hover, nav a.active {
    color: #FFD700;
    border-bottom: 2px solid #FFD700;
}

/* Main Content */
main {
    padding: 3rem 5%;
    text-align: center;
}

/* Sección Hero (Inicio) */
.hero {
    padding: 4rem 10%;
    background: linear-gradient(135deg, #fff5f8 0%, #fff 100%);
    border-radius: 20px;
    margin-bottom: 3rem;
}

.btn {
    display: inline-block;
    padding: 12px 30px;
    background-color: #FF69B4;
    color: white;
    text-decoration: none;
    border-radius: 30px;
    transition: transform 0.3s;
}

.btn:hover {
    background-color: #FFD700;
    transform: translateY(-3px);
}

/* Grid de Productos */
.grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 30px;
    margin-top: 2rem;
}

.card {
    background: white;
    padding: 20px;
    border-radius: 15px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    transition: transform 0.3s;
}

.card:hover {
    transform: scale(1.05);
}

.img-placeholder {
    font-size: 4rem;
    height: 150px;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #fcfcfc;
    margin-bottom: 15px;
}

/* Efecto de Brillo para Lámparas */
.glow-effect:hover {
    box-shadow: 0 0 20px rgba(255, 215, 0, 0.4);
}

/* Formulario */
.contact-form {
    max-width: 500px;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    gap: 15px;
}

.contact-form input, .contact-form textarea {
    padding: 12px;
    border: 1px solid #ddd;
    border-radius: 8px;
}

footer {
    padding: 2rem;
    background: #2D2D2D;
    color: white;
    text-align: center;
}

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>GlowPip - Inicio</title>
    <link rel="stylesheet" href="styles.css">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Playfair+Display:wght@700&display=swap" rel="stylesheet">
</head>
<body>
    <header>
        <div class="logo">GlowPip</div>
        <nav>
            <ul>
                <li><a href="index.html" class="active">Inicio</a></li>
                <li><a href="flores.html">Flores</a></li>
                <li><a href="lamparas.html">Lámparas</a></li>
                <li><a href="nosotros.html">Nosotros</a></li>
                <li><a href="contacto.html">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section class="hero">
            <h1>Arte que Brilla con Luz Propia</h1>
            <p>Descubre nuestras flores y lámparas artesanales hechas a mano con limpiapipas.</p>
            <a href="flores.html" class="btn">Ver Catálogo</a>
        </section>
    </main>
    <footer><p>&copy; 2026 GlowPip - Proyecto de Aula</p></footer>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Flores - GlowPip</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">GlowPip</div>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="flores.html" class="active">Flores</a></li>
                <li><a href="lamparas.html">Lámparas</a></li>
                <li><a href="nosotros.html">Nosotros</a></li>
                <li><a href="contacto.html">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Nuestro Jardín Eterno</h1>
        <div class="grid">
            <div class="card"><div class="img-placeholder">🌹</div><h3>Rosas</h3></div>
            <div class="card"><div class="img-placeholder">🌻</div><h3>Girasoles</h3></div>
            <div class="card"><div class="img-placeholder">🌷</div><h3>Tulipanes</h3></div>
        </div>
    </main>
    <footer><p>&copy; 2026 GlowPip - Proyecto de Aula</p></footer>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Lámparas - GlowPip</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">GlowPip</div>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="flores.html">Flores</a></li>
                <li><a href="lamparas.html" class="active">Lámparas</a></li>
                <li><a href="nosotros.html">Nosotros</a></li>
                <li><a href="contacto.html">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Lámparas Decorativas</h1>
        <div class="grid">
            <div class="card glow-effect"><div class="img-placeholder">💡</div><h3>Lirio de Luz</h3></div>
            <div class="card glow-effect"><div class="img-placeholder">✨</div><h3>Domo Floral</h3></div>
        </div>
    </main>
    <footer><p>&copy; 2026 GlowPip - Proyecto de Aula</p></footer>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Nosotros - GlowPip</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">GlowPip</div>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="flores.html">Flores</a></li>
                <li><a href="lamparas.html">Lámparas</a></li>
                <li><a href="nosotros.html" class="active">Nosotros</a></li>
                <li><a href="contacto.html">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Nuestra Historia</h1>
        <p>En GlowPip transformamos limpiapipas en arte duradero.</p>
    </main>
    <footer><p>&copy; 2026 GlowPip - Proyecto de Aula</p></footer>
</body>
</html>

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Contacto - GlowPip</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">GlowPip</div>
        <nav>
            <ul>
                <li><a href="index.html">Inicio</a></li>
                <li><a href="flores.html">Flores</a></li>
                <li><a href="lamparas.html">Lámparas</a></li>
                <li><a href="nosotros.html">Nosotros</a></li>
                <li><a href="contacto.html" class="active">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h1>Haz tu Pedido</h1>
        <form class="contact-form">
            <input type="text" placeholder="Nombre" required>
            <input type="email" placeholder="Correo" required>
            <textarea placeholder="Tu diseño personalizado..."></textarea>
            <button type="submit" class="btn">Enviar Solicitud</button>
        </form>

</html>
