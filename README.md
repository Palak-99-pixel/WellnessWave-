# WellnessWave-
Thrive. Balance. Flourish.
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WellnessWave - Thrive. Balance. Flourish.</title>
    <link rel="stylesheet" href="css/style.css">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="logo">WellnessWave</div>
        <nav>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#services">Wellness Areas</a></li>
                <li><a href="#resources">Resources</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="hero">
        <h1>Thrive. Balance. Flourish.</h1>
        <p>Transform your well-being with expert tips on physical fitness, mental health, nutrition, and technology balance.</p>
        <a href="#about" class="btn">Learn More</a>
    </section>

    <!-- About Section -->
    <section id="about" class="about">
        <h2>About WellnessWave</h2>
        <p>WellnessWave is your go-to platform for holistic well-being. Whether you're a student, researcher, professional, parent, or grandparent, we provide guidance to help you live a healthier and happier life.</p>
    </section>

    <!-- Wellness Areas -->
    <section id="services" class="services">
        <h2>Explore Wellness Areas</h2>
        <div class="service-box">
            <h3>Physical Fitness</h3>
            <p>Exercise plans, posture correction, and sleep hygiene tips.</p>
        </div>
        <div class="service-box">
            <h3>Mental & Emotional Health</h3>
            <p>Mindfulness, meditation, and stress relief strategies.</p>
        </div>
        <div class="service-box">
            <h3>Nutrition & Diet</h3>
            <p>Healthy eating habits, hydration tips, and superfoods.</p>
        </div>
        <div class="service-box">
            <h3>Technology & Well-being</h3>
            <p>Digital detox, healthy screen time, and wellness apps.</p>
        </div>
    </section>

    <!-- Resources -->
    <section id="resources" class="resources">
        <h2>Wellness Resources</h2>
        <p>Access wellness guides, self-improvement challenges, and expert blogs.</p>
        <a href="#" class="btn">Explore More</a>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="contact">
        <h2>Contact Us</h2>
        <p>Have a question? Reach out to us!</p>
        <form>
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <textarea placeholder="Your Message" required></textarea>
            <button type="submit">Send</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 WellnessWave. All rights reserved.</p>
    </footer>

</body>
</html>
/* General Styling */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background: #f0f8ff;
    color: #333;
}

/* Header */
header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 20px;
    background: #0077b6;
    color: white;
}

.logo {
    font-size: 24px;
    font-weight: bold;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
}

nav ul li {
    margin-left: 20px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

/* Hero Section */
.hero {
    text-align: center;
    padding: 80px 20px;
    background: #00b4d8;
    color: white;
}

.hero h1 {
    font-size: 36px;
}

.btn {
    background: white;
    color: #0077b6;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
}

.btn:hover {
    background: #0077b6;
    color: white;
}

/* Sections */
section {
    padding: 60px 20px;
    text-align: center;
}

.service-box {
    background: white;
    padding: 20px;
    margin: 10px;
    border-radius: 10px;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
}

/* Contact */
.contact form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.contact input, .contact textarea {
    width: 80%;
    max-width: 400px;
    padding: 10px;
    margin: 10px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.contact button {
    background: #0077b6;
    color: white;
    padding: 10px 20px;
    border: none;
    cursor: pointer;
}

.contact button:hover {
    background: #00b4d8;
}

/* Footer */
footer {
    background: #0077b6;
    color: white;
    text-align: center;
    padding: 20px;
}
