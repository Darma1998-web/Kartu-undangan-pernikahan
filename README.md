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
body {
  font-family: Arial, sans-serif;
  background: #f7f7f7;
  color: #333;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 600px;
  margin: auto;
  padding: 20px;
  background: #fff;
  box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
  border-radius: 10px;
}

header {
  text-align: center;
  margin-bottom: 20px;
}

header h1 {
  color: #b38b6d;
}

.event-details, .gallery, .rsvp {
  margin-bottom: 20px;
}

.gallery .images img {
  width: 100px;
  margin: 10px;
  border-radius: 10px;
}

form input, form button {
  display: block;
  width: 100%;
  margin-bottom: 10px;
  padding: 10px;
  border-radius: 5px;
  border: 1px solid #ddd;
}
document.getElementById('rsvp-form').addEventListener('submit', function(event) {
  event.preventDefault();
  const name = document.getElementById('name').value;
  const guests = document.getElementById('guests').value;

  if (name && guests) {
    alert(`Terima kasih, ${name}. Kehadiran Anda untuk ${guests} orang telah dikonfirmasi.`);
    document.getElementById('rsvp-form').reset();
  } else {
    alert('Silakan isi semua data.');
  }
});
