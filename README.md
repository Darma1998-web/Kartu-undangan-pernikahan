<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Website Sederhana</title>
  <link rel="stylesheet" href="style.css"> <!-- Hubungkan ke CSS -->
</head>
<body>
  <header>
    <h1>Selamat Datang di Website Saya</h1>
    <p>Ini adalah contoh website sederhana.</p>
  </header>

  <nav>
    <ul>
      <li><a href="#about">Tentang</a></li>
      <li><a href="#contact">Kontak</a></li>
    </ul>
  </nav>

  <main>
    <section id="about">
      <h2>Tentang Saya</h2>
      <p>Halo! Saya sedang belajar membuat website menggunakan HTML, CSS, dan JavaScript.</p>
    </section>

    <section id="contact">
      <h2>Kontak</h2>
      <form id="contactForm">
        <label for="name">Nama:</label>
        <input type="text" id="name" name="name" required>
        
        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>
        
        <button type="submit">Kirim</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2024 Website Saya</p>
  </footer>

  <script src="script.js"></script> <!-- Hubungkan ke JavaScript -->
</body>
</html>
