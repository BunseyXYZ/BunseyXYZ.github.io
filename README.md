<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Misu Studios</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Roboto', sans-serif;
            line-height: 1.6;
            color: #333;
        }

        header {
            background-color: #282c34;
            padding: 1rem 0;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 2rem;
        }

        nav .logo {
            font-size: 1.5rem;
            font-weight: bold;
            color: #fff;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-left: 2rem;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #f39c12;
        }

        .hero {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('hero-image.jpg') no-repeat center center/cover;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: #fff;
        }

        .hero h1 {
            font-size: 4rem;
            animation: fadeInUp 1s ease-out;
        }

        .hero p {
            font-size: 1.5rem;
            margin: 1rem 0;
            animation: fadeInUp 1.5s ease-out;
        }

        .btn-primary {
            background-color: #f39c12;
            color: #fff;
            padding: 0.75rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s ease;
        }

        .btn-primary:hover {
            background-color: #d35400;
        }

        section {
            padding: 4rem 2rem;
            text-align: center;
            background-color: #f4f4f4;
        }

        .about {
            background-color: #ecf0f1;
        }

        .games, .gallery {
            background-color: #fff;
        }

        .games .game-list {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .game-item {
            background-color: #f0f0f0;
            padding: 2rem;
            margin: 1rem;
            border-radius: 10px;
            flex-basis: 45%;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .gallery-items {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .gallery-items img {
            width: 300px;
            height: 200px;
            object-fit: cover;
            margin: 1rem;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .gallery-items img:hover {
            transform: scale(1.1);
        }

        .contact form {
            display: flex;
            flex-direction: column;
            align-items: center;
        }

        .contact form label {
            margin: 0.5rem 0;
        }

        .contact form input, .contact form textarea {
            width: 100%;
            max-width: 500px;
            padding: 0.75rem;
            margin-bottom: 1rem;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        .contact form button {
            width: 100%;
            max-width: 500px;
            padding: 0.75rem;
            background-color: #f39c12;
            color: #fff;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .contact form button:hover {
            background-color: #d35400;
        }

        footer {
            background-color: #282c34;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <!-- Navigation Bar -->
    <header>
        <nav>
            <div class="logo">Misu Studios</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#games">Games</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to Misu Studios</h1>
            <p>Revolutionizing Gaming Experiences</p>
            <a href="#about" class="btn-primary">Learn More</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About Misu Studios</h2>
        <p>At Misu Studios, we push the boundaries of creativity to deliver cutting-edge gaming experiences.</p>
    </section>

    <!-- Games Section -->
    <section id="games" class="games">
        <h2>Our Games</h2>
        <div class="game-list">
            <div class="game-item">
                <h3>Game Title 1</h3>
                <p>Description of the game. Engaging gameplay and stunning graphics.</p>
            </div>
            <div class="game-item">
                <h3>Game Title 2</h3>
                <p>Description of the game. Immersive worlds and captivating stories.</p>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="gallery">
        <h2>Gallery</h2>
        <div class="gallery-items">
            <img src="image1.jpg" alt="Gallery Image 1">
            <img src="image2.jpg" alt="Gallery Image 2">
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit" class="btn-primary">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Misu Studios. All Rights Reserved.</p>
    </footer>
</body>
</html>
