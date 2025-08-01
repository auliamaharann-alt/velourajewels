<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VeLoura Jewels</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>VeLoura Jewels</h1>
    <nav>
      <a href="#home">Beranda</a>
      <a href="#koleksi">Koleksi</a>
      <a href="#tentang">Tentang</a>
      <a href="#kontak">Kontak</a>
    </nav>
  </header>

  <section id="home">
    <h2>Selamat Datang di VeLoura Jewels</h2>
    <p>Perhiasan titanium elegan & tahan lama, untuk kilaumu yang abadi.</p>
  </section>

  <section id="koleksi">
    <h2>Koleksi Kami</h2>
    <div class="galeri">
      <div class="produk">
        <img src="https://via.placeholder.com/200" alt="Cincin Titanium">
        <p>Cincin Titanium Elegan</p>
      </div>
      <div class="produk">
        <img src="https://via.placeholder.com/200" alt="Kalung Titanium">
        <p>Kalung Minimalis</p>
      </div>
      <!-- Tambah produk lainnya di sini -->
    </div>
  </section>

  <section id="tentang">
    <h2>Tentang VeLoura</h2>
    <p>VeLoura Jewels adalah brand perhiasan titanium yang mengusung desain modern, elegan, dan tahan lama. Setiap koleksi dibuat dengan ketelitian tinggi untuk melengkapi gaya hidup kamu.</p>
  </section>

  <section id="kontak">
    <h2>Kontak Kami</h2>
    <p>Email: <a href="mailto:velourajewels@email.com">velourajewels@email.com</a></p>
    <p>Instagram: <a href="https://instagram.com/velourajewels">@velourajewels</a></p>
  </section>

  <footer>
    <p>© 2025 VeLoura Jewels. All rights reserved.</p>
  </footer>
</body>
</html>


body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fffafc;
  color: #333;
}

header {
  background-color: #000;
  color: gold;
  padding: 20px;
  text-align: center;
}

nav a {
  color: gold;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}

section {
  padding: 40px 20px;
  text-align: center;
}

.galeri {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 20px;
}

.produk {
  width: 200px;
}

.produk img {
  width: 100%;
  border-radius: 8px;
}

footer {
  background-color: #000;
  color: gold;
  text-align: center;
  padding: 15px;
  margin-top: 40px;
}
