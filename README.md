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






<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cuadro de Texto Copiable</title>
    <style>
        .text-container {
            background-color: black; /* Fondo negro */
            color: white; /* Letras blancas */
            padding: 20px;
            border-radius: 5px;
            margin: 20px;
            font-family: Arial, sans-serif;
            max-width: 300px;
            word-wrap: break-word;
        }
        .text-container textarea {
            width: 100%;
            height: 150px;
            background-color: black; /* Fondo negro */
            color: white; /* Letras blancas */
            border: none;
            resize: none; /* Para evitar que el usuario cambie el tamaño del área de texto */
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
        <textarea id="textToCopy" readonly>Este es el texto que puedes copiar.</textarea>
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


