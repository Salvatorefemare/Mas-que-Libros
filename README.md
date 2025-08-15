# Mas-que-Libros
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biblioteca Virtual</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem;
            text-align: center;
        }
        nav {
            background: #333;
            padding: 0.5rem;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        .container {
            padding: 20px;
            max-width: 1000px;
            margin: auto;
        }
        .libro {
            background: white;
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0px 0px 5px rgba(0,0,0,0.1);
        }
        .libro h3 {
            margin-top: 0;
        }
        button {
            background-color: #4CAF50;
            color: white;
            border: none;
            padding: 10px;
            margin-right: 10px;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #45a049;
        }
        /* Chatbot flotante */
        .chatbot-container {
            position: fixed;
            bottom: 10px;
            right: 10px;
            width: 350px;
            height: 500px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.3);
            border-radius: 10px;
            overflow: hidden;
            z-index: 999;
            background: white;
        }
    </style>
</head>
<body>
    <header>
        <h1>Biblioteca Virtual</h1>
        <p>Compra o alquila libros de tus autores favoritos</p>
    </header>

    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#catalogo">Catálogo</a>
    </nav>

    <div class="container" id="inicio">
        <h2>Bienvenido a la Biblioteca Virtual</h2>
        <p>Aquí encontrarás libros de distintos géneros y autores para leer desde casa.</p>
    </div>

    <div class="container" id="catalogo">
        <h2>Catálogo de Libros</h2>

        <div class="libro">
            <h3>Cien años de soledad</h3>
            <p><b>Autor:</b> Gabriel García Márquez</p>
            <p><b>Género:</b> Realismo mágico</p>
            <button>Comprar</button>
            <button>Alquilar</button>
        </div>

        <div class="libro">
            <h3>El Principito</h3>
            <p><b>Autor:</b> Antoine de Saint-Exupéry</p>
            <p><b>Género:</b> Fábula</p>
            <button>Comprar</button>
            <button>Alquilar</button>
        </div>

        <div class="libro">
            <h3>1984</h3>
            <p><b>Autor:</b> George Orwell</p>
            <p><b>Género:</b> Distopía</p>
            <button>Comprar</button>
            <button>Alquilar</button>
        </div>
    </div>

    <!-- Chatbot flotante -->
    <div class="chatbot-container">
        <iframe 
            src="https://copilotstudio.microsoft.com/environments/Default-6ca34ae1-466f-44bc-a7aa-0ac5a78c61b1/bots/cr3a3_isa/webchat?__version__=2" 
            frameborder="0" 
            style="width: 100%; height: 100%;">
        </iframe>
    </div>
</body>
</html>
