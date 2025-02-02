<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fitness Gym</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            background-color: #444;
            overflow: hidden;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            float: left;
        }
        nav a:hover {
            background-color: #ddd;
            color: black;
        }
        .container {
            padding: 20px;
        }
        .services, .testimonial {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .service, .testimonial-item {
            background-color: white;
            margin: 10px;
            padding: 20px;
            border-radius: 8px;
            width: 250px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em;
        }
        .cta-button {
            background-color: #4CAF50;
            color: white;
            padding: 15px 25px;
            text-decoration: none;
            border-radius: 5px;
            font-size: 18px;
        }
        .cta-button:hover {
            background-color: #45a049;
        }
        .cta-section {
            background-color: #444;
            color: white;
            text-align: center;
            padding: 30px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <img src="okok.jpeg" alt="Fitness Goals Logo"height="50px"width="50px"> <!-- Add your logo image here -->
        <h1 style="text-shadow: 3px 5px rgb(78, 73, 73)">Welcome to FitYou Gym</h1>
        <p>Sweat Today Shine Later</p>
    </header>

    <!-- Navigation Bar -->
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About Us</a>
        <a href="#services">Services</a>
        <a href="#classes">Classes</a>
        <a href="#contact">Contact</a>
    </nav>

    <!-- Main Content -->
    <div class="container">

        <!-- About Section -->
        <section id="about">
            <h2>About Us</h2>
            <p>FitYou Gym is committed to helping you achieve your fitness goals. Whether you are looking to build strength, lose weight, or improve your overall health, we have the perfect programs for you!
            This is where you destroy what you used to be yesterday to build your tomorrow.</p>
        </section>

        <!-- Services Section -->
        <section id="services">
            <h2>Our Services</h2>
            <div class="services">
                <div class="service">
                    <h3>Personal Training</h3>
                    <p>Customized training plans with a certified trainers.</p>
                </div>
                <div class="service">
                    <h3>Group Classes</h3>
                    <p>Join our high-energy group classes for motivation and fun!</p>
                </div>
                <div class="service">
                    <h3>Cardio And Zumba</h3>
                    <p>Efficient and playful zumba and cardio sessions for core and flexibility.</p>
                </div>
            </div>
        </section>

        <!-- Testimonials Section -->
        <section id="testimonials">
            <h2>What Our Members Say</h2>
            <div class="testimonial">
                <div class="testimonial-item">
                    <p>"Fitness Gym changed my life! The trainers are incredible and the environment is so motivating!"</p>
                    <p><strong>Sarah J.</strong></p>
                </div>
                <div class="testimonial-item">
                    <p>"I've never felt stronger and healthier. The group classes are the highlight of my week!"</p>
                    <p><strong>Mike T.</strong></p>
                </div>
            </div>
        </section>

        <!-- Call to Action Section -->
        <section class="cta-section">
            <h2>Ready to Get Started?</h2>
            <p>Join Fitness Gym today and take the first step towards a healthier you!</p>
            <a href="#contact" class="cta-button">Contact Us</a>
        </section>

    </div>

    <!-- Footer -->
    <footer id="contact">
        <h3>Contact Us</h3>
        <p>Email: <a href="mailto:ankshjyotish05@gmail.com" style="color: #fff;">ankshjyotish05@gmail.com</a></p>
        <p>Phone: 8917566596</p>
        <p>&copy; 2025 Fitness Gym</p>
    </footer>

</body>
</html>
