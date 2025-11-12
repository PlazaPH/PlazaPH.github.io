<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>DonEmilianoCARS — Certified Exclusivity</title>

<!-- Fonts -->
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Cinzel:wght@400;700&display=swap" rel="stylesheet">

<style>
  :root {
    --gold: #d4af37;
    --burgundy: #6d0f0f;
    --cream: #f6efe6;
    --bg: #070707;
    --muted: #bdb8b1;
    --white: #ffffff;
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }

  body {
    background: var(--bg);
    color: var(--gold);
    font-family: "Playfair Display", serif;
  }

  /* Masthead */
  .masthead {
    background: var(--burgundy);
    color: var(--gold);
    font-size: 14px;
    padding: 6px 22px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  /* Header */
  header.sitehead {
    position: sticky; top: 0; z-index: 1200;
    display: flex; align-items: center; gap: 20px;
    background: linear-gradient(180deg, rgba(0,0,0,0.4), rgba(0,0,0,0.1));
    padding: 14px 26px;
  }

  .brand {
    display: flex; align-items: center; gap: 14px;
  }

  .brand img.logo {
    height: 72px; width: auto;
    border-radius: 8px;
    box-shadow: 0 6px 20px rgba(0,0,0,0.6);
  }

  .title { font-family: 'Cinzel', serif; font-size: 20px; letter-spacing: 2px; }

  .mini-nav { margin-left: auto; display: flex; gap: 18px; }
  .mini-nav a {
    color: var(--muted); text-decoration: none; font-size: 14px;
    transition: color 0.2s ease;
  }
  .mini-nav a:hover { color: var(--gold); }

  /* Hero */
  .hero {
    position: relative;
    height: 80vh;
    background: url('DEC/Emblem.jpg') center/cover no-repeat;
    display: flex; align-items: center; justify-content: center;
    text-align: center;
  }

  .hero::after {
    content: ""; position: absolute; inset: 0;
    background: rgba(0,0,0,0.6);
  }

  .hero-inner { position: relative; z-index: 2; color: var(--gold); }

  .hero-logo { height: 120px; margin-bottom: 10px; }

  .hero-title {
    font-family: 'Cinzel', serif;
    font-size: 54px;
    letter-spacing: 4px;
    text-shadow: 0 6px 25px rgba(0,0,0,0.6);
  }

  .btn {
    background: linear-gradient(180deg, #7b0f0f, #490707);
    color: var(--gold);
    padding: 12px 32px;
    border-radius: 40px;
    text-decoration: none;
    font-weight: bold;
    transition: all 0.3s ease;
  }

  .btn:hover {
    transform: translateY(-4px);
    box-shadow: 0 10px 25px rgba(212,175,55,0.2);
    color: #fff;
  }

  /* Welcome */
  .welcome {
    background: var(--cream);
    color: #3b2b1b;
    text-align: center;
    padding: 72px 18px;
  }

  .welcome h2 { font-family: 'Cinzel', serif; margin-bottom: 20px; }
  .welcome p { max-width: 800px; margin: 0 auto; line-height: 1.8; }

  /* Featured */
  .featured {
    display: grid; grid-template-columns: repeat(auto-fit,minmax(300px,1fr));
    gap: 24px; padding: 60px; background: var(--bg);
  }

  .tile {
    position: relative; height: 420px; overflow: hidden;
    border-radius: 12px; cursor: pointer;
  }

  .tile img { width: 100%; height: 100%; object-fit: cover; filter: brightness(40%); transition: transform 0.4s ease; }
  .tile:hover img { transform: scale(1.05); }

  .tile-text {
    position: absolute; bottom: 30px; left: 30px; color: #fff;
  }

  /* Car Collection */
  .collection {
    padding: 56px 6%;
    background: var(--bg);
  }

  .car-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(260px,1fr));
    gap: 24px;
  }

  .car-card {
    background: #0f0f0f;
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.3s ease;
  }

  .car-card:hover { transform: translateY(-8px); }

  .car-card img {
    width: 100%;
    height: 180px;
    object-fit: cover;
  }

  .car-card .info {
    padding: 12px;
    color: var(--gold);
  }

  footer.sitefoot {
    background: var(--burgundy);
    color: var(--gold);
    padding: 40px 6%;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(200px,1fr));
    gap: 20px;
  }

  footer a {
    color: var(--gold);
    text-decoration: none;
  }

  footer a:hover {
    color: #fff;
  }
</style>
</head>

<body>

  <!-- Masthead -->
  <div class="masthead">
    <div>Email: <strong>DonEmel@gmail.com</strong></div>
    <div>Follow Us:
      <a href="#">Instagram</a> |
      <a href="#">Facebook</a>
    </div>
  </div>

  <!-- Header -->
  <header class="sitehead">
    <div class="brand">
      <img class="logo" src="DEC/Don Emiliano.png" alt="Don Emiliano Logo">
      <div>
        <div class="title">DonEmilianoCARS</div>
        <div style="font-size:12px;color:var(--muted)">Certified Exclusivity</div>
      </div>
    </div>
    <div class="mini-nav">
      <a href="#home">Home</a>
      <a href="#collection">Collection</a>
      <a href="#contact">Contact</a>
    </div>
  </header>

  <!-- Hero -->
  <section class="hero" id="home">
    <div class="hero-inner">
      <img class="hero-logo" src="DEC/Don Emiliano.png" alt="Logo">
      <h1 class="hero-title">DonEmilianoCARS</h1>
      <p>Certified Exclusivity</p>
      <div style="margin-top:20px;">
        <a href="#collection" class="btn">Browse Collection</a>
      </div>
    </div>
  </section>

  <!-- Welcome -->
  <section class="welcome">
    <h2>True Luxury is Flawless.</h2>
    <p>Welcome to DonEmilianoCARS — curators of certified, pre-owned luxury. Our vehicles embody exclusivity and precision craftsmanship for the discerning driver.</p>
  </section>

  <!-- Featured -->
  <section class="featured">
    <div class="tile">
      <img src="DEC/Emblem.jpg" alt="Emblem">
      <div class="tile-text">
        <h3>The Collection</h3>
        <a href="#collection" class="btn">Browse Now</a>
      </div>
    </div>

    <div class="tile">
      <img src="DEC/Inspection.jpg" alt="Inspection">
      <div class="tile-text">
        <h3>The Guarantee</h3>
        <a href="#contact" class="btn">Our Promise</a>
      </div>
    </div>
  </section>

  <!-- Collection -->
  <section class="collection" id="collection">
    <h2 style="text-align:center;color:var(--gold);margin-bottom:20px;">Our Premium Collection</h2>
    <div class="car-grid">
      <div class="car-card">
        <img src="DEC/BMW.jpg" alt="BMW X5">
        <div class="info">
          <h4>BMW X5 (2022)</h4>
          <p>$65,000 • Black, White</p>
        </div>
      </div>

      <div class="car-card">
        <img src="DEC/Mercedes.jpg" alt="Mercedes E-Class">
        <div class="info">
          <h4>Mercedes E-Class (2021)</h4>
          <p>$55,000 • Silver, Black</p>
        </div>
      </div>

      <div class="car-card">
        <img src="DEC/Tesla.jpg" alt="Tesla Model S">
        <div class="info">
          <h4>Tesla Model S (2023)</h4>
          <p>$90,000 • Red, Black</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="sitefoot">
    <div>
      <h4>DonEmilianoCARS</h4>
      <p>Certified Exclusivity — Trusted Luxury</p>
    </div>
    <div>
      <h4>Links</h4>
      <a href="#home">Home</a><br>
      <a href="#collection">Collection</a><br>
      <a href="#contact">Contact</a>
    </div>
    <div>
      <h4>Contact</h4>
      <p>Email: DonEmel@gmail.com</p>
      <p>Phone: +63 912 345 6789</p>
    </div>
  </footer>

</body>
</html>
