<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Büyükkoz Ticaret | BYKBZ</title>
    <style>
        * {
            box-sizing: border-box;
        }
        
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: #f4f4f4;
            line-height: 1.6;
        }
        
        header {
            background: #222;
            color: white;
            padding: 20px;
            text-align: center;
        }
        
        h1 {
            margin: 0;
            font-size: 28px;
            font-weight: bold;
        }
        
        nav {
            background: #444;
            padding: 10px;
            text-align: center;
        }
        
        nav a {
            color: white;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            transition: color 0.3s ease;
        }
        
        nav a:hover {
            color: #fcc000;
        }
        
        section {
            padding: 40px;
            max-width: 1200px;
            margin: 0 auto;
        }
        
        h2 {
            margin-bottom: 20px;
            color: #333;
            text-align: center;
            font-size: 24px;
        }
        
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        
        .card {
            background: white;
            border-radius: 8px;
            padding: 20px;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 20px rgba(0,0,0,0.15);
        }
        
        .card img {
            max-width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 6px;
            margin-bottom: 15px;
        }
        
        .card h3 {
            color: #222;
            margin: 0 0 10px 0;
            font-size: 18px;
        }
        
        .card p {
            color: #666;
            margin: 0;
            font-size: 14px;
        }
        
        .hero {
            background: linear-gradient(135deg, #444 0%, #222 100%);
            color: white;
            text-align: center;
            padding: 60px 20px;
            margin-bottom: 40px;
        }
        
        .hero h1 {
            font-size: 36px;
            margin: 0 0 20px 0;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        }
        
        .hero p {
            font-size: 18px;
            margin: 0;
            opacity: 0.9;
        }
        
        footer {
            background: #222;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
        }
        
        footer p {
            margin: 5px 0;
        }
        
        .footer-links {
            margin-top: 10px;
        }
        
        .footer-links a {
            color: #fcc000;
            text-decoration: none;
            margin: 0 10px;
            font-size: 14px;
        }
        
        .footer-links a:hover {
            text-decoration: underline;
        }
        
        /* Responsive Design */
        @media (max-width: 768px) {
            .hero h1 {
                font-size: 28px;
            }
            
            .hero p {
                font-size: 16px;
            }
            
            section {
                padding: 20px;
            }
            
            nav a {
                display: block;
                margin: 10px 0;
            }
        }
        
        /* Animasyon */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .card {
            animation: fadeIn 0.6s ease forwards;
        }
        
        .card:nth-child(1) { animation-delay: 0.1s; }
        .card:nth-child(2) { animation-delay: 0.2s; }
        .card:nth-child(3) { animation-delay: 0.3s; }
        .card:nth-child(4) { animation-delay: 0.4s; }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>BYKBZ | Büyükkoz</h1>
        <p>Ticaret</p>
    </header>
    
    <!-- Navigation -->
    <nav>
        <a href="#anasayfa">Ana Sayfa</a>
        <a href="#urunler">Ürünler</a>
        <a href="#hakkimizda">Hakkımızda</a>
        <a href="#iletisim">İletişim</a>
        <a href="#teklif">Teklif Al</a>
    </nav>
    
    <!-- Hero Section -->
    <section class="hero">
        <h1>Büyükkoz Ticaret</h1>
        <p>Yapı Malzemeleri ve İnşaat Çözümleri</p>
    </section>
    
    <!-- Main Content -->
    <section id="urunler">
        <h2>Ürünlerimiz</h2>
        <div class="grid">
            <div class="card">
                <img src="https://via.placeholder.com/220x150/444/ffffff?text=Yapı+Malzemeleri" alt="Yapı Malzemeleri">
                <h3>Yapı Malzemeleri</h3>
                <p>Çimento, demir, tuğla ve diğer temel yapı malzemeleri. Kaliteli ve dayanıklı ürünler.</p>
            </div>
            
            <div class="card">
                <img src="https://via.placeholder.com/220x150/444/ffffff?text=İzolasyon" alt="İzolasyon">
                <h3>İzolasyon</h3>
                <p>Isı, ses ve su izolasyon ürünleri. Enerji verimliliği için en iyi çözümler.</p>
            </div>
            
            <div class="card">
                <img src="https://via.placeholder.com/220x150/444/ffffff?text=Sıvalar" alt="Sıvalar">
                <h3>Sıvalar</h3>
                <p>İç ve dış cephe sıvaları, dekoratif sıvalar. Uzun ömürlü yüzey kaplamaları.</p>
            </div>
            
            <div class="card">
                <img src="https://via.placeholder.com/220x150/444/ffffff?text=Sistemler" alt="Sistemler">
                <h3>Sistemler</h3>
                <p>Komple yapı sistemleri ve entegre çözümler. Proje bazlı hizmetler.</p>
            </div>
        </div>
    </section>
    
    <!-- About Section -->
    <section id="hakkimizda" style="background: #f9f9f9; padding: 40px 20px; margin: 40px 0;">
        <h2>Hakkımızda</h2>
        <div style="max-width: 800px; margin: 0 auto; text-align: center;">
            <p>Büyükkoz Ticaret, 20 yılı aşkın süredir yapı malzemeleri sektöründe hizmet vermektedir. Kalite, güvenilirlik ve müşteri memnuniyetini ön planda tutarak, sektörün en iyilerinden biri olmaktayız.</p>
            <br>
            <p>Modern tesislerimizde depoladığımız ürünlerimizle, Türkiye'nin her yerine hızlı ve güvenilir teslimat yapıyoruz.</p>
        </div>
    </section>
    
    <!-- Contact Section -->
    <section id="iletisim">
        <h2>İletişim</h2>
        <div style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 30px;">
            <div class="card">
                <h3>📍 Adres</h3>
                <p>Osmangazi Mah. 15. Cad. No: 25<br>Bağcılar / İstanbul</p>
            </div>
            <div class="card">
                <h3>📞 Telefon</h3>
                <p>+90 212 555 01 23<br>+90 532 123 45 67</p>
            </div>
            <div class="card">
                <h3>✉️ E-posta</h3>
                <p>info@buyukkoz.com<br>satıs@buyukkoz.com</p>
            </div>
            <div class="card">
                <h3>🕒 Çalışma Saatleri</h3>
                <p>Pazartesi-Cuma: 08:00-18:00<br>Cumartesi: 09:00-15:00</p>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer>
        <div style="max-width: 1200px; margin: 0 auto;">
            <p><strong>BÜYÜKKOZ TİCARET</strong> | Yapı Malzemeleri • İzolasyon • Sıvalar • Sistemler</p>
            <div class="footer-links">
                <a href="#iletisim">İletişim</a> |
                <a href="#teklif">Teklif Al</a> |
                <a href="#hakkimizda">Hakkımızda</a> |
                <a href="#">Gizlilik Politikası</a>
            </div>
            <p style="margin-top: 15px; font-size: 12px; opacity: 0.8;">
                &copy; 2025 Büyükkoz Ticaret Ltd. Şti. Tüm hakları saklıdır.
            </p>
        </div>
    </footer>
</body>
</html>
