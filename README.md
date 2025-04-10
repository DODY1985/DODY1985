<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>VTC Prestige</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; }
    header { background: #111; color: white; padding: 20px; text-align: center; }
    nav a { color: white; margin: 0 15px; text-decoration: none; }
    section { padding: 40px 20px; }
    .services, .tarifs { background: #f5f5f5; }
    form { max-width: 500px; margin: auto; display: flex; flex-direction: column; }
    input, textarea { padding: 10px; margin: 10px 0; }
    button { padding: 10px; background: #111; color: white; border: none; cursor: pointer; }
    footer { text-align: center; padding: 20px; background: #222; color: white; }
  </style>
</head>
<body>
  <header>
    <h1>VTC Prestige</h1>
    <nav>
      <a href="#services">Services</a>
      <a href="#tarifs">Tarifs</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section>
    <h2>Bienvenue chez VTC Prestige</h2>
    <p>Service de transport privé haut de gamme. Ponctualité, confort et sécurité garantis.</p>
  </section>

  <section id="services" class="services">
    <h2>Nos Services</h2>
    <ul>
      <li>Transfert aéroport</li>
      <li>Chauffeur privé pour événements</li>
      <li>Longues distances</li>
      <li>Disponibilité 24h/24 - 7j/7</li>
    </ul>
  </section>

  <section id="tarifs" class="tarifs">
    <h2>Tarifs indicatifs</h2>
    <p>Tarif Paris > CDG : à partir de 60€</p>
    <p>Tarif Paris > Orly : à partir de 50€</p>
    <p>Contactez-nous pour un devis personnalisé</p>
  </section>

  <section id="contact">
    <h2>Contact & Réservation</h2>
    <form>
      <input type="text" placeholder="Nom" required>
      <input type="email" placeholder="Email" required>
      <input type="tel" placeholder="Téléphone" required>
      <textarea placeholder="Votre message ou demande de réservation" required></textarea>
      <button type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 VTC Prestige - Tous droits réservés</p>
  </footer>
</body>
</html>


