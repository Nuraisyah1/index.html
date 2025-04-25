<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <title>Perencana Menu</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="style.css">
  <style>
    table, th, td { border: 1px solid black; border-collapse: collapse; padding: 5px; }
    aside { background-color: #f0f0f0; padding: 10px; margin: 10px 0; }
  </style>
</head>
<body>
  <header>
    <h1>Perencana Menu Mingguan</h1>
    <nav>
      <ul>
        <li><a href="#monday">Senin</a></li>
        <li><a href="#tuesday">Selasa</a></li>
        <li><a href="#wednesday">Rabu</a></li>
        <li><a href="#thursday">Kamis</a></li>
        <li><a href="#friday">Jumat</a></li>
        <li><a href="#saturday">Sabtu</a></li>
        <li><a href="#sunday">Minggu</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section>
      <h2>Gambaran Umum</h2>
      <p>Rencanakan makanan mingguan Anda dengan mudah menggunakan gambar, data nutrisi, dan tautan resep.</p>
      <figure>
        <img src="https://via.placeholder.com/300x200" alt="Gambar perencanaan makanan">
        <figcaption>Tetap terorganisir dan makan lebih sehat.</figcaption>
      </figure>
    </section>

    <section id="monday">
      <h2>Senin</h2>
      <article>
        <h3>Sarapan</h3>
        <ul>
          <li>Oatmeal dengan pisang <a href="#">(Resep)</a></li>
        </ul>
        <h3>Makan Siang</h3>
        <ul>
          <li>Salad ayam panggang <a href="#">(Resep)</a></li>
        </ul>
        <h3>Makan Malam</h3>
        <ul>
          <li>Spaghetti dengan saus marinara <a href="#">(Resep)</a></li>
        </ul>
        <aside>
          <p><strong>Tips Hari Ini:</strong> Minumlah cukup air!</p>
        </aside>
      </article>
    </section>

    <section id="tuesday">
      <h2>Selasa</h2>
      <article>
        <h3>Sarapan</h3>
        <ul>
          <li>Telur orak-arik dan roti panggang <a href="#">(Resep)</a></li>
        </ul>
        <h3>Makan Siang</h3>
        <ul>
          <li>Sandwich kalkun <a href="#">(Resep)</a></li>
        </ul>
        <h3>Makan Malam</h3>
        <ul>
          <li>Sayuran tumis dengan nasi <a href="#">(Resep)</a></li>
        </ul>
        <details>
          <summary>Lihat informasi nutrisi</summary>
          <p>Kalori: 550 | Protein: 20g | Lemak: 18g</p>
        </details>
      </article>
    </section>

    <section id="tabel-nutrisi">
      <h2>Tabel Nutrisi</h2>
      <table>
        <caption>Informasi Nutrisi Harian</caption>
        <thead>
          <tr>
            <th>Hari</th>
            <th>Kalori</th>
            <th>Protein</th>
            <th>Lemak</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Senin</td>
            <td>1800</td>
            <td>75g</td>
            <td>60g</td>
          </tr>
          <tr>
            <td>Selasa</td>
            <td>1900</td>
            <td>80g</td>
            <td>65g</td>
          </tr>
        </tbody>
      </table>
    </section>

    <section id="video">
      <h2>Video Masak</h2>
      <video controls width="320">
        <source src="video-masak.mp4" type="video/mp4">
        Browser Anda tidak mendukung video.
      </video>
    </section>

    <section id="audio">
      <h2>Podcast Nutrisi</h2>
      <audio controls>
        <source src="podcast.mp3" type="audio/mpeg">
        Browser Anda tidak mendukung audio.
      </audio>
    </section>

    <section id="feedback">
      <h2>Masukan</h2>
      <form>
        <fieldset>
          <legend>Formulir Masukan</legend>
          <label for="name">Nama:</label>
          <input type="text" id="name" name="name" required><br>

          <label for="email">Email:</label>
          <input type="email" id="email" name="email"><br>

          <label for="tanggal">Tanggal:</label>
          <input type="date" id="tanggal" name="tanggal"><br>

          <label for="rating">Penilaian:</label>
          <input type="range" id="rating" name="rating" min="1" max="5"><br>

          <label for="comments">Komentar:</label><br>
          <textarea id="comments" name="comments" rows="4" cols="50"></textarea><br>

          <button type="submit">Kirim</button>
        </fieldset>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Perencana Menu. Seluruh hak cipta dilindungi.</p>
    <address>Hubungi kami: <a href="mailto:info@menumakan.com">info@menumakan.com</a></address>
  </footer>
</body>
</html>
