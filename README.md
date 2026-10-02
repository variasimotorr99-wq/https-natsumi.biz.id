<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Natsumi Digital — Produk Digital Murah & Terpercaya</title>

  <meta name="description" content="Natsumi Digital menyediakan berbagai produk digital dengan harga terjangkau. Order mudah melalui WhatsApp.">
  <meta name="theme-color" content="#0b0b0f">

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, Helvetica, sans-serif;
      background: #08080c;
      color: #ffffff;
      line-height: 1.6;
    }

    a {
      text-decoration: none;
      color: inherit;
    }

    /* ================= HEADER ================= */

    header {
      position: sticky;
      top: 0;
      z-index: 1000;
      background: rgba(8, 8, 12, 0.92);
      backdrop-filter: blur(12px);
      border-bottom: 1px solid rgba(255,255,255,0.08);
    }

    .navbar {
      max-width: 1150px;
      margin: auto;
      padding: 18px 20px;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }

    .logo {
      font-size: 22px;
      font-weight: 900;
      letter-spacing: 1px;
    }

    .logo span {
      color: #ff3158;
    }

    nav {
      display: flex;
      gap: 28px;
      align-items: center;
    }

    nav a {
      color: #d7d7df;
      font-size: 14px;
      transition: 0.3s;
    }

    nav a:hover {
      color: #ff3158;
    }

    .nav-button {
      background: linear-gradient(135deg, #ff3158, #ff1744);
      padding: 10px 17px;
      border-radius: 10px;
      color: white !important;
      font-weight: bold;
    }

    /* ================= HERO ================= */

    .hero {
      min-height: 650px;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 80px 20px;
      background:
        radial-gradient(circle at top right, rgba(255,49,88,0.18), transparent 35%),
        radial-gradient(circle at bottom left, rgba(120,40,255,0.12), transparent 35%),
        #08080c;
    }

    .hero-content {
      max-width: 850px;
    }

    .badge {
      display: inline-block;
      padding: 8px 15px;
      border-radius: 50px;
      background: rgba(255,49,88,0.12);
      border: 1px solid rgba(255,49,88,0.35);
      color: #ff5b79;
      font-size: 13px;
      font-weight: bold;
      margin-bottom: 22px;
    }

    .hero h1 {
      font-size: clamp(42px, 7vw, 76px);
      line-height: 1.05;
      font-weight: 900;
      margin-bottom: 22px;
    }

    .hero h1 span {
      background: linear-gradient(135deg, #ff3158, #ff8a9f);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
    }

    .hero p {
      max-width: 650px;
      margin: auto;
      color: #a9a9b3;
      font-size: 17px;
      margin-bottom: 35px;
    }

    .hero-buttons {
      display: flex;
      justify-content: center;
      gap: 14px;
      flex-wrap: wrap;
    }

    .btn {
      padding: 14px 24px;
      border-radius: 12px;
      font-weight: bold;
      transition: 0.3s;
      display: inline-block;
    }

    .btn-primary {
      background: linear-gradient(135deg, #ff3158, #ff1744);
      box-shadow: 0 10px 30px rgba(255,49,88,0.2);
    }

    .btn-primary:hover {
      transform: translateY(-3px);
    }

    .btn-secondary {
      border: 1px solid #292933;
      background: #111116;
      color: #eeeeee;
    }

    .btn-secondary:hover {
      border-color: #ff3158;
    }

    /* ================= PROMO ================= */

    .promo {
      background: linear-gradient(135deg, #ff3158, #d90038);
      padding: 16px 20px;
      text-align: center;
      font-weight: bold;
      font-size: 14px;
    }

    /* ================= GENERAL ================= */

    section {
      padding: 90px 20px;
    }

    .container {
      max-width: 1150px;
      margin: auto;
    }

    .section-title {
      text-align: center;
      margin-bottom: 45px;
    }

    .section-title h2 {
      font-size: 36px;
      margin-bottom: 10px;
    }

    .section-title p {
      color: #92929c;
    }

    /* ================= PRODUCTS ================= */

    .products {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 22px;
    }

    .product-card {
      background: linear-gradient(145deg, #121218, #0e0e13);
      border: 1px solid #24242e;
      border-radius: 18px;
      padding: 25px;
      position: relative;
      overflow: hidden;
      transition: 0.3s;
    }

    .product-card:hover {
      transform: translateY(-6px);
      border-color: rgba(255,49,88,0.5);
      box-shadow: 0 20px 50px rgba(0,0,0,0.3);
    }

    .product-icon {
      width: 55px;
      height: 55px;
      border-radius: 14px;
      display: flex;
      align-items: center;
      justify-content: center;
      background: rgba(255,49,88,0.12);
      font-size: 25px;
      margin-bottom: 20px;
    }

    .product-card h3 {
      font-size: 20px;
      margin-bottom: 9px;
    }

    .product-card p {
      color: #8f8f9a;
      font-size: 14px;
      min-height: 45px;
      margin-bottom: 20px;
    }

    .price {
      font-size: 25px;
      font-weight: 900;
      color: #ff496a;
      margin-bottom: 18px;
    }

    .order-btn {
      display: block;
      text-align: center;
      padding: 12px;
      border-radius: 10px;
      background: #ff3158;
      font-weight: bold;
      transition: 0.3s;
    }

    .order-btn:hover {
      background: #ff1744;
    }

    /* ================= PROMO BOX ================= */

    .promo-box {
      background:
        radial-gradient(circle at top right, rgba(255,49,88,0.2), transparent 40%),
        #121218;
      border: 1px solid #292934;
      border-radius: 24px;
      padding: 45px;
      text-align: center;
    }

    .promo-box h2 {
      font-size: 34px;
      margin-bottom: 12px;
    }

    .promo-box p {
      color: #a0a0aa;
      margin-bottom: 25px;
    }

    /* ================= HOW TO ORDER ================= */

    .steps {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 20px;
    }

    .step {
      padding: 30px;
      border-radius: 18px;
      background: #111116;
      border: 1px solid #24242e;
    }

    .step-number {
      width: 45px;
      height: 45px;
      border-radius: 50%;
      background: #ff3158;
      display: flex;
      align-items: center;
      justify-content: center;
      font-weight: 900;
      margin-bottom: 18px;
    }

    .step h3 {
      margin-bottom: 8px;
    }

    .step p {
      color: #8e8e98;
      font-size: 14px;
    }

    /* ================= CTA ================= */

    .cta {
      text-align: center;
      background: #0d0d12;
      border-top: 1px solid #20202a;
      border-bottom: 1px solid #20202a;
    }

    .cta h2 {
      font-size: 36px;
      margin-bottom: 12px;
    }

    .cta p {
      color: #92929c;
      margin-bottom: 25px;
    }

    /* ================= FOOTER ================= */

    footer {
      padding: 35px 20px;
      background: #060609;
      border-top: 1px solid #1b1b22;
    }

    .footer-content {
      max-width: 1150px;
      margin: auto;
      display: flex;
      justify-content: space-between;
      gap: 20px;
      align-items: center;
    }

    .footer-logo {
      font-weight: 900;
      font-size: 18px;
    }

    .footer-logo span {
      color: #ff3158;
    }

    .copyright {
      color: #70707a;
      font-size: 13px;
    }

    /* ================= MOBILE ================= */

    @media (max-width: 850px) {

      nav {
        display: none;
      }

      .products {
        grid-template-columns: 1fr;
      }

      .steps {
        grid-template-columns: 1fr;
      }

      .hero {
        min-height: 580px;
      }

      .hero h1 {
        font-size: 45px;
      }

      .section-title h2 {
        font-size: 30px;
      }

      .promo-box {
        padding: 30px 20px;
      }

      .footer-content {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>

<body>

  <!-- ================= PROMO BAR ================= -->

  <div class="promo">
    🔥 PROMO HARI INI — PRODUK DIGITAL HARGA TERJANGKAU
  </div>

  <!-- ================= HEADER ================= -->

  <header>
    <div class="navbar">

      <a href="#" class="logo">
        NATSUMI<span>DIGITAL</span>
      </a>

      <nav>
        <a href="#beranda">Beranda</a>
        <a href="#produk">Produk</a>
        <a href="#promo">Promo</a>
        <a href="#cara-order">Cara Order</a>

        <a
          href="https://wa.me/6282249211189"
          target="_blank"
          class="nav-button">
          Order Sekarang
        </a>
      </nav>

    </div>
  </header>


  <!-- ================= HERO ================= -->

  <section class="hero" id="beranda">

    <div class="hero-content">

      <div class="badge">
        ✨ NATSUMI DIGITAL
      </div>

      <h1>
        Solusi Digital<br>
        <span>Untuk Kebutuhanmu</span>
      </h1>

      <p>
        Temukan berbagai produk digital dengan harga terjangkau,
        proses cepat, dan pemesanan mudah melalui WhatsApp.
      </p>

      <div class="hero-buttons">

        <a
          href="#produk"
          class="btn btn-primary">
          🛒 Lihat Produk
        </a>

        <a
          href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order."
          target="_blank"
          class="btn btn-secondary">
          💬 Chat WhatsApp
        </a>

      </div>

    </div>

  </section>


  <!-- ================= PRODUK ================= -->

  <section id="produk">

    <div class="container">

      <div class="section-title">

        <h2>Produk Digital</h2>

        <p>
          Pilih produk yang kamu butuhkan dan langsung order melalui WhatsApp.
        </p>

      </div>


      <div class="products">


        <!-- PRODUK 1 -->

        <div class="product-card">

          <div class="product-icon">
            ⭐
          </div>

          <h3>Produk Digital 1</h3>

          <p>
            Produk digital dengan masa aktif 1 bulan.
          </p>

          <div class="price">
            Rp 15.000
          </div>

          <a
            href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order%20Produk%20Digital%201%20Rp15.000."
            target="_blank"
            class="order-btn">
            Order Sekarang
          </a>

        </div>


        <!-- PRODUK 2 -->

        <div class="product-card">

          <div class="product-icon">
            🔥
          </div>

          <h3>Produk Digital 2</h3>

          <p>
            Produk digital dengan masa aktif 2 bulan.
          </p>

          <div class="price">
            Rp 28.000
          </div>

          <a
            href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order%20Produk%20Digital%202%20Rp28.000."
            target="_blank"
            class="order-btn">
            Order Sekarang
          </a>

        </div>


        <!-- PRODUK 3 -->

        <div class="product-card">

          <div class="product-icon">
            💎
          </div>

          <h3>Produk Digital 3</h3>

          <p>
            Produk digital dengan masa aktif 3 bulan.
          </p>

          <div class="price">
            Rp 39.000
          </div>

          <a
            href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order%20Produk%20Digital%203%20Rp39.000."
            target="_blank"
            class="order-btn">
            Order Sekarang
          </a>

        </div>


        <!-- VIA INVITE -->

        <div class="product-card">

          <div class="product-icon">
            ⚡
          </div>

          <h3>Via Invite</h3>

          <p>
            Aktivasi melalui invite dengan proses yang praktis.
          </p>

          <div class="price">
            Rp 4.000
          </div>

          <a
            href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order%20Via%20Invite%20Rp4.000."
            target="_blank"
            class="order-btn">
            Order Sekarang
          </a>

        </div>


        <!-- VIA INVITE PERPANJANG -->

        <div class="product-card">

          <div class="product-icon">
            🔄
          </div>

          <h3>Via Invite + Perpanjang</h3>

          <p>
            Via invite yang dapat diperpanjang menggunakan 1 Gmail.
          </p>

          <div class="price">
            Rp 7.500
          </div>

          <a
            href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order%20Via%20Invite%20Perpanjang%20Rp7.500."
            target="_blank"
            class="order-btn">
            Order Sekarang
          </a>

        </div>


        <!-- FAMEHEAD PEMBELI -->

        <div class="product-card">

          <div class="product-icon">
            👤
          </div>

          <h3>Famehead Email Pembeli</h3>

          <p>
            Layanan menggunakan email pembeli.
          </p>

          <div class="price">
            Rp 10.000
          </div>

          <a
            href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order%20Famehead%20Email%20Pembeli%20Rp10.000."
            target="_blank"
            class="order-btn">
            Order Sekarang
          </a>

        </div>


        <!-- FAMEHEAD SELLER -->

        <div class="product-card">

          <div class="product-icon">
            🏪
          </div>

          <h3>Famehead Email Seller</h3>

          <p>
            Layanan email seller untuk kebutuhan digital.
          </p>

          <div class="price">
            Rp 17.000
          </div>

          <a
            href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order%20Famehead%20Email%20Seller%20Rp17.000."
            target="_blank"
            class="order-btn">
            Order Sekarang
          </a>

        </div>
        
        <!-- PRODUK BARU DENGAN GAMBAR (POSISI YANG BENAR) -->
        <div class="product-card">
          
          <!-- Bagian Gambar -->
          <img src="nama-gambar-kamu.jpg" alt="Produk Baru" style="width: 100%; border-radius: 14px; margin-bottom: 20px; object-fit: cover; aspect-ratio: 1/1;">
           <!-- YOUTUBE PREMIUM 1 BULAN -->
        <div class="product-card">
          
          <!-- Bagian Gambar -->
          <img src="youtube.jpg" alt="Youtube Premium" style="width: 100%; border-radius: 14px; margin-bottom: 20px; object-fit: cover; aspect-ratio: 1/1;">

          <h3>Youtube Premium 1 Bulan</h3>
          
          <p>
            Akun premium, garansi penuh 30 hari.
          </p>

          <div class="price">
            Rp 35.000
          </div>

          <a
            href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order%20Youtube%20Premium%201%20Bulan%20Rp35.000."
            target="_blank"
            class="order-btn">
            Order Sekarang
          </a>

        </div>
          <h3>Nama Produk Barumu</h3>
          
          <p>
            Tulis penjelasan singkat tentang produk barumu di sini.
          </p>

          <div class="price">
            Rp 50.000
          </div>

          <a
            href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20order%20Produk%20Baru."
            target="_blank"
            class="order-btn">
            Order Sekarang
          </a>

        </div>

      </div>

    </div>

  </section>


  <!-- ================= PROMO ================= -->

  <section id="promo">

    <div class="container">

      <div class="promo-box">

        <h2>🔥 Promo Natsumi Digital</h2>

        <p>
          Dapatkan produk digital dengan harga hemat.
          Klik tombol di bawah untuk melihat pilihan produk dan melakukan pemesanan.
        </p>

        <a
          href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20mau%20lihat%20promo%20yang%20tersedia."
          target="_blank"
          class="btn btn-primary">
          💬 Tanya Promo
        </a>

      </div>

    </div>

  </section>


  <!-- ================= CARA ORDER ================= -->

  <section id="cara-order">

    <div class="container">

      <div class="section-title">

        <h2>Cara Order</h2>

        <p>
          Pesan produk digital dengan mudah.
        </p>

      </div>


      <div class="steps">


        <div class="step">

          <div class="step-number">
            1
          </div>

          <h3>Pilih Produk</h3>

          <p>
            Pilih produk digital yang ingin kamu beli.
          </p>

        </div>


        <div class="step">

          <div class="step-number">
            2
          </div>

          <h3>Hubungi WhatsApp</h3>

          <p>
            Klik tombol Order dan kirim pesan melalui WhatsApp.
          </p>

        </div>


        <div class="step">

          <div class="step-number">
            3
          </div>

          <h3>Selesaikan Pesanan</h3>

          <p>
            Ikuti instruksi admin sampai pesanan selesai.
          </p>

        </div>


      </div>

    </div>

  </section>


  <!-- ================= CTA ================= -->

  <section class="cta">

    <div class="container">

      <h2>Siap Order?</h2>

      <p>
        Hubungi Natsumi Digital sekarang.
      </p>

      <a
        href="https://wa.me/6282249211189?text=Halo%20Natsumi%20Digital%2C%20saya%20ingin%20order."
        target="_blank"
        class="btn btn-primary">
        💬 Order Via WhatsApp
      </a>

    </div>

  </section>


  <!-- ================= FOOTER ================= -->

  <footer>

    <div class="footer-content">

      <div class="footer-logo">
        NATSUMI<span>DIGITAL</span>
      </div>

      <div class="copyright">
        © 2026 Natsumi Digital. All rights reserved.
      </div>

    </div>

  </footer>

</body>
</html>
