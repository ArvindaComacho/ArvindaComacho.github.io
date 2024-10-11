<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Newer Earth Program</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        /* Navbar styling */
        .navbar {
            position: sticky;
            top: 0;
            background-color: rgba(255, 255, 255, 0.9);
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 50px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
            z-index: 1000;
        }

        /* Logo styling */
        .navbar img {
            height: 50px;
        }

        /* Navigation links styling */
        .navbar a {
            text-decoration: none;
            color: black;
            padding: 14px 20px;
            font-size: 16px;
            font-weight: bold;
            transition: color 0.3s ease;
        }

        .navbar a:hover {
            color: #4CAF50; /* Green hover effect */
        }

        /* Event button styling */
        .navbar .events-button {
            background-color: #2F7D66;
            color: white;
            padding: 10px 20px;
            border-radius: 20px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .navbar .events-button:hover {
            background-color: #0c5b43; /* Darker green on hover */
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

        /* Footer text */
        .footer-text {
            text-align: center;
            padding: 20px;
            font-size: 18px;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <div class="navbar">
        <!-- Logo -->
        <img src="logo.png" alt="Newer Earth Logo"> <!-- Replace with actual logo path -->

        <!-- Navigation Links -->
        <div>
            <a href="#home">Home</a>
            <a href="#about">About Us</a>
            <a href="#landscape">Landscape Aesthetics</a>
            <a href="#learning">Learning Hub</a>
        </div>

        <!-- Events Button and Search Bar -->
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

    <!-- Footer Text -->
    <div class="footer-text">
        THE NEWER EARTH PROGRAMME
    </div>

</body>
</html>
