# meine-website
Swisslimosvip.com
<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8" />
  <title>Meine Website</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
      background: #f4f4f5;
      color: #111827;
      line-height: 1.6;
    }
    header {
      background: #111827;
      color: white;
      padding: 2rem 1.5rem;
      text-align: center;
    }
    header h1 {
      font-size: 2.2rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1rem;
      opacity: 0.9;
    }
    nav {
      background: #1f2933;
      padding: 0.5rem 1.5rem;
      text-align: center;
    }
    nav a {
      color: #e5e7eb;
      text-decoration: none;
      margin: 0 0.75rem;
      font-size: 0.95rem;
    }
    nav a:hover {
      text-decoration: underline;
    }
    .container {
      max-width: 900px;
      margin: 1.5rem auto;
      padding: 0 1.5rem 2rem;
    }
    .card {
      background: white;
      border-radius: 0.75rem;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      box-shadow: 0 10px 25px rgba(15, 23, 42, 0.08);
    }
    .card h2 {
      font-size: 1.4rem;
      margin-bottom: 0.75rem;
    }
    .card p {
      margin-bottom: 0.5rem;
      font-size: 0.98rem;
    }
    .btn {
      display: inline-block;
      margin-top: 0.75rem;
      padding: 0.6rem 1.2rem;
      border-radius: 999px;
      border: none;
      background: #111827;
      color: white;
      cursor: pointer;
      font-size: 0.95rem;
      text-decoration: none;
    }
    .btn:hover {
      opacity: 0.9;
    }
    footer {
      text-align: center;
      font-size: 0.8rem;
      color: #6b7280;
      padding: 1.5rem;
    }
    @media (max-width: 600px) {
      header h1 { font-size: 1.7rem; }
      .card { padding: 1.2rem; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Willkommen auf meiner Website</h1>
    <p>Hier kommt dein Slogan oder eine kurze Beschreibung hin.</p>
  </header>

  <nav>
    <a href="#about">Über mich</a>
    <a href="#projects">Projekte</a>
    <a href="#contact">Kontakt</a>
  </nav>

  <main class="container">
    <section id="about" class="card">
      <h2>Über mich</h2>
      <p>Hi! Ich bin ... (hier deinen Namen eintragen 😄).</p>
      <p>Schreibe hier ein paar Sätze über dich, deine Hobbys oder was du mit dieser Website zeigen möchtest.</p>
    </section>

    <section id="projects" class="card">
      <h2>Projekte</h2>
      <p>Hier kannst du deine Arbeiten, Ideen oder Ziele vorstellen.</p>
      <ul>
        <li>Projekt 1 – kurz erklären</li>
        <li>Projekt 2 – kurz erklären</li>
        <li>Projekt 3 – kurz erklären</li>
      </ul>
    </section>

    <section id="contact" class="card">
      <h2>Kontakt</h2>
      <p>Du kannst mich erreichen unter:</p>
      <p><strong>E-Mail:</strong> deine@mailadresse.de</p>
      <p>Oder verlinke hier deine Social-Media-Profile.</p>
      <a class="btn" href="mailto:deine@mailadresse.de">Jetzt eine E-Mail schreiben</a>
    </section>
  </main>

  <footer>
    © <span id="year"></span> Dein Name – Alle Rechte vorbehalten.
  </footer>

  <script>
    // Aktuelles Jahr automatisch setzen
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>


