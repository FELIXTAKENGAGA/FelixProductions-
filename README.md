# FelixProductions-

<!DOCTYPE html>


<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FelixProductions</title>
    <link rel="icon" type="image/png" href="/Users/felix/Downloads/channels4_profile.jpg">
    <!-- Your existing code continues below -->
    <link href="https://fonts.googleapis.com/css2?family=Luckiest+Guy&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Luckiest Guy', cursive;
            text-align: center;
            margin: 0;
            padding: 0;
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed;
        }
        .content {
            background-color: rgba(255, 255, 255, 0.7);
            padding: 20px;
            border-radius: 10px;
            margin: 20px;
            display: inline-block;
        }
        .button {
            padding: 30px 60px;
            margin: 20px;
            color: white;
            text-decoration: none;
            border-radius: 10px;
            display: inline-block;
            cursor: pointer;
            font-size: 36px;
        }
        img {
            max-width: 300px;
            margin: 20px;
        }
        h1, p {
            font-size: 50px;
            margin: 20px;
        }
    </style>
</head>
<body style="background-image: url('file:///C:/Users/felix/Downloads/pngtree-cool-neon-star-4k-uhd-glowing-abstract-background-in-blue-and-image_3705285.jpg');">
    <div class="content">
        <h1>THIS IS THE OFFICAL WEBSITE FOR FELIXPRODUCTIONS!</h1>
        <p>ALL OUR SOCIALS U NEEDA KNOW:</p>
        
        <img src="file:///C:/Users/felix/Downloads/unnamed.jpg" alt="Image 1">
        <img src="file:///C:/Users/felix/Downloads/apps.60673.9007199266244427.4d45042b-d7a5-4a83-be66-97779553b24d.png" alt="Image 2">
        <img src="file:///C:/Users/felix/Downloads/fcbfbc56928955d093c4e8ec779c3ff5.jpg" alt="Image 3">
        <img src="file:///C:/Users/felix/Downloads/apple-touch-icon-180-893d0d532e8fbba714cceb8d9eae9567.png" alt="Image 4">
        <img src="file:///C:/Users/felix/Downloads/channels4_profile.jpg" alt="Image 5">
        
        <p>Click the buttons for more:</p>
        
        <a href="https://www.youtube.com/channel/UC_9w6dCCois5QKgrhKyV-3g" class="button" style="background-color: #3498db;">YOUTUBE </a>
        <a href="https://twitter.com/FelixTheGoof" class="button" style="background-color: #e74c3c;">TWITTER </a>
        <a href="https://discord.gg/DKvHDbCTRc" class="button" style="background-color: #2ecc71;">DISCORD </a>
        <a href="https://soundcloud.com/felix-productions" class="button" style="background-color: #f39c12;">SOUNDCLOUD </a>
        <a href="https://www.roblox.com/users/4684618244/profile" class="button" style="background-color: #9b59b6;">ROBLOX </a>
        
        <p>HAVE A FUN TIME HERE!!</p>
    </div>


    <script>
        const buttons = document.querySelectorAll('.button');
        
        buttons.forEach(button => {
            button.style.backgroundColor = getRandomColor();
        });
        
        function getRandomColor() {
            const letters = '0123456789ABCDEF';
            let color = '#';
            for (let i = 0; i < 6; i++) {
                color += letters[Math.floor(Math.random() * 16)];
            }
            return color;
        }
    </script>
</body>
</html>
