# New-Style-Barber
<!DOCTYPE html>
<html lang="ku">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>New Style Barber</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Cairo', sans-serif;
      background: #0f172a;
      color: #f1f5f9;
    }
    header {
      background: linear-gradient(90deg,#111827,#1e293b);
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #f59e0b;
    }
    .logo {
      font-size: 32px;
      font-weight: 700;
      letter-spacing: 2px;
      color: #f59e0b;
    }
    .logo span {
      color: #f1f5f9;
    }
    nav {
      margin-top: 10px;
    }
    nav a {
      color: #f1f5f9;
      margin: 0 12px;
      text-decoration: none;
      font-weight: 600;
    }
    nav a:hover { color: #f59e0b; }
    .hero {
      padding: 80px 20px;
      text-align: center;
      background: linear-gradient(135deg,#020617,#0f172a);
    }
    .hero h1 {
      font-size: 42px;
      margin-bottom: 10px;
      text-shadow: 0 2px 10px rgba(0,0,0,0.7);
    }
    .hero p {
      font-size: 18px;
      opacity: 0.9;
    }
    .btn {
      display: inline-block;
      margin-top: 20px;
      padding: 12px 24px;
      background: #f59e0b;
      color: #111827;
      border-radius: 30px;
      text-decoration: none;
      font-weight: 700;
    }
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }
    h2 {
      text-align: center;
      color: #f59e0b;
      margin-bottom: 30px;
    }
    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
      gap: 20px;
    }
    .card {
      background: #1e293b;
      padding: 20px;
      border-radius: 16px;
      text-align: center;
      box-shadow: 0 4px 20px rgba(0,0,0,0.4);
    }
    .card h3 { color: #f59e0b; }
    footer {
      background: #020617;
      text-align: center;
      padding: 30px 20px;
      border-top: 1px solid #1e293b;
    }
    .phones p {
      margin: 6px 0;
      font-size: 16px;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">New <span>Style</span> Barber</div>
    <nav>
      <a href="#home">سەرەتا</a>
      <a href="#services">خزمەتگوزاری</a>
      <a href="#contact">پەیوەندی</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h1>New Style Barber</h1>
    <p>باشترین سەرتاشخانە بۆ ستایلی نوێ و جوان</p>
    <img src="/mnt/data/ChatGPT Image 17 فبراير 2026، 05_13_03 م.png" alt="New Style Barber Logo" style="max-width:320px;width:100%;border-radius:16px;margin-top:20px;box-shadow:0 6px 30px rgba(0,0,0,0.6);">
    <br>
    <a class="btn" href="#contact">پەیوەندی بکە</a>
  </section>

  <section id="services">
    <h2>خزمەتگوزاریەکان</h2>
    <div class="services">
      <div class="card">
        <h3>قژ بڕین</h3>
        <p>ستایلی نوێ و مۆدێرن بۆ هەموو تەمەن</p>
      </div>
      <div class="card">
        <h3>ریش تەراشین</h3>
        <p>شێوەی پرۆفیشناڵ و ڕێکخستنی ورد</p>
      </div>
      <div class="card">
        <h3>ستایلینگ</h3>
        <p>جێهێشتنی جەستەی قژ بە باشترین مەتریاڵ</p>
      </div>
      <div class="card">
        <h3>VIP مەساج</h3>
        <p>مەساجی دەموو جاو بۆ ئارامبوونەوە و جوانکاری ڕوو</p>
      </div>
      <div class="card">
        <h3>فیشیال (پاککردنەوەی ڕوو)</h3>
        <p>پاککردنەوە و تازەکردنەوەی پوست</p>
      </div>
      <div class="card">
        <h3>بۆیەی قژ</h3>
        <p>بۆیەی کوالیتی بەرز و ڕەنگی مۆدێرن</p>
      </div>
      <div class="card">
        <h3>سەشوار و برشینگ</h3>
        <p>جوانکاری کۆتایی بۆ ڕووکاری تەواو</p>
      </div>
      <div class="card">
        <h3>پاککردنەوەی منداڵان</h3>
        <p>خزمەتگوزاری تایبەتی بۆ منداڵان</p>
      </div>
      <div class="card">
        <h3>پەکەجی زاوای</h3>
        <p>ستایلی تەواو بۆ ڕۆژی زاوای</p>
      </div>
    </div>
  </section>

  <section id="gallery" style="background:#000;">
    <h2>وێنە</h2>
    <div style="text-align:center">
      <img src="/mnt/data/A_logo_for_\"New_Style_Barber\"_is_displayed_in_a_di.png" alt="New Style Barber Logo" style="max-width:320px;width:100%;border-radius:16px;box-shadow:0 4px 20px rgba(0,0,0,0.5);">
      <p style="margin-top:10px">لۆگۆی فەرمی New Style Barber</p>
    </div>
  </section>

  <section id="contact">
    <h2>پەیوەندی</h2>
    <div class="phones">
      <p><strong>Nihad:</strong> 07504298577</p>
      <p><strong>Mujib:</strong> 07504139323</p>
    </div>
  </section>

  <footer>
    © 2026 New Style Barber - All Rights Reserved
  </footer>
</body>
</html>
