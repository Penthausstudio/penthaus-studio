# penthaus-studio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Penthaus Studio</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="logo">P E N T H A U S</div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About Us</a></li>
                <li><a href="#services">Services</a></li>
                <li><a href="#gallery">Gallery</a></li>
                <li><a href="#events">Events</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background-color: #333;
    color: white;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    display: flex;
    gap: 15px;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

.hero {
    background: url('your-image.jpg') no-repeat center center/cover;
    color: white;
    text-align: center;
    padding: 100px 20px;
}

.btn {
    background-color: gold;
    color: black;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
}

section {
    padding: 50px 20px;
}

.service {
    margin-bottom: 20px;
}

form {
    display: flex;
    flex-direction: column;
    gap: 10px;
}

form input, form textarea {
    padding: 10px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: white;
}


    </header>

    <section id="home" class="hero">
        <h1>Welcome to Penthaus Studio</h1>
        <p>Your perfect space for photography, events, workshops, and videography</p>
        <a href="#contact" class="btn">Book Now</a>
    </section>

    <section id="services">
        <h2>Our Services</h2>
        <div class="service">
            <h3>Photography</h3>
            <p>Professional photography services for all your needs.</p>
        </div>
        <div class="service">
            <h3>Events</h3>
            <p>Host your events in our versatile space.</p>
        </div>
        <div class="service">
            <h3>Workshops</h3>
            <p>Join our engaging and informative workshops.</p>
        </div>
        <div class="service">
            <h3>Videography</h3>
            <p>High-quality videography services available.</p>
        </div>
    </section>

    <section id="gallery">
        <h2>Gallery</h2>
        <!-- Image gallery will go here -->
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>21A Glasgow Road, Johannesburg 2092</p>
        <p>Email: <a href="mailto:info@penthaus.studio">info@penthaus.studio</a></p>
        <p>Phone: +27 123 456 7890</p>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name">
            <label for="email">Email:</label>
            <input type="email" id="email" name="email">
            <label for="message">Message:</label>
            <textarea id="message" name="message"></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Penthaus Studio. All rights reserved.</p>
    </footer>
</body>
</html>
