[contact.html](https://github.com/user-attachments/files/24978637/contact.html)
<!doctype html>
<html lang="ro">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>STIZO Geotehnic — Contact</title>
  <meta name="description" content="Contact STIZO Geotehnic — date firmă și program.">
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header class="site-header">
    <div class="container">
      <a class="logo" href="/">STIZO Geotehnic</a>
      <nav>
        <a href="/">Acasă</a>
        <a href="contact.html">Contact</a>
      </nav>
    </div>
  </header>

  <main class="container contact-page">
    <h1>Contact</h1>
    <p>Trimite-ne un mesaj și te vom contacta în cel mai scurt timp.</p>

    <!-- Formular: înlocuiește YOUR_FORMSPREE_ENDPOINT cu endpoint-ul tău Formspree dacă vrei trimitere prin Formspree -->
    <form action="https://formspree.io/f/YOUR_FORMSPREE_ENDPOINT" method="POST" class="contact-form">
      <label for="name">Nume</label>
      <input id="name" name="name" type="text" required>

      <label for="email">Email</label>
      <input id="email" name="email" type="email" required>

      <label for="phone">Telefon</label>
      <input id="phone" name="phone" type="text">

      <label for="message">Mesaj</label>
      <textarea id="message" name="message" rows="6" required></textarea>

      <button type="submit" class="btn">Trimite</button>
    </form>

    <section class="contact-info">
      <h2>Date firmă</h2>
      <p>PFA Oancea Ionuț Daniel</p>
      <p>CUI: 48907412</p>
      <p>Telefon: <a href="tel:+40737659256">073 765 9256</a></p>
      <p>Email: <a href="mailto:ionut.oancea91@yahoo.com">ionut.oancea91@yahoo.com</a></p>
      <p>Program: Luni–Vineri 08:00–16:00 — Sâmbătă & Duminică închis</p>
    </section>

    <section class="map">
      <!-- Dacă vrei hartă Google: înlocuiește cu embedul de la Google Maps -->
      <iframe src="https://www.google.com/maps/embed?pb=" width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
    </section>
  </main>

  <footer class="site-footer">
    <div class="container">
      <p>© <span id="year2"></span> STIZO Geotehnic.</p>
    </div>
  </footer>

  <script>
    document.getElementById('year2').textContent = new Date().getFullYear();
  </script>
</body>
</html>
