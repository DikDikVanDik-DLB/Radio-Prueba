<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Radio DikDik FM</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Segoe UI',Arial,sans-serif;
    background:linear-gradient(135deg,#0f172a,#1e293b);
    color:white;
}

header{
    text-align:center;
    padding:60px 20px;
}

.logo{
    font-size:80px;
}

h1{
    margin-top:10px;
    font-size:3rem;
}

.subtitle{
    color:#cbd5e1;
    margin-top:10px;
}

.live{
    color:#ef4444;
    font-size:1.2rem;
    margin-top:20px;
    font-weight:bold;
}

.player{
    max-width:900px;
    margin:auto;
    padding:20px;
}

.player-card{
    background:#1e293b;
    border-radius:20px;
    padding:30px;
}

audio{
    width:100%;
    margin-top:20px;
}

.content{
    max-width:1200px;
    margin:auto;
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
    padding:20px;
}

.card{
    background:#1e293b;
    border-radius:15px;
    padding:25px;
}

.card h2{
    margin-bottom:15px;
    color:#22c55e;
}

.card p{
    margin-bottom:10px;
}

footer{
    background:#111827;
    text-align:center;
    padding:30px;
    margin-top:40px;
}

.social a{
    color:white;
    text-decoration:none;
    margin:0 10px;
}

.social a:hover{
    color:#22c55e;
}
</style>

</head>

<body>

<header>

<div class="logo">🎙️</div>

<h1>Radio DikDik FM</h1>

<p class="subtitle">
Música • Noticias • Entrevistas • Podcast
</p>

<div class="live">
🔴 TRANSMISIÓN EN VIVO
</div>

</header>

<div class="player">

<div class="player-card">

<h2>Escuchanos Online</h2>

<audio controls>
    <source src="https://ejemplo.com/live" type="audio/mpeg">
    Tu navegador no soporta audio HTML5.
</audio>

<p style="margin-top:15px;">
✅ Sitio web operativo
</p>

</div>

</div>

<section class="content">

<div class="card">
<h2>📻 Sobre Nosotros</h2>
<p>
Bienvenidos a Radio DikDik FM.
Un espacio pensado para compartir música,
información, entrevistas y contenidos especiales.
</p>
</div>

<div class="card">
<h2>🗓 Programación</h2>
<p>08:00 - Noticias</p>
<p>10:00 - Música Variada</p>
<p>14:00 - Entrevistas</p>
<p>18:00 - Actualidad</p>
<p>20:00 - Música Nocturna</p>
</div>

<div class="card">
<h2>📞 Contacto</h2>
<p>Email: contacto@radiodikdik.com</p>
<p>WhatsApp: +54 9 XXX XXX XXXX</p>
<p>Instagram: @radiodikdik</p>
</div>

</section>

<footer>

<h3>Radio DikDik FM</h3>

<div class="social">
<a href="#">Facebook</a>
<a href="#">Instagram</a>
<a href="#">YouTube</a>
</div>

<br>

<p>
© 2026 Radio DikDik FM
</p>

</footer>

</body>
</html>
