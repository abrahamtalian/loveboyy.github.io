<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi amor</title>
    <style>
        body {
            margin: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background: linear-gradient(135deg, #ffafbd, #ffc3a0);
            font-family: Arial, sans-serif;
            color: #fff;
            text-align: center;
        }
        .container {
            padding: 20px;
        }
        h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        p {
            font-size: 1.2em;
            max-width: 500px;
            margin: 0 auto 20px;
        }
        .heart {
            width: 100px;
            height: 100px;
            background: #ff4d4d;
            position: relative;
            margin: 20px auto;
            transform: rotate(-45deg);
            animation: beat 1.2s ease-in-out infinite;
        }
        .heart::before,
        .heart::after {
            content: '';
            width: 100px;
            height: 100px;
            background: #ff4d4d;
            border-radius: 50%;
            position: absolute;
        }
        .heart::before {
            top: -50px;
            left: 0;
        }
        .heart::after {
            left: 50px;
            top: 0;
        }
        @keyframes beat {
            0%, 100% {
                transform: scale(1) rotate(-45deg);
            }
            50% {
                transform: scale(1.1) rotate(-45deg);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Para mi chico Ariel</h1>
        <p>Te amo con todo mi corazón. Eres mi persona favorita, mi apoyo y mi alegría. ¡Gracias por hacerme tan feliz!</p>
        <div class="heart"></div>
    </div>
</body>
</html>
