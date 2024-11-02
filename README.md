
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HOVE Supermarket</title>
    <style>
        /* Basic reset and styling */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }
        body {
            background-color: #f7f7f7;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 1rem 0;
            text-align: center;
        }
        .container {
            width: 90%;
            margin: 0 auto;
            padding: 1rem 0;
        }
        .hero {
            background-image: url("hee.png");
            background-size: cover;
            background-position: center;
            height: 300px;
          
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .hero h1 {
            font-size: 3rem;
        }
        .hero p {
            font-size: 1.2rem;
        }
        .categories, .products {
            margin: 2rem 0;
        }
        .categories h2, .products h2 {
            margin-bottom: 1rem;
        }
        .categories-grid, .products-grid {
            display: flex;
            gap: 1rem;
            flex-wrap: wrap;
        }
        .category, .product {
            flex: 1 1 calc(25% - 1rem);
            background-color: white;
            padding: 1rem;
            border-radius: 5px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .category img, .product img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 5px;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

<header>
    <h1>Welcome to HOVE Supermarket</h1>
    <p>Your one-stop shop for everything you need!</p>
</header>

<section class="hero">
    <div>
        
    </div>
</section>

<div class="container">
    <!-- Categories Section -->
    <section class="categories">
        <h2><ul><li>Shop by Category</li></ul></h2>
        <div class="categories-grid">
            <div class="category">
                <img src="F and B.jpeg" alt="Fresh bananas" width="150" height="150">
                <h3><a href="section of fruits.html">Fruits & Vegetables</a></h3>
            </div>
            <div class="category">
                <img src="dairy.jpeg" alt="Dairy Products">
                <h3><a href="dairies.html">Dairy Products</a></h3>
            </div>
            <div class="category">
                <img src="fish and meat.jpeg" alt="Meat & Fish">
                <h3><a href="Fish and meat.html">Meat & Fish</a></h3>
            </div>
            <div class="category">
                <img src="house hold.jpeg" alt="Household Supplies">
                <h3><a href="house hold things.html">Household Supplies</a></h3>
            </div>
        </div>
    </section>

    <!-- Featured Products Section -->
    <section class="products">
       <ul> <li><h2>Featured Products</h2></li></ul>
        <div class="products-grid">
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 1">
                <h3>Organic Apples</h3>
                <p>$3.99 / lb</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 2">
                <h3>Fresh Milk</h3>
                <p>$1.99 / bottle</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 3">
                <h3>Chicken Breast</h3>
                <p>$5.99 / lb</p>
            </div>
            <div class="product">
                <img src="https://via.placeholder.com/150" alt="Product 4">
                <h3>Laundry Detergent</h3>
                <p>$8.99 / bottle</p>
            </div>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2024 HOVE Supermarket. All rights reserved.</p>
</footer>

</body>
</html>