<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>LAU LÖSEV FAYDA TOPLULUĞU</title>
  
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" />
  <!-- AOS Animasyon CSS -->
  <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet" />

  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fff8f6;
    }
    header {
      background-color: #b71c1c;
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 2.8em;
    }
    header p {
      font-size: 1.2em;
      margin-top: 10px;
    }
    nav a {
      color: #b71c1c !important;
      font-weight: bold;
      margin: 0 10px;
    }
    h2 {
      color: #c62828;
      margin-bottom: 20px;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }
    footer {
      background-color: #b71c1c;
      color: white;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>LAU LÖSEV FAYDA TOPLULUĞU</h1>
    <p>LÖSEV GÜNEŞTEN DOĞACAK</p>
  </header>

  <nav class="navbar navbar-expand-lg navbar-light bg-light sticky-top">
    <div class="container">
      <a class="navbar-brand fw-bold" href="#">Topluluk</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
        aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ms-auto">
          <li class="nav-item"><a class="nav-link" href="#hakkimizda">Hakkımızda</a></li>
          <li class="nav-item"><a class="nav-link" href="#etkinlikler">Etkinlikler</a></li>
          <li class="nav-item"><a class="nav-link" href="#galeri">Galeri</a></li>
          <li class="nav-item"><a class="nav-link" href="#iletisim">İletişim</a></li>
        </ul>
      </div>
    </div>
  </nav>

  <section id="hakkimizda" class="container py-5" data-aos="fade-up">
    <h2>Hakkımızda</h2>
    <p>
      LAU LÖSEV Fayda Topluluğu, Kuzey Kıbrıs Türk Cumhuriyeti’nde Lösev’i temsilen kurulan ilk ve tek fayda topluluğudur.
      Lösev, lösemili çocuklar ve yetişkin kanser hastaları için hiçbir devlet desteği almadan faaliyet gösteren, gönüllülük esasına dayalı bir vakıftır.
      Bizler de bu topluluğun bir uzantısı olarak üniversitemizde kanser farkındalığı yaratmak, destek toplamak ve yardım organizasyonları düzenlemek amacıyla yola çıktık.
      Yıl boyunca gerçekleştirdiğimiz etkinliklerle hem sosyal bilinci artırıyor, hem de öğrenciler arasında dayanışma ve toplumsal duyarlılık kültürünü geliştiriyoruz.
      LAU LÖSEV Fayda Topluluğu olarak, umutla başlayan her adımın büyük farklar yaratacağına inanıyoruz.
    </p>
  </section>

  <section id="etkinlikler" class="bg-light py-5" data-aos="fade-right">
    <div class="container">
      <h2>Etkinlikler</h2>
      <ul class="list-group list-group-flush">
        <li class="list-group-item">🎗️ <strong>Farkındalık Haftası Standı:</strong> Kampüste bilgilendirici broşürler ve mini söyleşilerle kanser farkındalığı artırıldı.</li>
        <li class="list-group-item">🎬 <strong>Lösev Film Gecesi:</strong> Lösev belgeseli gösterimi ve ardından açık oturum gerçekleştirildi.</li>
        <li class="list-group-item">🎁 <strong>Yeni Yıl Hediye Kampanyası:</strong> Lösemili çocuklara el yapımı kartlar ve küçük hediyeler gönderildi.</li>
      </ul>
    </div>
  </section>

  <section id="galeri" class="container py-5" data-aos="zoom-in">
    <h2>Galeri</h2>
    <div class="row">
      <div class="col-md-4 mb-3"><img src="https://via.placeholder.com/300x200?text=Etkinlik+1" alt="Etkinlik 1" class="img-fluid" /></div>
      <div class="col-md-4 mb-3"><img src="https://via.placeholder.com/300x200?text=Etkinlik+2" alt="Etkinlik 2" class="img-fluid" /></div>
      <div class="col-md-4 mb-3"><img src="https://via.placeholder.com/300x200?text=Etkinlik+3" alt="Etkinlik 3" class="img-fluid" /></div>
    </div>
  </section>

  <section id="iletisim" class="bg-light py-5" data-aos="fade-left">
    <div class="container">
      <h2>İletişim</h2>
      <p>Bizimle iletişime geçmek için:</p>
      <ul>
        <li><strong>Instagram:</strong> <a href="#">@lau.losevkulubu</a></li>
        <li><strong>E-posta:</strong> info@losevfayda.org</li>
      </ul>
    </div>
  </section>

  <footer>
    <p>© 2025 LAU Lösev Fayda Topluluğu. Tüm Hakları Saklıdır.</p>
  </footer>

  <!-- Bootstrap JS Bundle -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
  <!-- AOS Animasyon JS -->
  <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
  <script>
    AOS.init();
  </script>
</body>
</html>
