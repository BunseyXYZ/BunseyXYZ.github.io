<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Misu Studios</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="style.css">
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
