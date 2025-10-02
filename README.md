<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Geetha Service Center — TV Sales & Repair</title>
  <meta name="description" content="Geetha Service Center: TV sales, installation, and repair. Trusted technicians, genuine parts, and quick service." />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <style>
    :root{
      --accent:#0f6cff;
      --muted:#6b7280;
      --card-bg:#ffffff;
      --bg:#f7fafc;
      --max-width:1100px;
      --radius:12px;
      font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
      color-scheme: light;
    }
    *{box-sizing:border-box}
    body{margin:0;background:var(--bg);color:#0b1220;line-height:1.5}
    .container{max-width:var(--max-width);margin:0 auto;padding:28px}

    /* Header */
    header{display:flex;align-items:center;justify-content:space-between;gap:16px}
    .brand{display:flex;align-items:center;gap:12px}
    .logo{width:56px;height:56px;border-radius:10px;background:linear-gradient(135deg,var(--accent),#06b6d4);display:grid;place-items:center;color:white;font-weight:700}
    nav a{margin-left:18px;text-decoration:none;color:var(--muted);font-weight:600}

    /* Hero */
    .hero{display:grid;grid-template-columns:1fr 420px;gap:28px;align-items:center;margin-top:28px}
    .hero-card{background:linear-gradient(180deg,rgba(255,255,255,0.8),rgba(255,255,255,0.95));padding:28px;border-radius:var(--radius);box-shadow:0 6px 24px rgba(12,18,35,0.06)}
    .hero h1{margin:0;font-size:28px}
    .tag{display:inline-block;margin-top:10px;padding:8px 12px;background:#eef2ff;color:var(--accent);border-radius:999px;font-weight:600;font-size:13px}
    .cta-row{margin-top:18px;display:flex;gap:12px}
    .btn{display:inline-block;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700}
    .btn-primary{background:var(--accent);color:white}
    .btn-outline{border:1px solid #e6eefc;color:var(--accent);background:transparent}

    /* Services */
    .services{display:flex;gap:12px;margin-top:18px}
    .service{flex:1;padding:14px;border-radius:10px;background:var(--card-bg);box-shadow:0 4px 16px rgba(12,18,35,0.04);text-align:center}
    .service h3{margin:8px 0 4px}
    .service p{margin:0;color:var(--muted);font-size:14px}

    /* Products */
    .products{margin-top:28px}
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(220px,1fr));gap:16px}
    .card{background:var(--card-bg);border-radius:12px;overflow:hidden;box-shadow:0 6px 20px rgba(12,18,35,0.05);}
    .card img{width:100%;height:160px;object-fit:cover;display:block}
    .card-body{padding:12px}
    .price{font-weight:700}
    .muted{color:var(--muted);font-size:13px}

    /* Contact */
    .contact{display:grid;grid-template-columns:1fr 380px;gap:18px;margin-top:28px}
    form{background:var(--card-bg);padding:18px;border-radius:12px;box-shadow:0 6px 24px rgba(12,18,35,0.04)}
    label{display:block;font-weight:600;margin-bottom:6px}
    input,textarea,select{width:100%;padding:10px;border-radius:8px;border:1px solid #e6eefc;margin-bottom:12px}

    footer{margin-top:36px;padding:20px 0;text-align:center;color:var(--muted);font-size:14px}

    @media (max-width:880px){
      .hero{grid-template-columns:1fr}
      .contact{grid-template-columns:1fr}
      nav{display:none}
    }
  </style>
</head>
<body>
  <div class="container">
    <header>
      <div class="brand">
        <div class="logo">G.E</div>
        <div>
          <div style="font-weight:700">Geetha Electronics</div>
          <div style="font-size:13px;color:var(--muted)">TV Sales • Installation • Repair</div>
        </div>
      </div>
      <nav>
        <a href="#services">Services</a>
        <a href="#products">Products</a>
        <a href="#contact">Contact</a>
        <a href="O:\OneDrive\Documents\shop webpage\passwordpage.html">Login</a>
      </nav>
    </header>

    <section class="hero">
      <div class="hero-card">
        <span class="tag">Trusted since 2005</span>
        <h1>Reliable TV sales & repair in your neighborhood</h1>
        <p style="color:var(--muted);margin-top:8px">We sell major-brand LED, OLED and Smart TVs, provide professional installation and fast in-store or on-site repairs with genuine parts.</p>

        <div class="cta-row">
          <a class="btn btn-primary" href="#contact">Book a Repair</a>
          <a class="btn btn-outline" href="#products">Browse TVs</a>
        </div>

        <div class="services" id="services">
          <div class="service">
            <div style="font-size:20px;font-weight:700">Repair</div>
            <p>Panel, power board, software & sound fixes.</p>
          </div>
          <div class="service">
            <div style="font-size:20px;font-weight:700">Installation</div>
            <p>Wall-mount, smart setup, AV calibration.</p>
          </div>
          <div class="service">
            <div style="font-size:20px;font-weight:700">Sales</div>
            <p>New & refurbished TVs with warranty.</p>
          </div>
        </div>
      </div>

      <aside style="padding:18px;background:linear-gradient(180deg,#ffffff,#fbfdff);border-radius:12px;box-shadow:0 6px 20px rgba(12,18,35,0.04)">
        <div style="font-weight:700;margin-bottom:8px">Quick Info</div>
        <div class="muted">Location</div>
        <div>Sandhai Bazar, Nagalapuram, Tamil Nadu 628904</div>
        <div style="margin-top:10px;color:var(--muted)">Phone</div>
        <div><a href="tel:+919786986330" style="color:var(--accent);text-decoration:none;font-weight:700">+91 9786986330</a></div>
        <div style="margin-top:10px;color:var(--muted)">Hours</div>
        <div>Mon–Sat: 9:00am — 9:00pm</div>

        <div style="margin-top:14px">
          <a class="btn btn-primary" href="#contact">Request Pickup</a>
        </div>
      </aside>
    </section>

    <section class="products" id="products">
      <h2 style="margin:0 0 12px">Featured TVs</h2>
      <div class="grid">
        <article class="card">
          <img src="https://picsum.photos/seed/tv1/800/450" alt="Smart LED TV">
          <div class="card-body">
            <div style="display:flex;justify-content:space-between;align-items:center">
              <div>
                <div style="font-weight:700">32" Smart LED TV</div>
                <div class="muted">1080p • Smart OS • HDMI x3</div>
              </div>
              <div class="price">₹15,999</div>
            </div>
          </div>
        </article>

        <article class="card">
          <img src="https://picsum.photos/seed/tv2/800/450" alt="4K HDR TV">
          <div class="card-body">
            <div style="display:flex;justify-content:space-between;align-items:center">
              <div>
                <div style="font-weight:700">50" 4K UHD</div>
                <div class="muted">4K HDR • Dolby Vision • 60Hz</div>
              </div>
              <div class="price">₹34,499</div>
            </div>
          </div>
        </article>

        <article class="card">
          <img src="https://picsum.photos/seed/tv3/800/450" alt="OLED TV">
          <div class="card-body">
            <div style="display:flex;justify-content:space-between;align-items:center">
              <div>
                <div style="font-weight:700">55" OLED</div>
                <div class="muted">Self-lit pixels • Perfect blacks</div>
              </div>
              <div class="price">₹19,999</div>
            </div>
          </div>
        </article>

        <article class="card">
          <img src="https://picsum.photos/seed/tv4/800/450" alt="Refurbished TV">
          <div class="card-body">
            <div style="display:flex;justify-content:space-between;align-items:center">
              <div>
                <div style="font-weight:700">42" Refurbished</div>
                <div class="muted">Tested • 3-month warranty</div>
              </div>
              <div class="price">₹11,499</div>
            </div>
          </div>
        </article>

      </div>
    </section>

    <section class="contact" id="contact">
      <form action="#" onsubmit="alert('Request submitted — we will call you to confirm.');return false;">
        <h3 style="margin-top:0">Book a service / Ask a question</h3>
        <label for="name">Name</label>
        <input id="name" name="name" type="text" placeholder="Your full name" required>
        <label for="phone">Phone</label>
        <input id="phone" name="phone" type="tel" placeholder="Mobile number" required>
        <label for="service">Service Type</label>
        <select id="service" name="service">
          <option>TV Repair (Pickup)</option>
          <option>On-site Repair</option>
          <option>New TV Purchase</option>
          <option>Installation / Mounting</option>
        </select>
        <label for="message">Message</label>
        <textarea id="message" name="message" rows="4" placeholder="Tell us the problem or what you're looking for"></textarea>
        <button type="submit" class="btn btn-primary">Send Request</button>
      </form>

      <aside style="height:100%;">
        <div style="background:var(--card-bg);padding:16px;border-radius:12px;box-shadow:0 6px 24px rgba(12,18,35,0.04);height:100%">
          <h3 style="margin-top:0">Visit Us</h3>
          <p class="muted">Geetha Electronics</p>
          <p>Sandhai Bazar, Nagalapuram, Tamil Nadu 628904</p>
          <p class="muted">Call</p>
          <p><a href="tel:+919786986330">+91 9786986330</a></p>
          <p class="muted">Email</p>
          <p><a href="mailto:jayaramramesh001@gmail.com">jayaramramesh001@gmail.com</a></p>

          <div style="margin-top:12px">
            <source srcset="WhatsApp Image 2025-09-26 at 21.53.56_2ec13c48.jpg" media="(max-width:12px)">
            <img src="WhatsApp Image 2025-09-26 at 21.53.56_2ec13c48.jpg" alt="owner photo">
          </div>
        </div>
      </aside>
    </section>

    <footer>
      © <span id="year"></span> Geetha Electronics — All rights reserved-2025.
    </footer>
  </div>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
