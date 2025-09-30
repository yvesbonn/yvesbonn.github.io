# yvesbonn.github.io
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Boucherie du Terroir</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #fdfdfd;
      color: #333;
    }
    header {
      background: #8B0000;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 15px;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
      max-width: 1000px;
      margin: auto;
    }
    .produits {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
    }
    .carte {
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      background: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .carte img {
      max-width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #8B0000;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>🥩 Boucherie du Terroir</h1>
    <p>Viandes locales, fraîches et de qualité</p>
    <nav>
      <a href="#produits">Nos Produits</a>
      <a href="#apropos">À propos</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="produits">
    <h2>Nos produits</h2>
    <div class="produits">
      <div class="carte">
        <img src="https://via.placeholder.com/250x150" alt="Côte de bœuf">
        <h3>Côte de bœuf</h3>
        <p>Prix : 25 €/kg</p>
      </div>
      <div class="carte">
        <img src="https://via.placeholder.com/250x150" alt="Gigot d’agneau">
        <h3>Gigot d’agneau</h3>
        <p>Prix : 22 €/kg</p>
      </div>
      <div class="carte">
        <img src="https://via.placeholder.com/250x150" alt="Poulet fermier">
        <h3>Poulet fermier</h3>
        <p>Prix : 12 €/kg</p>
      </div>
    </div>
  </section>

  <section id="apropos">
    <h2>À propos</h2>
    <p>Notre boucherie familiale vous propose des viandes issues d’élevages locaux, sélectionnées avec soin pour garantir fraîcheur et saveur.</p>
  </section>

  <section id="contact">
    <h2>Contact</h2>
    <p>📍 Adresse : 123 Rue du Marché, 31000 Toulouse</p>
    <p>📧 Email : <a href="mailto:contact@boucherieduterroir.fr">contact@boucherieduterroir.fr</a></p>
    <p>📞 Téléphone : 06 00 00 00 00</p>
  </section>

  <footer>
    <p>© 2025 Boucherie du Terroir - Tous droits réservés</p>
  </footer>
</body>
</html>
