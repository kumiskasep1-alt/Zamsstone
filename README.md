<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Zamsstone</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#faf8f5;
    color:#333;
}

header{
    background:#fff;
    padding:20px;
    text-align:center;
    box-shadow:0 2px 8px rgba(0,0,0,.08);
}

header h1{
    font-size:38px;
    letter-spacing:2px;
}

header p{
    color:#777;
    margin-top:8px;
}

.hero{
    padding:80px 20px;
    text-align:center;
}

.hero h2{
    font-size:42px;
    margin-bottom:20px;
}

.hero p{
    max-width:700px;
    margin:auto;
    color:#666;
    line-height:1.8;
}

.button{
    display:inline-block;
    margin-top:30px;
    padding:14px 35px;
    background:#b58b55;
    color:white;
    text-decoration:none;
    border-radius:30px;
}

.products{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
    padding:50px;
}

.card{
    background:white;
    border-radius:15px;
    overflow:hidden;
    box-shadow:0 5px 20px rgba(0,0,0,.08);
}

.card img{
    width:100%;
    height:250px;
    object-fit:cover;
}

.card h3{
    padding:15px;
}

.card p{
    padding:0 15px 20px;
    color:#666;
}

footer{
    text-align:center;
    padding:30px;
    background:white;
    margin-top:40px;
}

</style>
</head>

<body>

<header>
<h1>Zamsstone</h1>
<p>Natural Gemstone • Cabochon • Handmade Jewelry</p>
</header>

<section class="hero">
<h2>Beautiful Natural Gemstones</h2>

<p>
Discover premium handcrafted cabochons made from carefully selected natural stones.
Perfect for jewelry makers, collectors, and gemstone lovers around the world.
</p>

<a href="https://instagram.com" class="button">
Visit Instagram
</a>

</section>

<section class="products">

<div class="card">
<img src="images/red-moss-agate.jpg">
<h3>Red Moss Agate</h3>
<p>Beautiful natural patterns with premium polish.</p>
</div>

<div class="card">
<img src="images/ocean-jasper.jpg">
<h3>Ocean Jasper</h3>
<p>Unique colors and natural ocean-like patterns.</p>
</div>

<div class="card">
<img src="images/palm-root.jpg">
<h3>Palm Root</h3>
<p>Rare fossilized palm root cabochons.</p>
</div>

<div class="card">
<img src="images/fordite.jpg">
<h3>Fordite</h3>
<p>Colorful handmade Fordite cabochons.</p>
</div>

</section>

<footer>

<h3>Custom Orders Available</h3>

<p>
We can produce custom shapes, sizes, and engraved cabochons based on your design.
Worldwide Shipping.
</p>

<p><br>
Instagram : @Zamsstone
</p>

</footer>

</body>
</html>
