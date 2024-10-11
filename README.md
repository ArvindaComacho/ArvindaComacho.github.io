<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Banner with Transparent Scroll Effect</title>
    <style>
        /* General page styling */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        /* Navbar styling */
        .navbar {
            position: sticky;
            top: 0;
            background-color: rgba(51, 51, 51, 1); /* Solid color at the start */
            overflow: hidden;
            z-index: 1000;
            transition: background-color 0.3s ease; /* Smooth transition */
        }

        /* Change navbar background to transparent on scroll */
        body.scrolled .navbar {
            background-color: rgba(51, 51, 51, 0.8); /* 80% transparency */
        }

        /* Navbar links styling */
        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        /* White hover effect */
        .navbar a:hover {
            background-color: white;
            color: black;
        }

        /* Add content for demo purposes */
        .content {
            padding: 16px;
            margin-top: 30px;
            height: 2000px; /* Just to demonstrate scrolling */
        }
    </style>
    <script>
        // Add class to body when scrolling
        window.onscroll = function() {
            var body = document.body;
            var html = document.documentElement;
            var scrollTop = window.pageYOffset || body.scrollTop || html.scrollTop;

            if (scrollTop > 50) {
                body.classList.add('scrolled');
            } else {
                body.classList.remove('scrolled');
            }
        };
    </script>
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
        <h2>Sticky Navbar with Transparency Effect</h2>
        <p>Scroll down to see the navbar become transparent, and hover over links to see the white hover effect.</p>
        <p>Add your website's content here.</p>
    </div>

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Banner with Transparent Scroll Effect</title>
    <style>
        /* General page styling */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
        }

        /* Navbar styling */
        .navbar {
            position: sticky;
            top: 0;
            background-color: rgba(51, 51, 51, 1); /* Solid color at the start */
            overflow: hidden;
            z-index: 1000;
            transition: background-color 0.3s ease; /* Smooth transition */
        }

        /* Change navbar background to transparent on scroll */
        body.scrolled .navbar {
            background-color: rgba(51, 51, 51, 0.8); /* 80% transparency */
        }

        /* Navbar links styling */
        .navbar a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
            transition: background-color 0.3s ease, color 0.3s ease;
        }

        /* White hover effect */
        .navbar a:hover {
            background-color: white;
            color: black;
        }

        /* Add content for demo purposes */
        .content {
            padding: 16px;
            margin-top: 30px;
            height: 2000px; /* Just to demonstrate scrolling */
        }
    </style>
    <script>
        // Add class to body when scrolling
        window.onscroll = function() {
            var body = document.body;
            var html = document.documentElement;
            var scrollTop = window.pageYOffset || body.scrollTop || html.scrollTop;

            if (scrollTop > 50) {
                body.classList.add('scrolled');
            } else {
                body.classList.remove('scrolled');
            }
        };
    </script>
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
        <h2>Sticky Navbar with Transparency Effect</h2>
        <p>Scroll down to see the navbar become transparent, and hover over links to see the white hover effect.</p>
        <p>Add your website's content here.</p>
    </div>
</body>
</html>
