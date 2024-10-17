<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>My Endless Love larasani junita</title>
    <style>
        body {
            background-color: #fff0f5;
            font-family: 'Georgia', serif;
            color: #ff3366;
            margin: 0;
            overflow: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }

        .container {
            text-align: center;
            background-color: #fff;
            border: 2px solid #ff99cc;
            border-radius: 15px;
            box-shadow: 0 0 30px rgba(255, 153, 204, 0.5);
            padding: 30px;
            width: 70%;
            max-width: 600px;
            z-index: 2;
            position: relative;
        }

        h1 {
            font-size: 40px;
            margin-bottom: 20px;
            color: #ff3366;
        }

        p {
            font-size: 20px;
            line-height: 1.6;
            margin: 10px 0;
        }

        .signature {
            margin-top: 30px;
            font-style: italic;
            font-size: 22px;
        }

        
        .heart {
            position: absolute;
            color: #ff3366;
            font-size: 30px;
            animation: float 6s infinite ease-in-out;
        }

   
        @keyframes float {
            0% {
                transform: translateY(0) scale(1);
                opacity: 1;
            }
            50% {
                transform: translateY(-100px) scale(1.5);
                opacity: 0.6;
            }
            100% {
                transform: translateY(-200px) scale(0.8);
                opacity: 0;
            }
        }

        
        .heart:nth-child(1) { left: 20%; animation-duration: 4s; }
        .heart:nth-child(2) { left: 40%; animation-duration: 5s; }
        .heart:nth-child(3) { left: 60%; animation-duration: 6s; }
        .heart:nth-child(4) { left: 80%; animation-duration: 7s; }
        .heart:nth-child(5) { left: 90%; animation-duration: 5s; }

        audio {
            display: none;
        }
    </style>
</head>
<body>

   
    <div class="heart">❤️</div>
    <div class="heart">💖</div>
    <div class="heart">💘</div>
    <div class="heart">💞</div>
    <div class="heart">💕</div>

    <div class="container">
        <h1>My Endless Love</h1>
        <p>Dear Love,</p>
        <p>Every day I wake up thinking of you. Your smile, your laughter, and the way you make everything better. You are my sunshine on a rainy day and my strength when I feel weak.</p>
        <p>I will love you, today, tomorrow, and forever. ❤️</p>
        <p class="signature">Yours always,<br> [larasani junita]</p>
    </div>

    <audio autoplay loop>
        <source src="beutiful.mp3" type="audio/mp3"/>
	Your browser does not support the audio tag.
    </audio>
<button onclick="document.getElementById('myAudio').play()">Play Music</button>

</body>
</html>
