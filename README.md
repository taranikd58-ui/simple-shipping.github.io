# simple-shipping.github.io<!doctype html>
<html lang="bn">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>আমার ওয়েবসাইট</title>
  <style>
    body{font-family:system-ui,-apple-system,Segoe UI,Roboto,'Noto Sans Bengali',sans-serif;margin:0;color:#222}
    header{background:#0f172a;color:#fff;padding:20px 16px}
    .container{max-width:900px;margin:0 auto;padding:20px}
    nav{display:flex;gap:12px;align-items:center}
    a.logo{font-weight:700;color:#fff;text-decoration:none}
    a.link{color:#a8b3c6;text-decoration:none}
    .hero{background:#f8fafc;padding:40px;border-radius:8px;margin-top:18px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px;margin-top:18px}
    .card{background:#fff;padding:16px;border-radius:8px;box-shadow:0 6px 18px rgba(15,23,42,0.06)}
    footer{margin-top:28px;padding:18px 0;color:#555;text-align:center}
    @media (max-width:520px){header{padding:14px}}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <nav>
        <a class="logo" href="#">TomarSite</a>
        <div style="flex:1"></div>
        <a class="link" href="#about">About</a>
        <a class="link" href="#services">Services</a>
        <a class="link" href="#contact">Contact</a>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <h1>স্বাগতম — তোমার ওয়েবসাইট শুরু করার জায়গা</h1>
      <p>এটি একটি বেসিক টেমপ্লেট। তুমি চাইলে আমি এটাকে কাস্টমাইজ করে দেব — রং, লেখা, ছবি, এবং পেজ গুলো যোগ করে।</p>
    </section>

    <section id="about" class="grid">
      <div class="card">
        <h3>About</h3>
        <p>এখানে তোমার সম্পর্কে ছোট্ট বিবরণ থাকবে — নাম, কাজ, এবং লক্ষ্য।</p>
      </div>
      <div class="card" id="services">
        <h3>Services</h3>
        <p>যে সার্ভিস বা বিষয় তুমি দেবে তার সংক্ষিপ্ত তালিকা।</p>
      </div>
      <div class="card" id="contact">
        <h3>Contact</h3>
        <p>ইমেইল: you@example.com<br>ফোন: +91-XXXXXXXXXX</p>
      </div>
    </section>

    <footer>
      © {new Date().getFullYear()} TomarSite — Built with ❤️
    </footer>
  </main>

  <script>
    // এই লাইনটি শুধু footer এ বর্তমান বছর দেখাতে
    document.querySelector('footer').innerHTML = '© ' + new Date().getFullYear() + ' TomarSite — Built with ❤️';
  </script>
</body>
</html>
