<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scroll Triggered Animation</title>
    
    <!-- AOS Library CSS -->
    <link href="https://cdn.jsdelivr.net/npm/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            text-align: center;
            padding: 50px;
            background-color: #3498db;
            color: white;
        }

        h1 {
            margin: 0;
            font-size: 3rem;
        }

        .content-section {
            padding: 50px 20px;
            text-align: center;
            background-color: #fff;
        }

        .content-section img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .image-container {
            max-width: 800px;
            margin: 50px auto;
        }

        footer {
            padding: 30px;
            text-align: center;
            background-color: #2c3e50;
            color: white;
        }
    </style>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Scroll Down to See Animations</h1>
    </header>

    <!-- Content Sections with Scroll Animations -->
    <section class="content-section" data-aos="fade-up">
        <h2>Beautiful Nature 1</h2>
        <div class="image-container">
            <img src="https://via.placeholder.com/800x400" alt="Nature Image 1">
        </div>
    </section>

    <section class="content-section" data-aos="fade-left">
        <h2>Beautiful Nature 2</h2>
        <div class="image-container">
            <img src="https://via.placeholder.com/800x400" alt="Nature Image 2">
        </div>
    </section>

    <section class="content-section" data-aos="fade-right">
        <h2>Beautiful Nature 3</h2>
        <div class="image-container">
            <img src="https://via.placeholder.com/800x400" alt="Nature Image 3">
        </div>
    </section>

    <section class="content-section" data-aos="zoom-in">
        <h2>Beautiful Nature 4</h2>
        <div class="image-container">
            <img src="https://via.placeholder.com/800x400" alt="Nature Image 4">
        </div>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>Copyright © 2024 Your Website</p>
    </footer>

    <!-- AOS Library JS -->
    <script src="https://cdn.jsdelivr.net/npm/aos@2.3.1/dist/aos.js"></script>

    <!-- Initialize AOS -->
    <script>
        AOS.init({
            duration: 1000,  // Animation duration in milliseconds
            easing: 'ease-in-out',  // Easing style
            once: true,  // Whether animation should happen only once
        });
    </script>
    
</body>
</html>
