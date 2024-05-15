<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shein Shop</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to Shein Shop</h1>
    </header>

    <section class="products">
        <h2>Featured Products</h2>
        <!-- Add your products here -->
        <div class="product">
            <img src="product1.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>Description of Product 1</p>
            <button>Add to Cart</button>
        </div>
        <div class="product">
            <img src="product2.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>Description of Product 2</p>
            <button>Add to Cart</button>
        </div>
        <!-- Add more products as needed -->
    </section>

    <section class="tamara">
        <h2>Shop with Tamara</h2>
        <p>Pay for your purchases with Tamara, the easy way to shop now and pay later.</p>
        <!-- Add Tamara logo or description -->
        <img src="tamara_logo.png" alt="Tamara Logo">
    </section>

    <section class="paypal">
        <h2>Checkout with PayPal</h2>
        <p>Pay securely with PayPal. Fast checkout, secure payments.</p>
        <!-- Add PayPal checkout button or logo -->
        <img src="paypal_logo.png" alt="PayPal Logo">
    </section>

    <footer>
        <p>&copy; 2024 Shein Shop. All rights reserved.</p>
    </footer>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background-color: #f4f4f4;
    padding: 20px;
    text-align: center;
}

.products {
    padding: 20px;
}

.product {
    border: 1px solid #ddd;
    border-radius: 5px;
    padding: 10px;
    margin-bottom: 20px;
}

.product img {
    max-width: 100%;
    height: auto;
}

.tamara, .paypal {
    background-color: #f9f9f9;
    padding: 20px;
    margin-top: 20px;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 20px;
    text-align: center;
}


