# flower-shop
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <nav class="navbar">
        
        <div class="logo">
             <img src="images/logo.png/hero-flower.png/bouquet.jpg/logo.png" alt="logo">
       </div>

       <ul class="menu">
         <li><a href="#">Home</a></li>
            <li><a href="#">Shop</a></li>
            <li><a href="#">About us</a></li>
    
    </ul>
    <button class="cart-btn">
            🛒 56
        </button>
    </nav>

    <section class="hero">
        <div class="hero text">
            <h1>
                Always <span>Fresh</span><br>
                Flowers
            </h1>
            <p>
            Indulge your senses with the beauty and fragrance
            of our fresh flower shop.
            </p>
         </div>
         <div class="hero-image">
        <img src="images/logo.png/hero-flower.png/bouquet.jpg/image 1.png" alt="hero-flower">
    </div>

</section>
<section class="plants">

    <h2>Our <span>Plants</span></h2>

    <p>
        Indulge your senses with the beauty and fragrance
        of our fresh flower shop.
    </p>

</section>
<div class="product-container">

    <div class="card">
        <img src="images/logo.png/unsplash_0IsBu45B3T8.png" alt="lili">
        <h3>Lily Blossom</h3>
        <p>69$</p>
        <button>ADD TO CART</button>
    </div>
    <div class="card">
        <img src="images/logo.png/unsplash_0IsBu45B3T8.png" alt="lili">
        <h3>Lavender Bunch</h3>
        <p>69$</p>
        <button>ADD TO CART</button>
    </div>
    <div class="card">
        <img src="images/logo.png/unsplash_0IsBu45B3T8.png" alt="lili">
        <h3>Sunflower Set</h3>
        <p>69$</p>
        <button>ADD TO CART</button>
    </div>
    <div class="card">
        <img src="images/logo.png/unsplash_0IsBu45B3T8.png" alt="lili">
        <h3>Tulip Bundle</h3>
        <p>69$</p>
        <button>ADD TO CART</button>
    </div>

</div>
</body>
</html>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body{
    font-family:Arial, sans-serif;
}
.navbar{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:20px 80px;
}
.menu{
    display:flex;
    list-style:none;
    gap:30px;
}
.menu a{
text-decoration: none;
color:#444;
}
.cart-btn{
    padding:8px 18px;
    border:1px solid #ccc;
    border-radius:20px;
    background:white;
    cursor:pointer;
}
.hero{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:80px;
}
.hero text{
     max-width:450px;
}
.hero h1{
    font-size: 55px;
}
.hero span{
    color: #E95A08;
}
.hero p{
    margin-top: 20px;
    color: #777;
    line-height: 1.6;
}
.hero-image img{
    width: 450px;
}
.plants{
    text-align:center;
    margin-top:50px;
}
.plants h2{
    font-size: 40px;
}
.plants span{
    color:#E95A08;
}
.plants p{
    color:#777;
    margin-top:10px;
}
.product-container{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:20px;
    padding:50px 80px;
}
.card{
    text-align:center;
}
.card img{
    width: 100px;
    border-radius: 8px;
}
.card h3{
    margin-top: 10px;
}
.card p{
    margin: 5px 0 10px;
}
.card button{
    width:100%;
    background:#E95A08;
    color:white;
    border:none;
    padding:12px;
    cursor:pointer;
}
.hero{
    flex-direction: column;
}
.hero-image img{
    width:100%;
    margin-top:30px;
}
.product-container{
    grid-template-columns:repeat(2,1fr);
}
.navbar{
     padding:20px;
}

