<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>For Chhavi ❤️</title>
    <style>
        body {
            text-align: center;
            background: url('https://i.postimg.cc/1XDvDtYs/IMG-0962.jpg') no-repeat center center/cover;
            color: white;
            font-family: 'Arial', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
            transition: background 1s ease-in-out;
        }
        .container {
            background: rgba(0, 0, 0, 0.6);
            padding: 20px;
            border-radius: 15px;
            max-width: 600px;
        }
        h1 {
            font-size: 2.5em;
        }
        p {
            font-size: 1.2em;
            margin-top: 15px;
        }
        .ring {
            font-size: 4em;
            animation: ring-animation 2s infinite alternate;
        }
        @keyframes ring-animation {
            0% { transform: scale(1); }
            100% { transform: scale(1.2); }
        }
        .button {
            background: red;
            color: white;
            padding: 15px 30px;
            border: none;
            border-radius: 10px;
            font-size: 1.2em;
            cursor: pointer;
            margin-top: 20px;
            transition: 0.3s;
        }
        .button:hover {
            background: pink;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Chhavi, My Love Forever ❤️</h1>
        <p>"From the moment I met you, my world changed forever. You are my light, my happiness, and my everything. On this special day, I just want to say... Will you always be mine? 💖"</p>
        <div class="ring">💍</div>
        <button class="button" onclick="showLove()">Will You Be Mine? 💕</button>
        <p id="message" style="display:none; font-size: 1.5em; margin-top: 20px;">I Love You Forever, Chhavi! ❤️</p>
    </div>
    <audio autoplay loop>
        <source src="your-old-hindi-romantic-song.mp3" type="audio/mpeg">
    </audio>
    <script>
        function showLove() {
            document.getElementById('message').style.display = 'block';
        }

        // Slideshow effect for background images
        let images = [
            'https://i.postimg.cc/1XDvDtYs/IMG-0962.jpg',
            'https://i.postimg.cc/1tkWg6Bv/IMG-1254.jpg',
            'https://i.postimg.cc/C1BPLJGZ/IMG-2685.jpg',
            'https://i.postimg.cc/Bvw70RK9/IMG-2689.jpg',
            'https://i.postimg.cc/05SWTW5F/IMG-2690.jpg',
            'https://i.postimg.cc/7Yysw3f6/IMG-2691.jpg',
            'https://i.postimg.cc/wTcWv1mk/IMG-2692.jpg'
        ];

        let index = 0;
        function changeBackground() {
            document.body.style.backgroundImage = `url('${images[index]}')`;
            index = (index + 1) % images.length;
        }
        setInterval(changeBackground, 5000); // Change every 5 seconds
    </script>
</body>
</html>
