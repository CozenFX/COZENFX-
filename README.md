<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>[Your Name] | Trading Mentor</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        /* Base Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }

        body {
            background: #0f172a;
            color: #ffffff;
            line-height: 1.6;
        }

        /* Header */
        .hero {
            background: linear-gradient(135deg, #1e3a8a 0%, #0f172a 100%);
            padding: 100px 20px;
            text-align: center;
        }

        .hero h1 {
            font-size: 3.5rem;
            margin-bottom: 20px;
            background: linear-gradient(45deg, #3b82f6, #60a5fa);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Course Section */
        .courses {
            padding: 80px 20px;
            display: grid;
            gap: 30px;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
        }

        .course-card {
            background: #1e293b;
            border-radius: 15px;
            padding: 30px;
            transition: transform 0.3s;
        }

        .course-card:hover {
            transform: translateY(-10px);
        }

        .price {
            font-size: 2.5rem;
            color: #3b82f6;
            margin: 20px 0;
        }

        /* Testimonials */
        .testimonials {
            padding: 80px 20px;
            background: #1e293b;
        }

        .testimonial-card {
            background: #0f172a;
            padding: 30px;
            border-radius: 15px;
            margin: 20px 0;
        }

        /* CTA Button */
        .cta {
            background: linear-gradient(45deg, #3b82f6, #60a5fa);
            color: white;
            padding: 15px 40px;
            border-radius: 50px;
            text-decoration: none;
            display: inline-block;
            margin: 20px 0;
            font-weight: bold;
            transition: transform 0.3s;
        }

        .cta:hover {
            transform: scale(1.05);
        }

        /* Footer */
        footer {
            background: #1e293b;
            padding: 40px 20px;
            text-align: center;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 2.5rem;
            }
        }
    </style>
</head>
<body>
    <!-- Hero Section -->
    <header class="hero">
        <h1>Master the Markets with [Your Name]</h1>
        <p>Professional Trader & Mentor | 10+ Years Experience</p>
        <a href="#courses" class="cta">View Courses</a>
    </header>

    <!-- Courses Section -->
    <section id="courses" class="courses">
        <div class="course-card">
            <h3>Beginner's Bootcamp</h3>
            <div class="price">$497</div>
            <ul>
                <li><i class="fas fa-check"></i> Market Fundamentals</li>
                <li><i class="fas fa-check"></i> Risk Management</li>
                <li><i class="fas fa-check"></i> Basic Strategies</li>
            </ul>
            <a href="#enroll" class="cta">Enroll Now</a>
        </div>

        <div class="course-card">
            <h3>Advanced Mastery</h3>
            <div class="price">$1497</div>
            <ul>
                <li><i class="fas fa-check"></i> Advanced Strategies</li>
                <li><i class="fas fa-check"></i> Psychology Training</li>
                <li><i class="fas fa-check"></i> 1-on-1 Mentorship</li>
            </ul>
            <a href="#enroll" class="cta">Enroll Now</a>
        </div>
    </section>

    <!-- Enrollment Form -->
    <section id="enroll" class="testimonials">
        <h2>Enroll in Your Success</h2>
        <form style="max-width: 500px; margin: 0 auto;">
            <input type="text" placeholder="Full Name" required>
            <input type="email" placeholder="Email" required>
            <select required>
                <option value="">Select Course</option>
                <option>Beginner's Bootcamp</option>
                <option>Advanced Mastery</option>
            </select>
            <button type="submit" class="cta">Secure Checkout</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>© 2023 [Your Name]. All rights reserved</p>
        <p>Disclaimer: Trading involves risk</p>
    </footer>
</body>
</html>
