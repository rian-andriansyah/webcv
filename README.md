<!DOCTYPE html>
<html>
<head>
  <title>Website Pribadi</title>
  <style>
    body {
      font-family: 'Playfair Display', serif;
      margin: 0;
      padding: 0;
    }
    
    .header {
      text-align: left;
      background-image: url("https://www.example.com/path/to/header-image.jpg");
      background-size: cover;
      background-position: center;
      padding: 226px 0;
      color: #261088;
      font-size: 29px;
      display: none; /* Menyembunyikan header secara default */
    }
    
    .menu {
      background-color: #ccc;
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 999;
    }
    
    .menu ul {
      display: flex;
      list-style: none;
      margin: 0;
      padding: 0;
    }
    
    .menu li {
      padding: 10px;
    }
    
    .menu a {
      color: #0f0303;
      text-decoration: none;
      transition: color 0.3s;
    }
    
    .menu a:hover {
      color: #ccc;
    }
    
    .menu-right {
      margin-left: auto;
      font-size: 20px;
    }
    
    .content {
      margin-top: 70px;
      padding: 20px;
    }
    
    .content h2 {
      font-size: 24px;
    }
    
    .content p {
      margin-bottom: 10px;
    }
    
    .footer {
      text-align: center;
      background-color: #f1f1f1;
      padding: 10px;
      clear: both;
    }
    
    .gallery {
      margin-top: 70px;
      padding: 20px;
    }
    
    .gallery h2 {
      font-size: 24px;
    }
    
    .gallery img {
      max-width: 100%;
      height: auto;
      margin-bottom: 10px;
    }
    
    /* Perubahan untuk membuat menu responsif */
    @media screen and (max-width: 768px) {
      .menu ul {
        flex-direction: column;
        text-align: center;
      }
      
      .menu li {
        padding: 10px 0;
      }
      
      .menu-right {
        font-size: 16px;
      }
    }
  </style>
  <script>
    function showHomeHeader() {
      var header = document.querySelector('.header');
      header.style.display = 'block';
    }
  </script>
</head>
<body>
  <div class="menu">
    <ul>
      <li><a href="#" onclick="showHomeHeader();">Home</a></li>
      <li><a href="#profile">Profil / CV</a></li>
      <li><a href="#gallery">Galeri</a></li>
    </ul>
    <div class="menu-right">rianBoma</div>
  </div>

  <div class="header">
    <h1>Welcome to Rian Website</h1>
    <h2>Saya adalah Junior developer yang berfokus dalam pengembangan web atau Desain UI dan UX</h2>
  </div>

  <div class="content">
    <div id="profile">
      <h2>Pendidikan</h2>
      <p>Nama: Rian Andriansyah</p>
      <p>Alamat: Jalan Citeureup Desa Citeireup, Kecamatan Kawali, Kabupaten Ciamis, Provinsi Jawa Barat</p>
      <p>Pendidikan Formal:</p>
      <ul>
        <li>Sekolah Dasar Negeri 1 Citeureup</li>
        <li>Sekolah Kejuruan Negeri 1 Kawali</li>
        <li>STIMIK DCI Tasikmalaya</li>
      </ul>
      <p>Pelatihan yang pernah diikuti:</p>
      <ul>
        <li>Pelatihan Sepakbola</li>
        <li>Pelatihan Komputer</li>
      </ul>
      <p>Pengalaman Kerja:</p>
      <ul>
        <li>PT Piranti Teknik Indonesia (2022-Sekarang)</li>
      </ul>
    </div>
  </div>
  
  <div class="gallery">
    <div id="gallery">
      <h2>Tulisan</h2>
      <img src="wisata.jpg" alt="Foto 1">
      <img src="futsal.jpg" alt="Foto 2">
      <img src="kemah.jpg" alt="Foto 3">
      <img src="voly.jpg" alt="Foto 4">
    </div>
  </div>
  
  <div class="footer">
    <p>Hak Cipta &copy; 2023 Website Rian Andriansyah</p>
  </div>
</body>
</html>

