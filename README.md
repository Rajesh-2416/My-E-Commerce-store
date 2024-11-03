# My-E-Commerce-store 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My E-commerce Store</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <style>
        /* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body Styling */
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    color: #333;
    line-height: 1.6;
}

/* Header Styling */
header {
    background-color: #333;
    color: #fff;
    padding: 1rem 0;
    text-align: center;
}

header h1 {
    margin-bottom: 0.5rem;
}

header nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 1.5rem;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

header nav ul li a:hover {
    color: #00aaff;
}

/* Featured Products Section */
#products {
    max-width: 1100px;
    margin: 2rem auto;
    padding: 0 1rem;
    text-align: center;
}

#products h2 {
    font-size: 2rem;
    color: #333;
    margin-bottom: 1rem;
}

.product-gallery {
    display: flex;
    gap: 2rem;
    flex-wrap: wrap;
    justify-content: center;
}

.product-item {
    background-color: #fff;
    padding: 1rem;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    width: 200px;
    text-align: center;
}

.product-item img {
    max-width: 100%;
    height: auto;
    border-radius: 8px;
}

.product-item h3 {
    margin: 0.5rem 0;
}

.product-item p {
    font-size: 1.2rem;
    color: #00aaff;
    font-weight: bold;
}

/* Categories Section */
#categories {
    background-color: #e9f5ff;
    padding: 2rem 0;
    text-align: center;
}

#categories h2 {
    font-size: 2rem;
    margin-bottom: 1rem;
}

.category-list {
    list-style: none;
    display: flex;
    gap: 1.5rem;
    justify-content: center;
}

.category-list li a {
    text-decoration: none;
    color: #333;
    font-weight: bold;
    background-color: #fff;
    padding: 0.5rem 1rem;
    border-radius: 5px;
    transition: background-color 0.3s ease;
}

.category-list li a:hover {
    background-color: #00aaff;
    color: #fff;
}

/* Footer Styling */
footer {
    background-color: #333;
    color: #fff;
    padding: 1rem;
    text-align: center;
}

footer p {
    margin-bottom: 0.5rem;
}

footer ul {
    list-style: none;
    display: flex;
    justify-content: center;
    gap: 1rem;
}

footer ul li a {
    color: #00aaff;
    text-decoration: none;
    font-weight: bold;
    transition: color 0.3s ease;
}

footer ul li a:hover {
    color: #fff;
}

/* Responsive Styling */
@media (max-width: 768px) {
    .product-gallery {
        flex-direction: column;
        align-items: center;
    }

    .category-list {
        flex-direction: column;
        gap: 0.5rem;
    }
}

    </style>
    <!-- Header Section -->
    <header>
        <h1>My E-commerce Store</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#categories">Categories</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Featured Products Section -->
    <section id="products">
        <h2>Featured Products</h2>
        <div class="product-gallery">
            <div class="product-item">
                <img src="images/kelly-sikkema-hB_WJo1xbUc-unsplash.jpg" alt="Product 1">
                <h3>Product 1</h3>
                <p>$20.00</p>
            </div>
            <div class="product-item">
                <img src="images/minh-pham-OtXADkUh3-I-unsplash.jpg" alt="Product 2">
                <h3>Product 2</h3>
                <p>$25.00</p>
            </div>
            <div class="product-item">
                <img src="images/tamara-bellis-U2ymajzuqFk-unsplash.jpg" alt="Product 3">
                <h3>Product 3</h3>
                <p>$30.00</p>
            </div>
            <!-- Add more product items as needed -->
        </div>
    </section>

    <!-- Categories Section -->
    <section id="categories">
        <h2>Shop by Category</h2>
        <ul class="category-list">
            <li><a href="#">Electronics</a></li>
            <li><a href="#">Fashion</a></li>
            <li><a href="#">Home & Living</a></li>
            <li><a href="#">Beauty</a></li>
            <!-- Add more categories as needed -->
        </ul>
    </section>

    <!-- Footer Section -->
    <footer>
        <p>&copy; 2023 My E-commerce Store. All rights reserved.</p>
        <ul>
            <li><a href="https://www.linkedin.com">LinkedIn</a></li>
            <li><a href="https://twitter.com">Twitter</a></li>
        </ul>
    </footer>
</body>
</html>
