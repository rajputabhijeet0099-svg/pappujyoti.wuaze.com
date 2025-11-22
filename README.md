<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Business Website</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #f7f7f7;
        }

        /* Header */
        header {
            background: #0b5ed7;
            color: white;
            padding: 15px 40px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
        }

        header h2 {
            margin: 0;
            font-size: 24px;
        }

        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Hero Section */
        .hero {
            background: url('https://images.unsplash.com/photo-1521737604893-d14cc237f11d') no-repeat center/cover;
            height: 90vh;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
            text-align: center;
            padding: 20px;
        }

        .hero h1 {
            font-size: 50px;
            margin: 0;
        }

        .hero p {
            font-size: 20px;
        }

        .btn {
            background: #0b5ed7;
            color: white;
            padding: 12px 25px;
            border: none;
            font-size: 16px;
            cursor: pointer;
            margin-top: 20px;
            border-radius: 5px;
        }

        .btn:hover {
            background: #084298;
        }

        /* Sections */
        section {
            padding: 60px 40px;
            text-align: center;
        }

        h2 {
            color: #0b5ed7;
        }

        .services {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }

        .card {
            background: white;
            width: 280px;
            margin: 15px;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        /* Contact */
        form {
            max-width: 500px;
            margin: auto;
        }

        input, textarea {
            width: 100%;
            padding: 12px;
            margin-top: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        /* Footer */
        footer {
            background: #0b5ed7;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }

        /* Responsive */
        @media(max-width: 768px) {
            .hero h1 { font-size: 35px; }
            .services { flex-direction: column; }
        }
    </style>
</head>
<body>

<header>
    <h2>Your Business</h2>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">About</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<!-- Hero -->
<div class="hero" id="home">
    <div>
        <h1>Grow Your Business With Us</h1>
        <p>We provide professional services to boost your business.</p>
        <button class="btn">Get Started</button>
    </div>
</div>

<!-- About -->
<section id="about">
    <h2>About Us</h2>
    <p>We are a professional business service provider helping companies grow digitally and strategically.</p>
</section>

<!-- Services -->
<section id="services">
    <h2>Our Services</h2>

    <div class="services">
        <div class="card">
            <h3>Web Development</h3>
            <p>Modern, fast and responsive websites for your business.</p>
        </div>

        <div class="card">
            <h3>Marketing</h3>
            <p>Grow your business with our advanced marketing strategies.</p>
        </div>

        <div class="card">
            <h3>Branding</h3>
            <p>We build powerful brands that stand out in the market.</p>
        </div>
    </div>
</section>

<!-- Contact -->
<section id="contact">
    <h2>Contact Us</h2>
    <form>
        <input type="text" placeholder="Your Name" required>
        <input type="email" placeholder="Email Address" required>
        <textarea placeholder="Your Message" rows="5" required></textarea>
        <button class="btn" type="submit">Send Message</button>
    </form>
</section>

<footer>
    © 2025 Your Business — All Rights Reserved
</footer>

</body>
</html>
[contact.html](https://github.com/user-attachments/files/23690193/contact.html)
[script.js](https://github.com/user-attachments/files/23690192/script.js)
