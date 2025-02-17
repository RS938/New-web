<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Accessory Store</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        header {
            background: #333;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-bottom: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        .hero {
            display: flex;
            align-items: center;
            justify-content: center;
            background: #f4f4f4;
            padding: 20px;
        }
        .hero img {
            width: 300px; /* Set a specific width for vertical image */
            height: auto; /* Maintain aspect ratio */
            border-radius: 5px;
            margin-right: 20px; /* Space between image and text */
        }
        .hero h1 {
            font-size: 2.5em;
            color: #333;
        }
        .welcome-image {
            width: 100%;
            height: auto;
            display: block;
        }
        .body-section {
            padding: 20px;
            background: #f4f4f4;
            margin: 10px 0;
        }
        .product-gallery {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }
        .product {
            background: white;
            border: 1px solid #ddd;
            margin: 10px;
            padding: 15px;
            border-radius: 5px;
            text-align: center;
            width: 30%;
        }
        .product img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .reviews, .faqs, .connect {
            padding: 20px;
            background: #f4f4f4;
            margin: 10px 0;
        }
        .review, .faq {
            background: white;
            border: 1px solid #ddd;
            margin: 10px 0;
            padding: 15px;
            border-radius: 5px;
        }
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }
        .connect a {
            display: block;
            margin: 5px 0;
            color: blue;
            text-decoration: none;
        }
        .connect i {
            margin-right: 8px;
        }
    </style>
</head>
<body>

<header>
    <h1>Accessory Store</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#">Products</a>
        <a href="#">About Us</a>
        <a href="#">FAQs</a>
        <a href="#">Contact</a>
    </nav>
</header>

<img src="https://www.turnoffthelights.com/support/wp-content/uploads/2021/06/etsy-dark-mode-with-the-free-turn-off-the-lights-browser-extension-2048x1057.png.webp" alt="Welcome to Accessory Store" class="welcome-image">

<div class="hero">
    <h1>Discover Unique Accessories</h1>
</div>

<section class="body-section">
    <h2>Our Products</h2>
    <div class="product-gallery">
        <div class="product">
            <img src="https://cdn.augrav.com/online/jewels/2019/11/11124142/Love-In-Morse-Code-Gold-Couple-Rings1.jpg" alt="Accessory 1">
            <h3>Accessory 1</h3>
            <p>$19.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://i.etsystatic.com/6922778/c/679/539/0/203/il/1436a3/3007137843/il_680x540.3007137843_tv3i.jpg" alt="Accessory 2">
            <h3>Accessory 2</h3>
            <p>$29.99</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="https://i.pinimg.com/originals/b7/20/1e/b7201e6b811cf67b0ebcd33fdc15fc33.jpg" alt="Accessory 3">
            <h3>Accessory 3</h3>
            <p>$24.99</p>
            <button>Add to Cart</button>
        </div>
    </div>
</section>

<section class="reviews">
    <h2>Customer Reviews</h2>
    <div class="review">
        <p><strong>Jane Doe:</strong> "Amazing accessories! I love my new bag!"</p>
    </div>
    <div class="review">
        <p><strong>John Smith:</strong> "Great quality and fast shipping!"</p>
    </div>
    <div class="review">
        <p><strong>Emily Johnson:</strong> "I always find something unique here!"</p>
    </div>
</section>

<section class="faqs">
    <h2>Frequently Asked Questions</h2>
    <div class="faq">
        <p><strong>Q1: What is your return policy?</strong></p>
        <p>A1: We offer a 30-day return policy for unused items.</p>
    </div>
    <div class="faq">
        <p><strong>Q2: How can I track my order?</strong></p>
        <p>A2: You will receive a tracking link via email once your order is shipped.</p>
    </div>
    <div class="faq">
        <p><strong>Q3: Do you offer international shipping?</strong></p>
        <p>A3: Yes, we ship worldwide!</p>
    </div>
</section>

<section class="connect">
    <h2>Connect with Us</h2>
    <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook"></i> Facebook</a>
    <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
    <a href="https://twitter.com" target="_blank"><i class="fab fa-twitter"></i> Twitter</a>
    <a href="mailto:info@accessorystore.com"><i class="fas fa-envelope"></i> Email Us</a>
</section>

<footer>
    <p>&copy; 2025 Accessory Store. All rights reserved.</p>
</footer>

</body>
</html>
