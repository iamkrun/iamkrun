<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfume Boutique</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background: #f4c2c2;
            padding: 20px;
            font-size: 24px;
        }
        .hero {
            padding: 50px;
            background: url('perfume-banner.jpg') no-repeat center center/cover;
            color: white;
            font-size: 30px;
        }
        .products {
            display: flex;
            justify-content: center;
            gap: 20px;
            padding: 20px;
        }
        .product {
            border: 1px solid #ddd;
            padding: 10px;
            width: 200px;
        }
        footer {
            background: #333;
            color: white;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>Perfume Boutique</header>
    <div class="hero">Discover the Essence of Luxury</div>
    <div class="products">
        <div class="product">
            <img src="perfume1.jpg" alt="Perfume 1" width="100%">
            <h3>Rose Essence</h3>
            <p>$50</p>
        </div>
        <div class="product">
            <img src="perfume2.jpg" alt="Perfume 2" width="100%">
            <h3>Ocean Breeze</h3>
            <p>$60</p>
        </div>
    </div>
    <footer>Contact us at info@perfumeboutique.com</footer>
</body>
</html>
