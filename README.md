# web-004

<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagen de Fondo</title>
    <style>
        body {
            background-image: url('fondo n1.jpg'); /* Imagen de fondo */
            background-size: cover; /* Ajusta la imagen para cubrir toda la pantalla */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que la imagen se repita */
            margin: 0;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <h1>¡Hola Mundo!</h1>
    <p> </p>
</body>
</html>







<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Configuración de Dimensiones</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            height: 130vh; /* Altura de la página completa */
            width: 100vw; /* Ancho de la página completa */
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .container {
            width: 80%; /* Ancho del contenedor */
            height: 80%; /* Altura del contenedor */
            background-color: white;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1></h1>
        <p></p>
    </div>
</body>
</html>






<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuadro de Texto Copiable</title>
    <style>
        .text-container {
            background-color: black; /* Fondo negro */
            color: white; /* Letras blancas */
            padding: 30px;
            border-radius: 5px;
            margin: 40px;
            font-family: Arial, sans-serif;
            max-width: 300px;
            word-wrap: break-word;
        }
        .text-container textarea {
            width: 200%;
            height: 200px;
            background-color: black; /* Fondo negro */
            color: white; /* Letras blancas */
            border: none;
            resize: none; /* Para evitar que el usuario cambie el tamaño del área de texto */
        }
        .copy-btn {
            margin-top: 50px;
            padding: 40px 40px;
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
</htm 
  </textarea>
        <button class="copy-btn" onclick="copyText()">Copiar Texto</button>
    </div>
    <script>
        function copyText() {
            var textArea = document.getElementById("textToCopy");
            textArea.select();
            document.execCommand("copy");
            alert("Texto copiado al portapapeles!");
        }
    </script>
</body>
</html>


