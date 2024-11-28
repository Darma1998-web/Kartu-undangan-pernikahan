<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Undangan Pernikahan</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="container">
    <header>
      <h1>Undangan Pernikahan</h1>
      <p>Nama Mempelai</p>
    </header>
    <section class="event-details">
      <h2>Detail Acara</h2>
      <p>📅 Tanggal: 25 Desember 2024</p>
      <p>📍 Lokasi: Hotel Harmoni, Jakarta</p>
    </section>
    <section class="gallery">
      <h2>Galeri</h2>
      <div class="images">
        <img src="foto1.jpg" alt="Foto Mempelai">
        <img src="foto2.jpg" alt="Foto Prewedding">
      </div>
    </section>
    <section class="rsvp">
      <h2>Konfirmasi Kehadiran</h2>
      <form id="rsvp-form">
        <input type="text" id="name" placeholder="Nama Anda" required>
        <input type="number" id="guests" placeholder="Jumlah Tamu" required>
        <button type="submit">Konfirmasi</button>
      </form>
    </section>
  </div>
  <script src="script.js"></script>
</body>
</html>
