<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Perpustakaan Martha Sagala</title>

    <!-- fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Miniver&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      rel="stylesheet"
    />

    <!-- my style -->
    <link rel="stylesheet" href="css/style.css" />
  </head>
  <body>
    <!-- navbar start -->
    <nav class="navbar">
      <a hreef="#" class="navbar-logo"
        >Perpustakaan<span>Martha Sagala</span></a
      >

      <div class="navbar-nav">
        <a href="#">Home</a>
        <a href="#about">Tentang Kami</a>
        <a href="#kontak">Kontak Kami</a>
        <a href="#arsip">Arsip Kami</a>
      </div>
    </nav>
    <!-- navbar end -->

    <!-- hero section start -->
    <section class="hero" id="home">
      <main class="content">
        <h1>Selamat Datang</h1>
        <p>
          Selamat datang di perpustakaan pribadi saya. Perpustakaan ini sebagai
          media untuk menyimpan hasil materi kuliah, kreatifitas, dan proyek
          yang berhasil saya kerjakan. hal ini berguna untuk memudahkan saya
          dalam sistem temu balik dan sebagai media untuk mengembangkan
          kreatifitas.
        </p>
      </main>
    </section>
    <!-- hero section end -->

    <!-- about section start -->
    <section id="about" class="about">
      <h2>Tentang Kami</h2>
      <p>
        Saya Martha Sagala mahasiswa Perpustakaan dan Sains Informasi,
        Universitas Sumatera Utara. Saya adalah pembuat dari website ini.
      </p>
      <div class="row"></div>
      <div class="content">
        <h3>Kerjasama</h3>
        <p>
          Perpustakaan milik saya sudah bekerjasama dengan
          <a href="https://www.unud.ac.id/">Perpustakaan UDAYANA</a>
        </p>
      </div>
    </section>
    <!-- about section end -->

    <!-- kontak section start -->
    <section id="kontak" class="kontak">
      <h2>Kontak Kami</h2>
      <p>
        Bagaimana dengan pengalaman anda mengunjungi website saya. Jika terdapat
        pesan atau pertanyaan dapat menghubungi saya melalui form di bawah ini.
      </p>

      <div class="row">
        <iframe
          src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d7964.224008327102!2d98.65196493488772!3d3.561676000000019!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x30312fe03ed8450b%3A0xe84941c195268efc!2sUniversitas%20Sumatera%20Utara!5e0!3m2!1sid!2sid!4v1741626405439!5m2!1sid!2sid"
          allowfullscreen=""
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
        ></iframe>

        <form action="">
          <div class="input-group">
            <i data-feather="user"></i>
            <input type="text" placeholder="Nama" />
          </div>
          <div class="input-group">
            <i data-feather="email"></i>
            <input type="text" placeholder="Email" />
          </div>
          <div class="input-group">
            <i data-feather="pesan"></i>
            <input type="text" placeholder="Pesan" />
          </div>
          <button type="submit" class="btn">Kirim Pesan</button>
        </form>
      </div>
    </section>
    <!-- kontak section end -->

    <!-- my javascript -->
    <script scr="js/script,js"></script>
  </body>
</html>
