<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Floral - Premium Perfumes</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');
        
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #fff5e1;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background: black;
            padding: 20px;
            font-size: 35px;
            color: #333;
            font-weight: bold;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .logo-text {
            display: flex;
            align-items: center;
            gap: 15px;
			background-color:black;
			padding:10px 20px;
			border-radius:10px;
        }
		.logo-text span{
		color:white;
		}
        .logo-text img {
            height: 60px;
        }
        nav {
            display: flex;
            justify-content: center;
            background: #ffaa00;
            padding: 15px;
        }
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-size: 18px;
            font-weight: bold;
        }
        .container {
            padding: 40px 20px;
            text-align: center;
        }
        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .product-card {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
            text-align: left;
            transition: transform 0.3s ease-in-out;
        }
        .product-card:hover {
            transform: translateY(-5px);
        }
        .product-card img {
            width: 100%;
            border-radius: 10px;
            height: 350px;
            object-fit: cover;
        }
        .product-card h3, .product-card p {
            margin-left: 10px;
        }
        .buy-btn {
            display: block;
            width: max-content;
            padding: 10px 20px;
            background: #ffaa00;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            margin: 10px auto;
            font-weight: bold;
        }
        .about, .contact {
            text-align: center;
            padding: 40px;
            background: #ffcc00;
            color: white;
        }
        .about h2, .contact h2 {
            font-size: 28px;
            margin-bottom: 15px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo-text">
            <img src=" https://i.postimg.cc/vHkBbc6h/IMG-20250405-WA0016.jpg" alt="Floral Logo">
            <span>Perfumes</span>
        </div>
    </header>
    <nav>
        <a href="#about">About</a>
        <a href="#collection">Collection</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="about" id="about">
        <h2>About Us</h2>
        <p>"Floral -Evoke a sense of presence and mystique."</p>
    </div>
    <div class="container" id="collection">
        <h2> Our Perfumes Collection </h2>
        <div class="product-grid">
            <div class="product-card">
                <img src="https://i.postimg.cc/RZj7np5r/IMG-20250405-WA0007.jpg" alt="Floral Love">
                <h3>Floral Love 50</h3>
                <p>Invigorating and Up lifting with rich rose and bright lilly.</p>
                <p>💰 Price: ₹799</p>
                <a href="#" class="buy-btn">Buy Now</a>
            </div>
            <div class="product-card">
                <img src="https://i.postimg.cc/mgxkYvDS/IMG-20250405-WA0006.jpg " alt="Floral Thug ">
                <h3>Floral Thug</h3>
                <p>Sophisticated and elegent scent that is perfect for any occasion.</p>
                <p>💰 Price: ₹899</p>
                <a href="#" class="buy-btn">Buy Now</a>
            </div>
            <div class="product-card">
                <img src="https://i.postimg.cc/NjTyZgVV/IMG-20250405-WA0009.jpg" alt="Floral Spice">
                <h3>Floral spice</h3>
                <p>Leaving a lingering trail of vanilla and musk.</p>
                <p>💰 Price: ₹999</p>
                <a href="#" class="buy-btn">Buy Now</a>
            </div>
            <div class="product-card">
                <img src="https://i.postimg.cc/2jF0NYp1/IMG-20250405-WA0005.jpg" alt="Floral Cherry Wine">
                <h3>Floral Cherry Wine</h3>
               <p>A captivating fragrance that opens with a burst of juicy berries .</p>
                <p>💰 Price: ₹1,099</p>
                <a href="#" class="buy-btn">Buy Now</a>
            </div>
        </div>
    </div>
    <div class="contact" id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@floral.com</p>
        <p>Phone: +91 98765 43210</p>
    </div>
</body>
</html>
