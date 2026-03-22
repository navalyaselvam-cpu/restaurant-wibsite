# restaurant-wibsite<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>kaavi Foodies Restaurant</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <h1>🍴 kaavi Foodies Restaurant</h1>
    <nav>
        <a href="#">Home</a>
        <a href="#menu">Menu</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Delicious Food Awaits 😋</h2>
    <p>Fresh • Tasty • Affordable</p>
</section>

<section id="menu">
    <h2>Our Menu</h2>

    <div class="menu">

        <div class="item">
            <img src="https://source.unsplash.com/200x150/?pizza" alt="Pizza">
            <h3>Pizza</h3>
            <p>Cheesy delight</p>
            <span>₹200</span>
        </div>

        <div class="item">
            <img src="https://source.unsplash.com/200x150/?burger" alt="Burger">
            <h3>Burger</h3>
            <p>Juicy & crispy</p>
            <span>₹150</span>
        </div>

        <div class="item">
            <img src="https://source.unsplash.com/200x150/?pasta" alt="Pasta">
            <h3>Pasta</h3>
            <p>Creamy special</p>
            <span>₹180</span>
        </div>

    </div>
</section>

<section id="about">
    <h2>About Us</h2>
    <p>We serve fresh and hygienic food with great taste.</p>
</section>

<section id="contact">
    <h2>Contact</h2>
    <p>📍 Your City</p>
    <p>📞 9876543210</p>
</section>

<footer>
    <p>© 2026 kaavi Foodies Restaurant</p>
</footer>

</body>
</html>
body {
    margin: 0;
    font-family: Arial;
    background: #f4f4f4;
}

/* Header */
header {
    background: #222;
    color: white;
    text-align: center;
    padding: 15px;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
}

nav a:hover {
    color: yellow;
}

/* Hero */
.hero {
    text-align: center;
    padding: 70px;
    background: linear-gradient(to right, orange, red);
    color: white;
}

/* Menu */
#menu {
    text-align: center;
    padding: 40px;
}

.menu {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.item {
    background: white;
    padding: 15px;
    width: 220px;
    box-shadow: 0 0 10px gray;
    border-radius: 10px;
    text-align: center;
}

.item img {
    width: 100%;
    border-radius: 10px;
}

.item:hover {
    transform: scale(1.05);
}

/* About & Contact */
#about, #contact {
    text-align: center;
    padding: 30px;
}

/* Footer */
footer {
    background: #222;
    color: white;
    text-align: center;
    padding: 10px;
}
