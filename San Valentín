<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¿Quieres ser mi San Valentín?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffccd5;
        }
        .container {
            margin-top: 100px;
        }
        h1 {
            color: #d6336c;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 18px;
            border: none;
            cursor: pointer;
            margin: 10px;
        }
        .yes {
            background-color: #ff4d6d;
            color: white;
        }
        .no {
            background-color: #ff4d6d;
            color: white;
            position: absolute;
        }
    </style>
    <script>
        function moveNoButton() {
            let button = document.getElementById("no");
            button.style.top = Math.random() * window.innerHeight + "px";
            button.style.left = Math.random() * window.innerWidth + "px";
        }
        function showMessage() {
            alert("¡Sabía que dirías que sí! ❤️");
        }
    </script>
</head>
<body>
    <div class="container">
        <h1>¿Quieres ser mi San Valentín? 💖</h1>
        <div class="buttons">
            <button class="yes" onclick="showMessage()">Sí</button>
            <button class="no" id="no" onmouseover="moveNoButton()">No</button>
        </div>
    </div>
</body>
</html>
