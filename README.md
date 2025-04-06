<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>ChegEo – Explore. Learn. Create.</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary-color: #000;
      --bg-color: #f8f8f8;
      --text-color: #222;
    }
    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
    }
    .dark-mode {
      --bg-color: #121212;
      --text-color: #eee;
    }
    header {
      background: #000 url('https://source.unsplash.com/1600x900/?nature,education') center/cover no-repeat;
      height: 100vh;
      color: white;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 0 20px;
    }
    header h1 { font-size: 3em; margin: 0; }
    header p { font-size: 1.2em; margin: 20px 0; }
    .cta-buttons a {
      text-decoration: none;
      background: var(--primary-color);
      color: white;
      padding: 12px 24px;
      margin: 10px;
      border-radius: 30px;
    }
    section { padding: 60px 20px; max-width: 1000px; margin: auto; }
    .programs {
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
      justify-content: center;
    }
    .program {
      background: white;
      padding: 20px;
      border-radius: 16px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      width: 300px;
    }
    footer {
      background: #000;
      color: white;
      text-align: center;
      padding: 20px;
    }
    .whatsapp-float {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      font-size: 30px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-decoration: none;
    }
    .toggle-darkmode {
      position: fixed;
      bottom: 100px;
      right: 20px;
      padding: 10px;
      background: #333;
      color: white;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    @media (max-width: 768px) {
      header h1 { font-size: 2em; }
      .programs { flex-direction: column; align-items: center; }
    }
  </style>
</head>
<body>
  <button class="toggle-darkmode" onclick="document.body.classList.toggle('dark-mode')">Dark Mode</button>
  <a href="https://wa.me/6281234567890" class="whatsapp-float" target="_blank">&#x1F4AC;</a>

  <header>
    <h1>Explore. Learn. Create.</h1>
    <p>Wisata edukasi dan kreatif untuk generasi pencipta</p>
    <div class="cta-buttons">
      <a href="#programs">Lihat Program</a>
      <a href="#contact">Booking</a>
    </div>
  </header>

  <section id="about">
    <h2>Tentang ChegEo</h2>
    <p>ChegEo adalah ruang eksplorasi wisata edukatif dan kreatif. Dirancang untuk belajar, mencipta, dan terhubung – secara langsung.</p>
  </section>

  <section id="programs">
    <h2>Program Unggulan</h2>
    <div class="programs">
      <div class="program">
        <h3>Creator Camp</h3>
        <p>Belajar produksi konten langsung di spot alam</p>
      </div>
      <div class="program">
        <h3>Edu Trip</h3>
        <p>Jelajah sambil belajar budaya, alam, dan teknologi</p>
      </div>
      <div class="program">
        <h3>Workshop</h3>
        <p>Kelas langsung dengan kreator profesional</p>
      </div>
    </div>
  </section>

  <section id="contact">
    <h2>Hubungi Kami</h2>
    <form>
      <input type="text" placeholder="Nama Lengkap" required>
      <input type="email" placeholder="Email" required>
      <input type="date" required>
      <select required>
        <option value="">Pilih Program</option>
        <option>Creator Camp</option>
        <option>Edu Trip</option>
        <option>Workshop</option>
      </select>
      <textarea placeholder="Pesan tambahan..."></textarea>
      <button type="submit">Kirim</button>
    </form>
    <p>Email: info@chegeo.com | WA: 0895362699995</p>
  </section>

  <footer>
    <p>&copy; 2025 ChegEo. All rights reserved.</p>
  </footer>
</body>
</html>
