# DULICHAND-CLOTH-SHOP
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dulichand Cloth Shop</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins;
}

body{
background:#f5f5f5;
}

/* HEADER */

header{
background:#111;
color:white;
display:flex;
justify-content:space-between;
padding:20px 10%;
align-items:center;
}

header h1{
color:#ffcc00;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-size:18px;
transition:.3s;
}

nav a:hover{
color:#ffcc00;
}

/* HERO */

.hero{
height:90vh;
background:url("https://images.unsplash.com/photo-1521336575822-6da63fb45455") center/cover;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:white;
}

.hero h2{
font-size:50px;
background:rgba(0,0,0,0.5);
padding:20px;
border-radius:10px;
}

/* CATEGORY */

.section{
padding:60px 10%;
text-align:center;
}

.categories{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
margin-top:40px;
}

.cat{
background:white;
border-radius:10px;
overflow:hidden;
box-shadow:0 5px 15px rgba(0,0,0,0.2);
transition:.4s;
}

.cat:hover{
transform:scale(1.05);
}

.cat img{
width:100%;
height:250px;
object-fit:cover;
}

.cat h3{
padding:15px;
}

/* PRODUCTS */

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:25px;
margin-top:40px;
}

.card{
background:white;
border-radius:10px;
overflow:hidden;
box-shadow:0 5px 15px rgba(0,0,0,0.2);
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card h4{
padding:10px;
}

/* ABOUT */

.about{
background:#111;
color:white;
padding:60px 10%;
text-align:center;
}

/* MAP */

.map iframe{
width:100%;
height:350px;
border:0;
}

/* WHATSAPP BUTTON */

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
font-size:20px;
text-decoration:none;
}

/* FOOTER */

footer{
background:#000;
color:white;
text-align:center;
padding:20px;
}

</style>
</head>

<body>

<header>

<h1>Dulichand Cloth</h1>

<nav>
<a href="#">Home</a>
<a href="#">Categories</a>
<a href="#">Products</a>
<a href="#">About</a>
<a href="#">Contact</a>
</nav>

</header>

<div class="hero">
<h2>Best Quality Clothes For Everyone</h2>
</div>

<section class="section">

<h2>Shop Categories</h2>

<div class="categories">

<div class="cat">
<img src="https://images.unsplash.com/photo-1520975922324-7a41b9d1d46b">
<h3>Men Clothing</h3>
</div>

<div class="cat">
<img src="https://images.unsplash.com/photo-1529139574466-a303027c1d8b">
<h3>Women Clothing</h3>
</div>

<div class="cat">
<img src="https://images.unsplash.com/photo-1516762689617-e1cffcef479d">
<h3>Kids Clothing</h3>
</div>

</div>

</section>

<section class="section">

<h2>Popular Products</h2>

<div class="products">

<div class="card">
<img src="https://images.unsplash.com/photo-1523381210434-271e8be1f52b">
<h4>Stylish Shirt</h4>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1593032465171-8b1d1d4d9d88">
<h4>Designer Saree</h4>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1583001809952-618b5cb0c1b1">
<h4>Lehenga</h4>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1602810318383-e386cc2a3ccf">
<h4>Premium Fabric</h4>
</div>

</div>

</section>

<section class="about">

<h2>About Dulichand Cloth Shop</h2>
<p>
We provide high quality clothing for men, women and kids.
Best fabrics, latest fashion designs and affordable prices.
Visit our shop for the best clothing collection.
</p>

</section>

<section class="map">

<iframe src="https://maps.google.com/maps?q=india&t=&z=13&ie=UTF8&iwloc=&output=embed"></iframe>

</section>

<a class="whatsapp" href="https://wa.me/91XXXXXXXXXX">
Order on WhatsApp
</a>

<footer>

<p>© 2026 Dulichand Cloth Shop | All Rights Reserved</p>

</footer>

</body>
</html>
