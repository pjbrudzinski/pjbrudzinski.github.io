<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Showcasing my dance and artistry.">
    <title>Your Dance & Artistry</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="navbar">
            <h1>Dance & Artistry</h1>
            <nav>
                <ul>
                    <li><a href="#about">About Me</a></li>
                    <li><a href="#gallery">Gallery</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="about" class="about">
        <div class="container">
            <h2>About Me</h2>
            <p>Welcome! I am [Your Name], a passionate dancer and artist. I specialize in [mention your style: hip-hop, ballet, contemporary, etc.]. Dance is my form of expression, and I create art through movement.</p>
            <p>Here you'll find videos of my performances, art projects, and more. Enjoy exploring my journey!</p>
        </div>
    </section>

    <section id="gallery" class="gallery">
        <div class="container">
            <h2>Video Gallery</h2>
            <div class="gallery-grid">
                <!-- Replace the YouTube video URLs with your own -->
                <div class="gallery-item">
                    <iframe src="https://www.youtube.com/embed/your_video_id_1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <div class="gallery-item">
                    <iframe src="https://www.youtube.com/embed/your_video_id_2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <!-- Add more videos as needed -->
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Me</h2>
            <p>If you'd like to get in touch or collaborate, feel free to send me a message!</p>
            <p>Email: [your_email@example.com]</p>
        </div>
    </section>

    <footer>
        <div class="footer-content">
            <p>&copy; 2024 [Your Name]. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>
/* General Styles */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Arial', sans-serif;
    background-color: #f5f5f5;
    color: #333;
}

h1, h2 {
    text-align: center;
}

.container {
    width: 80%;
    margin: 0 auto;
}

/* Navbar Styles */
.navbar {
    background-color: #333;
    color: white;
    padding: 10px 0;
}

.navbar h1 {
    font-size: 24px;
    margin-left: 20px;
    display: inline-block;
}

.navbar nav ul {
    list-style-type: none;
    display: inline-block;
    margin-left: 20px;
}

.navbar nav ul li {
    display: inline;
    margin-right: 20px;
}

.navbar nav ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
}

/* About Section */
.about {
    background-color: #fff;
    padding: 50px 0;
}

.about p {
    text-align: center;
    font-size: 18px;
    line-height: 1.6;
}

/* Gallery Section */
.gallery {
    background-color: #eaeaea;
    padding: 50px 0;
}

.gallery h2 {
    margin-bottom: 30px;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 20px;
}

.gallery-item iframe {
    width: 100%;
    height: 200px;
    border-radius: 8px;
}

/* Contact Section */
.contact {
    background-color: #fff;
    padding: 50px 0;
}

.contact p {
    text-align: center;
    font-size: 18px;
}

/* Footer */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 20px 0;
}

footer p {
    font-size: 14px;
}
