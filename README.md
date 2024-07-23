# E-commerce-Product-Page
# HTML-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Cricket Bat Product Page</title>
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="https://www.example.com/home">Home</a></li>
                <li><a href="https://www.example.com/shop">Shop</a></li>
                <li><a href="https://www.example.com/cart">Cart (<span id="cart-count">0</span>)</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section class="product">
            <div class="product-image">
                <img src="cricket-bat-image.png" alt="Cricket Bat Image">
            </div>
            <div class="product-info">
                <h1>Kashmir Willow Cricket Bat</h1>
                <p>This cricket bat is made from high-quality Kashmir willow wood, providing exceptional durability and performance. The bat features a unique design with a flat face and a long handle, making it perfect for aggressive players.</p>
                <p>Price: $199.99</p>
                <button id="add-to-cart">Add to Cart</button>
            </div>
        </section>

        <section class="product-details">
            <h2>Product Details</h2>
            <ul>
                <li>Material: Kashmir Willow Wood</li>
                <li>Weight: 2.8 lbs</li>
                <li>Handle Length: 12 inches</li>
            </ul>
        </section>

        <section class="reviews">
            <h2>Reviews</h2>
            <ul>
                <li>
                    <p>Rating: 5/5</p>
                    <p>Review: This cricket bat is amazing! The quality is top-notch and the performance is exceptional.</p>
                </li>
                <li>
                    <p>Rating: 4/5</p>
                    <p>Review: This cricket bat is good, but not great. The handle could be a bit longer.</p>
                </li>
            </ul>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Cricket Store</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>

# CSS-

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    background-color: #f0f0f0;
    padding: 1rem;
    text-align: center;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

header nav {
    flex: 1;
}

header nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

header nav li {
    margin-right: 20px;
}

header nav a {
    color: #337ab7;
    text-decoration: none;
}

header nav a:hover {
    color: #23527c;
}

.product {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    padding: 2rem;
}

.product-image {
    width: 50%;
    margin-right: 20px;
}

.product-image img {
    width: 100%;
    height: 300px;
    object-fit: cover;
    border-radius: 10px;
}

.product-info {
    width: 50%;
    padding: 20px;
}

.product-info h1 {
    font-size: 24px;
    margin-bottom: 10px;
}

.product-info p {
    margin-bottom: 20px;
}

.product-info button {
    background-color: #337ab7;
    color: #fff;
    border: none;
    padding: 10px 20px;
    font-size: 18px;
    cursor: pointer;
}

.product-info button:hover {
    background-color: #23527c;
}

.product-details {
    padding: 2rem;
    border-top: 1px solid #ccc;
}

.product-details ul {
    list-style: none;
    margin: 0;
    padding: 0;
}

.product-details li {
    margin-bottom: 10px;
}

.reviews {
    padding: 2rem;
    border-top: 1px solid #ccc;
}

.reviews ul {
    list

