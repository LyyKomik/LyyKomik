<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LyyKomik</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: white;
      padding: 1em;
      text-align: center;
    }
    main {
      padding: 1em;
    }
    .komik-item {
      background-color: white;
      margin-bottom: 1em;
      padding: 1em;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .komik-item img {
      max-width: 100%;
      border-radius: 8px;
    }
    .pertanyaan-form {
      background-color: white;
      padding: 1em;
      margin-bottom: 1em;
      border-radius: 8px;
    }
    .pertanyaan-form input, .pertanyaan-form select {
      width: 100%;
      padding: 0.5em;
      margin-bottom: 1em;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    @media (max-width: 600px) {
      header {
        font-size: 1.2em;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Selamat Datang lyy komik</h1>
  </header>
  <main>
    <div class="pertanyaan-form">
      <h2>Tanyakan Beberapa Hal</h2>
      <form>
        <label for="genre">Genre Komik Favorit Anda:</label>
        <select id="genre">
          <option value="aksi">Aksi</option>
          <option value="romantis">Romantis</option>
          <option value="fantasi">Fantasi</option>
          <option value="horor">Horor</option>
        </select>

        <label for="rekomendasi">Jenis Rekomendasi:</label>
        <select id="rekomendasi">
          <option value="genre">Berdasarkan Genre</option>
          <option value="rating">Berdasarkan Rating</option>
        </select>

        <label for="notifikasi">Ingin Menerima Notifikasi?</label>
        <select id="notifikasi">
          <option value="ya">Ya</option>
          <option value="tidak">Tidak</option>
        </select>

        <button type="submit">Kirim</button>
      </form>
    </div>

    <div class="komik-item">
      <h3>Komik Terbaru: "Aksi Petualang"</h3>
      <img src="komik1.jpg" alt="Komik 1">
      <p>Genre: Aksi</p>
      <a href="#">Baca Komik</a>
    </div>
    <div class="komik-item">
      <h3>Komik Terbaru: "Cinta dalam Gelap"</h3>
      <img src="komik2.jpg" alt="Komik 2">
      <p>Genre: Romantis</p>
      <a href="#">Baca Komik</a>
    </div>
  </main>
</body>
</html>
