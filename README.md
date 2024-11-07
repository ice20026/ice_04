
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuadro de Texto con Botón de Copia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .text-container {
            background-color: black; /* Fondo negro */
            color: white; /* Letras blancas */
            padding: 20px;
            border-radius: 5px;
            margin: 20px;
            font-family: Arial, sans-serif;
            max-width: 600px;
            width: 100%;
            word-wrap: break-word;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .text-container textarea {
            width: 100%;
            height: 150px; /* Altura configurable */
            background-color: black; /* Fondo negro */
            color: white; /* Letras blancas */
            border: none;
            border-radius: 5px;
            resize: none; /* Para evitar que el usuario cambie el tamaño del área de texto */
            padding: 10px;
        }
        .copy-btn {
            margin-top: 10px;
            padding: 10px 20px;
            color: white;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .copy-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="text-container">
        <textarea id="textToCopy" readonly>
        
        
        <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página Web</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 20px;
            text-align: center;
        }
        nav ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
        }
        nav ul li {
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .container {
            padding: 20px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenido a Mi Página Web</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Sobre Mí</a></li>
                <li><a href="#">Proyectos</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
    <div class="container">
        <h2>Contenido Principal</h2>
        <p>Este es un ejemplo de una página web básica con un diseño inicial.</p>
    </div>
    <footer>
        <p>&copy; 2024 Mi Nombre. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
        </textarea>
        <button class="copy-btn" onclick="copyText()">Copiar Texto</button>
    </div>
    <script>
        function copyText() {
            var textArea = document.getElementById("textToCopy");
            textArea.select();
            document.execCommand("copy");
            alert("¡Texto copiado al portapapeles!");
        }
    </script>
</body>
</html>






<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descripción de Elemento</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        .description-container {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: 20px auto;
        }
        .description-container h2 {
            margin-top: 0;
        }
        .description-container p {
            color: #666;
        }
    </style>
</head>
<body>
    <div class="description-container">
        <h2>como empezar una web
        explicacion del codigo </h2>
        <p>
  Explicación del Código
HTML: Define la estructura de la página, incluyendo el encabezado, la navegación, el contenido principal y el pie de página.

CSS: Aplica estilos básicos a los elementos de la página.

body: Establece la fuente principal, elimina márgenes y padding por defecto, y aplica un color de fondo.

header: Define el estilo del encabezado con un fondo oscuro y texto blanco.

nav ul: Establece un menú de navegación horizontal.

.container: Define el contenedor principal para el contenido.

footer: Define el estilo del pie de página, que está fijo en la parte inferior de la ventana.       </p>
    </div>
</body>
</html>




<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Configuración de Dimensiones de Página</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            height: 250vh; /* Altura de la página completa */
            width: 100vw; /* Ancho de la página completa */
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #f0f0f0;
        }
        .container {
            width: 0vw; /* Ancho del contenedor */
            height: 0vh; /* Altura del contenedor */
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            margin: auto; /* Centra el contenedor en la página */
        }
    </style>
</head>
<body>
    <div class="container">
        <h1></h1>
    </div>
</body>
</html>
















<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuadro de Texto con Botón de Copia</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .text-container {
            background-color: black; /* Fondo negro */
            color: white; /* Letras blancas */
            padding: 20px;
            border-radius: 5px;
            margin: 20px;
            font-family: Arial, sans-serif;
            max-width: 600px;
            width: 100%;
            word-wrap: break-word;
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .text-container textarea {
            width: 100%;
            height: 150px; /* Altura configurable */
            background-color: black; /* Fondo negro */
            color: white; /* Letras blancas */
            border: none;
            border-radius: 5px;
            resize: none; /* Para evitar que el usuario cambie el tamaño del área de texto */
            padding: 10px;
        }
        .copy-btn {
            margin-top: 10px;
            padding: 10px 20px;
            color: white;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .copy-btn:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="text-container">
        <textarea id="textToCopy" readonly>
        
        

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botones, Hipervínculos y Fondos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            text-align: center;
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .btn {
            display: inline-block;
            font-size: 18px;
            padding: 15px 30px;
            color: white;
            background-color: #007BFF;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none;
            margin: 10px;
            transition: background-color 0.3s, box-shadow 0.3s;
        }
        .btn:hover {
            background-color: #0056b3;
            box-shadow: 0 6px 8px rgba(0, 0, 0, 0.15);
        }
        a {
            color: #007BFF;
            text-decoration: none;
            margin: 10px;
            display: inline-block;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Ejemplo de Página Web</h1>
        <p>Esta es una página de ejemplo que incluye botones, hipervínculos y un fondo estilizado.</p>
        <!-- Botón que actúa como hipervínculo -->
        <a href="https://www.ejemplo.com" class="btn">Visitar Ejemplo</a>  
        <!-- Hipervínculo de texto -->
        <a href="https://www.ejemplo.com">Enlace de Texto</a>
    </div>
</body>
</html>
</textarea>
        <button class="copy-btn" onclick="copyText()">Copiar Texto</button>
    </div>
    <script>
        function copyText() {
            var textArea = document.getElementById("textToCopy");
            textArea.select();
            document.execCommand("copy");
            alert("¡Texto copiado al portapapeles!");
        }
    </script>
</body>
</html>






<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Descripción de Elemento</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        .description-container {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            max-width: 600px;
            margin: 20px auto;
        }
        .description-container h2 {
            margin-top: 0;
        }
        .description-container p {
            color: #666;
        }
    </style>
</head>
<body>
    <div class="description-container">
        <h2>codigo para poner fondo,hipervinculo y aplicar fondos </h2>
        <p>

        
        Explicación del Código
HTML: Define la estructura básica de la página, incluyendo el contenedor para el contenido principal, botones y enlaces.

CSS: Aplica estilos a la página, el contenedor, los botones y los hipervínculos.

body: Utiliza display: flex; justify-content: center; align-items: center; height: 100vh; para centrar el contenido vertical y horizontalmente en la pantalla. Aplica un color de fondo gris claro.

.container: Define el contenedor con un fondo blanco, padding, bordes redondeados y sombra. También centra el texto.

.btn: Estiliza el botón con un color de fondo azul, texto blanco, bordes redondeados y una sombra. También define efectos al pasar el ratón.

a: Estiliza los hipervínculos con un color azul y elimina la subrayado por defecto. Agrega un efecto de subrayado al pasar el ratón.  
        </p>
    </div>
</body>
</html>
















