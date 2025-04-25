<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Contoh 100 Tag HTML</title>
  <link rel="stylesheet" href="style.css">
  <style>body { font-family: sans-serif; }</style>
  <script>console.log("Script aktif!");</script>
</head>
<body>

  <header><h1>Judul Halaman</h1></header>
  <nav>
    <ul>
      <li><a href="#section1">Bagian 1</a></li>
      <li><a href="#section2">Bagian 2</a></li>
    </ul>
  </nav>

  <main>
    <section id="section1">
      <h2>Konten Utama</h2>
      <article>
        <h3>Artikel Singkat</h3>
        <p>Ini paragraf dengan <strong>penekanan</strong>, <em>penekanan miring</em>, dan <mark>teks ditandai</mark>.</p>
        <p><b>Bold</b>, <i>Italic</i>, <u>Underline</u>, <small>Kecil</small>, <sub>Sub</sub>, <sup>Sup</sup></p>
        <p><code>let x = 10;</code>, <kbd>Ctrl+C</kbd>, <samp>Output</samp>, <var>x</var></p>
        <blockquote>Ini adalah kutipan panjang.</blockquote>
        <q>Ini kutipan pendek.</q>
        <abbr title="HyperText Markup Language">HTML</abbr>,
        <cite>Nama Buku</cite>,
        <address>Jalan Coding No.1</address>,
        <time datetime="2025-04-25">Hari Ini</time>
        <data value="123">Data</data>
        <del>Hapus</del> <ins>Sisip</ins>
      </article>
    </section>

    <section id="section2">
      <h2>List dan Tabel</h2>
      <ul>
        <li>Satu</li>
        <li>Dua</li>
      </ul>
      <ol>
        <li>Tiga</li>
        <li>Empat</li>
      </ol>

      <table>
        <caption>Tabel Contoh</caption>
        <colgroup>
          <col style="background-color:lightgrey;">
          <col>
        </colgroup>
        <thead><tr><th>Kolom 1</th><th>Kolom 2</th></tr></thead>
        <tbody><tr><td>Data 1</td><td>Data 2</td></tr></tbody>
        <tfoot><tr><td colspan="2">Footer</td></tr></tfoot>
      </table>
    </section>

    <section>
      <h2>Formulir</h2>
      <form>
        <fieldset>
          <legend>Data Diri</legend>
          <label for="nama">Nama:</label>
          <input type="text" id="nama" name="nama" list="namaList">
          <datalist id="namaList">
            <option value="Andi">
            <option value="Budi">
          </datalist>
          <label for="bio">Bio:</label>
          <textarea id="bio"></textarea><br>
          <label for="hobi">Hobi:</label>
          <select id="hobi">
            <optgroup label="Fisik">
              <option>Lari</option>
              <option>Renang</option>
            </optgroup>
            <optgroup label="Non-Fisik">
              <option>Membaca</option>
            </optgroup>
          </select>
          <br>
          <button type="submit">Kirim</button>
          <output>Hasil akan muncul di sini</output>
        </fieldset>
      </form>
    </section>

    <section>
      <h2>Multimedia</h2>
      <figure>
        <img src="https://via.placeholder.com/150" alt="Contoh Gambar">
        <figcaption>Gambar Placeholder</figcaption>
      </figure>
      <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
        <track kind="captions" src="captions.vtt" srclang="id" label="Indonesia">
        <p>Browser Anda tidak mendukung audio.</p>
      </audio>
      <video controls>
        <source src="video.mp4" type="video/mp4">
        <p>Browser tidak mendukung video.</p>
      </video>
      <progress value="70" max="100"></progress>
      <meter value="0.5">50%</meter>
      <iframe src="https://example.com" title="Contoh Iframe"></iframe>
      <embed src="file.pdf" type="application/pdf">
      <object data="data.swf" type="application/x-shockwave-flash">
        <param name="autoplay" value="false">
      </object>
    </section>

    <section>
      <h2>Canvas & SVG</h2>
      <canvas width="200" height="100"></canvas>
      <svg width="100" height="100">
        <circle cx="50" cy="50" r="40" stroke="black" stroke-width="3" fill="red" />
        <rect width="90" height="40" x="5" y="50" fill="blue" />
        <line x1="0" y1="0" x2="100" y2="100" stroke="green" />
        <polygon points="50,5 90,90 10,90" fill="orange"/>
        <path d="M10 10 h 80 v 80 h -80 Z" fill="none" stroke="black"/>
        <title>Gambar SVG</title>
      </svg>
    </section>

    <section>
      <h2>Template & Noscript</h2>
      <template>
        <p>Ini adalah template yang belum dirender.</p>
      </template>
      <noscript>
        <p>Javascript dinonaktifkan.</p>
      </noscript>
    </section>
  </main>

  <footer><p>&copy; 2025 Contoh HTML</p></footer>
</body>
</html>
