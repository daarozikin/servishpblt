<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Service HP Blitar</title>
  <style>
    * {margin:0; padding:0; box-sizing:border-box; scroll-behavior:smooth;}
    body {font-family:'Segoe UI', sans-serif; background:#f7f9fc; color:#333;}
    header {
      background: linear-gradient(to right, #007bff, #0056b3);
      color: white;
      padding: 30px 20px;
      text-align: center;
      position: relative;
    }
    header h1 {font-size: 2.5em;}
    #clock {
      position: absolute;
      top: 20px;
      right: 30px;
      font-size: 14px;
    }
    nav {
      text-align: center;
      background: #fff;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      padding: 10px;
    }
    nav a {
      margin: 0 15px;
      text-decoration: none;
      color: #007bff;
      font-weight: bold;
    }
    section {
      max-width: 900px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      opacity: 0;
      transform: translateY(20px);
      transition: all 0.5s ease-in-out;
    }
    section.visible {
      opacity: 1;
      transform: translateY(0);
    }
    h2 {color: #007bff; margin-bottom: 10px;}
    ul {padding-left: 20px; line-height: 1.7;}
    footer {
      text-align: center;
      background: #007bff;
      color: white;
      padding: 25px;
      margin-top: 50px;
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-top: 10px;
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
    button:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>

<header>
  <h1>Service HP Blitar</h1>
  <div id="clock">--:--:--</div>
  <p>Solusi cepat, aman, dan bergaransi untuk kerusakan HP Anda</p>
</header>

<nav>
  <a href="#layanan">Layanan</a>
  <a href="#alasan">Kenapa Kami</a>
  <a href="#kontak">Kontak</a>
</nav>

<section id="layanan">
  <h2>Layanan Kami</h2>
  <ul>
    <li><strong>Perbaikan Software:</strong> Bootloop, update sistem, flashing, aplikasi error.</li>
    <li><strong>Perbaikan Hardware:</strong> Tombol rusak, IC, port charger, speaker, mic.</li>
    <li><strong>Ganti LCD / Layar:</strong> Penggantian layar retak atau mati total.</li>
    <li><strong>Unlock iCloud / FRP:</strong> Aman, legal, data tetap terjaga.</li>
    <li><strong>Kemasukan Air:</strong> Penanganan cepat sebelum terjadi kerusakan serius.</li>
  </ul>
</section>

<section id="alasan">
  <h2>Kenapa Pilih Kami?</h2>
  <ul>
    <li>Teknisi bersertifikat dan berpengalaman</li>
    <li>Estimasi harga jujur & transparan</li>
    <li>Sparepart original / OEM berkualitas</li>
    <li>Garansi perbaikan hingga 1 bulan</li>
  </ul>
</section>

<section id="kontak">
  <h2>Kontak Kami</h2>
  <p>📍 Alamat: Jl. Urip Sumoharjo No.21, Wlingi, Blitar</p>
  <p>📞 Telp: 0813-5788-0573</p>
  <form id="contactForm">
    <input type="text" placeholder="Nama Anda" required />
    <input type="email" placeholder="Email Aktif" required />
    <textarea rows="4" placeholder="Pesan Anda..." required></textarea>
    <button type="submit">Kirim Pesan</button>
  </form>
</section>

<footer>
  &copy; 2025 Service HP Blitar. Dibuat oleh Daarozikin.
</footer>

<script>
  // Waktu real-time
  function updateClock() {
    const now = new Date();
    document.getElementById('clock').innerText =
      now.toLocaleTimeString('id-ID');
  }
  setInterval(updateClock, 1000);
  updateClock();

  // Animasi scroll muncul
  const sections = document.querySelectorAll("section");
  window.addEventListener("scroll", () => {
    const trigger = window.innerHeight * 0.85;
    sections.forEach((sec) => {
      const top = sec.getBoundingClientRect().top;
      if (top < trigger) sec.classList.add("visible");
    });
  });

  // Notifikasi form
  document.getElementById("contactForm").addEventListener("submit", function (e) {
    e.preventDefault();
    alert("Pesan berhasil dikirim! Kami akan segera menghubungi Anda.");
    this.reset();
  });
</script>

</body>
</html>
