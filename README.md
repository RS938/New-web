<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gemstone Store</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Times New Roman', Times, serif, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #a44c7c; /* Light background color */
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background-color: #a44c7c; /* Light pink */
        }
        .logo img {
            height: 50px;
        }
        h1 {
            font-style: italic;
            color: #ff99cc; /* Light pink color */
            margin: 0;
        }
        nav {
            display: flex;
            gap: 15px;
        }
        nav a {
            text-decoration: none;
            color: #333;
            padding: 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        nav a:hover {
            background-color: #ffb3d1; /* Light pink hover */
        }
        .hero {
            background: url('https://images-na.ssl-images-amazon.com/images/G/01/AMAZON_FASHION/2017/EDITORIAL/SPRING_2/WOMEN/ACCESSORIES/SPRNG2_A_women_BB._V533794450_.jpg') center/cover; /* Placeholder for carousel or video */
            text-align: center;
            padding: 50px 0;
            color: white;    
        }
        .section-heading {
            text-align: center;
            color: #ff99cc; /* Light pink color */
            margin: 20px 0;
        }
        .about-us-section {
            background-color: #ffe6f2; /* Aesthetic background for About Us */
            padding: 20px;
            text-align: center;
        }
        .faq-section, .review-section, .shop-section {
            padding: 20px;
        }
        .faq-container, .review-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center; /* Center the cards */
            gap: 10px; /* Space between cards */
        }
        .faq-card, .review-card {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
            width: 150px; /* Width for cards */
            background: rgba(255, 255, 255, 0.9); /* Semi-transparent white for cards */
        }
        .faq-card img, .review-card img {
            width: 100%; /* Make images responsive */
            height: auto; /* Maintain aspect ratio */
        }
        .accessory-container {
            display: flex;
            overflow-x: auto; /* Enable horizontal scrolling */
            justify-content: center; /* Center the cards */
            gap: 10px; /* Reduced space between cards */
            padding: 10px 0;
        }
        .accessory-card {
            border: 1px solid #ddd;
            padding: 10px;
            text-align: center;
            width: 150px; /* Reduced width for cards */
            background: rgba(255, 255, 255, 0.9); /* Semi-transparent white for cards */
            flex: none; /* Prevent flex items from growing */
        }
        .accessory-card img {
            width: 100%; /* Make images responsive */
            height: auto; /* Maintain aspect ratio */
        }
        footer {
            display: flex;
            flex-direction: column;
            align-items: center; /* Center align footer contents */
            padding: 20px;
            background-color: #a44c7c; /* Light pink */
        }
        .social-media {
            display: flex;
            gap: 15px; /* Space between icons */
        }
        .social-media a {
            text-decoration: none;
            color: #333;
        }
        .copyright {
            font-size: 14px;
            margin-top: 10px; /* Space above copyright */
            text-align: center; /* Center align footer text */
        }
    </style>
</head>
<body>
    <header>
        <title>Gemstone Store</title>
    <style>
        header {
            background-color: rgba(146, 44, 90, 0.9); /* Light pink background */
            padding: 20px;
            text-align: center; /* Center align text */
        }

        header h1 {
            font-style: italic; /* Italics for the title */
            color: #ff99cc; /* Light pink text color */
            margin: 0; /* Remove default margin */
        }
    </style>
</head>
<body>
    <header>
        <h1>Gemstones</h1>
    </header>
</body>
</html>
        <nav>
            <a href="#home">Home</a>
            <a href="#shop">Shop</a>
            <a href="#about">About Us</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Discover Your Style</h2>
        <p>Trendy accessories for every occasion!</p>
        </div>
        <button>Shop Now</button>
    </section>

    <section id="about" class="about-us-section">
        <h2 class="section-heading">About Us</h2>
        <p>We are dedicated to providing the highest quality gemstones and accessories. Our passion for beauty and craftsmanship drives us to offer a curated selection that enhances your style.</p>
    </section>

    <section id="shop" class="shop-section">
        <h2 class="section-heading">Shop With Us</h2>
        <div class="accessory-container">
            <div class="accessory-card">
                <img src="https://i.pinimg.com/736x/6d/0e/09/6d0e09716406468cbb04a2ef0e59fb21.jpg" alt="Glasses"> <!-- Replace with actual accessory image -->
                <h3>Daily wear</h3>
                <p>Stylish daily aesthetics</p>
            </div>
            <div class="accessory-card">
                <img src="https://i.pinimg.com/originals/b6/6b/53/b66b539986456480aa85749fd3cf2e26.png" alt="Hairstylying"> <!-- Replace with actual accessory image -->
                <h3>Hairstylying</h3>
                <p>High quality accessories</p>
            </div>
            <div class="accessory-card">
                <img src="https://i.pinimg.com/originals/d4/18/13/d4181381d37ec71df6bbd3a1fed733c8.jpg" alt="Hairstylying"> <!-- Replace with actual accessory image -->
                <h3>Necklace</h3>
                <p>Dailywear</p>
            </div>
            <div class="accessory-card">
                <img src="https://i.pinimg.com/originals/5d/5c/46/5d5c46015d164680e25fc1a0547e79f9.jpg" alt="Accessory 4"> <!-- Replace with actual accessory image -->
                <h3>Accessories</h3>
                <p>Aesthetic jewelry</p>
            </div>
            <!-- Add more accessory cards as needed -->
        </div>
    </section>

    <section id="reviews" class="review-section">
        <h2>Customer Reviews</h2>
        <div class="review-container">
            <div class="review-card">
                <img src="https://i.pinimg.com/originals/a4/bd/fa/a4bdfa806f02b9c984d1c9cf71130f1a.png" alt="Reviewer 1" class="reviewer-img">
                <h3>Jane Doe</h3>
                <p>"Absolutely stunning collection! I love the quality and the variety of gemstones available."</p>
            </div>
            <div class="review-card">
                <img src="https://i.pinimg.com/736x/ba/d9/6b/bad96b180120c6775a0da33ecefcc93c.jpg" alt="Reviewer 2" class="reviewer-img">
                <h3>John Smith</h3>
                <p>"Great quality and beautiful designs! My favorite store for gemstones!"</p>
            </div>
            <div class="review-card">
                <img src="https://i.pinimg.com/originals/78/8e/89/788e89de3a61b2b269349d22464ca1f8.jpg" alt="Reviewer 3" class="reviewer-img">
                <h3>Emily Johnson</h3>
                <p>"Excellent customer service and fast shipping. Highly recommend!"</p>
            </div>
            <div class="review-card">
                <img src="https://i.pinimg.com/736x/d4/aa/de/d4aade0ae19afd82a0834182673ddb51.jpg" alt="Reviewer 4" class="reviewer-img">
                <h3>Michael Brown</h3>
                <p>"The gemstone jewelry I purchased is absolutely gorgeous. Will be back for more!"</p>
            </div>
            <!-- Add more review cards as needed -->
        </div>
    </section>
    <section id="faqs" class="faq-section">
        <h2>FAQs</h2>
        <div class="faq-container">
            <div class="faq-card">
                <h3>What is a gemstone?</h3>
                <p>A gemstone is a precious or semi-precious stone that is cut and polished for use in jewelry.</p>
            </div>
            <div class="faq-card">
                <h3>How do I care for my gemstones?</h3>
                <p>To care for your gemstones, keep them clean and avoid exposure to harsh chemicals.</p>
            </div>
            <div class="faq-card">
                <h3>Are gemstones treated?</h3>
                <p>Many gemstones undergo treatments to enhance their appearance, such as heat treatment or oiling.</p>
            </div>
            <div class="faq-card">
                <h3>How can I tell if a gemstone is genuine?</h3>
                <p>You can verify the authenticity of a gemstone by consulting a gemologist or getting a certification.</p>
            </div>
            <div class="faq-card">
                <h3>What is the return policy for gemstones?</h3>
                <p>Please refer to our return policy page for detailed information on returns and exchanges.</p>
            </div>
            <div class="faq-card">
                <h3>Do you offer custom jewelry designs?</h3>
                <p>Yes, we offer custom jewelry design services. Please contact us for more details.</p>
            </div>
        </div>
        
        <h2>Have a Question? Ask Us!</h2>
        <form class="question-form">
            <label for="name">Your Name:</label>
            <input type="text" id="name" name="name" required>
    
            <label for="email">Your Email:</label>
            <input type="email" id="email" name="email" required>
    
            <label for="question">Your Question:</label>
            <textarea id="question" name="question" rows="4" required></textarea>
    
            <button type="submit">Submit Question</button>
        </form>
    </section>
    <footer>
        <div>
            <div class="social-icons">
                <a href="https://facebook.com" target="_blank" class="fab fa-facebook-f"></a>
                <a href="https://twitter.com" target="_blank" class="fab fa-twitter"></a>
                <a href="https://instagram.com" target="_blank" class="fab fa-instagram"></a>
                <a href="https://map loaction.com" target="_blank" class="fab fa-map location"></a>
            
            </body>
            </html>
                <a href="mailto:info@gemstonestore.com" class="fas fa-envelope"></a>
            </div>
            <div class="contact-us">
                <p><a href="info@gemstonestore.com" style="color: black;">Contact Us</a></p>
            </div>
            <div class="copyright">
                <p>&copy; 2025 Gemstonesstore . All rights reserved.</p>
            </div>
        </footer>
</body>
</html>
