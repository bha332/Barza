<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaza Awareness Campaign</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000000; /* Black background */
            color: #FFFFFF; /* White text */
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #cd7f32; /* Copper Orange */
            color: white;
            text-align: center;
            padding: 20px;
        }
        h1, h2 {
            color: #cd7f32; /* Copper Orange */
        }
        .content {
            padding: 20px;
            text-align: center;
        }
        .video-popup {
            position: relative;
            text-align: center;
            padding: 40px;
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.05); }
            100% { transform: scale(1); }
        }
        .circle-text {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 300px;
            height: 300px;
            border: 10px solid #cd7f32;
            border-radius: 50%;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            font-size: 20px;
            animation: rotate 8s linear infinite;
        }
        @keyframes rotate {
            0% { transform: translate(-50%, -50%) rotate(0deg); }
            100% { transform: translate(-50%, -50%) rotate(360deg); }
        }
        a {
            color: #cd7f32;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .links-section {
            padding: 20px;
            margin: 10px;
        }
        button {
            background-color: #cd7f32; /* Copper Orange */
            color: white;
            border: none;
            padding: 15px 20px;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background-color: #a15a2f; /* Darker shade */
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333333;
        }
    </style>
</head>
<body>
    <header>
        <h1>Gaza Awareness Campaign</h1>
    </header>
    <main class="content">
        <div class="video-popup">
            <iframe src="https://drive.google.com/file/d/1BvcSnb4zIlUKcA38PlUb1NMBvCWG2wXZ/preview" width="560" height="315" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
            <div class="circle-text">
                <p>People Are Dying!</p>
            </div>
        </div>
        <section class="links-section">
            <h2>How to Help</h2>
            <ul>
                <li><a href="https://www.un.org/en" target="_blank">United Nations</a></li>
                <li><a href="https://www.hrw.org" target="_blank">Human Rights Watch</a></li>
                <li><a href="https://www.aljazeera.com" target="_blank">Al Jazeera</a></li>
                <li><a href="https://www.amnesty.org" target="_blank">Amnesty International</a></li>
                <li><a href="https://www.theguardian.com" target="_blank">The Guardian</a></li>
                <li><a href="https://www.bbc.com/news/world/middle-east" target="_blank">BBC News</a></li>
            </ul>
        </section>
    </main>
    <footer>
        &copy; 2024 Gaza Awareness Campaign. All Rights Reserved.
    </footer>
</body>
</html>
