<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Art Friseur</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f4f4;
}

nav {
    background: #111;
    color: white;
    display: flex;
    justify-content: space-between;
    padding: 15px 20px;
    position: sticky;
    top: 0;
}

nav a {
    color: white;
    margin: 0 10px;
    text-decoration: none;
}

header {
    background: linear-gradient(135deg, #111, #444);
    color: white;
    text-align: center;
    padding: 60px 20px;
}

section {
    max-width: 900px;
    margin: auto;
    background: white;
    padding: 20px;
    margin-top: 20px;
    border-radius: 10px;
}

.badge {
    display: inline-block;
    background: #eee;
    padding: 8px 12px;
    margin: 5px;
    border-radius: 20px;
}

img {
    width: 100%;
    border-radius: 10px;
    margin-top: 10px;
}

.whatsapp {
    position: fixed;
    bottom: 20px;
    right: 20px;
    background: #25D366;
    color: white;
    padding: 15px;
    border-radius: 50px;
    text-decoration: none;
}
</style>
</head>

<body>

<nav>
    <div><b>For Art Friseur</b></div>
    <div>
        <a href="#home">Home</a>
        <a href="#about">Über uns</a>
        <a href="#contact">Kontakt</a>
    </div>
</nav>

<header id="home">
    <h1>For Art Friseur</h1>
    <p>Friseur in Linz – Zeppelinstraße 21</p>
</header>

<section id="about">

<h2>Über uns</h2>
<p>
Moderner Friseursalon in Linz mit Fokus auf Stil, Qualität und persönliche Betreuung.
</p>

<span class="badge">🚻 WC</span>
<span class="badge">💳 Nur Barzahlung</span>
<span class="badge">👶 Kinderfreundlich</span>
<span class="badge">📅 Ohne Termin</span>
<span class="badge">🅿️ Gratis Parkplatz</span>

<h2>Leistungen</h2>
<ul>
<li>Damenhaarschnitt</li>
<li>Herrenhaarschnitt</li>
<li>Styling</li>
<li>Moderne Looks</li>
</ul>

</section>

<section>
<h2>Standortbeschreibung</h2>

<p><b>Adresse:</b> Zeppelinstraße 21, 4030 Linz</p>

<p>
🚗 Gut erreichbar mit dem Auto, Parkplätze in der Nähe vorhanden.<br><br>

🚌 Öffentliche Verkehrsmittel sind in der Umgebung verfügbar.<br><br>

🚶 Zentrale Lage – leicht zu Fuß erreichbar.<br><br>

💡 Empfehlung: Termin vorher vereinbaren.
</p>

<h2>Standort (Google Maps)</h2>

<iframe
src="https://www.google.com/maps?q=Zeppelinstra%C3%9Fe%2021%2C%204030%20Linz&output=embed"
height="300"
style="border:0; border-radius:10px; width:100%;">
</iframe>

</section>

<section>
<h2>Frisuren Galerie</h2>

<img src="https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9">
<img src="https://images.unsplash.com/photo-1519699047748-de8e457a634e">
<img src="https://images.unsplash.com/photo-1521590832167-7bcbfaa6381f">

</section>

<section id="contact">
<h2>Kontakt</h2>

<p><b>Adresse:</b> Zeppelinstraße 21, 4030 Linz</p>
<p><b>Telefon:</b> 0660 6645055</p>

<form action="mailto:deinemail@example.com">
<input type="text" placeholder="Name" required>
<input type="email" placeholder="E-Mail" required>
<textarea placeholder="Nachricht"></textarea>
<button type="submit">Senden</button>
</form>

</section>

<a class="whatsapp" href="https://wa.me/436600000000">
💬 WhatsApp
</a>

</body>
</html>
