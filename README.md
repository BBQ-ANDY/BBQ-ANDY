<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <title>BBQ-ANDY | Smoked Roastbeef & Pastrami</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body {
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
            background-color: #0f0f0f;
            color: #f2f2f2;
        }
        header {
            background: linear-gradient(rgba(0,0,0,0.7), rgba(0,0,0,0.7)),
                        url("images/smoker_fleisch.jpg") center/cover;
            padding: 100px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 3.2em;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }
        header p {
            font-size: 1.3em;
            color: #ff9800;
        }
        section {
            max-width: 1100px;
            margin: auto;
            padding: 60px 20px;
        }
        h2 {
            color: #ff9800;
            margin-bottom: 30px;
            text-align: center;
        }
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 25px;
        }
        .card {
            background: #1c1c1c;
            border-radius: 10px;
            overflow: hidden;
        }
        .card img {
            width: 100%;
            display: block;
        }
        .card div {
            padding: 20px;
        }
        footer {
            background: #000;
            text-align: center;
            padding: 30px 15px;
            font-size: 0.9em;
        }
        a {
            color: #ff9800;
            text-decoration: none;
        }
    </style>
</head>

<body>

<header>
    <h1>BBQ-ANDY</h1>
    <p>Low & Slow · Smoked Roastbeef · Smoked Pastrami</p>
</header>

<section>
    <h2>Über BBQ-ANDY</h2>
    <p style="text-align:center; max-width:800px; margin:auto;">
        Willkommen bei <strong>BBQ-ANDY</strong>.  
        Hier dreht sich alles um echtes BBQ – Geduld, Rauch und kompromisslosen Geschmack.
        Mein Fokus liegt auf <strong>gesmoktem Roastbeef</strong> und
        <strong>hausgemachtem Pastrami</strong> – vom Rohfleisch bis zur perfekten Scheibe.
    </p>
</section>

<section>
    <h2>Smoked Roastbeef</h2>
    <div class="grid">
        <div class="card">
            <img src="images/roastbeef_platte.jpg" alt="Smoked Roastbeef Platte">
            <div>Saftig gesmoktes Roastbeef, dünn aufgeschnitten</div>
        </div>
        <div class="card">
            <img src="images/roastbeef_nah.jpg" alt="Roastbeef Anschnitt">
            <div>Perfekter Rauchring & zarter Kern</div>
        </div>
    </div>
</section>

<section>
    <h2>Smoked Pastrami</h2>
    <div class="grid">
        <div class="card">
            <img src="images/pastrami_ganz.jpg" alt="Pastrami im Smoker">
            <div>Gepökelt, gerubbt und langsam geräuchert</div>
        </div>
        <div class="card">
            <img src="images/pastrami_scheiben.jpg" alt="Pastrami Scheiben">
            <div>Aromatisch, saftig und intensiv im Geschmack</div>
        </div>
    </div>
</section>

<section>
    <h2>Kontakt</h2>
    <p style="text-align:center;">
        📧 <a href="mailto:andy.jacky4@gmail.com">andy.jacky4@gmail.com</a>
    </p>
</section>

<footer>
    © 2026 BBQ-ANDY · Smoked with Passion
</footer>

</body>
</html>
