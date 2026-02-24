<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<title>Mis ojos bonitos por siempre</title>

<style>
body{
    margin:0;
    padding:0;
    background:linear-gradient(to bottom,#000000,#1a001a);
    overflow-x:hidden;
    font-family: Arial, sans-serif;
    color:white;
    text-align:center;
}

/* Nombre arriba */
.nombre{
    position:absolute;
    top:5%;
    width:100%;
    font-size:2em;
    color:#ff99cc;
    animation:flotarNombre 6s ease-in-out infinite;
}

@keyframes flotarNombre{
    0%,100%{transform:translateY(0);}
    50%{transform:translateY(15px);}
}

/* Título */
h1{
    margin-top:18%;
    font-size:3em;
    animation:latido 1.5s infinite;
}

@keyframes latido{
    0%{transform:scale(1);}
    50%{transform:scale(1.1);}
    100%{transform:scale(1);}
}

/* Corazones */
.corazon{
    position:absolute;
    color:#ff4d6d;
    font-size:20px;
    animation:flotar 6s linear infinite;
}

@keyframes flotar{
    0%{transform:translateY(100vh);opacity:1;}
    100%{transform:translateY(-10vh);opacity:0;}
}

/* Fecha */
.fecha{
    margin-top:50px;
    font-size:1em;
    color:#888;
}

/* Playlist estilo cine */
.playlist{
    display:flex;
    flex-direction:column;
    gap:15px;
    align-items:center;
    margin-top:40px;
}

.capitulo{
    margin-top:25px;
    font-weight:normal;
    color:#ff99cc;
    letter-spacing:2px;
}

.botonCine{
    display:inline-block;
    padding:15px 30px;
    background:linear-gradient(45deg,#ff4d6d,#ff1a75);
    color:white;
    text-decoration:none;
    border-radius:50px;
    font-size:1.1em;
    box-shadow:0 0 20px rgba(255,77,109,0.6);
    transition:0.4s;
}

.botonCine:hover{
    transform:scale(1.1);
    box-shadow:0 0 35px rgba(255,77,109,0.9);
}

/* Frase */
.frase{
    margin-top:30px;
    font-size:1.2em;
    color:#dddddd;
    animation:fadeIn 3s ease-in-out;
}

@keyframes fadeIn{
    from{opacity:0;}
    to{opacity:1;}
}
</style>
</head>

<body>

<div class="nombre">Ferchis ♾️</div>

<h1>Mis ojos bonitos por siempre 💗</h1>

<div class="frase">
    Algunas historias no se explican…<br>
    Se sienten.<br><br>
    Esta es la nuestra.
</div>

<div class="playlist">

    <h2 class="capitulo">Capítulo I — Ella es diferente</h2>
    <a href="https://www.youtube.com/watch?v=erC4wgk-QT8&list=RDerC4wgk-QT8&start_radio=1" target="_blank" class="botonCine">🎵 Ella es una G</a>

    <h2 class="capitulo">Capítulo II — Déjate querer</h2>
    <a href="https://www.youtube.com/watch?v=vbHU5vUwS-A&list=RDvbHU5vUwS-A&start_radio=1" target="_blank" class="botonCine">💗 Déjate querer — Santa Grifa</a>

    <h2 class="capitulo">Capítulo III — Entre sábanas blancas</h2>
    <a href="https://www.youtube.com/watch?v=lRP7b8bl6l4&list=RDlRP7b8bl6l4&start_radio=1" target="_blank" class="botonCine">🌙 Sábanas blancas — Santa Grifa</a>

    <h2 class="capitulo">Capítulo IV — Si tuviera una fortuna</h2>
    <a href="https://www.youtube.com/watch?v=v4xts8nEOfk&list=RDv4xts8nEOfk&start_radio=1" target="_blank" class="botonCine">✨ Si tuviera una fortuna — Santa Grifa</a>

    <h2 class="capitulo">Capítulo V — ¿Cómo le digo?</h2>
    <a href="https://www.youtube.com/watch?v=_I_zjqbPwOE&list=RD_I_zjqbPwOE&start_radio=1" target="_blank" class="botonCine">🔥 Como le digo — Khea</a>

    <h2 class="capitulo">Capítulo Final — Mi Perla</h2>
    <a href="https://www.youtube.com/watch?v=AvtYyTIfcHY&list=RDAvtYyTIfcHY&start_radio=1" target="_blank" class="botonCine">💎 Perla — Cro</a>

</div>

<div class="fecha">24 • 01 • 2025</div>

<script>
function crearCorazon(){
    const corazon = document.createElement("div");
    corazon.classList.add("corazon");
    corazon.innerHTML = "💗";
    corazon.style.left = Math.random()*100 + "vw";
    corazon.style.fontSize = Math.random()*20 + 15 + "px";
    corazon.style.animationDuration = Math.random()*3 + 3 + "s";
    document.body.appendChild(corazon);

    setTimeout(()=>{
        corazon.remove();
    },6000);
}
setInterval(crearCorazon,300);
</script>

</body>
</html>
