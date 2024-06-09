<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Madhava's Creative Corner</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #111;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            color: #ff6347;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #333;
        }
        nav a {
            color: #fff;
            padding: 14px 20px;
            text-decoration: none;
            text-transform: uppercase;
        }
        nav a:hover {
            background-color: #575757;
        }
        .container {
            padding: 20px;
        }
        .product {
            border: 1px solid #444;
            padding: 10px;
            margin: 10px;
            text-align: center;
        }
        .product img {
            width: 100%;
            max-width: 300px;
        }
        .product h2 {
            color: #ff6347;
        }
        footer {
            background-color: #111;
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
        <h1>Madhava's Creative Corner</h1>
        <p>Contact: 7011945816, 9871500274</p>
    </header>
    <nav>
        <a href="#mugs">Mugs</a>
        <a href="#tshirts">T-Shirts</a>
        <a href="#caps">Caps</a>
        <a href="#keychains">Keychains</a>
    </nav>
    <div class="container">
        <section id="mugs" class="product">
            <h2>Sublimation Printing Mugs</h2>
            <img src="mug.jpg" alt="Sublimation Mug">
            <p>High-quality sublimation printing mugs.</p>
            <button>Buy Now</button>
        </section>
        <section id="tshirts" class="product">
            <h2>Sublimation Printing T-Shirts</h2>
            <img src="tshirt.jpg" alt="Sublimation T-Shirt">
            <p>Comfortable and stylish sublimation printing T-Shirts.</p>
            <button>Buy Now</button>
        </section>
        <section id="caps" class="product">
            <h2>Sublimation Printing Caps</h2>
            <img src="cap.jpg" alt="Sublimation Cap">
            <p>Trendy sublimation printing caps.</p>
            <button>Buy Now</button>
        </section>
        <section id="keychains" class="product">
            <h2>Sublimation Printing Keychains</h2>
            <img src="keychain.jpg" alt="Sublimation Keychain">
            <p>Durable sublimation printing keychains.</p>
            <button>Buy Now</button>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Madhava's Creative Corner</p>
    </footer>
</body>
</html>
