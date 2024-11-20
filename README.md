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
            background-color: #000;
            color: #fff;
            text-align: center;
            overflow-x: hidden;
        }

        /* Video Section */
        .video-container {
            position: relative;
            width: 100%;
            height: 100vh;
            overflow: hidden;
        }

        .video-container video {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            min-width: 100%;
            min-height: 100%;
            object-fit: cover;
        }

        .motion-text {
            position: absolute;
            top: 10%;
            left: 50%;
            transform: translateX(-50%);
            font-size: 2.5rem;
            font-weight: bold;
            text-transform: uppercase;
            animation: fadeInOut 4s infinite;
        }

        @keyframes fadeInOut {
            0%, 100% { opacity: 0; }
            50% { opacity: 1; }
        }

        /* Links Section */
        .links-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
            margin: 20px auto;
            padding: 20px;
        }

        .link-card {
            width: 200px;
            background-color: #222;
            border: 2px solid #444;
            border-radius: 10px;
            text-align: center;
            overflow: hidden;
            transition: transform 0.3s;
        }

        .link-card:hover {
            transform: scale(1.05);
        }

        .link-card img {
            width: 100%;
            height: 120px;
            object-fit: cover;
        }

        .link-card a {
            display: block;
            padding: 10px;
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        .link-card a:hover {
            color: #00b7ff;
        }

        .free-help {
            margin: 20px 0;
            font-size: 1.2rem;
            color: #f00;
        }
    </style>
</head>
<body>

    <!-- Video Section -->
    <div class="video-container">
        <video autoplay loop controls id="gaza-video">
            <source src="https://bha332.github.io/barza/assets/copy_BE49A0DC-82B3-4D83-8028-F6AED2B252F3.mp4" type="video/mp4">
            Your browser does not support the video tag.
        </video>
        <div class="motion-text">Hear Their Cries</div>
    </div>

    <!-- Links Section -->
    <div class="free-help">
        You can help for free by sharing this website and raising awareness.
    </div>
    <div class="links-container">
        <div class="link-card">
            <img src="https://matwprojectusa.org/images/donation.jpg" alt="Donate">
            <a href="https://matwprojectusa.org/appeals/limbs-of-hope?gclsrc=aw.ds&gad_source=1&gclid=CjwKCAiArva5BhBiEiwA-oTnXRdHFureTMQmJbVV9R84T0NDzRwTCRzZoAh1vtlAEUk3ggKLvOCm9BoCeDYQAvD_BwE" target="_blank">
                Donate to Gaza Relief
            </a>
        </div>
        <div class="link-card">
            <img src="https://www.aljazeera.com/mritems/imagecache/mbdxlarge/mritems/Images/2023/10/7/aljazeera.jpg" alt="Live Updates">
            <a href="https://www.aljazeera.com/tag/gaza/" target="_blank">
                Live Updates on Gaza
            </a>
        </div>
        <div class="link-card">
            <img src="https://www.aljazeera.com/mritems/imagecache/mbdxlarge/mritems/Images/2023/10/7/aljazeera-newsfeed.jpg" alt="Victims">
            <a href="https://www.aljazeera.com/program/newsfeed/2024/10/7/the-names-of-those-killed-in-israels-genocide-in-gaza" target="_blank">
                Names of the Victims
            </a>
        </div>
    </div>

</body>
</html>
