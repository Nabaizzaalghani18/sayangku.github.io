<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animasi Cinta</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f8d7da;
            font-family: Arial, sans-serif;
        }
        .heart {
            font-size: 100px;
            color: red;
            animation: heartbeat 1s infinite;
        }
        @keyframes heartbeat {
            0%, 100% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.2);
            }
        }
    </style>
</head>
<body>
    <div>
        <div class="heart">❤️</div>
    </div>
    <div>
        <h1>I LOVE YOU MILAA!!!!!!</h1>
        <button onclick="location.href='animasi2.html'">Lanjutkan</button>
        <audio id="romanticMusic" src="path/to/your/romantic-music.mp3" loop autoplay></audio>
    </div>
    <div>
        <div class="heart">❤️</div>
    </div>
    <script>
        const music = document.getElementById('romanticMusic');
        music.volume = 0.5; 
    </script>
</body>
</html>
