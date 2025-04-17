<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LABXDROP — Unveil Your Essence</title>
    <style>
        body {
            margin: 0;
            font-family: 'Poppins', sans-serif;
            background-color: #F8F8F8;
            color: #000;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 50px;
            background-color: #046A38;
        }
        header h1 {
            color: white;
            margin: 0;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin-left: 30px;
            font-weight: 500;
        }
        .hero {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 90vh;
            background: url('your-product-image.jpg') no-repeat center center/cover;
            text-align: center;
            color: white;
            position: relative;
        }
        .hero::after {
            content: "";
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background: rgba(0, 0, 0, 0.4);
        }
        .hero-text {
            position: relative;
            z-index: 1;
        }
        .hero-text h2 {
            font-size: 3rem;
            margin: 0 0 20px;
        }
        .hero-text button {
            padding: 12px 30px;
            background-color: #D4AF37;
            border: none;
            color: #000;
            font-size: 1rem;
            cursor: pointer;
            border-radius: 25px;
            transition: background 0.3s ease;
        }
        .hero-text button:hover {
            background-color: #b89c30;
        }
    </style>
</head>
<body>
    <header>
        <h1>LABXDROP</h1>
        <nav>
            <a href="#">Home</a>
            <a href="#">Shop</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
            <a href="#">Cart</a>
        </nav>
    </header><section class="hero">
    <div class="hero-text">
        <h2>Unveil Your Essence</h2>
        <button>Shop Now</button>
    </div>
</section>

</body>
</html>
