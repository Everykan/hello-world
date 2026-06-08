<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Perfil Artístico | Tu Nombre</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- ESTILOS CSS -->
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #1e1e1e;
            color: white;
            padding: 40px 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        header p {
            font-size: 1.1rem;
            max-width: 600px;
            margin: 10px auto 0;
        }

        nav {
            background-color: #333;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            max-width: 1000px;
            margin: 40px auto;
            padding: 20px;
            background-color: white;
            border-radius: 8px;
        }

        section h2 {
            border-bottom: 2px solid #ddd;
            padding-bottom: 10px;
        }

        /* PUBLICACIONES */
        .publicacion {
            margin-bottom: 25px;
        }

        .publicacion h3 {
            margin-bottom: 5px;
        }

        .publicacion p {
            margin: 0;
            color: #555;
        }

        /* CONTACTO */
        .contacto p {
            margin: 8px 0;
        }

        .contacto a {
            color: #0066cc;
            text-decoration: none;
        }

        .contacto a:hover {
            text-decoration: underline;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #1e1e1e;
            color: white;
            margin-top: 40px;
        }

        @media (max-width: 768px) {
            header h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>

<body>

    <!-- ENCABEZADO -->
    <header>
        <h1>Tu Nombre Artístico</h1>
        <p>Artista visual / Escritor / Músico / Fotógrafo  
        Especializado en expresión creativa y proyectos artísticos contemporáneos.</p>
    </header>

    <!-- MENÚ -->
    <nav>
        <a href="#publicaciones">Publicaciones</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <!-- SECCIÓN PUBLICACIONES -->
    <section id="publicaciones">
        <h2>Publicaciones</h2>

        <div class="publicacion">
            <h3>Título de la obra 1</h3>
            <p>Breve descripción de la obra, proyecto artístico o publicación.</p>
        </div>

        <div class="publicacion">
            <h3>Título de la obra 2</h3>
            <p>Descripción corta explicando el concepto, técnica o año.</p>
        </div>

        <div class="publicacion">
            <h3>Título de la obra 3</h3>
            <p>Detalles relevantes de la publicación o exposición.</p>
        </div>
    </section>

    <!-- SECCIÓN CONTACTO -->
    <section id="contacto">
        <h2>Contacto</h2>

        <div class="contacto">
            <p><strong>Email:</strong> <a href="mailto:tuemail@ejemplo.com">tuemail@ejemplo.com</a></p>
            <p><strong>Instagram:</strong> <a href="https://instagram.com/tuperfil" target="_blank">@tuperfil</a></p>
            <p><strong>LinkedIn:</strong> <a href="#" target="_blank">Ver perfil</a></p>
        </div>
    </section>

    <!-- PIE DE PÁGINA -->
    <footer>
        <p>© 2026 · Tu Nombre Artístico</p>
    </footer>

</body>
</html>