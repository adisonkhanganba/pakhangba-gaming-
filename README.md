<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Pakhangba Gaming</title>

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Segoe UI,sans-serif;
}

body{
background:#0b1120;
color:white;
}

header{
background:#111827;
padding:15px 40px;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
}

.logo{
font-size:28px;
font-weight:bold;
color:#00e5ff;
}

nav a{
color:white;
text-decoration:none;
margin-left:20px;
}

.hero{
text-align:center;
padding:100px 20px;
background:linear-gradient(to right,#0f172a,#1e293b);
}

.hero h1{
font-size:60px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
color:#cbd5e1;
}

.btn{
display:inline-block;
margin-top:25px;
padding:12px 30px;
background:#00e5ff;
color:black;
border-radius:30px;
text-decoration:none;
font-weight:bold;
}

.section{
padding:60px 10%;
}

.section h2{
text-align:center;
margin-bottom:30px;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.card{
background:#1e293b;
padding:20px;
border-radius:12px;
}

.card h3{
margin-bottom:10px;
color:#00e5ff;
}

.leaderboard table{
width:100%;
border-collapse:collapse;
}

.leaderboard th,
.leaderboard td{
padding:12px;
border-bottom:1px solid #334155;
text-align:left;
}

.auth{
display:grid;
grid-template-columns:1fr 1fr;
gap:20px;
}

.form-box{
background:#1e293b;
padding:25px;
border-radius:12px;
}

input{
width:100%;
padding:12px;
margin-top:10px;
margin-bottom:15px;
border:none;
border-radius:6px;
}

button{
width:100%;
padding:12px;
background:#00e5ff;
border:none;
border-radius:6px;
font-weight:bold;
cursor:pointer;
}

footer{
background:#111827;
text-align:center;
padding:20px;
}

@media(max-width:768px){
.auth{
grid-template-columns:1fr;
}
.hero h1{
font-size:40px;
}
}
</style>
</head>
<body>

<header>
<div class="logo">PAKHANGBA</div>
<nav>
<a href="#games">Games</a>
<a href="#leaderboard">Leaderboard</a>
<a href="#tournaments">Tournaments</a>
<a href="#login">Login</a>
</nav>
</header>

<section class="hero">
<h1>PAKHANGBA GAMING</h1>
<p>Play • Compete • Win</p>
<a href="#games" class="btn">Explore Games</a>
</section>

<section id="games" class="section">
<h2>Featured Games</h2>
<div class="grid">

<div class="card">
<h3>Battle Arena</h3>
<p>Online PvP battles.</p>
</div>

<div class="card">
<h3>Racing Legends</h3>
<p>Compete in high-speed races.</p>
</div>

<div class="card">
<h3>Survival Quest</h3>
<p>Explore and survive.</p>
</div>

</div>
</section>

<section id="leaderboard" class="section leaderboard">
<h2>Top Players</h2>

<table>
<tr>
<th>Rank</th>
<th>Player</th>
<th>Points</th>
</tr>

<tr>
<td>1</td>
<td>DragonX</td>
<td>9800</td>
</tr>

<tr>
<td>2</td>
<td>ShadowPro</td>
<td>9100</td>
</tr>

<tr>
<td>3</td>
<td>BlazeKing</td>
<td>8750</td>
</tr>

</table>
</section>

<section id="tournaments" class="section">
<h2>Upcoming Tournaments</h2>

<div class="grid">

<div class="card">
<h3>Battle Arena Cup</h3>
<p>Date: July 15</p>
<p>Prize Pool: ₹50,000</p>
</div>

<div class="card">
<h3>Racing Championship</h3>
<p>Date: August 2</p>
<p>Prize Pool: ₹25,000</p>
</div>

</div>
</section>

<section id="login" class="section">
<h2>Account</h2>

<div class="auth">

<div class="form-box">
<h3>Login</h3>
<input type="email" placeholder="Email">
<input type="password" placeholder="Password">
<button>Login</button>
</div>

<div class="form-box">
<h3>Sign Up</h3>
<input type="text" placeholder="Username">
<input type="email" placeholder="Email">
<input type="password" placeholder="Password">
<button>Create Account</button>
</div>

</div>
</section>

<footer>
<p>© 2026 Pakhangba Gaming. All Rights Reserved.</p>
</footer>

</body>
</html>
