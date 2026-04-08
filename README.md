# Vehiculos-WW1
Trabajo informatica
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Vehículos de la Primera Guerra Mundial</title>
    <link rel="stylesheet" href="styles.css">
  <style> 
body {
    font-family: "Courier New", Courier, monospace;
    background-color: #e6dcc3; antiguo */
    color: #2b2b2b; 
    margin: 0;
    padding: 0;
    background-image: repeating-linear-gradient(
        0deg,
        rgba(255,255,255,0.02),
        rgba(255,255,255,0.02) 1px,
        transparent 1px,
        transparent 4px
    ); 
}


header {
    background-color: #bcbcbc; envejecido */
    text-align: center;
    padding: 50px 10px;
    border-bottom: 4px solid #7a7a7a;
    box-shadow: inset 0 -2px 0 rgba(0,0,0,0.1);
}

header h1 {
    font-size: 3em;
    color: #1f1f1f;
    margin-bottom: 10px;
    text-shadow: 1px 1px 0 #dcdcdc;
    letter-spacing: 2px;
}

header p {
    font-size: 1.3em;
    color: #3a3a3a;
    font-style: italic;
}

nav {
    background-color: #a8a8a8;
    border-bottom: 3px solid #7a7a7a;
}

nav ul {
    list-style: none;
    display: flex;
    justify-content: center;
    padding: 12px 0;
    margin: 0;
}

nav ul li {
    margin: 0 25px;
}

nav ul li a {
    text-decoration: none;
    color: #1f1f1f;
    font-weight: bold;
    text-transform: uppercase;
    letter-spacing: 1px;
    transition: color 0.3s, text-shadow 0.3s;
}

nav ul li a:hover {
    color: #4b4b4b;
    text-shadow: 1px 1px 0 #e0e0e0;
}


.divider {
    border-top: 3px dashed #7a7a7a;
    margin: 50px 0;
}


section {
    max-width: 900px;
    margin: 0 auto;
    padding: 30px 25px;
    background-color: #e0e0e0; 
    border-radius: 6px;
    box-shadow: 0 0 15px rgba(0,0,0,0.15);
    border-left: 6px solid #7a7a7a;
}

section h2 {
    color: #1f1f1f;
    border-bottom: 3px dotted #7a7a7a;
    padding-bottom: 10px;
    margin-bottom: 25px;
}
article {
    margin-bottom: 35px;
}

article h3 {
    color: #3a3a3a;
    margin-bottom: 14px;
    text-transform: uppercase;
    letter-spacing: 0.5px;
}

article p {
    line-height: 1.8;
    color: #2b2b2b;
}

.article-divider {
    border-top: 1px dashed #7a7a7a;
    margin: 20px 0;
}
img {
    max-width: 30%;
    height: auto;
    display: block;
    margin: 15px 0 20px 0;
    border: 2px solid #7a7a7a;
    border-radius: 2px;
    box-shadow: 0 4px 6px rgba(0,0,0,0.2);
    filter: grayscale(100%) contrast(1.2) brightness(0.9); 
}
table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 25px;
    background-color: #e0e0e0;
    border: 2px solid #7a7a7a;
}

table th, table td {
    padding: 12px;
    text-align: left;
    border: 1px solid #7a7a7a;
}

table th {
    background-color: #bcbcbc;
    color: #1f1f1f;
}

table tr:nth-child(even) {
    background-color: #d5d5d5;
}
iframe {
    display: block;
    margin: 0 auto;
    max-width: 100%;
    border: 3px solid #7a7a7a;
    border-radius: 4px;
    box-shadow: 0 5px 12px rgba(0,0,0,0.15);
    filter: grayscale(100%);
}
footer {
    background-color: #bcbcbc;
    text-align: center;
    padding: 25px 10px;
    border-top: 4px solid #7a7a7a;
    color: #3a3a3a;
    font-size: 1em;
} 
</style>
</head>

<body>

<header>
    <h1>Vehículos de la Primera Guerra Mundial</h1>
    <p>Clasificación de los vehículos militares</p>
</header>

<nav>
    <ul>
        <li><a href="#Descripcion">Descripción</a></li>
        <li><a href="#tipos">Tipos de vehículos</a></li>
        <li><a href="#video">Video</a></li>
        <li><a href="#tabla">Tabla</a></li>
    </ul>
</nav>

<div class="divider"></div>

<section id="Descripcion">
    <h2>Descripción</h2>

    <p>
    Durante la Primera Guerra Mundial, los vehículos jugaron un papel crucial en el transporte de tropas, suministros y armas. 
    Permitieron mayor movilidad en un conflicto caracterizado por las trincheras y los campos de batalla extensos.
    <br><br>
    Países como Reino Unido, Alemania y Francia desarrollaron vehículos blindados, camiones y tanques que revolucionaron la guerra mecanizada.
    </p>
</section>

<div class="divider"></div>

<section id="tipos">
    <h2>Tipos de Vehículos</h2>

    <article>
        <h3>Tanque Británico Mark I</h3>

        <img src="https://www.super-hobby.es/zdjecia/3/0/9/3585_rd.jpg" alt="Tanque Mark I">

        <p>
        El Mark I fue el primer tanque utilizado en combate por el ejército británico en 1916. 
        Diseñado para romper las líneas de trincheras, tenía orugas para atravesar terrenos difíciles.
        </p>
        <div class="article-divider"></div>
    </article>

    <article>
        <h3>Tanque Alemán A7V</h3>

        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRHOjRoLPTMIGg_6nYqDfNkD85wHJ8tsCDcgg&s" alt="Tanque A7V">

        <p>
        El A7V fue el único tanque alemán desplegado en la Primera Guerra Mundial. 
        Tenía un gran cañón frontal y espacio para transportar hasta 18 soldados.
        </p>
        <div class="article-divider"></div>
    </article>

    <article>
        <h3>Camión de Transporte Renault EG</h3>

        <img src="https://www.diariodetransporte.com/wp-content/uploads/2025/08/renault14.jpg" alt="Camión Renault EG">

        <p>
        Este camión francés se utilizó para transportar suministros y tropas rápidamente detrás del frente de batalla. 
        Era conocido por su durabilidad en terrenos difíciles.
        </p>
    </article>
</section>

<div class="divider"></div>

<section id="video">
    <h2>Video</h2>
    <iframe width="560" height="315" src="https://www.youtube.com/embed/pvhbOqcjcns?si=9O239vbISAC-ZspE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</section>

<div class="divider"></div>

<section id="tabla">
    <h2>Tabla de vehiculos de la WW1</h2>

    <table border="1" cellpadding="10">
        <tr>
            <th>País</th>
            <th>Modelo</th>
            <th>Año</th>
            <th>Tipo</th>
            <th>Peso aprox.</th>
            <th>Tripulación</th>
            <th>Armamento</th>
            <th>Velocidad máx.</th>
            <th>Uso principal</th>
            <th>Descripción</th>
        </tr>

        <tr>
            <td>Reino Unido</td>
            <td>Mark I</td>
            <td>1916</td>
            <td>Tanque</td>
            <td>28 t</td>
            <td>8</td>
            <td>2 cañones de 6 libras, 4 ametralladoras</td>
            <td>6 km/h</td>
            <td>Asalto de trincheras</td>
            <td>Primer tanque usado en combate, diseñado para romper trincheras y obstáculos.</td>
        </tr>

        <tr>
            <td>Alemania</td>
            <td>A7V</td>
            <td>1918</td>
            <td>Tanque</td>
            <td>30 t</td>
            <td>18</td>
            <td>1 cañón de 57 mm, 6 ametralladoras</td>
            <td>15 km/h</td>
            <td>Apoyo a infantería</td>
            <td>Tanque alemán con gran capacidad de transporte de soldados y potencia de fuego frontal.</td>
        </tr>

        <tr>
            <td>Francia</td>
            <td>Renault FT</td>
            <td>1917</td>
            <td>Tanque ligero</td>
            <td>6,5 t</td>
            <td>2</td>
            <td>1 cañón de 37 mm o ametralladora</td>
            <td>7 km/h</td>
            <td>Reconocimiento y combate ligero</td>
            <td>Tanque ligero con torreta giratoria, muy influyente en diseños posteriores.</td>
        </tr>

        <tr>
            <td>Francia</td>
            <td>Renault EG</td>
            <td>1915</td>
            <td>Camión</td>
            <td>3 t</td>
            <td>2</td>
            <td>N/A</td>
            <td>25 km/h</td>
            <td>Transporte de suministros y tropas</td>
            <td>Camión robusto y confiable usado detrás del frente para transporte logístico.</td>
        </tr>

        <tr>
            <td>Reino Unido</td>
            <td>Rolls-Royce Armoured Car</td>
            <td>1914</td>
            <td>Vehículo blindado</td>
            <td>4,7 t</td>
            <td>3</td>
            <td>1 ametralladora</td>
            <td>72 km/h</td>
            <td>Patrullas y reconocimiento</td>
            <td>Vehículo blindado ligero usado en misiones de patrulla y apoyo rápido.</td>
        </tr>

        <tr>
            <td>Alemania</td>
            <td>DKW Motos Blindadas</td>
            <td>1916</td>
            <td>Moto blindada</td>
            <td>350 kg</td>
            <td>1</td>
            <td>N/A</td>
            <td>50 km/h</td>
            <td>Mensajería y reconocimiento</td>
            <td>Moto adaptada con blindaje ligero para transporte rápido de mensajes y exploración.</td>
        </tr>

        <tr>
            <td>Francia</td>
            <td>Citroën-Kégresse P17</td>
            <td>1918</td>
            <td>Vehículo semioruga</td>
            <td>2,5 t</td>
            <td>4</td>
            <td>N/A</td>
            <td>20 km/h</td>
            <td>Transporte en terrenos difíciles</td>
            <td>Vehículo experimental de tracción híbrida para transporte en terreno irregular.</td>
        </tr>

        <tr>
            <td>Reino Unido</td>
            <td>Whippet Mk A</td>
            <td>1917</td>
            <td>Tanque medio</td>
            <td>14 t</td>
            <td>3</td>
            <td>2 ametralladoras</td>
            <td>13 km/h</td>
            <td>Explotación de rupturas de líneas enemigas</td>
            <td>Tanque rápido y más ágil que el Mark I, diseñado para apoyar a la infantería después de la ruptura inicial.</td>
        </tr>

    </table>
</section>

<div class="divider"></div>

<footer>
    <p>Trabajo de informática</p>
</footer>

</body>
</html>
