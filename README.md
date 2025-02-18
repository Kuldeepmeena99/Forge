<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Forge</title>
    <style>
        body {
            font-family: sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #f0f0f0;
            padding: 20px;
            text-align: center;
        }
        nav {
            background-color: #333;
            color: white;
            padding: 10px;
        }
        nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            text-align: center; /* Center the navigation items */
        }
        nav li {
            display: inline;
            margin: 0 15px; /* Add some spacing between items */
        }
        nav a {
            color: white;
            text-decoration: none;
            padding: 5px 10px; /* Add padding to the links */
        }
        main {
            padding: 20px;
        }
        .product {
            display: inline-block;
            width: 30%; /* Adjust as needed */
            margin: 1%;
            border: 1px solid #ccc;
            padding: 10px;
            box-sizing: border-box; /* Include padding in width calculation */
            text-align: center; /* Center the product content */
            vertical-align: top; /* Align products to the top */

        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <h1>Your Brand Name</h1>
        <p>Your tagline or a short description</p>
    </header>

    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Men</a></li>
            <li><a href="#">Women</a></li>
            <li><a href="#">Accessories</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <main>
        <div class="product">
            <img src="placeholder.jpg" alt="Product 1">
            <h3>Product 1</h3>
            <p>Description of product 1.</p>
            <p>$XX.XX</p>
        </div>
        <div class="product">
            <img src="placeholder.jpg" alt="Product 2">
            <h3>Product 2</h3>
            <p>Description of product 2.</p>
            <p>$XX.XX</p>
        </div>
        <div class="product">
            <img src="placeholder.jpg" alt="Product 3">
            <h3>Product 3</h3>
            <p>Description of product 3.</p>
            <p>$XX.XX</p>
        </div>
        </main>

    <footer>
        <p>&copy; 2023 Your Brand Name. All rights reserved.</p>
    </footer>

</body>
</html>
