<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RJ Digital Creations</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background-color: white;
            color: black;
            font-family: Arial, sans-serif;
        }
        header, footer {
            background-color: #8b0000;
            padding: 20px;
            text-align: center;
            color: white;
        }
        header img {
            max-width: 150px;
            height: auto;
            display: block;
            margin: 0 auto 10px auto;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .hero {
            text-align: center;
            padding: 50px;
            background-color: #f8f8f8;
        }
        .cta {
            display: inline-block;
            padding: 10px 20px;
            background-color: #8b0000;
            color: white;
            text-decoration: none;
            font-weight: bold;
            border-radius: 5px;
        }
        section {
            padding: 40px;
            text-align: center;
        }
        .gallery img {
            width: 200px;
            height: auto;
            margin: 10px;
            border: 2px solid #8b0000;
        }
        form {
            max-width: 400px;
            margin: auto;
            background-color: #f8f8f8;
            padding: 20px;
            border-radius: 5px;
        }
        label, input, textarea, button {
            display: block;
            width: 100%;
            margin-bottom: 10px;
        }
        button {
            background-color: #8b0000;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <img src="RJ Logo.jpg" alt="Website Logo">
        <h1>Bringing Your Ideas to Life with Stunning Designs</h1>
    </header>
    
    <section id="home">
        <div class="hero">
            <h2>Bringing Your Ideas to Life with Stunning Designs</h2>
        </div>
    </section>
    
    <section id="about">
        <h2>About Us</h2>
        <p>We specialize in: <br> Logo Design <br> Marketing Material Designs <br> Website Designs.</p>
    </section>
    
    <section id="services">
        <h2>Our Services</h2>
        <ul>
            <li>Logo Design</li>
            <li>Social Media Graphics</li>
            <li>Website Design</li>
            <li>Marketing Materials</li>
        </ul>
    </section>
    
    <section id="contact">
        <h2>Contact Us</h2>
        <form>
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            
            <button type="submit">Send</button>
        </form>
    </section>
    
    <footer>
        <p>&copy; 2025 RJ Digital Creations. All rights reserved.</p>
    </footer>
</body>
</html>
