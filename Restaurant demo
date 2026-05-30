<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ember & Spice | Premium Dining</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#0f0f0f;
    color:white;
}

.navbar{
    position:fixed;
    width:100%;
    top:0;
    z-index:1000;
    background:rgba(0,0,0,0.9);
    backdrop-filter:blur(10px);
}

.nav-container{
    max-width:1200px;
    margin:auto;
    padding:18px 20px;
    display:flex;
    justify-content:space-between;
    align-items:center;
}

.logo{
    color:#d4af37;
    font-size:1.8rem;
    font-weight:700;
}

.nav-links{
    display:flex;
    gap:25px;
}

.nav-links a{
    text-decoration:none;
    color:white;
    transition:0.3s;
}

.nav-links a:hover{
    color:#d4af37;
}

.hero{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.7)),
    url("https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?auto=format&fit=crop&w=1600&q=80");
    background-size:cover;
    background-position:center;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:20px;
}

.hero-content h1{
    font-size:4rem;
    color:#d4af37;
}

.hero-content p{
    margin:20px 0;
    font-size:1.2rem;
}

.btn{
    display:inline-block;
    padding:14px 30px;
    background:#d4af37;
    color:black;
    text-decoration:none;
    border-radius:30px;
    font-weight:600;
    transition:0.3s;
}

.btn:hover{
    transform:translateY(-3px);
}

section{
    padding:90px 20px;
}

.container{
    max-width:1200px;
    margin:auto;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title h2{
    color:#d4af37;
    font-size:2.5rem;
}

.about-grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
    align-items:center;
}

.about-grid img{
    width:100%;
    border-radius:15px;
}

.menu-grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.menu-card{
    background:#1a1a1a;
    padding:25px;
    border-radius:15px;
    transition:0.3s;
}

.menu-card:hover{
    transform:translateY(-5px);
}

.menu-card h3{
    color:#d4af37;
    margin-bottom:10px;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:15px;
}

.gallery img{
    width:100%;
    height:250px;
    object-fit:cover;
    border-radius:12px;
}

.testimonials{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.testimonial{
    background:#1a1a1a;
    padding:25px;
    border-radius:15px;
}

.form-container{
    max-width:700px;
    margin:auto;
}

input, textarea{
    width:100%;
    padding:15px;
    margin-bottom:15px;
    border:none;
    border-radius:10px;
}

button{
    border:none;
    cursor:pointer;
}

.contact-box{
    text-align:center;
    margin-top:30px;
}

.footer{
    text-align:center;
    padding:30px;
    background:#000;
}

.whatsapp{
    position:fixed;
    right:20px;
    bottom:20px;
    background:#25D366;
    color:white;
    padding:15px 20px;
    border-radius:50px;
    text-decoration:none;
    font-weight:600;
}

@media(max-width:768px){

.hero-content h1{
    font-size:2.7rem;
}

.about-grid{
    grid-template-columns:1fr;
}

.nav-links{
    display:none;
}
}
</style>
</head>
<body>

<nav class="navbar">
<div class="nav-container">
<div class="logo">🔥 Ember & Spice</div>

<div class="nav-links">
<a href="#about">About</a>
<a href="#menu">Menu</a>
<a href="#gallery">Gallery</a>
<a href="#reserve">Reserve</a>
<a href="#contact">Contact</a>
</div>
</div>
</nav>

<section class="hero">
<div class="hero-content">
<h1>Ember & Spice</h1>
<p>Where Fire Meets Flavor</p>
<a href="#reserve" class="btn">Reserve Your Table</a>
</div>
</section>

<section id="about">
<div class="container">

<div class="section-title">
<h2>About Us</h2>
</div>

<div class="about-grid">
<img src="https://images.unsplash.com/photo-1552566626-52f8b828add9?auto=format&fit=crop&w=1200&q=80">

<div>
<h3>Premium Dining Experience</h3>
<br>
<p>
At Ember & Spice, every dish is crafted with passion,
bringing together bold flavors, fresh ingredients,
and an unforgettable dining atmosphere.
</p>
<br>
<p>
Whether it's a family dinner, date night,
or corporate gathering, our chefs deliver
an exceptional culinary experience.
</p>
</div>

</div>
</div>
</section>

<section id="menu">
<div class="container">

<div class="section-title">
<h2>Signature Menu</h2>
</div>

<div class="menu-grid">

<div class="menu-card">
<h3>Butter Chicken</h3>
<p>Rich creamy tomato gravy.</p>
<br>
<strong>₹420</strong>
</div>

<div class="menu-card">
<h3>Paneer Tikka</h3>
<p>Char-grilled cottage cheese.</p>
<br>
<strong>₹320</strong>
</div>

<div class="menu-card">
<h3>Chicken Biryani</h3>
<p>Traditional dum-style biryani.</p>
<br>
<strong>₹390</strong>
</div>

<div class="menu-card">
<h3>Veg Biryani</h3>
<p>Fragrant basmati rice and spices.</p>
<br>
<strong>₹290</strong>
</div>

<div class="menu-card">
<h3>Garlic Naan</h3>
<p>Freshly baked tandoor bread.</p>
<br>
<strong>₹80</strong>
</div>

<div class="menu-card">
<h3>Tiramisu</h3>
<p>Classic Italian dessert.</p>
<br>
<strong>₹220</strong>
</div>

</div>
</div>
</section>

<section id="gallery">
<div class="container">

<div class="section-title">
<h2>Gallery</h2>
</div>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=1200&q=80">

<img src="https://images.unsplash.com/photo-1414235077428-338989a2e8c0?auto=format&fit=crop&w=1200&q=80">

<img src="https://images.unsplash.com/photo-1559339352-11d035aa65de?auto=format&fit=crop&w=1200&q=80">

<img src="https://images.unsplash.com/photo-1514933651103-005eec06c04b?auto=format&fit=crop&w=1200&q=80">

</div>
</div>
</section>

<section>
<div class="container">

<div class="section-title">
<h2>What Our Guests Say</h2>
</div>

<div class="testimonials">

<div class="testimonial">
★★★★★
<br><br>
Amazing ambience and fantastic food.
</div>

<div class="testimonial">
★★★★★
<br><br>
Perfect place for family dinners.
</div>

<div class="testimonial">
★★★★★
<br><br>
One of the best dining experiences in Bengaluru.
</div>

</div>

</div>
</section>

<section id="reserve">
<div class="container">

<div class="section-title">
<h2>Reserve a Table</h2>
</div>

<div class="form-container">

<form id="reservationForm">

<input type="text" placeholder="Your Name" required>

<input type="email" placeholder="Email Address" required>

<input type="tel" placeholder="Phone Number" required>

<textarea rows="5" placeholder="Reservation Details"></textarea>

<button class="btn" type="submit">Book Now</button>

</form>

</div>

</div>
</section>

<section id="contact">
<div class="container">

<div class="section-title">
<h2>Contact Us</h2>
</div>

<div class="contact-box">
<p>📍 42 Oakwood Avenue, Indiranagar, Bengaluru</p>
<br>
<p>📞 +91 98765 43210</p>
<br>
<p>✉ reservations@emberandspice.com</p>
</div>

<br><br>

<iframe
src="https://maps.google.com/maps?q=indiranagar%20bangalore&t=&z=13&ie=UTF8&iwloc=&output=embed"
width="100%"
height="350"
style="border:0;border-radius:15px;"
loading="lazy">
</iframe>

</div>
</section>

<footer class="footer">
<p>© 2026 Ember & Spice. All Rights Reserved.</p>
</footer>

<a class="whatsapp"
href="https://wa.me/919876543210"
target="_blank">
WhatsApp
</a>

<script>
document
.getElementById("reservationForm")
.addEventListener("submit", function(e){

e.preventDefault();

alert(
"Thank you! Your reservation request has been received."
);

this.reset();

});
</script>

</body>
</html>
