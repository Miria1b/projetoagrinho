<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Campo vs. Cidade</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.js"></script>
    <script src="sketch.js"></script>
    <style>
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background-color: #f0f0f0;
            font-family: sans-serif;
            color: #333;
        }
        canvas {
            display: block;
            border: 2px solid #555;
        }
        #instrucoes {
            text-align: center;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div id="instrucoes">
        <h1>Campo vs. Cidade</h1>
        <p>Arraste os elementos para o lado correto: <strong>Campo (esquerda)</strong> ou <strong>Cidade (direita)</strong>.</p>
        <p>Você tem 30 segundos!</p>
    </div>
</body>
</html>
