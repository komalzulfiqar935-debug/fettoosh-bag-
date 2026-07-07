# fettoosh-bag-<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bag Shop</title>

<style>
body{
margin:0;
font-family:Arial,sans-serif;
background:#f5f5f5;
}
header{
background:#222;
color:white;
padding:20px;
text-align:center;
}
.products{
display:flex;
flex-wrap:wrap;
justify-content:center;
padding:20px;
}
.card{
background:white;
width:280px;
margin:15px;
border-radius:10px;
box-shadow:0 0 10px rgba(0,0,0,.1);
overflow:hidden;
}
.card img{
width:100%;
height:250px;
object-fit:cover;
}
.card h2{
padding:10px;
}
.card p{
padding:0 10px;
}
button{
background:#25D366;
color:white;
border:none;
padding:12px;
margin:10px;
width:90%;
border-radius:6px;
font-size:16px;
}
footer{
background:#222;
color:white;
text-align:center;
padding:15px;
margin-top:20px;
}
</style>

</head>

<body>

<header>
<h1>My Bag Shop</h1>
<p>Best Quality Bags</p>
</header>

<div class="products">

<div class="card">
<img src="https://via.placeholder.com/300x250">
<h2>School Bag</h2>
<p>Price: Rs.2500</p>
<button>Order on WhatsApp</button>
</div>

<div class="card">
<img src="https://via.placeholder.com/300x250">
<h2>Hand Bag</h2>
<p>Price: Rs.3500</p>
<button>Order on WhatsApp</button>
</div>

</div>

<footer>
© 2026 My Bag Shop
</footer>

</body>
</html>
