# Berlini-Star
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Berlin Star Reinigung</title>
  <style>
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      color: #003366;
      background-color: #f4faff;
    }
    .hero {
      background: linear-gradient(rgba(0,0,0,0.4), rgba(0,0,0,0.4)), url('https://images.unsplash.com/photo-1600585154340-be6161a56a0c') center/cover no-repeat;
      color: white;
      padding: 100px 20px;
      text-align: center;
    }
    .hero .btn {
      margin-top: 20px;
      background: #00aaff;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
    }
    .navbar {
      background: #ffffffcc;
      position: sticky;
      top: 0;
      padding: 10px 0;
      text-align: center;
      box-shadow: 0 2px 5px rgba(0,0,0,0.05);
    }
    .navbar ul {
      list-style: none;
      padding: 0;
    }
    .navbar li {
      display: inline-block;
      margin: 0 15px;
    }
    .navbar a {
      text-decoration: none;
      color: #0077cc;
      font-weight: 500;
    }
    .section {
      padding: 50px 20px;
      max-width: 900px;
      margin: auto;
    }
    .section.light {
      background-color: #ffffff;
    }
    form input, form textarea {
      width: 100%;
      margin: 10px 0;
      padding: 12px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      background-color: #0077cc;
      color: white;
      padding: 12px 24px;
      border: none;
      border-radius: 4px;
      cursor: pointer;
    }
    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 20px;
    }
  </style>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@300;500;700&display=swap" rel="stylesheet">
</head>
<body>
  <header class="hero">
    <div class="overlay">
      <h1>Berlin Star Reinigung</h1>
      <p>Ihr kompetenter Partner für Reinigungsdienste und Facility Management</p>
      <a href="#angebote" class="btn">Angebot anfordern</a>
    </div>
  </header>

  <nav class="navbar">
    <ul>
      <li><a href="#about">Über Uns</a></li>
      <li><a href="#services">Dienstleistungen</a></li>
      <li><a href="#angebote">Angebot</a></li>
      <li><a href="#contact">Kontakt</a></li>
    </ul>
  </nav>

  <section id="about" class="section">
    <h2>Über Uns</h2>
    <p>Mit einem engagierten Team aus geschultem und zuverlässigem Personal stehen wir Ihnen für professionelle Reinigungsdienstleistungen zur Seite. Unsere oberste Priorität ist Ihre Zufriedenheit – deshalb arbeiten wir effizient, termintreu und mit höchster Sorgfalt...</p>
  </section>

  <section id="services" class="section light">
    <h2>Unsere Dienstleistungen</h2>
    <ul>
      <li>Bürogebäude und Großunternehmen</li>
      <li>Kindergärten und Bildungseinrichtungen</li>
      <li>Arztpraxen und medizinische Einrichtungen</li>
      <li>Industrie- und Lagerhallen</li>
      <li>Fenster- und Glasreinigung</li>
    </ul>
  </section>

  <section id="angebote" class="section">
    <h2>Angebot anfordern</h2>
    <form action="mailto:berlinstarreinigung@gmail.com" method="POST" enctype="text/plain">
      <input type="text" name="name" placeholder="Ihr Name" required />
      <input type="text" name="firma" placeholder="Firmenname" />
      <input type="email" name="email" placeholder="E-Mail" required />
      <textarea name="nachricht" placeholder="Ihre Nachricht" required></textarea>
      <button type="submit">Absenden</button>
    </form>
  </section>

  <section id="contact" class="section light">
    <h2>Kontakt</h2>
    <p>Email: berlinstarreinigung@gmail.com</p>
    <p>WhatsApp: <a href="https://wa.me/4917632157335" target="_blank">0176 32157335</a></p>
  </section>

  <footer>
    <p>© 2025 Berlin Star Reinigung – Alle Rechte vorbehalten.</p>
  </footer>
</body>
</html>
