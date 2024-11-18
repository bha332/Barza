<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaza Awareness Campaign</title>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Press+Start+2P&display=swap" rel="stylesheet">
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body and Background */
        body {
            font-family: 'Press Start 2P', cursive;
            background-color: #b46e3f; /* Orange Copper */
            color: #fff;
            text-align: center;
        }

        /* Video Container */
        .video-container {
            position: relative;
            width: 100%;
            height: 100vh;
            overflow: hidden;
        }

        /* Full-Screen Video */
        #gaza-video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        /* Floating Text */
        .floating-text h1 {
            position: absolute;
            top: 20%;
            left: 50%;
            transform: translateX(-50%);
            font-size: 4em;
            color: red;
            font-family: 'Pacifico', cursive;
            animation: floatText 6s infinite;
        }

        @keyframes floatText {
            0% { top: 20%; }
            50% { top: 30%; }
            100% { top: 20%; }
        }

        /* Links Section */
        .links-container {
            position: absolute;
            bottom: 10%;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
        }

        .links-container h2 {
            margin-bottom: 20px;
            font-size: 2em;
            font-family: 'Pacifico', cursive;
        }

        .links-container ul {
            list-style: none;
        }

        .links-container li {
            margin: 10px 0;
        }

        .links-container a {
            color: #fff;
            text-decoration: none;
            font-size: 1.5em;
            transition: color 0.3s;
        }

        .links-container a:hover {
            color: #f00;
        }

        /* Footer */
        footer {
            position: absolute;
            bottom: 0;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.7);
            padding: 10px;
            color: #fff;
            font-size: 0.9em;
        }
    </style>
</head>
<body>

<!-- Video Section -->
<div class="video-container">
 <video autoplay muted loop playsinline id="gaza-video">
    <source src="https://bha332.github.io/barza/assets/videos/ttdae0304-1_E0qQNas8.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

    <!-- Floating Text -->
    <div class="floating-text">
        <h1>HEAR THEIR CRIES</h1>
    </div>
</div>


    <!-- Links Section -->
    <div class="links-container">
        <h2>How You Can Help</h2>
        <ul>
            <li><a href="https://matwprojectusa.org/crisis-and-emergencies/palestine?gclsrc=aw.ds&gad_source=1&gclid=CjwKCAiAxea5BhBeEiwAh4t5K7et6PDpa1tfMXKTNRWLEiJOg7Pmtp4GtDA748ZuuNXfZpph0_7PeBoClCMQAvD_BwE" target="_blank">Donate to Gaza Relief</a></li>
            <li><a href="https://www.unicef.org/sop/take-action" target="_blank">Take Action - How to Get Involved</a></li>
            <li><a href="https://www.aljazeera.com/program/newsfeed/2024/10/7/the-names-of-those-killed-in-israels-genocide-in-gaza" target="_blank">Gaza Death Toll</a></li>
            <li><a href="https://www.aljazeera.com/tag/gaza/" target="_blank">Stay Up to Date on Gaza News</a></li>
        </ul>
    </div>

    <!-- Footer -->
    <footer>
        <p>&copy; 2024 Barza - Gaza Awareness Campaign</p>
    </footer>

    <script>
        // Simple JavaScript function to alert visitors
        window.onload = function() {
            alert("Thank you for visiting. Please help raise awareness about Gaza's destruction.");
        };
    </script>

</body>
</html>
