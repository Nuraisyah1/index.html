<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>100 HTML Tags</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <base href="https://example.com/">
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>Judul Situs</h1>
    <nav>
      <menu>
        <menuitem label="Home"></menuitem>
      </menu>
      <ul>
        <li><a href="#section1">Bagian 1</a></li>
        <li><a href="#section2">Bagian 2</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="section1">
      <h2>Bagian Satu</h2>
      <article>
        <h3>Artikel 1</h3>
        <p>Ini paragraf <mark>penting</mark> dari artikel 1.</p>
        <time datetime="2025-04-22">22 April 2025</time>
        <address>Jl. Contoh No. 1, Indonesia</address>
        <figure>
          <img src="https://via.placeholder.com/150" alt="Contoh Gambar">
          <figcaption>Gambar Placeholder</figcaption>
        </figure>
        <progress value="70" max="100"></progress>
        <meter value="0.6">60%</meter>
      </article>

      <aside>
        <details>
          <summary>Informasi Tambahan</summary>
          <p>Ini adalah detail tambahan.</p>
        </details>
      </aside>

      <blockquote cite="https://example.com">Ini adalah kutipan.</blockquote>
      <cite>— Sumber Kutipan</cite>
      <pre>kode:
function hello() {
  return "Hello!";
}</pre>
      <code>&lt;div&gt;Contoh Code&lt;/div&gt;</code>
      <kbd>Ctrl + C</kbd>
      <samp>Output Sistem</samp>
      <var>x</var>
    </section>

    <section id="section2">
      <h2>Formulir</h2>
      <form>
        <label for="nama">Nama:</label>
        <input type="text" id="nama"><br>
        <label for="email">Email:</label>
        <input type="email" id="email"><br>
        <input type="checkbox" id="langganan">
        <label for="langganan">Langganan</label><br>
        <input type="radio" name="gender" value="L"> Laki-laki
        <input type="radio" name="gender" value="P"> Perempuan<br>
        <select>
          <option value="1">Satu</option>
          <option value="2">Dua</option>
        </select><br>
        <textarea rows="4" cols="50">Isi komentar di sini...</textarea><br>
        <button type="submit">Kirim</button>
      </form>

      <table>
        <caption>Data Siswa</caption>
        <thead>
          <tr><th>Nama</th><th>Umur</th></tr>
        </thead>
        <tbody>
          <tr><td>Ani</td><td>17</td></tr>
          <tr><td>Budi</td><td>18</td></tr>
        </tbody>
        <tfoot>
          <tr><td colspan="2">Jumlah: 2 siswa</td></tr>
        </tfoot>
      </table>
    </section>

    <hr>
    <canvas id="myCanvas" width="200" height="100"></canvas>
    <svg width="100" height="100">
      <circle cx="50" cy="50" r="40" stroke="green" fill="yellow" />
    </svg>
    <iframe src="https://example.com" title="Contoh Iframe"></iframe>
    <embed src="video.mp4" type="video/mp4">
    <object data="data.pdf" type="application/pdf" width="300" height="200"></object>

    <video width="320" height="240" controls>
      <source src="video.mp4" type="video/mp4">
    </video>

    <audio controls>
      <source src="audio.mp3" type="audio/mpeg">
    </audio>

    <b>Bold</b>
    <i>Italic</i>
    <u>Underline</u>
    <strong>Strong</strong>
    <em>Emphasis</em>
    <abbr title="HyperText Markup Language">HTML</abbr>
    <small>Small text</small>
    <sub>Subscript</sub>
    <sup>Superscript</sup>
    <del>Hapus</del>
    <ins>Tambah</ins>
    <span>Ini span</span>
    <br>
    <wbr>
    <noscript>Aktifkan JavaScript untuk konten lengkap</noscript>
    <template>
      <p>Ini adalah template</p>
    </template>
    <script>console.log("Hello World!");</script>

  </main>

  <footer>
    <p>&copy; 2025 - Dibuat oleh <bdi>Nama</bdi></p>
    <bdo dir="rtl">Teks Terbalik</bdo>
    <data value="42">Jawaban</data>
    <output>42</output>
    <del>Data Lama</del>
    <ins>Data Baru</ins>
    <ruby>漢 <rt>Kan</rt></ruby>
    <section>
      <h4 hidden>Bagian Tersembunyi</h4>
    </section>
  </footer>

</body>
</html>
# index.html
