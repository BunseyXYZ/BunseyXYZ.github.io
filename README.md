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
        }

        a {
            text-decoration: none;
            color: #c7b7ed;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 30px;
            background-color: #000;
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
            padding: 150px 0;
            text-align: center;
            background-color: #111;
        }

        header h1 {
            font-size: 3.5rem;
            color: #c7b7ed;
        }

        header p {
            font-size: 1.2rem;
            margin-top: 10px;
            color: #fff;
        }

        section {
            padding: 60px 30px;
            text-align: center;
        }

        section h2 {
            font-size: 2.5rem;
            margin-bottom: 40px;
            color: #c7b7ed;
        }

        .services-container, .testimonials-container {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            margin-bottom: 50px;
        }

        .service, .testimonial {
            background-color: #111;
            padding: 20px;
            margin: 20px;
            width: 250px;
            border: 1px solid #c7b7ed;
            border-radius: 5px;
        }

        footer {
            background-color: #000;
            padding: 40px;
            text-align: center;
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
            padding: 10px 20px;
            background-color: #c7b7ed;
            color: #000;
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
        <p>Crafting Unique Art & Immersive Adult Games</p>
    </header>

    <section id="services">
        <h2>Our Services</h2>
        <div class="services-container">
            <div class="service">
                <h3>3D Map Design</h3>
                <p>Custom, detailed 3D maps for various applications.</p>
            </div>
            <div class="service">
                <h3>Adult Products & E-Commerce</h3>
                <p>Designing, marketing, and selling adult products.</p>
            </div>
            <div class="service">
                <h3>Adult Game Development</h3>
                <p>Immersive gaming experiences with unique gameplay.</p>
            </div>
            <div class="service">
                <h3>Discord Bot Development</h3>
                <p>Custom bots to enhance your Discord community.</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Misu Studios</h2>
        <p>At Misu Studios, we specialize in creating groundbreaking content in the adult gaming community. Our dedicated team of artists is committed to pushing boundaries with innovative projects that deliver unique gameplay experiences.</p>
    </section>

    <section id="testimonials">
    <h2>Client Testimonials</h2>
    <div class="testimonials-container">
        <div class="testimonial">
            <p>"Bunsey is one of the greatest creators to ever grace this community, and no, I'm not being held at gunpoint to say this—I mean every word!"</p>
            <p>- Pirate Hub</p>
        </div>
        <div class="testimonial">
            <p>"Misu Airlines are a 10/10. They have really, really hot planes!"</p>
            <p>- Darby</p>
        </div>
        <div class="testimonial">
            <p>"PEAAAAAAK PEAAAAAAAAAAAAAAAAKK"</p>
            <p>- bbnnuuyy</p>
        </div>
        <div class="testimonial">
            <p>"akrscoi 2.0 it’s a good thing 👍 rr34 may get better traction but using the knowledge and skill acquired from making rr34 to make better content on other platforms is much better. Been seeing really promising works lately, keep it up!"</p>
            <p>- Kaltvin</p>
        </div>
        <div class="testimonial">
            <p>"I'd like to announce that Bunsey has died of prostate cancer."</p>
            <p>- Dude with 5k followers</p>
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
