# 7-AI-Landing-Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>7-AI | Smarter Portfolio Management</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            color: #333;
        }

        header {
            background: #1e1e2d;
            color: white;
            padding: 20px 50px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            font-size: 24px;
            margin: 0;
        }

        header nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 16px;
        }

        header nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        .hero h2 {
            font-size: 48px;
            margin: 0 0 20px;
        }

        .hero p {
            font-size: 20px;
            margin: 0 0 30px;
        }

        .hero button {
            background: white;
            color: #2575fc;
            border: none;
            padding: 15px 30px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }

        .hero button:hover {
            background: #ddd;
        }

        .features {
            display: flex;
            justify-content: center;
            padding: 50px 20px;
            background: #f9f9f9;
        }

        .feature {
            margin: 0 20px;
            text-align: center;
            max-width: 300px;
        }

        .feature img {
            width: 80px;
            margin-bottom: 20px;
        }

        .feature h3 {
            font-size: 20px;
            margin: 10px 0;
        }

        .testimonials {
            padding: 50px 20px;
            text-align: center;
        }

        .testimonials h2 {
            margin-bottom: 30px;
            font-size: 32px;
        }

        .testimonial {
            max-width: 500px;
            margin: 0 auto 20px;
            font-style: italic;
        }

        .cta {
            background: #1e1e2d;
            color: white;
            text-align: center;
            padding: 50px 20px;
        }

        .cta h2 {
            margin-bottom: 20px;
            font-size: 32px;
        }

        .cta button {
            background: #2575fc;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }

        .cta button:hover {
            background: #6a11cb;
        }

        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 20px 0;
        }

        footer p {
            margin: 0;
            font-size: 14px;
        }
    </style>
</head>
<body>
    <header>
        <h1>7-AI</h1>
        <nav>
            <a href="#features">Features</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Smarter Portfolio Management</h2>
        <p>Revolutionize how you manage portfolios with advanced analytics and AI-driven insights.</p>
        <button>Get Started</button>
    </section>

    <section id="features" class="features">
        <div class="feature">
            <img src="https://via.placeholder.com/80" alt="Feature Icon">
            <h3>AI-Driven Insights</h3>
            <p>Leverage machine learning to make smarter investment decisions.</p>
        </div>
        <div class="feature">
            <img src="https://via.placeholder.com/80" alt="Feature Icon">
            <h3>Scenario Analysis</h3>
            <p>Run multiple scenarios to stress-test your strategies.</p>
        </div>
        <div class="feature">
            <img src="https://via.placeholder.com/80" alt="Feature Icon">
            <h3>Collaboration Tools</h3>
            <p>Seamlessly collaborate with your team in real-time.</p>
        </div>
    </section>

    <section id="testimonials" class="testimonials">
        <h2>What Our Users Say</h2>
        <div class="testimonial">
            <p>"7-AI has completely transformed the way we manage portfolios. The insights are unparalleled."</p>
            <p>- Jane Doe, Portfolio Manager</p>
        </div>
        <div class="testimonial">
            <p>"I love how intuitive and powerful the platform is. It's a game-changer for our team."</p>
            <p>- John Smith, CFO</p>
        </div>
    </section>

    <section id="contact" class="cta">
        <h2>Ready to Transform Your Portfolio Management?</h2>
        <button>Contact Us</button>
    </section>

    <footer>
        <p>&copy; 2024 7-AI. All rights reserved.</p>
    </footer>
</body>
</html>
