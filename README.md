<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Misu Studios</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            line-height: 1.6;
        }

        a {
            text-decoration: none;
            color: #c7b7ed;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            background-color: #000;
            padding: 15px 30px;
            border-bottom: 2px solid #c7b7ed;
        }

        nav a {
            color: #fff;
            margin-right: 20px;
            font-weight: bold;
        }

        nav a:hover {
            color: #c7b7ed;
        }

        header {
            padding: 100px 0;
            text-align: center;
            background-color: #111;
            color: #fff;
        }

        header h1 {
            font-size: 3rem;
            color: #c7b7ed;
        }

        section {
            padding: 60px 30px;
        }

        section h2 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 2rem;
            color: #c7b7ed;
        }

        .services, .about, .testimonials {
            margin-bottom: 50px;
        }

        .services-container, .testimonials-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .service, .testimonial {
            background-color: #111;
            margin: 10px;
            padding: 20px;
            width: 300px;
            border: 1px solid #c7b7ed;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #000;
            border-top: 2px solid #c7b7ed;
        }

        .contact-form input, .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #c7b7ed;
            border-radius: 5px;
            background-color: #222;
            color: #fff;
        }

        .contact-form button {
            background-color: #c7b7ed;
            color: #000;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }

        .contact-form button:hover {
            background-color: #fff;
            color: #c7b7ed;
        }
    </style>
</head>
<body>
    <nav>
        <div class="logo">
            <a href="#">Misu Studios</a>
        </div>
        <div class="nav-links">
            <a href="#services">Services</a>
            <a href="#about">About</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#contact">Contact</a>
        </div>
    </nav>

    <header>
        <h1>Welcome to Misu Studios</h1>
        <p>Creative Art, Adult Game Development, and More</p>
    </header>

    <section id="services" class="services">
        <h2>Our Services</h2>
        <div class="services-container">
            <div class="service">
                <h3>3D Map Design</h3>
                <p>We create custom and detailed 3D maps for a variety of applications.</p>
            </div>
            <div class="service">
                <h3>Adult Products & E-Commerce</h3>
                <p>Designing, marketing, and selling adult products with secure platforms.</p>
            </div>
            <div class="service">
                <h3>Adult Game Development</h3>
                <p>Developing immersive adult gaming experiences with unique gameplay.</p>
            </div>
            <div class="service">
                <h3>Discord Bot Development</h3>
                <p>Creating custom bots to enhance Discord communities.</p>
            </div>
        </div>
    </section>

    <section id="about" class="about">
        <h2>About Misu Studios</h2>
        <p>Misu Studios is a team of passionate artists and developers. We are committed to pushing boundaries in the adult gaming community by creating innovative content with distinctive gameplay and environments. With over four years of industry expertise, 150+ satisfied clients annually, and two active partnerships, we strive for excellence in every project.</p>
    </section>

    <section id="testimonials" class="testimonials">
        <h2>Client Testimonials</h2>
        <div class="testimonials-container">
            <div class="testimonial">
                <p>"Bunsey is one of the greatest creators to ever grace this community, and no, I'm not being held at gunpoint to say this—I mean every word!"</p>
                <p>- Pirate Hub</p>
            </div>
        </div>
    </section>

    <section id="contact" class="contact-form">
        <h2>Contact Us</h2>
        <form action="#">
            <input type="text" name="name" placeholder="Your Name" required>
            <input type="email" name="email" placeholder="Your Email" required>
            <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <footer>
        <p>© 2024 Misu Studios. All rights reserved.</p>
    </footer>
</body>
</html>
