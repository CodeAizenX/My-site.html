<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abia-Bassey Leroy Eno | Web Developer</title>
    <style>
        /* Base Reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }

        /* Navigation */
        nav {
            background-color: #1a252f;
            color: #fff;
            padding: 1rem 2rem;
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 1000;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        nav .logo {
            font-size: 1.2rem;
            font-weight: bold;
            letter-spacing: 1px;
        }

        nav ul {
            display: flex;
            list-style: none;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-size: 0.9rem;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #3498db;
        }

        /* Hero Section */
        header {
            background: linear-gradient(rgba(26, 37, 47, 0.9), rgba(26, 37, 47, 0.9)), url('https://unsplash.com') no-repeat center center/cover;
            height: 100vh;
            color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 0 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.2rem;
            color: #bdc3c7;
            margin-bottom: 15px;
        }

        .matric {
            font-size: 1rem;
            color: #3498db;
            background: rgba(255,255,255,0.1);
            padding: 5px 15px;
            border-radius: 20px;
            margin-bottom: 30px;
            display: inline-block;
            font-family: monospace;
            letter-spacing: 1px;
        }

        .btn {
            display: inline-block;
            background-color: #3498db;
            color: #fff;
            padding: 10px 30px;
            text-decoration: none;
            border-radius: 5px;
            transition: background 0.3s;
        }

        .btn:hover {
            background-color: #2980b9;
        }

        /* Container & Sections */
        .container {
            max-width: 1100px;
            margin: auto;
            padding: 80px 20px;
        }

        section h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 40px;
            position: relative;
        }

        section h2::after {
            content: '';
            display: block;
            width: 50px;
            height: 3px;
            background-color: #3498db;
            margin: 10px auto 0;
        }

        /* About Section */
        #about p {
            text-align: center;
            max-width: 800px;
            margin: 0 auto 15px auto;
            font-size: 1.1rem;
        }

        /* Grid Layout for Projects/Courses */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .card {
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            text-align: center;
        }

        .card h3 {
            margin-bottom: 15px;
            color: #2c3e50;
        }

        .course-tag {
            display: inline-block;
            background-color: #e74c3c;
            color: #fff;
            padding: 3px 10px;
            font-size: 0.8rem;
            border-radius: 20px;
            margin-bottom: 10px;
            text-transform: uppercase;
            font-weight: bold;
        }

        /* Contact Form */
        form {
            max-width: 600px;
            margin: 0 auto;
            background: #fff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
        }

        .form-group {
            margin-bottom: 20px;
        }

        .form-group label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .form-group input, .form-group textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }

        form button {
            width: 100%;
            padding: 12px;
            background-color: #2c3e50;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
            font-size: 1rem;
            transition: background 0.3s;
        }

        form button:hover {
            background-color: #1a252f;
        }

        /* Footer */
        footer {
            background-color: #1a252f;
            color: #fff;
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            header h1 { font-size: 2rem; }
            nav ul { display: none; }
        }
    </style>
</head>
<body>

    <!-- Navigation -->
    <nav>
        <div class="logo">ALB</div>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#portfolio">Academic & Projects</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <!-- Hero Section -->
    <header id="home">
        <h1>Abia-Bassey Leroy Eno</h1>
        <p>Web Developer | University of Uyo</p>
        <div class="matric">Matric No: 25/CO/IS/005</div>
        <div>
            <a href="#contact" class="btn">Get In Touch</a>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="container">
        <h2>About Me</h2>
        <p>I am Abia-Bassey Leroy Eno, a passionate Web Developer currently studying at the University of Uyo. I specialize in crafting clean, functional, and user-friendly digital experiences.</p>
        <p>Driven by curiosity, I balance my practical development work with rigorous academic coursework to build efficient systems from the ground up.</p>
    </section>

    <!-- Portfolio & Coursework Section -->
    <section id="portfolio" style="background-color: #f1f2f6;">
        <div class="container">
            <h2>Academic & Development Focus</h2>
            <div class="grid">
                <!-- Course 1 -->
                <div class="card">
                    <span class="course-tag">Coursework</span>
                    <h3>INF 121</h3>
                    <p>Foundational principles of Information Systems, data management, or structural informatics being undertaken at UniUyo.</p>
                </div>
                <!-- Course 2 -->
                <div class="card">
                    <span class="course-tag">Coursework</span>
                    <h3>COS 121</h3>
                    <p>Core concepts in Computer Science, focusing on programming methodologies, algorithms, or problem-solving structures.</p>
                </div>
                <!-- Web Dev Card -->
                <div class="card">
                    <span class="course-tag">Dev Focus</span>
                    <h3>Web Development</h3>
                    <p>Designing modern, responsive websites utilizing HTML, CSS, JavaScript, and progressive backend frameworks.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="container">
        <h2>Contact Me</h2>
        <form onsubmit="event.preventDefault(); alert('Message sent successfully!');">
            <div class="form-group">
                <label for="name">Name</label>
                <input type="text" id="name" required>
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input type="email" id="email" required>
            </div>
            <div class="form-group">
                <label for="message">Message</label>
                <textarea id="message" rows="5" required></textarea>
            </div>
            <button type="submit">Send Message</button>
        </form>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2026 Abia-Bassey Leroy Eno. All Rights Reserved.</p>
    </footer>

</body>
</html>
