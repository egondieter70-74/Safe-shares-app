<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>King David Coffee Ventures</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #6b4c2e; /* Earthy coffee brown */
            color: white;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #4b3621;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 40px 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        #home {
            background-color: #d2b48c; /* Light tan for coffee theme */
            text-align: center;
        }
        #about, #team {
            background-color: white;
        }
        #contact {
            background-color: #f4f4f4;
        }
        h1, h2 {
            color: #6b4c2e;
        }
        .team-member {
            display: inline-block;
            width: 45%;
            margin: 10px;
            text-align: center;
        }
        footer {
            background-color: #4b3621;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>King David Coffee Ventures</h1>
        <p>Premium Coffee Experiences in Kampala, Uganda</p>
    </header>

    <nav>
        <a href="#home" onclick="smoothScroll('#home')">Home</a>
        <a href="#about" onclick="smoothScroll('#about')">About Us</a>
        <a href="#team" onclick="smoothScroll('#team')">Our Team</a>
        <a href="#contact" onclick="smoothScroll('#contact')">Contact</a>
    </nav>

    <section id="home">
        <h2>Welcome to King David Coffee Ventures</h2>
        <p>We are dedicated to sourcing and serving the finest Ugandan coffee, blending tradition with innovation to create unforgettable experiences for coffee lovers in Kampala and beyond.</p>
        <!-- Add your coffee image here, e.g., <img src="coffee-banner.jpg" alt="Coffee Banner" style="width:100%; max-height:400px;"> -->
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>Founded in Kampala, Uganda, King David Coffee Ventures specializes in high-quality coffee production, distribution, and retail. Our mission is to promote sustainable farming practices while delivering exceptional coffee products to our customers.</p>
        <p>We focus on ethical sourcing from local farmers, ensuring every cup tells a story of quality and community.</p>
    </section>

    <section id="team">
        <h2>Our Leadership Team</h2>
        <div class="team-member">
            <h3>Hans Vriens</h3>
            <p>CEO</p>
            <p>With extensive experience in the coffee industry, Hans leads our strategic vision and international partnerships.</p>
            <!-- Add photo: <img src="hans-vriens.jpg" alt="Hans Vriens" style="width:150px; border-radius:50%;"> -->
        </div>
        <div class="team-member">
            <h3>Geoffrey Assiimwe</h3>
            <p>Director</p>
            <p>Geoffrey oversees operations and local initiatives, bringing deep knowledge of Uganda's coffee landscape.</p>
            <!-- Add photo: <img src="geoffrey-assiimwe.jpg" alt="Geoffrey Assiimwe" style="width:150px; border-radius:50%;"> -->
        </div>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Location: Kampala, Uganda</p>
        <p>Email: info@kingdavidcoffee.com (replace with your actual email)</p>
        <p>Phone: +256-XXX-XXXXXX (add your contact number)</p>
        <!-- Add a simple form if needed -->
        <form>
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="message">Message:</label><br>
            <textarea id="message" name="message"></textarea><br>
            <input type="submit" value="Send">
        </form>
    </section>

    <footer>
        &copy; 2026 King David Coffee Ventures. All rights reserved.
    </footer>

    <script>
        function smoothScroll(target) {
            document.querySelector(target).scrollIntoView({ behavior: 'smooth' });
        }
    </script>

</body>
</html># Safe-shares-app
Safe shares for older people
