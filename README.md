<!DOCTYPE html><html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>El VarÃ³n Barber Shop</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:'Poppins',sans-serif;background:#0f0f0f;color:white}
header{display:flex;justify-content:space-between;align-items:center;padding:20px 10%;background:black;border-bottom:2px solid gold}
header h1{color:gold;font-size:28px}
nav a{color:white;margin-left:20px;text-decoration:none;font-size:16px}
.hero{height:90vh;background:url('https://images.unsplash.com/photo-1621605815971-fbc98d665033') center/cover no-repeat;display:flex;flex-direction:column;justify-content:center;align-items:center;text-align:center}
.hero h2{font-size:48px;background:rgba(0,0,0,0.6);padding:20px;border-radius:10px}
.hero p{margin-top:10px;font-size:18px}
.btn{margin-top:20px;background:gold;color:black;padding:14px 28px;border-radius:8px;text-decoration:none;font-weight:600}
.section{padding:70px 10%;text-align:center}
.section h2{margin-bottom:40px;font-size:32px;color:gold}
.services{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:25px}
.card{background:#1b1b1b;padding:30px;border-radius:12px;transition:0.3s}
.card:hover{transform:translateY(-8px)}
.price{margin-top:10px;font-size:20px;color:gold}
.gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.gallery img{width:100%;border-radius:10px}
.contact{background:#111;padding:60px 10%;text-align:center}
.whatsapp{display:inline-block;margin-top:20px;background:#25D366;color:white;padding:15px 30px;border-radius:8px;text-decoration:none;font-weight:600}
footer{background:black;text-align:center;padding:20px;margin-top:40px;color:#aaa}
</style>
</head>
<body><header>
<h1>El VarÃ³n Barber Shop</h1>
<nav>
<a href="#">Inicio</a>
<a href="#servicios">Servicios</a>
<a href="#galeria">GalerÃ­a</a>
<a href="#contacto">Contacto</a>
</nav>
</header><section class="hero">
<h2>Estilo de Hombre, Corte de VarÃ³n</h2>
<p>Donde cada corte es una obra de arte</p>
<a class="btn" href="#contacto">Reservar Cita</a>
</section><section class="section" id="servicios">
<h2>Servicios</h2>
<div class="services"><div class="card">
<h3>Corte Premium</h3>
<p>Estilo moderno o clÃ¡sico</p>
<div class="price">$5</div>
</div><div class="card">
<h3>Corte + Barba</h3>
<p>Perfilado profesional</p>
<div class="price">$8</div>
</div><div class="card">
<h3>DiseÃ±os</h
