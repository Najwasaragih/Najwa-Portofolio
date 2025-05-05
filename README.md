<!DOCTYPE html>
<html lang="de">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>3D Designer Portfolio</title>
  <link rel="stylesheet" href="styles.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f5f5f5;
      color: #333;
    }

    header {
      background: #1e1e1e;
      color: white;
      padding: 2rem;
      text-align: center;
    }

    nav a {
      margin: 0 1rem;
      color: #ccc;
      text-decoration: none;
    }

    nav a:hover {
      color: white;
    }

    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 1.5rem;
    }

    .project {
      background: white;
      border-radius: 12px;
      padding: 1rem;
      box-shadow: 0 2px 8px rgba(0,0,0,0.1);
      text-align: center;
    }

    .project img {
      width: 100%;
      border-radius: 8px;
    }

    footer {
      text-align: center;
      padding: 1rem;
      background: #1e1e1e;
      color: white;
    }

    ul {
      list-style-type: none;
      padding: 0;
    }

    ul li {
      background: white;
      margin: 0.5rem 0;
      padding: 0.5rem 1rem;
      border-radius: 8px;
      box-shadow: 0 1px 4px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <header>
    <h1>Hallo, ich bin Najwa Pelagia Saragih</h1>
    <p>Angehende Designerin auf der Suche nach einem Ausbildungsplatz</p>
    <nav>
      <a href="#about">Über mich</a>
      <a href="#portfolio">Portfolio</a>
      <a href="#skills">Software</a>
      <a href="#contact">Kontakt</a>
    </nav>
  </header>

  <section id="about">
    <h2>Über mich</h2>
    <p>Ich bin eine engagierte und kreative Absolventin einer Multimedia-Berufsschule mit einem starken Interesse an visueller Gestaltung und digitalem Design. Während meiner Ausbildung habe ich umfangreiche Kenntnisse in der Arbeit mit verschiedenen Design- und Animationsprogrammen erworben, insbesondere in den Bereichen 3D-Modellierung, Videobearbeitung und Grafikdesign.</p>
    <p>Ich liebe es, Ideen visuell umzusetzen und mit modernen Tools wie Autodesk Maya, Blender oder Adobe Premiere Pro zu experimentieren. Mein Ziel ist es, durch eine Ausbildung als 3D-Designerin nicht nur mein technisches Wissen zu vertiefen, sondern auch aktiv an spannenden, realen Projekten mitzuwirken.</p>
    <p>Ich gelte als teamfähig, lernbereit und detailorientiert – Eigenschaften, die ich bei verschiedenen Schulprojekten und Praktika erfolgreich einsetzen konnte. Mit Leidenschaft und Neugier möchte ich den nächsten Schritt in meiner kreativen Laufbahn machen.</p>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="gallery">
      <div class="project">
        <img src="images/project1.jpg" alt="Premiere Pro Projekt">
        <h3>Videobearbeitung mit Adobe Premiere Pro</h3>
        <p>Videoschnitt-Projekt mit Fokus auf Szenenübergänge, Titelanimation und Soundeffekte.</p>
      </div>
      <div class="project">
        <img src="images/project2.jpg" alt="Maya Sculpting">
        <h3>3D-Sculpting mit Autodesk Maya</h3>
        <p>Modellierung eines Charakters in Maya, Schwerpunkt auf organische Formen und Details.</p>
      </div>
      <div class="project">
        <img src="images/project3.jpg" alt="Photoshop Broschüre">
        <h3>Schulbroschüre mit Adobe Photoshop</h3>
        <p>Design und Layout einer informativen Broschüre für eine Schule, inklusive Typografie und Farbschema.</p>
      </div>
    </div>
  </section>

  <section id="skills">
    <h2>Software & Tools</h2>
    <ul>
      <li>Adobe Premiere Pro</li>
      <li>Autodesk Maya</li>
      <li>Adobe Photoshop</li>
      <li>Blender</li>
    </ul>
  </section>

  <section id="contact">
    <h2>Kontakt</h2>
    <p>Email: najwapelagiasaragih@gmail.com</p>
    <p>WhatsApp: +62 82284603092</p>
  </section>

  <footer>
    <p>&copy; 2025 Najwa Pelagia Saragih. Alle Rechte vorbehalten.</p>
  </footer>
</body>
</html>
