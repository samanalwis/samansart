<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Art for Sale</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Saman's Art Gallery</h1>
        <p>Discover and purchase unique artwork</p>
    </header>
    
    <nav>
        <a href="#gallery">Gallery</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container" id="gallery">
        <h2>Art Gallery</h2>
        <div class="gallery">
            <div class="art-item">
                <a href="other-pages/artwork1.html">
                    <img src="images/artwork1.jpg" alt="Artwork 1">
                    <p>Title: Artwork 1</p>
                    <p>Price: $50</p>
                </a>
            </div>
        </div>
    </div>

    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <h4>Follow @samanartgallery on Instagram and Facebook or Call 012345678.</h4>
        <form class="contact-form" action="https://formspree.io/f/{your-form-id}" method="POST">
            <label for="name">Name</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message</label>
            <textarea id="message" name="message" rows="5" required></textarea>
            <button type="submit">Send Message</button>
        </form>
    </div>

    <footer>
        <p>&copy; 2024 Saman's Art Store. All rights reserved.</p>
    </footer>
</body>
</html>
