<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gym Equipment Store</title>
    <link rel="stylesheet" href="style.css">
    <script defer src="script.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
</head>
<body>
    <!-- Navbar -->
    <nav class="navbar">
        <h1>Gym Equipment Store</h1>
        <div class="navbar-links">
            <a href="#home">Home</a>
            <a href="#products">Products</a>
            <a href="#contact">Contact</a>
            <a href="#cart"><i class="fa-solid fa-cart-shopping"></i> Cart (<span id="cart-count">0</span>)</a>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="hero" id="home">
        <h1>Train like a beast, shop like a pro!</h1>
        <p>Upgrade your fitness with the best gym equipment.</p>
        <button onclick="scrollToProducts()">Shop Now</button>
    </header>

    <!-- Products Section -->
    <section class="products" id="products">
        <h2>Our Collection</h2>
        <div class="product-list">
            <div class="product">
                <img src="download.jpeg" alt="Dumbbell">
                <h3>Dumbbells</h3>
                <p>RS400</p>
                <button onclick="addToCart(400)">Add to Cart</button>
            </div>
            <div class="product">
                <img src="images.jpeg" alt="Treadmill">
                <h3>Treadmill</h3>
                <p>RS18000</p>
                <button onclick="addToCart(18000)">Add to Cart</button>
            </div>
            <div class="product">
                <img src="barbell.jpg" alt="Barbell">
                <h3>Barbell</h3>
                <p>RS2500</p>
                <button onclick="addToCart(2500)">Add to Cart</button>
            </div>
            <div class="product">
                <img src="ettlebell.jpg" alt="Kettlebell">
                <h3>Kettlebell</h3>
                <p>RS1200</p>
                <button onclick="addToCart(1200)">Add to Cart</button>
            </div>
            <div class="product">
                <img src="benchpress.jpg" alt="Bench Press">
                <h3>Bench Press</h3>
                <p>RS5500</p>
                <button onclick="addToCart(5500)">Add to Cart</button>
            </div>
            <div class="product">
                <img src="esistance-band.jpeg" alt="Resistance Bands">
                <h3>Resistance Bands</h3>
                <p>RS800</p>
                <button onclick="addToCart(800)">Add to Cart</button>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@gymstore.com</p>
        <p>Phone: 8524935953</p>
        <a rel=""
    </section>
</body>
</html>
