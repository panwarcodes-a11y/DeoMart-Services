<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>DeoMart Services</title>

<style>

body{
margin:0;
font-family:sans-serif;
background:#0f172a;
color:white;
}

header{
background:#14532d;
padding:25px;
text-align:center;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
padding:20px;
}

.card{
background:#1e293b;
padding:15px;
border-radius:20px;
text-align:center;
box-shadow:0 0 10px rgba(0,0,0,0.5);
}

.card img{
width:100%;
border-radius:15px;
}

button{
background:#22c55e;
border:none;
padding:12px 20px;
border-radius:10px;
color:white;
font-size:16px;
margin-top:10px;
cursor:pointer;
}

</style>

</head>

<body>

<header>
<h1>DeoMart</h1>
<p>All Services & Delivery at Your Doorstep</p>
</header>

<section class="services">

<div class="card">
<img src="https://images.unsplash.com/photo-1621905252507-b35492cc74b4">
<h2>AC Repair</h2>
<p>Starting ₹299</p>
<button>Book Now</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1581092919535-7146ff1a5905">
<h2>Electrician</h2>
<p>Starting ₹199</p>
<button>Book Now</button>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1581578731548-c64695cc6952">
<h2>Plumbing</h2>
<p>Starting ₹249</p>
<button>Book Now</button>
</div>

</section>

<script>

alert("Welcome to DeoMart");

</script>

</body>
</html>
