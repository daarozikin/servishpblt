<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Service HP Blitar - Profesional & Terpercaya</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      transition: background-color 0.3s, color 0.3s;
    }
    body.dark {
      background-color: #121212;
      color: #f0f0f0;
    }
    header {
      background: url('https://i.ibb.co/9NZk38g/repair-banner.jpg') no-repeat center center/cover;
      color: white;
      text-align: center;
      padding: 100px 20px 60px;
      position: relative;
    }
    header h1 {
      font-size: 3rem;
      margin-bottom: 10px;
      text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
    }
    header p {
      font-size: 1.2rem;
      text-shadow: 1px 1px 3px rgba(0,0,0,0.5);
    }
    nav {
      background-color: #0056b3;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 15px;
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
    }
    section {
      background: white;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
      margin-bottom: 30px;
      padding: 30px;
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.6s ease-out, transform 0.6s ease-out;
    }
    section.visible {
      opacity: 1;
      transform: translateY(0);
    }
    section.dark {
      background: #1e1e1e;
    }
    h2 { color: #007bff; margin-bottom: 20px; }
    ul li { margin-bottom: 10px; line-height: 1.6; }
    .img-box { margin: 20px 0; text-align: center; }
    .img-box img {
      max-width: 100%;
      border-radius: 10px;
    }
    footer {
      background: #007bff;
      color: white;
      text-align: center;
      padding: 30px 10px;
      margin-top: 50px;
    }
    .btn-wa {
      position: fixed;
      bottom: 20px;
      right: 20px;
      background-color: #25D366;
      color: white;
      border: none;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      font-size: 30px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.3);
      cursor: pointer;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
      margin-top: 20px;
    }
    input, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-family: inherit;
    }
    button {
      background: #007bff;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 15px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
    }
    .dark-toggle {
      position: fixed;
      top: 20px;
      left: 20px;
      background: #007bff;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      z-index: 1000;
    }
  </style>
</head>
<body>

<button class="dark-toggle" onclick="toggleDarkMode()">🌓</button>

<header>
  <h1>Service HP Blitar</h1>
  <p>Spesialis Perbaikan HP | Cepat - Aman - Bergaransi</p>
</header>

<nav>
  <a href="#layanan">Layanan</a>
  <a href="#tentang">Tentang</a>
  <a href="#galeri">Galeri</a>
  <a href="#kontak">Kontak</a>
</nav>

<div class="container">
  <section id="layanan">
    <h2>Layanan Kami</h2>
    <div class="img-box">
      <img src="https://i.ibb.co/wdzb4M4/repair-service.jpg" alt="Service HP" />
    </div>
    <ul>
      <li><strong>Perbaikan Software:</strong> Flashing, bootloop, virus, error sistem.</li>
      <li><strong>Perbaikan Hardware:</strong> Tombol rusak, IC charger, port USB.</li>
      <li><strong>Ganti LCD / Touchscreen:</strong> Layar retak atau tidak responsif.</li>
      <li><strong>Unlock iCloud / FRP:</strong> Tanpa ribet, aman dan legal.</li>
      <li><strong>Servis HP Kemasukan Air:</strong> Penanganan cepat agar tidak short.</li>
    </ul>
  </section>

  <section id="tentang">
    <h2>Tentang Kami</h2>
    <p>Kami adalah penyedia layanan perbaikan HP terpercaya di Blitar sejak 2017. Dengan teknisi berpengalaman dan alat lengkap, kami siap membantu segala jenis kerusakan HP Anda. Layanan cepat, harga transparan, dan bergaransi.</p>
  </section>

  <section id="galeri">
    <h2>Galeri Servis</h2>
    <div class="gallery">
      <img src="https://i.ibb.co/gRR3PPG/service1.jpg" alt="Servis 1">
      <img src="https://i.ibb.co/xFgxXsk/service2.jpg" alt="Servis 2">
      <img src="https://i.ibb.co/zQzDDJ1/service3.jpg" alt="Servis 3">
    </div>
  </section>

  <section id="kontak">
    <h2>Kontak Kami</h2>
    <p>📍 Alamat: Jl. Urip Sumoharjo No.21, Wlingi, Blitar</p>
    <p>📞 Telp: 0813-5788-0573</p>
    <form id="formWA">
      <input type="text" id="nama" placeholder="Nama Anda" required />
      <input type="text" id="nohp" placeholder="Nomor HP" required />
      <textarea id="pesan" rows="4" placeholder="Keluhan atau jenis kerusakan HP" required></textarea>
      <button type="submit">Kirim via WhatsApp</button>
    </form>
  </section>
</div>

<footer>
  &copy; 2025 Service HP Blitar. Dibuat dengan ❤️ oleh Daarozikin.
</footer>

<button class="btn-wa" onclick="window.open('https://wa.me/6281357880573?text=Halo,%20saya%20ingin%20servis%20HP.', '_blank')">💬</button>

<script>
  function toggleDarkMode() {
    document.body.classList.toggle('dark');
    document.querySelectorAll('section').forEach(s => s.classList.toggle('dark'));
  }

  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('section').forEach(section => {
    observer.observe(section);
  });

  document.getElementById("formWA").addEventListener("submit", function(e) {
    e.preventDefault();
    const nama = document.getElementById("nama").value;
    const nohp = document.getElementById("nohp").value;
    const pesan = document.getElementById("pesan").value;
    const waLink = `https://wa.me/6281357880573?text=Halo,%20nama%20saya%20${encodeURIComponent(nama)}%20(${encodeURIComponent(nohp)}),%20saya%20ingin%20servis:%20${encodeURIComponent(pesan)}`;
    window.open(waLink, '_blank');
  });
</script>

</body>
</html>
