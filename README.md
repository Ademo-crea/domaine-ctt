<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Domaine des Coteaux de Château-Thierry</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">

<style>

* {margin:0;padding:0;box-sizing:border-box;}

body {
    font-family: 'Open Sans', sans-serif;
    background: #f8f7f3;
    color: #2c2c2c;
}

nav {
    position: fixed;
    width: 100%;
    background: rgba(31,61,43,0.95);
    padding: 15px 0;
    z-index: 1000;
    text-align: center;
}

nav a {
    color: white;
    margin: 0 20px;
    text-decoration: none;
    font-weight: 600;
}

/* HERO IMAGE VIN */
.hero {
    height: 100vh;
    background: url('https://images.unsplash.com/photo-1510626176961-4b57d4fbad03') center/cover no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
    color: white;
}

.hero h1 {
    font-family: 'Playfair Display', serif;
    font-size: 4em;
}

section {
    padding: 100px 20px;
    max-width: 1100px;
    margin: auto;
}

h2 {
    font-family: 'Playfair Display', serif;
    color: #1f3d2b;
    margin-bottom: 20px;
    font-size: 2.5em;
}

.card {
    background: white;
    padding: 30px;
    margin-top: 30px;
    border-radius: 12px;
    box-shadow: 0 10px 25px rgba(0,0,0,0.08);
    transition: transform 0.3s;
}

.card:hover {
    transform: translateY(-5px);
}

.grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 30px;
}

.cta {
    background: #1f3d2b;
    color: white;
    text-align: center;
    padding: 80px 20px;
}

button {
    margin-top: 20px;
    padding: 15px 30px;
    border: none;
    background: #c5a46d;
    color: white;
    font-weight: bold;
    border-radius: 5px;
}

footer {
    background: #1f3d2b;
    color: white;
    text-align: center;
    padding: 30px;
}

@media(max-width: 800px) {
    .grid {grid-template-columns: 1fr;}
    .hero h1 {font-size: 2.5em;}
}

</style>
</head>

<body>

<nav>
    <a href="#accueil">Accueil</a>
    <a href="#domaine">Domaine</a>
    <a href="#vins">Vins</a>
    <a href="#contact">Contact</a>
</nav>

<div class="hero" id="accueil">
    <div>
        <h1>Domaine des Coteaux</h1>
        <p>Chardonnay • Effervescent • Excellence</p>
    </div>
</div>

<section id="domaine">
    <h2>Le Domaine</h2>

    <div class="grid">
        <div class="card">
            <h3>Le fondateur</h3>
            <p>Benoît Hubert développe un projet viticole basé sur précision scientifique et qualité.</p>
        </div>

        <div class="card">
            <h3>Le terroir</h3>
            <p>Coteaux calcaires et climat tempéré offrent des conditions idéales au Chardonnay.</p>
        </div>
    </div>
</section>

<section id="vins">
    <h2>Nos Vins</h2>

    <div class="card">
        <h3>Cuvée Initiale</h3>
        <p>Un Chardonnay effervescent frais et accessible.</p>
        <ul>
            <li>Arômes : agrumes, fleurs blanches</li>
            <li>Bouche : vive et légère</li>
            <li>Prix estimé : 12€</li>
        </ul>
    </div>

    <div class="card">
        <h3>Cuvée Prestige</h3>
        <p>Une cuvée plus complexe, idéale pour les grandes occasions.</p>
        <ul>
            <li>Arômes : brioche, fruits mûrs</li>
            <li>Bouche : ample et élégante</li>
            <li>Prix estimé : 18€</li>
        </ul>
    </div>

    <div class="card">
        <h3>Cuvée Terroir</h3>
        <p>Expression pure du sol calcaire de Château-Thierry.</p>
        <ul>
            <li>Arômes : minéralité, citron</li>
            <li>Bouche : tendue et saline</li>
            <li>Prix estimé : 22€</li>
        </ul>
    </div>

</section>

<div class="cta">
    <h2>Découvrir le domaine</h2>
    <p>Dégustations prochainement disponibles</p>
    <button>Nous contacter</button>
</div>

<section id="contact">
    <h2>Contact</h2>
    <p>📍 Aisne – France</p>
    <p>📧 contact@domaine-ctt.fr</p>
    <p>📞 06 00 00 00 00</p>
</section>

<footer>
    <p>© 2026 Domaine des Coteaux de Château-Thierry – Benoît Hubert</p>
</footer>

</body>
</html>
