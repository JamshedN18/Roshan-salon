<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Roshan Salon</title>

<style>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    background: #f9f9f9;
}

header {
    background: #111;
    color: white;
    text-align: center;
    padding: 20px;
}

header h1 {
    margin: 0;
}

nav {
    background: #333;
    padding: 10px;
    text-align: center;
}

nav a {
    color: white;
    margin: 10px;
    text-decoration: none;
}

.container {
    padding: 20px;
}

.section {
    margin: 30px 0;
}

.card {
    background: white;
    padding: 20px;
    margin: 10px 0;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

button {
    background: green;
    color: white;
    padding: 10px;
    border: none;
    cursor: pointer;
    border-radius: 5px;
}

footer {
    background: #111;
    color: white;
    text-align: center;
    padding: 15px;
}
</style>
</head>

<body>

<header>
    <h1>💇‍♂️ Roshan Salon</h1>
    <p>Pimpri Chinchwad, Pune</p>
</header>

<nav>
    <a href="#services">Services</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
</nav>

<div class="container">

<!-- SERVICES -->
<div class="section" id="services">
<h2>💼 Our Services</h2>

<div class="card">
<h3>Hair Cutting</h3>
<p>Professional hair cutting for all styles.</p>
<p>₹100</p>
</div>

<div class="card">
<h3>Beard Shaping</h3>
<p>Stylish beard trim and shaping.</p>
<p>₹80</p>
</div>

<div class="card">
<h3>Head Massage</h3>
<p>Relaxing oil massage.</p>
<p>₹100</p>
</div>

<div class="card">
<h3>Hair Colour</h3>
<p>Trendy hair coloring service.</p>
<p>₹200</p>
</div>

</div>

<!-- ABOUT -->
<div class="section" id="about">
<h2>👨‍🔧 About Us</h2>
<p>Welcome to Roshan Salon! We provide professional grooming services with modern styles at affordable prices. Customer satisfaction is our priority.</p>
</div>

<!-- CONTACT -->
<div class="section" id="contact">
<h2>📞 Contact Us</h2>
<p>📍 Location: Pimpri Chinchwad, Pune</p>
<p>📱 Phone: 9421159097</p>

<button onclick="callNow()">Call Now</button>
<button onclick="whatsappNow()">WhatsApp</button>
</div>

</div>

<footer>
<p>© 2026 Roshan Salon | All Rights Reserved</p>
</footer>

<script>
function callNow() {
    window.location.href = "tel:9421159097";
}

function whatsappNow() {
    window.location.href = "https://wa.me/919421159097";
}
</script>

</body>
</html>
