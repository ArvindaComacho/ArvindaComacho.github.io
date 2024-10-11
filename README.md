<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Newer Earth Programme</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
        }

        /* Navbar */
        .navbar {
            position: sticky;
            top: 0;
            background-color: rgba(255, 255, 255, 0.95);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 50px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            z-index: 1000;
            font-size: 1.1rem;
        }

        .navbar img {
            height: 60px;
        }

        .navbar .nav-links {
            display: flex;
            gap: 20px;
        }

        .navbar .nav-links a {
            color: #333;
            text-decoration: none;
            padding: 10px 15px;
            border-radius: 5px;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        .navbar .nav-links a:hover {
            background-color: rgba(46, 204, 113, 0.1);
            color: #27ae60;
        }

        .navbar .events-button {
            background-color: #2F7D66;
            color: white;
            padding: 10px 20px;
            border-radius: 30px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .navbar .events-button:hover {
            background-color: #0c5b43;
        }

        /* Search bar */
        .search-container {
            display: flex;
            align-items: center;
        }

        .search-container input[type="text"] {
            padding: 8px 15px;
            border: 1px solid #ddd;
            border-radius: 20px;
            background-color: #f9f9f9;
        }

        /* Hero Section */
        .hero {
            position: relative;
            background-image: url('background-image.jpg'); /* Replace with actual image */
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

        .hero::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.5); /* Add a darker overlay */
            z-index: 1;
        }

        .hero-content {
            z-index: 2;
            max-width: 900px;
            padding: 0 20px;
        }

        .hero h1 {
            font-size: 60px;
            font-weight: bold;
        }

        .hero p {
            font-size: 24px;
            font-style: italic;
            margin-top: 10px;
        }

        /* Programme Section */
        .programme {
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 50px 20px;
            text-align: center;
        }

        .programme img {
            width: 300px;
            height: 300px;
            border-radius: 50%;
            object-fit: cover;
            margin-right: 30px;
        }

        .programme-text {
            max-width: 600px;
        }

        .programme-text h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }

        .programme-text p {
            font-size: 18px;
            color: #555;
        }

        /* Stats Section */
        .stats {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            background-color: #f0f0f0;
        }

        .stats .stat-item {
            text-align: center;
            font-size: 20px;
        }

        .stats .stat-item span {
            display: block;
            font-size: 40px;
            color: #4CAF50;
        }

        /* People Powered Section */
        .people-powered {
            background-color: #2F7D66;
            color: white;
            padding: 50px 20px;
            text-align: center;
        }

        .people-powered img {
            width: 300px;
            border-radius: 50%;
            object-fit: cover;
            margin-bottom: 20px;
        }

        .people-powered h2 {
            font-size: 30px;
            margin-bottom: 20px;
            color: #f2c14e;
        }

        .people-powered p {
            font-size: 18px;
            line-height: 1.6;
            color: #eee;
        }

        /* Footer Section */
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

        /* Responsive Design */
        @media (max-width: 768px) {
            .navbar {
                flex-direction: column;
            }

            .programme {
                flex-direction: column;
            }

            .programme img {
                margin-bottom: 20px;
            }

            .stats {
                flex-direction: column;
                gap: 20px;
            }

            .people-powered img {
                width: 250px;
            }
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <div class="navbar">
        <img src="logo.png" alt="Newer Earth Logo"> <!-- Replace with actual logo -->
        <div class="nav-links">
            <a href="#home">Home</a>
            <a href="#about">About Us</a>
            <a href="#landscape">Landscape Aesthetics</a>
            <a href="#learning">Learning Hub</a>
        </div>
        <div class="search-container">
            <input type="text" placeholder="Search...">
            <a href="#events" class="events-button">EVENTS!</a>
        </div>
    </div>

    <!-- Hero Section -->
    <div class="hero">
        <div class="hero-content">
            <h1>The Environment Matters</h1>
            <p>Making sustainability fun</p>
        </div>
    </div>

    <!-- Programme Section -->
    <div class="programme">
        <img src="hands-holding-plant.jpg" alt="Hands Holding Plant"> <!-- Replace with actual image -->
        <div class="programme-text">
            <h2>The Newer Earth Programme</h2>
            <p>We bring sustainability to unexpected places. Whether it’s planting native wildflower meadows in your backyard, teaching new gardeners to grow their own food, or helping local wildlife, we empower homeowners to help the environment.</p>
        </div>
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
        <img src="people-holding-hands.jpg" alt="People Holding Hands"> <!-- Replace with actual image -->
        <h2>People Powered</h2>
        <p>Newer Earth thrives on community support: we're not backed by large funds or national organizations. Through determination and effort, we aim to rejuvenate our community's natural environment, making it a welcoming space for all its inhabitants.</p>
        <p>With your assistance, we aspire to build partnerships with national agencies, non-profits, and local farms. If you believe that the environment matters, get involved!</p>
    </div>

    <!-- Footer Section -->
    <div class="footer">
        <p>The Environment Matters</p>
        <p>Contact Us: newerearth@gmail.com</p>
    </div>

</
