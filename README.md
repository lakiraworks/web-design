<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Innovations | Leading the Future of Technology</title>
    <style>
        /* Keyframes for animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        @keyframes slideIn {
            from {
                transform: translateY(-20px);
                opacity: 0;
            }
            to {
                transform: translateY(0);
                opacity: 1;
            }
        }

        /* Common styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            color: #333;
            background-color: #f5f7fa;
        }

        /* Navigation Bar */
        nav {
            background: #370047;
            padding: 20px;
            color: white;
            position: sticky;
            top: 0;
            z-index: 1000;
            animation: fadeIn 0.5s ease;
        }

        nav .container {
            max-width: 1200px;
            margin: auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav ul {
            list-style: none;
            display: flex;
            margin: 0;
            padding: 0;
        }

        nav li {
            margin: 0 15px;
        }

        nav a {
            color: rgb(0, 193, 207);
            text-decoration: none;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #635b5b;
        }

        /* Hero Section */
        header {
            background: url('Leonardo_Anime_XL_An_animestyle_artwork_for_a_collection_cover_3 (1).jpg') repeat center center/cover;
            height: 90vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
            animation: fadeIn 1s ease;
        }

        .hero-content {
            max-width: 700px;
            color: rgb(255, 255, 255);
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }

        .hero-btn {
            padding: 12px 24px;
            background: #80d0c7;
            color: #0a2a43;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s, transform 0.3s;
        }

        .hero-btn:hover {
            background: #0a2a43;
            color: rgb(255, 255, 255);
            transform: scale(1.05);
        }

        /* Section Styles */
        .section {
            padding: 80px 20px;
            text-align: center;
            animation: fadeIn 1s ease;
        }

        /* About Us Section */
        #about {
            background: rgba(97, 83, 177, 0.418);
        }

        /* Services Section */
        #services {
            background: rgba(255, 255, 255, 0.418);
        }

        .service-card {
            background: white;
            border-radius: 8px;
            padding: 20px;
            width: 250px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.3);
        }

        /* Technologies Section */
        #technologies {
            background: rgba(97, 83, 177, 0.418);
        }

        /* Team Section */
        #team {
            background: #f4f4f4;
        }

        .team-member img {
            border-radius: 50%;
            width: 100px;
            height: 100px;
            margin-bottom: 10px;
        }

        /* Contact Section */
        #contact {
            background: white;
        }

        input, textarea {
            padding: 15px;
            margin: 10px 0;
            border: 1px solid #ddd;
            border-radius: 5px;
            transition: border-color 0.3s;
        }

        input:focus, textarea:focus {
            border-color: #80d0c7;
            outline: none;
        }

        button {
            padding: 15px 30px;
            background: #0a2a43;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background 0.3s;
        }

        button:hover {
            background: #333;
        }

        /* Footer */
        footer {
            background: #0a2a43;
            color: white;
            text-align: center;
            padding: 15px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        footer .social-media a {
            color: #80d0c7;
            margin: 0 10px;
            text-decoration: none;
            transition: color 0.3s;
        }

        footer .social-media a:hover {
            color: white;
        }
    </style>
</head>
<body>

    <!-- navigationBar -->
    <nav>
        <div class="container">
            <h1 class="logo">AI Innovations</h1>
            <ul class="nav-links">
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#technologies">Technologies</a></li>
                <li><a href="#team">Team</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- hero section -->
    <header>
        <div class="hero-content">
            <h1 style="font-size: 3rem; margin-bottom: 15px;">AI Innovations</h1>
            <p style="font-size: 1.5rem; margin-bottom: 30px;">Empowering the Future with Advanced AI Solutions</p>
            <a href="#about" class="hero-btn">Discover More</a>
        </div>
    </header>

    <!-- about us section -->
    <section id="about" class="section">
        <h2 style="font-size: 2.5rem; color: #0a2a43;">About Us</h2>
        <p style="max-width: 800px; margin: auto; font-size: 1.2rem;">At AI Innovations, we harness the latest advancements in artificial intelligence to drive meaningful changes. Our mission is to develop solutions that redefine the boundaries of what's possible.</p>
    </section>

    <!-- Services Section -->
    <section id="services" class="section">
        <h2 style="font-size: 2.5rem; color: #0a2a43;">Our Services</h2>
        <div style="display: flex; flex-wrap: wrap; justify-content: center; gap: 20px;">
            <div class="service-card">
                <h3 style="color: #0093e9;">Machine Learning</h3>
                <p>Advanced algorithms designed to make data-driven decisions with unprecedented accuracy.</p>
            </div>
            <div class="service-card">
                <h3 style="color: #0093e9;">Data Analysis</h3>
                <p>Powerful tools that turn complex data into actionable insights.</p>
            </div>
            <div class="service-card">
                <h3 style="color: #0093e9;">Natural Language Processing</h3>
                <p>AI that understands and processes human language to drive effective communication.</p>
            </div>
            <div class="service-card">
                <h3 style="color: #0093e9;">Robotics</h3>
                <p>Innovative robotics solutions that enhance automation and productivity.</p>
            </div>
        </div>
    </section>

    <!-- Technologies Section -->
    <section id="technologies" class="section">
        <h2 style="font-size: 2.5rem; color: #0a2a43;">Our Technologies</h2>
        <p style="max-width: 800px; margin: auto; font-size: 1.2rem;">We specialize in a range of cutting-edge technologies that push the boundaries of artificial intelligence.</p>
        <ul style="list-style: none; padding: 0; font-size: 1.1rem; color: #555;">
            <li>Deep Learning</li>
            <li>Computer Vision</li>
            <li>Big Data Analytics</li>
            <li>Cloud Computing</li>
        </ul>
    </section>

    <!-- Team Section -->
    <section id="team" class="section">
        <h2 style="font-size: 2.5rem; color: #0a2

