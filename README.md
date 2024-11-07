<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Secciones de Código</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        .section {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin-bottom: 20px;
        }
        .section h2 {
            margin-top: 0;
            background-color: #007BFF;
            color: white;
            padding: 10px;
            border-radius: 5px 5px 0 0;
        }
        .code-block {
            background-color: #333;
            color: white;
            padding: 20px;
            border-radius: 5px;
            overflow-x: auto;
            margin-top: 10px;
        }
        code {
            display: block;
            white-space: pre-wrap;
            word-wrap: break-word;
        }
    </style>
</head>
<body>
    <div class="section">
        <h2>Sección 1: Ejemplo HTML</h2>
        <div class="code-block">
            <code>
                &lt;!-- Código HTML --&gt;
                &lt;div&gt;
                    &lt;p&gt;Este es un ejemplo de código HTML.&lt;/p&gt;
                &lt;/div&gt;
            </code>
        </div>
    </div>
    <div class="section">
        <h2>Sección 2: Ejemplo CSS</h2>
        <div class="code-block">
            <code>
                /* Código CSS */
                body {
                    background-color: #f0f0f0;
                    font-family: Arial, sans-serif;
                }
            </code>
        </div>
    </div>
    <div class="section">
        <h2>Sección 3: Ejemplo JavaScript</h2>
        <div class="code-block">
            <code>
                // Código JavaScript
                console.log('Hola Mundo!');
            </code>
        </div>
    </div>
</body>
</html>
