<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gaza Awareness Campaign</title>
    <style>
        /* General Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Body and Background */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #121212;
            color: #fff;
            text-align: center;
        }

        /* Video Section */
        .video-container {
            position: relative;
            width: 100%;
            max-height: 90vh;
            overflow: hidden;
        }

        video {
            width: 100%;
            height: auto;
        }

        /* Content Overlay */
        .overlay-content {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        p {
            font-size: 1.2rem;
        }

        a {
            display: inline-block;
            margin-top: 1rem;
            padding: 0.5rem 1rem;
            background-color: #ff4500;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1rem;
        }

        a:hover {
            background-color: #ff6347;
        }
    </style>
</head>
<body>
    <!-- Video Section -->
    <div class="video-container">
        <video autoplay muted loop id="gaza-video">
            <source src="https://bha332.github.io/Barza/assets/videos/copy_BE49A0DC-82B3-4D83-8028-F6AED2B252F3.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <div class="overlay-content">
            <h1>Support Displaced Individuals</h1>
            <p>Help us raise awareness and support refugees in need.</p>
            <a href="https://example.com/donate" target="_blank">Learn More</a>
        </div>
    </div>
</body>
</html>
