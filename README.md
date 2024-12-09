<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhay099's Bio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #000; /* Black background */
            color: white; /* White text color */
        }
        header {
            background-color: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #555;
            padding: 10px;
        }
        nav a {
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            text-align: center;
        }
        nav a:hover {
            background-color: #111;
        }
        main {
            padding: 20px;
            text-align: center;
        }
        .section-block {
            background-color: #222; /* Darker block background */
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
            animation: fadeIn 2s ease-in-out;
        }
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
        @keyframes backgroundAnimation {
            0% { background-position: 0 0; }
            100% { background-position: 100% 100%; }
        }
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(45deg, rgba(0, 0, 0, 0.5) 25%, transparent 25%), 
                        linear-gradient(-45deg, rgba(0, 0, 0, 0.5) 25%, transparent 25%), 
                        linear-gradient(45deg, transparent 75%, rgba(0, 0, 0, 0.5) 75%), 
                        linear-gradient(-45deg, transparent 75%, rgba(0, 0, 0, 0.5) 75%);
            background-size: 50px 50px;
            z-index: -1;
            animation: backgroundAnimation 10s linear infinite;
        }
        .social-links a {
            color: #fff; /* Changed to white */
            margin: 0 10px;
            text-decoration: none;
            transition: color 0.3s;
            background-color: #444; /* Button background */
            padding: 10px 20px;
            border-radius: 5px;
            display: inline-block; /* Ensures button styling */
        }
        .social-links a:hover {
            color: #111;
            background-color: #666; /* Hover effect */
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            width: 100%;
            bottom: 0;
            animation: slideUp 1s ease-out;
        }
        @keyframes slideUp {
            from {
                transform: translateY(100%);
            }
            to {
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Abhay099's Bio</h1>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#hobbies">Hobbies</a>
        <a href="#follow">Follow Me</a>
    </nav>
    <main>
        <div class="section-block" id="about">
            <h2>About Abhay099</h2>
            <p>Hi! I am Abhay099, a beginner student who loves coding.</p>
        </div>
        <div class="section-block" id="hobbies">
            <h2>Hobbies</h2>
            <p>I enjoy playing Bedwars on the Pika Network.</p>
        </div>
        <div class="section-block" id="follow">
            <h2>Follow Me</h2>
            <p>You can follow me on:</p>
            <div class="social-links">
                <a href="https://discordapp.com/users/your_user_id" class="button">Discord</a>
                <a href="https://www.youtube.com/channel/your_channel_id" class="button">YouTube</a>
                <a href="https://open.spotify.com/user/your_user_id" class="button">Spotify</a>
            </div>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 Abhay099. All rights reserved.</p>
    </footer>
</body>
</html>
