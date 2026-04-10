<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Services IT Premium</title>
<style>
body {
    margin: 0;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background: #0f172a;
    color: white;
}
header {
    background: linear-gradient(90deg, #0f172a, #1e293b);
    padding: 20px 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}
header h1 {
    color: #38bdf8;
}
nav a {
    color: white;
    margin-left: 20px;
    text-decoration: none;
    font-weight: 500;
}
.hero {
    text-align: center;
    padding: 100px 20px;
    background: radial-gradient(circle, #1e293b, #020617);
}
.hero h2 {
    font-size: 48px;
    margin-bottom: 20px;
}
.hero p {
    font-size: 20px;
    color: #94a3b8;
}
.btn {
    margin-top: 30px;
    padding: 15px 30px;
    background: #38bdf8;
    color: black;
    border: none;
    border-radius: 8px;
    font-size: 18px;
    cursor: pointer;
}
.services {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 20px;
    padding: 50px;
}
.card {
    background: #1e293b;
    padding: 25px;
    border-radius: 15px;
    transition: 0.3s;
}
.card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
}
.card h3 {
    color: #38bdf8;
}
.card p {
    color: #cbd5f5;
}
footer {
    text-align: center;
    padding: 30px;
    background: #020617;
    color: #64748b;
}
</style>
</head>
<body>
<header>
    <h1>IT Premium</h1>
    <nav>
        <a href="#">Accueil</a>
        <a href="#services">Services</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<section class="hero">
    <h2>Solutions IT & Cybersécurité haut de gamme</h2>
    <p>Sites web, automatisation, sécurité et assistance informatique</p>
    <button class="btn">Demander un devis</button>
</section>

<section id="services" class="services">

<div class="card">
<h3>Création de sites web</h3>
<p>Sites modernes, rapides et adaptés mobile avec automatisation, paiements et tableaux de bord.</p>
</div>

<div class="card">
<h3>Hébergement & gestion</h3>
<p>Mise en ligne, maintenance, sauvegardes et optimisation des performances.</p>
</div>

<div class="card">
<h3>Sécurité des comptes</h3>
<p>Protection contre piratage, audit sécurité et authentification forte.</p>
</div>

<div class="card">
<h3>Support IT</h3>
<p>Dépannage PC/Mac, installation de logiciels et optimisation système.</p>
</div>

<div class="card">
<h3>Récupération d'accès</h3>
<p>Aide officielle pour récupérer vos comptes et sécurisation après récupération.</p>
</div>

<div class="card">
<h3>Services sur mesure</h3>
<p>Réseau, automatisation, configuration et conseils technologiques.</p>
</div>

</section>

<footer>
<p>© 2026 IT Premium - Tous droits réservés</p>
</footer>

</body>
</html>
