<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HMSolutions - IT Sales and Services</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        body {
            line-height: 1.6;
            color: #333;
        }

        .container {
            width: 90%;
            margin: 0 auto;
        }

        header {
            background-color: #2c3e50;
            color: #fff;
            padding: 1rem 0;
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 1.5rem;
            font-weight: bold;
        }

        .nav-links {
            list-style: none;
            display: flex;
        }

        .nav-links li {
            margin-left: 1rem;
        }

        .nav-links a {
            color: #fff;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .nav-links a:hover {
            color: #3498db;
        }

        .hero {
            background-image: url('https://source.unsplash.com/random/1600x900/?technology');
            background-size: cover;
            background-position: center;
            height: 60vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: #fff;
        }

        .hero-content {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 2rem;
            border-radius: 10px;
        }

        .hero h1 {
            font-size: 2.5rem;
            margin-bottom: 1rem;
        }

        .cta-button {
            display: inline-block;
            background-color: #3498db;
            color: #fff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        .cta-button:hover {
            background-color: #1f8cd4;
        }

        .featured-products, .services, .testimonials {
            padding: 2rem 0;
        }

        h2 {
            text-align: center;
            margin-bottom: 1rem;
        }

        .product-grid, .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1rem;
        }

        .product-card, .service-card {
            background-color: #f9f9f9;
            padding: 1rem;
            border-radius: 5px;
            text-align: center;
            transition: transform 0.3s ease;
        }

        .product-card:hover, .service-card:hover {
            transform: translateY(-5px);
        }

        .testimonial {
            background-color: #f9f9f9;
            padding: 1rem;
            border-radius: 5px;
            margin-bottom: 1rem;
        }

        footer {
            background-color: #2c3e50;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }

        .social-icons {
            margin-top: 1rem;
        }

        .social-icons a {
            color: #fff;
            font-size: 1.5rem;
            margin: 0 0.5rem;
            text-decoration: none;
        }

        @media (max-width: 768px) {
            .nav-links {
                display: none;
            }

            .hero h1 {
                font-size: 2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav class="container">
            <div class="logo">HMSolutions</div>
            <ul class="nav-links">
                <li><a href="index.html">Home</a></li>
                <li><a href="Products.html">Products</a></li>
                <li><a href="Sales.html">Sales</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="Terms_of_Service.html">Terms of Service</a></li>
                <li><a href="About_Us.html">About Us</a></li>
                <li><a href="Contact_Page.html">Contact</a></li>
                <li><a href="Admin_Login.html">Admin</a></li>
                <li><a href="Login.html">Login</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="hero">
            <div class="hero-content">
                <h1>Empowering You with varity of IT gadgets</h1>
                <a href="Products.html" class="cta-button">Shop Now</a>
            </div>
        </section>

        <section class="featured-products container">
            <h2>Featured Products</h2>
            <div class="product-grid">
                <div class="product-card">
                    <h3>Product 1</h3>
                    <p>Description of Product 1</p>
                </div>
                <div class="product-card">
                    <h3>Product 2</h3>
                    <p>Description of Product 2</p>
                </div>
                <div class="product-card">
                    <h3>Product 3</h3>
                    <p>Description of Product 3</p>
                </div>
            </div>
        </section>

        <section class="services container">
            <h2>Our Services</h2>
            <div class="services-grid">
                <div class="service-card">
                    <h3>Service 1</h3>
                    <p>Description of Service 1</p>
                </div>
                <div class="service-card">
                    <h3>Service 2</h3>
                    <p>Description of Service 2</p>
                </div>
                <div class="service-card">
                    <h3>Service 3</h3>
                    <p>Description of Service 3</p>
                </div>
            </div>
        </section>

        <section class="testimonials container">
            <h2>Customer Testimonials</h2>
            <div class="testimonial">
                <p>"HMSolutions has been a game-changer for our business. Their products and services are top-notch!"</p>
                <p>- John Doe, CEO of XYZ Company</p>
            </div>
        </section>
    </main>

    <footer>
        
        <div class="footer-left">
            <ul>
            <li><a href="Contact_Page.html">Contact</a></li>
                <li><a href="About_Us.html">About Us</a></li>
                <li><a href="Blog.html">Blog</a></li>
                <li><a href="#careers">Careers</a></li>
                <li><a href="#privacy-policy">Privacy Policy</a></li>
                <li><a href="FAQs.html">FAQs</a></li>
            </ul>
            </div>
    
        <div class="container">
            <p>&copy; 2024 HMSolutions. All rights reserved.</p>
            <div class="social-icons">
                <a href="https://web.facebook.com/unclehussainimusa" aria-label="Facebook">&#xf09a;</a>
                <a href="https://x.com/HMusa3" aria-label="Twitter">&#xf099;</a>
                <a href="https://www.linkedin.com/in/hussaini-musa-68614283/" aria-label="LinkedIn">&#xf0e1;</a>
            </div>
        </div>
    </footer>

    <script>
        // Add smooth scrolling to all links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();

                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Add animation to product and service cards
        const cards = document.querySelectorAll('.product-card, .service-card');
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.style.opacity = 1;
                    entry.target.style.transform = 'translateY(0)';
                }
            });
        }, {
            threshold: 0.1
        });

        cards.forEach(card => {
            card.style.opacity = 0;
            card.style.transform = 'translateY(20px)';
            card.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
            observer.observe(card);
        });
    </script>
</body>
</html>
