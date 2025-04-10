<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MAN-VTC | Chauffeur Privé</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #000;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    header img.logo {
      max-width: 200px;
      display: block;
      margin: 0 auto 10px;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #333;
    }
    nav a {
      color: #fff;
      padding: 14px 20px;
      text-decoration: none;
    }
    nav a:hover {
      background-color: #575757;
    }
    section {
      padding: 20px;
      max-width: 900px;
      margin: auto;
    }
    .contact-info {
      background-color: #fff;
      padding: 20px;
      margin-top: 20px;
      border-radius: 8px;
    }
    form {
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      margin-top: 20px;
    }
    input, textarea, button {
      width: 100%;
      padding: 10px;
      margin-top: 10px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background-color: #000;
      color: #fff;
      border: none;
      cursor: pointer;
    }
    button:hover {
      background-color: #444;
    }
    footer {
      background-color: #000;
      color: #fff;
      text-align: center;
      padding: 10px;
      margin-top: 40px;
    }
    .profile-img {
      width: 100%;
      max-width: 600px;
      margin: 20px auto;
      display: block;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <header>
    <img src="LOGO VTC.jpg" alt="Logo MAN-VTC" class="logo">
    <h1>MAN-VTC</h1>
    <p>Ponctualité, Confort, Excellence</p>
  </header>

  <nav>
    <a href="#services">Services</a>
    <a href="#contact">Contact</a>
    <a href="#reservation">Réservation</a>
  </nav>

  <section id="services">
    <h2>Nos Services</h2>
    <p>MAN-VTC vous propose des trajets confortables, ponctuels et sécurisés dans toute la région. Transferts aéroports, gares, événements privés ou professionnels.</p>
    <img src="photo profile.jpg" alt="Voiture MAN VTC" class="profile-img">
  </section>

  <section id="contact" class="contact-info">
    <h2>Contact</h2>
    <p>Téléphone : <a href="tel:+33744883147">07 44 88 31 47</a></p>
    <p>Email : <a href="mailto:manvtc85@gmail.com">manvtc85@gmail.com</a></p>
  </section>

  <section id="reservation">
    <h2>Réserver un trajet</h2>
    <form>
      <label for="name">Nom</label>
      <input type="text" id="name" name="name" required>

      <label for="phone">Téléphone</label>
      <input type="tel" id="phone" name="phone" required>

      <label for="details">Détails du trajet</label>
      <textarea id="details" name="details" rows="4" required></textarea>

      <button type="submit">Envoyer</button>
    </form>
  </section>

  <footer>
    <p>&copy; 2025 MAN-VTC. Tous droits réservés.</p>
  </footer>

