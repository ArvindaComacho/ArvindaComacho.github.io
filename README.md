<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Newer Earth Programme</title>
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
        }

        /* Navbar styling */
        .navbar {
            position: sticky;
            top: 0;
            background-color: rgba(255, 255, 255, 0.9);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 50px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            z-index: 1000;
        }

        /* Logo styling */
        .navbar img {
            height: 60px;
        }

        /* Navigation links */
        .navbar a {
            text-decoration: none;
            color: black;
            padding: 14px 20px;
            font-size: 16px;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .navbar a:hover {
            color: #4CAF50;
        }

        /* Events button */
        .navbar .events-button {
            background-color: #2F7D66;
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .navbar .events-button:hover {
            background-color: #0c5b43;
        }

        /* Search bar styling */
        .search-container {
            display: flex;
            align-items: center;
        }

        .search-container input[type="text"] {
            padding: 8px;
            border: none;
            border-radius: 20px;
            background-color: #eee;
        }

        /* Hero section */
        .hero {
            background-image: url('background-image.jpg'); /* Replace with your actual image path */
            background-size: cover;
            background-position: center;
            height: 90vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }

        .hero h1 {
            font-size: 60px;
            margin: 0;
            font-weight: bold;
        }

        .hero p {
            font-size: 24px;
            font-style: italic;
            margin: 10px 0;
        }

        /* Programme section */
        .programme {
            padding: 50px 20px;
            text-align: center;
        }

        .programme h2 {
            margin-bottom: 20px;
            font-size: 30px;
        }

        .programme p {
            font-size: 18px;
            margin-bottom: 30px;
        }

        .programme img {
            width: 200px;
            border-radius: 50%;
        }

        /* Stats section */
        .stats {
            display: flex;
            justify-content: space-around;
            align-items: center;
            background-color: #f0f0f0;
            padding: 20px;
        }

        .stat-item {
            text-align: center;
            font-size: 20px;
            font-weight: bold;
        }

        .stat-item span {
            display: block;
            font-size: 40px;
            color: #4CAF50;
        }

        /* People powered section */
        .people-powered {
            background-color: #2F7D66;
            color: white;
            padding: 50px 20px;
            text-align: center;
        }

        .people-powered h2 {
            font-size: 30px;
            margin-bottom: 20px;
            color: #f2c14e;
        }

        .people-powered p {
            font-size: 18px;
            line-height: 1.6;
        }

        .people-powered img {
            width: 200px;
            border-radius: 50%;
            margin-bottom: 20px;
        }

        /* Footer section */
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 20px;
            font-size: 16px;
        }

        .footer a {
            color: #4CAF50;
            text-decoration: none;
        }

        .footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <div class="navbar">
        <img src="logo.png" alt="Newer Earth Logo"> <!-- Replace with actual logo path -->
        <div>
            <a href="#home">Home</a>
            <a href="#about">About Us</a>
            <a href="#landscape">Landscape Aesthetics</a>
            <a href="#learning">Learning Hub</a>
        </div>
        <div class="search-container">
            <a href="#events" class="events-button">EVENTS!</a>
            <input type="text" placeholder="Search...">
        </div>
    </div>

    <!-- Hero Section -->
    <div class="hero">
        <h1>The Environment Matters</h1>
        <p>Making sustainability fun</p>
    </div>

    <!-- Programme Section -->
    <div class="programme">
        <h2>The Newer Earth Programme</h2>
        <p>We bring sustainability to unexpected places. Whether it’s planting native wildflower meadows in your backyard, teaching new gardeners to grow their own food, or helping local wildlife, we empower homeowners to help the environment.</p>
        <img src="hands-holding-plant.jpg" alt="Hands Holding Plant"> <!-- Replace with actual image path -->
    </div>

    <!-- Stats Section -->
    <div class="stats">
        <div class="stat-item">
            <span>1</span>
            Years
        </div>
        <div class="stat-item">
            <span>0</span>
            Programmes
        </div>
        <div class="stat-item">
            <span>3</span>
            Participants
        </div>
        <div class="stat-item">
            <span>3</span>
            Volunteers
        </div>
    </div>

    <!-- People Powered Section -->
    <div class="people-powered">
        <img src="people-holding-hands.jpg" alt="People Holding Hands"> <!-- Replace with actual image path -->
        <h2>People Powered</h2>
        <p>Newer Earth thrives on community support: we're not backed by large funds or national organizations. Through determination and effort, we aim to rejuvenate our community's natural environment, making it a welcoming space for all its inhabitants.</p>
        <p>With your assistance, we aspire to build partnerships with national agencies, non-profits, and local farms. If you believe that the environment matters, get involved!</p>
    </div>

    <!-- Footer Section -->
    <div class="footer">
        <p>The Environment Matters</p>
        <p>Contact Us: newerearth@gmail.com</p>
    </div>

</body>
</html>
