<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feliz 21 de Marzo</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: radial-gradient(circle, #ffdd57, #ffa500, #ff6b00);
            margin: 0;
            font-family: 'Arial', sans-serif;
            overflow: hidden;
            animation: backgroundFlow 15s infinite alternate;
        }

        .container {
            text-align: center;
            animation: fadeIn 2s ease-in-out;
        }

        h1 {
            color: #ffffff;
            font-size: 4.5em;
            margin-bottom: 10px;
            text-shadow: 3px 3px 10px #ff8c00;
            animation: glowText 2s infinite alternate;
        }

        p {
            color: #fff;
            font-size: 1.8em;
            text-shadow: 1px 1px 6px #e6a700;
        }

        .bouquet img {
            width: 300px;
            animation: bounceIn 2s ease-out;
            filter: drop-shadow(0 0 15px #ffdb58);
        }

        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }

        @keyframes backgroundFlow {
            0% { background: radial-gradient(circle, #ffdd57, #ffa500, #ff6b00); }
            50% { background: radial-gradient(circle, #ffbb33, #ff7700, #e64a00); }
            100% { background: radial-gradient(circle, #ffdd57, #ffa500, #ff6b00); }
        }

        @keyframes glowText {
            from { text-shadow: 3px 3px 10px #ff8c00, 0 0 20px #ffd700; }
            to { text-shadow: 3px 3px 20px #ff4500, 0 0 30px #ffdd57; }
        }

        @keyframes bounceIn {
            0% { transform: scale(0.3); opacity: 0; }
            50% { transform: scale(1.1); opacity: 1; }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>

<div class="container">
    <h1>¡Feliz 21 de Marzo!</h1>
    <p>Que tu día sea tan radiante como este ramo de flores amarillas 🌻✨</p>
    <div class="bouquet">
        <img src="Mira este GIF... 👀 https://pin.it/4w2RWA1bu" alt="Ramo de flores amarillas">
    </div>
</div>

</body>
</html>
