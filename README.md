<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Raise Awareness</title>
  <style>
    /* Video background styling */
    video {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      z-index: -1; /* Ensures content is above the video */
    }

    /* Styling for the How to Help section */
    .how-to-help {
      display: flex;
      justify-content: center;
      gap: 20px; /* Adjust the gap between buttons */
      position: relative;
      z-index: 1; /* Keeps buttons above video */
      margin-top: 50px; /* Adjust the top margin if needed */
    }

    /* Styling for button images */
    .button-image {
      width: 200px; /* Adjust image size */
      height: auto;
      transition: transform 0.3s ease;
    }

    /* Hover effect for buttons */
    .button-image:hover {
      transform: scale(1.1); /* Zoom effect on hover */
    }

    /* Optional: Center the text content */
    .content {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      color: white;
      text-align: center;
      font-size: 24px;
      z-index: 2; /* Ensures text is above video */
    }
  </style>
</head>
<body>
  <!-- Video element: Replace 'your-video-file.mp4' with the path to your video -->
  <video autoplay muted loop>
    <source src="your-video-file.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>

  <!-- Optional content section (text can be customized) -->
  <div class="content">
    <h1>Global Displacement Awareness</h1>
    <p>Join us in making a difference.</p>
  </div>

  <!-- How to help section with interactive buttons (images) -->
  <div class="how-to-help">
    <a href="link-to-donate">
      <img src="donate-image.jpg" alt="Donate" class="button-image">
    </a>
    <a href="link-to-volunteer">
      <img src="volunteer-image.jpg" alt="Volunteer" class="button-image">
    </a>
    <a href="link-to-raise-awareness">
      <img src="raise-awareness-image.jpg" alt="Raise Awareness" class="button-image">
    </a>
  </div>
</body>
</html>
