><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Service HP Profesional Blitar</title>
  <style>
    /* Reset & font */
    * {
      margin: 0; padding: 0; box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #333;
      background: url('https://images.unsplash.com/photo-1512499617640-c2f99905394f?auto=format&fit=crop&w=1350&q=80') no-repeat center center fixed;
      background-size: cover;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
    }
    /* Overlay gelap agar teks terbaca */
    body::before {
      content: "";
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      background: rgba(0, 0, 0, 0.5);
      z-index: -1;
    }
    header {
      background-color: rgba(0, 123, 255, 0.8);
      color: white;
      text-align: center;
      padding: 3rem 1rem;
      box-shadow: 0 4px 8px rgba(0,0,0,0.3);
    }
    header h1 {
      font-size: 2.8rem;
      margin-bottom: 0.5rem;
    }
    header p {
      font-size: 1.2rem;
      font-weight: 500;
    }
    nav {
      background: #004085;
      display: flex;
      justify-content: center;
      gap: 2rem;
      padding: 1rem 0;
      box-shadow: 0 2px 5px rgba(0,0,0,0.25);
    }
    nav a {
      color: white;
      text-decoration: none;
      font-weight: 600;
      font-size: 1.1rem;
      transition: color 0.3s ease;
    }
    nav a:hover {
      color: #ffc107;
    }
    main {
      flex: 1;
      max-width: 1100px;
      margin: 2rem auto 4rem;
      background: rgba(255,255,255,0.95);
      border-radius: 12px;
      padding: 2rem 3rem;
      box-shadow: 0 8px 24px rgba(0,0,0,0.15);
    }
    section {
      margin-bottom: 3rem;
    }
    h2 {
      color: #007bff;
      margin-bottom: 1rem;
      border-bottom: 3px solid #007bff;
      padding-bottom: 0.5rem;
      font-weight: 700;
    }
    ul {
      list-style-type: disc;
      padding-left: 1.5rem;
      color: #444;
      font-size: 1.05rem;
      line-height: 1.7;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill,minmax(280px,1fr));
      gap: 1.2rem;
      margin-top: 1rem;
    }
    .gallery img {
      width: 100%;
      height: 180px;
      object-fit: cover;
      border-radius: 10px;
      box-shadow: 0 3px 8px rgba(0,0,0,0.15);
      transition: transform 0.3s ease;
      cursor: pointer;
    }
    .gallery img:hover {
      transform: scale(1.05);
      box-shadow: 0 6px 15px rgba(0,0,0,0.25);
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 1.2rem;
    }
    input, textarea {
      padding: 0.9rem 1rem;
      font-size: 1rem;
      border: 1.8px solid #ccc;
      border-radius: 8px;
      resize: vertical;
      transition: border-color 0.3s ease;
    }
    input:focus, textarea:focus {
      outline: none;
      border-color: #007bff;
      box-shadow: 0 0 5px #007bffaa;
    }
    button {
      background-color: #007bff;
      color: white;
      font-size: 1.1rem;
      padding: 1rem 0;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: 700;
      transition: background-color 0.3s ease;
    }
    button:hover {
      background-color: #0056b3;
    }
    #form-message {
      padding: 1rem;
      border-radius: 8px;
      background-color: #d4edda;
      border: 1px solid #c3e6cb;
      color: #155724;
      font-weight: 600;
      display: none;
      text-align: center;
      margin-bottom: 1rem;
    }
    footer {
      background-color: #007bff;
      color: white;
      text-align: center;
      padding: 1.5rem 1rem;
      font-weight: 600;
      box-shadow: 0 -4px 10px rgba(0,0,0,0.15);
    }
    /* Scroll animation fade-in */
    .fade-in {
      opacity: 0;
      transform: translateY(40px);
      transition: opacity 0.8s ease-out, transform 0.8s ease-out;
    }
    .fade-in.visible {
      opacity: 1;
      transform: translateY(0);
    }
    /* Floating WhatsApp button */
    #wa-button {
      position: fixed;
      bottom: 25px;
      right: 25px;
      background: #25D366;
      color: white;
      border: none;
      border-radius: 50%;
      width: 60px;
      height: 60px;
      font-size: 32px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: background-color 0.3s ease;
      z-index: 1000;
    }
    #wa-button:hover {
      background: #128C4A;
    }
  </style>
</head>
<body>

<header>
  <h1>Service HP Profesional Blitar</h1>
  <p>Spesialis Reparasi Android & iPhone dengan Teknisi Bersertifikat</p>
</header>

<nav>
  <a href="#galeri">Galeri</a>
  <a href="#layanan">Layanan</a>
  <a href="#form-pesan">Pesan Servis</a>
</nav>

<main>
  <section id="galeri" class="fade-in">
    <h2>Galeri Servis Profesional</h2>
    <div class="gallery" aria-label="Foto layanan servis HP">
      <img src="https://images.unsplash.com/photo-1580894908361-0d7b2f85aa1b?auto=format&fit=crop&w=800&q=60" alt="Teknisi sedang memperbaiki layar HP" />
      <img src="https://images.unsplash.com/photo-1536579462240-d0a289c43d5b?auto=format&fit=crop&w=800&q=60" alt="Penggantian LCD HP" />
      <img src="https://images.unsplash.com/photo-1549924231-f129b911e442?auto=format&fit=crop&w=800&q=60" alt="Memperbaiki hardware HP" />
      <img src="https://images.unsplash.com/photo-1549924231-4a7de6183ec8?auto=format&fit=crop&w=800&q=60" alt="Pengecekan HP setelah servis" />
      <img src="https://images.unsplash.com/photo-1580910051072-4f4a18c1e6d8?auto=format&fit=crop&w=800&q=60" alt="Teknisi bekerja dengan alat profesional" />
    </div>
  </section>

  <section id="layanan" class="fade-in">
    <h2>Layanan Kami</h2>
    <ul>
      <li><strong>Perbaikan Software:</strong> Atasi bootloop, lemot, sistem error, flashing & reset sistem.</li>
      <li><strong>Ganti LCD / Layar Sentuh:</strong> Penggantian layar pecah/bergaris dengan sparepart original berkualitas.</li>
      <li><strong>Perbaikan Hardware:</strong> Servis IC, port charger, tombol rusak, speaker & mikrofon mati.</li>
      <li><strong>Unlock iCloud / FRP:</strong> Buka kunci iCloud iPhone & akun Google (FRP) Android secara aman dan legal.</li>
      <li><strong>Servis HP Kemasukan Air:</strong> Penanganan cepat dan pencegahan korosi kerusakan mesin HP.</li>
    </ul>
  </section>

  <section id="form-pesan" class="fade-in" aria-label="Formulir pemesanan servis HP">
    <h2>Form Pemesanan Servis</h2>
    <form id="form-servis">
      <div id="form-message" role="alert" aria-live="polite"></div>
      <input type="text" name="nama" placeholder="Nama Anda" required aria-required="true" />
      <input type="tel" name="nomor" placeholder="Nomor WhatsApp" required aria-required="true" />
      <textarea name="pesan" placeholder="Jenis kerusakan atau layanan yang diinginkan..." rows="4" required aria-required="true"></textarea>
      <button type="submit">Kirim Pemesanan</button>
    </form>
    <p style="margin-top: 1rem;">Atau scan QR Code untuk langsung menghubungi WhatsApp kami:</p>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://wa.me/6281357880573" alt="QR Code WhatsApp Service HP Blitar" style="margin-top: 0.5rem;" />
  </section>
</main>

<button id="wa-button" aria-label="Chat WhatsApp" title="Chat WhatsApp" onclick="openWhatsApp()">💬</button>

<footer>
  &copy; 2025 Service HP Profesional Blitar. Semua Hak Dilindungi.
</footer>

<script>
  // Validasi dan submit form
  document.getElementById('form-servis').addEventListener('submit', function(e) {
    e.preventDefault();

    const nama = this.nama.value.trim();
    const nomor = this.nomor.value.trim();
    const pesan = this.pesan.value.trim();
    const messageBox = document.getElementById('form-message');

    if (!nama || !nomor || !pesan) {
      alert('Mohon lengkapi semua kolom sebelum mengirim.');
      return;
    }

    // Tampilkan pesan sukses
    messageBox.textContent = 'Pesanan Anda berhasil dikirim! Terima kasih.';
    messageBox.style.display = 'block';
    messageBox.style.backgroundColor = '#d4edda';
    messageBox.style.color = '#155724';
    messageBox.style.border = '1px solid #c3e6cb';
    messageBox.style.borderRadius = '5px';
    messageBox.style.padding = '1rem';
    messageBox.style.marginBottom = '1rem';

    // Reset form
    this.reset();

    // Hilangkan pesan sukses setelah 5 detik
    setTimeout(() => {
      messageBox.style.display = 'none';
    }, 5000);
  });

  // Animasi fade-in saat scroll
  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
        observer.unobserve(entry.target);
      }
    });
  }, { threshold: 0.1 });

  document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));

  // Fungsi tombol WhatsApp mengambang
  function openWhatsApp() {
    const phone = '6281357880573';
    const text = 'Halo, saya ingin servis HP.';
    window.open(`https://wa.me/${phone}?text=${encodeURIComponent(text)}`, '_blank');
  }
</script>

</body>
