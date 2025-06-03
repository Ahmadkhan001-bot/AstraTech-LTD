<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AstraTech | Innovating the Future</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #2d3748, #1a202c);
            color: white;
        }
        nav {
            background: #1a202c;
            padding: 1rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
        nav h1 {
            color: #63b3ed;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 1rem;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            transition: color 0.3s;
        }
        nav ul li a:hover {
            color: #63b3ed;
        }
        section {
            padding: 2rem;
            text-align: center;
        }
        .hero {
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
        }
        .hero a {
            padding: 0.5rem 1rem;
            background: #63b3ed;
            color: #1a202c;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s;
        }
        .hero a:hover {
            background: #4299e1;
        }
        .services {
            background: #2d3748;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1rem;
        }
        .service-card {
            background: #1a202c;
            padding: 1rem;
            border-radius: 10px;
        }
        footer {
            background: #1a202c;
            padding: 1rem;
            text-align: center;
            color: #718096;
        }
    </style>
</head>
<body>
    <!-- Navbar -->
    <nav>
        <h1>AstraTech</h1>
        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#services">Services</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav><!-- Hero Section -->
<section class="hero">
    <h2>Welcome to AstraTech</h2>
    <p>Innovating the Future Through Cutting-Edge Technology</p>
    <a href="#services">Get Started</a>
</section>

<!-- About Section -->
<section id="about">
    <h3>About AstraTech</h3>
    <p>At AstraTech, we are dedicated to providing state-of-the-art solutions that empower businesses and individuals to thrive in a technology-driven world. Our commitment to innovation drives us to create groundbreaking products and services.</p>
</section>

<!-- Services Section -->
<section id="services" class="services">
    <div class="service-card">
        <h4>Website Development</h4>
        <p>Crafting modern, responsive websites tailored to your business needs.</p>
    </div>
    <div class="service-card">
        <h4>App Development</h4>
        <p>Building innovative and user-friendly mobile applications.</p>
    </div>
    <div class="service-card">
        <h4>AI Solutions</h4>
        <p>Leveraging artificial intelligence to solve real-world challenges.</p>
    </div>
</section>

<!-- Contact Section -->
<section id="contact">
    <h3>Contact Us</h3>
    <p>We'd love to hear from you! Reach out to us for more information about our services.</p>
    <p><strong>Phone:</strong> 08060908514</p>
    <p><strong>Address:</strong> Tudun Wada, Kano State</p>
    <p><strong>Email:</strong> AstraTech@gmail.com</p>
</section>

<!-- Footer -->
<footer>
    <p>&copy; 2025 AstraTech. All Rights Reserved.</p>
</footer>

<script>
    document.querySelectorAll('a').forEach(link => {
        link.addEventListener('click', e => {
            e.preventDefault();
            const target = document.querySelector(link.getAttribute('href'));
            if (target) {
                target.scrollIntoView({ behavior: 'smooth' });
            }
        });
    });
</script>

</body>
</html>