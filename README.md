<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Banner</title>
    <style>
        /* General page styling */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        /* Banner / Navbar styling */
        .navbar {
            position: sticky;
            top: 0;
            background-color: #333;
            overflow: hidden;
            z-index: 1000;
        }

        /* Navbar links styling */
        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }

        /* Change color on hover */
        .navbar a:hover {
            background-color: #ddd;
            color: black;
        }

        /* Add content for demo purposes */
        .content {
            padding: 16px;
            margin-top: 30px;
            height: 2000px; /* Just to demonstrate scrolling */
        }
    </style>
</head>
<body>

    <div class="navbar">
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#landscape">Landscape Aesthetics</a>
        <a href="#learning">Learning Hub</a>
        <a href="#events">Events</a>
    </div>

    <div class="content">
        <h2>Sticky Navbar Example</h2>
        <p>Scroll down this page to see the navbar stay at the top of the page.</p>
        <p>Add your website's content here.</p>
    </div>

</body>
</html>
