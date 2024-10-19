# Tours-Norway
Web Technology Lab : Mini Project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Visit Norway</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Navigation Bar -->
    <header>
        <nav>
            <div class="logo">
                <h1>Explore Norway</h1>
            </div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Norway</a></li>
                <li><a href="#places">Places to Visit</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="home">
        <div class="hero-content">
            <h2>Discover the Beauty of Norway</h2>
            <p>Explore breathtaking fjords, stunning northern lights, and rich Viking history!</p>
            <a href="#places" class="btn">Start Your Journey</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about">
        <div class="about-container">
            <h2>About Norway</h2>
            <p>Norway is a Scandinavian country encompassing mountains, glaciers, and deep coastal fjords. Known for its natural beauty, it’s a top destination for adventurers and nature lovers. Norway is also rich in history, particularly known for its Viking heritage.</p>
            <img src="norway.jpg" alt="Norway" class="about-img">
        </div>
    </section>

    <!-- Places to Visit -->
    <section id="places">
        <div class="places-container">
            <h2>Must-Visit Places in Norway</h2>
            <div class="places-grid">
                <div class="place">
                    <img src="fjord.jpg" alt="Norwegian Fjords">
                    <h3>Norwegian Fjords</h3>
                    <p>The iconic fjords offer stunning natural beauty with steep cliffs and calm waters.</p>
                </div>
                <div class="place">
                    <img src="aurora.jpg" alt="Northern Lights">
                    <h3>Northern Lights</h3>
                    <p>Experience the magical Aurora Borealis lighting up the Arctic skies.</p>
                </div>
                <div class="place">
                    <img src="oslo.jpg" alt="Oslo">
                    <h3>Oslo</h3>
                    <p>The capital city, known for its museums, green spaces, and waterfronts.</p>
                </div>
                <div class="place">
                    <img src="bergen.jpg" alt="Bergen">
                    <h3>Bergen</h3>
                    <p>A charming city surrounded by mountains and fjords, famous for its colorful wooden houses.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <div class="contact-container">
            <h2>Contact Us</h2>
            <form>
                <label for="name">Name:</label>
                <input type="text" id="name" name="name" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="message">Message:</label>
                <textarea id="message" name="message" required></textarea>
                
                <button type="submit">Submit</button>
            </form>
        </div>
    </section>

    <footer>
        <p>© 2024 Explore Norway | All rights reserved.</p>
    </footer>
</body>
</html>

