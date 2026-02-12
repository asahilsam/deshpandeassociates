# deshpandeassociates[Uploading index.html…]()
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8"/>
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <meta name="theme-color" content="#070b12"/>
  <title>Deshpande & Associates — Tax & Financial Consultants</title>
  <meta name="description" content="PAN-India GST, ITR, FSSAI, MSME services. Payment after work. Quick support on WhatsApp."/>
  <style>
    :root{
      --bg:#070b12;
      --bg2:#0b1220;
      --card:#0d1423;
      --card2:#0b1220;
      --text:#e8edf7;
      --muted:#9fb0c7;
      --line:rgba(255,255,255,.08);
      --shadow: 0 18px 50px rgba(0,0,0,.45);
      --radius:20px;
      --gold:#d8b35a;
      --gold2:#f0d48a;
      --wa:#25D366;
      --max:1150px;
    }
    *{box-sizing:border-box}
    html,body{height:100%}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial;
      background:
        radial-gradient(900px 500px at 20% 0%, rgba(216,179,90,.16), transparent 60%),
        radial-gradient(1000px 600px at 90% 30%, rgba(120,180,255,.12), transparent 55%),
        linear-gradient(180deg, var(--bg), var(--bg2));
      color:var(--text);
      overflow-x:hidden;
    }
    a{color:inherit;text-decoration:none}
    img{max-width:100%;display:block}
    .container{width:min(var(--max), 92%); margin:0 auto}

    /* Topbar */
    .topbar{
      position:sticky; top:0; z-index:999;
      backdrop-filter: blur(12px);
      background: rgba(7,11,18,.72);
      border-bottom:1px solid var(--line);
    }
    .topbar-inner{
      display:flex; align-items:center; justify-content:space-between;
      gap:14px; padding:12px 0;
    }
    .brand{
      display:flex; align-items:center; gap:12px;
      min-width: 0;
    }
    .brand-logo{
      width:44px; height:44px; border-radius:14px;
      display:grid; place-items:center;
      background: linear-gradient(135deg, rgba(216,179,90,.22), rgba(255,255,255,.05));
      border:1px solid rgba(216,179,90,.25);
      overflow:hidden;
      flex:0 0 auto;
    }
    .brand-title{
      display:flex; flex-direction:column; line-height:1.05;
      min-width:0;
    }
    .brand-title strong{
      font-size:15px; letter-spacing:.3px;
      white-space:nowrap; overflow:hidden; text-overflow:ellipsis;
    }
    .brand-title span{
      font-size:12px; color:var(--muted);
      white-space:nowrap; overflow:hidden; text-overflow:ellipsis;
    }
    nav{
      display:flex; align-items:center; gap:10px;
      flex:0 0 auto;
    }
    .nav-link{
      font-size:13px; color:var(--muted);
      padding:10px 10px; border-radius:999px;
      border:1px solid transparent;
    }
    .nav-link:hover{border-color:rgba(255,255,255,.10); color:var(--text)}
    .wa-btn{
      display:inline-flex; align-items:center; gap:10px;
      padding:10px 14px;
      border-radius:999px;
      background: linear-gradient(135deg, rgba(37,211,102,.22), rgba(255,255,255,.03));
      border:1px solid rgba(37,211,102,.35);
      box-shadow: 0 10px 30px rgba(0,0,0,.25);
      font-weight:800;
      white-space:nowrap;
    }
    .wa-ico{width:18px;height:18px;flex:0 0 auto}

    /* Hero */
    .hero{padding:42px 0 18px}
    .hero-grid{
      display:grid;
      grid-template-columns: 1.15fr .85fr;
      gap:18px;
      align-items:stretch;
    }
    .hero-left{
      padding:22px 22px;
      border-radius: var(--radius);
      background: linear-gradient(180deg, rgba(255,255,255,.03), rgba(255,255,255,.02));
      border:1px solid var(--line);
      box-shadow: var(--shadow);
      position:relative;
      overflow:hidden;
    }
    .badge{
      display:inline-flex; align-items:center; gap:10px;
      padding:9px 12px;
      border-radius:999px;
      background: rgba(216,179,90,.12);
      border:1px solid rgba(216,179,90,.25);
      color: var(--gold2);
      font-weight:800;
      font-size:13px;
    }
    .badge .dot{
      width:8px;height:8px;border-radius:999px;background:var(--gold);
      box-shadow:0 0 0 6px rgba(216,179,90,.12);
    }
    h1{
      margin:14px 0 10px;
      font-size:44px;
      letter-spacing:-.8px;
      line-height:1.06;
    }
    h1 .gold{color:var(--gold2)}
    .sub{
      margin:0 0 18px;
      color:var(--muted);
      font-size:16px;
      line-height:1.6;
      max-width: 62ch;
    }
    .cta-row{display:flex; flex-wrap:wrap; gap:10px}
    .btn{
      display:inline-flex; align-items:center; justify-content:center;
      gap:10px;
      padding:12px 16px;
      border-radius:14px;
      border:1px solid rgba(255,255,255,.10);
      background: rgba(255,255,255,.03);
      color:var(--text);
      font-weight:900;
      cursor:pointer;
      transition: transform .08s ease;
    }
    .btn:hover{transform: translateY(-1px)}
    .btn.primary{
      background: linear-gradient(135deg, rgba(216,179,90,.22), rgba(255,255,255,.03));
      border-color: rgba(216,179,90,.35);
    }
    .btn.wa{
      background: linear-gradient(135deg, rgba(37,211,102,.22), rgba(255,255,255,.03));
      border-color: rgba(37,211,102,.35);
    }

    .hero-right{
      border-radius: var(--radius);
      background: linear-gradient(180deg, rgba(13,20,35,.92), rgba(11,18,32,.92));
      border:1px solid var(--line);
      box-shadow: var(--shadow);
      padding:18px;
      display:flex; flex-direction:column; gap:12px;
    }
    .logo-wrap{
      background: rgba(255,255,255,.03);
      border:1px solid rgba(255,255,255,.08);
      border-radius: 18px;
      padding:14px;
      display:grid; place-items:center;
      min-height: 160px;
    }
    .logo-img{
      max-width: 100%;
      width: 360px;
      height: auto;
      filter: drop-shadow(0 18px 40px rgba(0,0,0,.35));
    }
    .info{
      display:grid; gap:10px;
      padding:12px;
      border-radius: 18px;
      background: rgba(255,255,255,.02);
      border:1px solid rgba(255,255,255,.06);
    }
    .info .row{display:flex; align-items:center; justify-content:space-between; gap:10px}
    .info .k{color:var(--muted); font-size:13px}
    .info .v{font-weight:900}
    .pill{
      display:inline-flex; align-items:center; gap:8px;
      padding:8px 10px;
      border-radius:999px;
      border:1px solid rgba(255,255,255,.10);
      background: rgba(255,255,255,.02);
      color:var(--muted);
      font-size:13px;
      font-weight:800;
    }
    .pill svg{width:16px;height:16px;opacity:.9}

    /* Sections */
    section{padding:22px 0}
    .section-title{
      font-size:20px;
      margin:0 0 6px;
      letter-spacing:-.3px;
    }
    .section-sub{margin:0 0 16px; color:var(--muted); line-height:1.6}

    /* Cards */
    .grid{
      display:grid;
      grid-template-columns: repeat(4, 1fr);
      gap:12px;
    }
    .card{
      border-radius: 18px;
      padding:16px;
      background: linear-gradient(180deg, rgba(255,255,255,.03), rgba(255,255,255,.02));
      border:1px solid rgba(255,255,255,.08);
      box-shadow: 0 14px 40px rgba(0,0,0,.25);
      position:relative;
      overflow:hidden;
    }
    .card h3{margin:0 0 6px; font-size:16px}
    .card p{margin:0 0 14px; color:var(--muted); line-height:1.55; font-size:13px}
    .price{
      display:flex; align-items:center; justify-content:space-between; gap:10px;
      padding-top:12px;
      border-top:1px solid rgba(255,255,255,.08);
      font-weight:900;
    }
    .price span{color:var(--muted); font-weight:800}
    .price b{color:var(--gold2); font-size:18px}
    .card .tag{
      position:absolute; top:14px; right:14px;
      padding:7px 10px;
      border-radius:999px;
      font-size:12px;
      font-weight:900;
      color:var(--gold2);
      background: rgba(216,179,90,.10);
      border:1px solid rgba(216,179,90,.22);
    }

    /* WhatsApp strip */
    .wa-strip{
      margin-top:14px;
      border-radius: 18px;
      padding:14px 16px;
      background: linear-gradient(135deg, rgba(37,211,102,.14), rgba(255,255,255,.02));
      border:1px solid rgba(37,211,102,.25);
      display:flex; align-items:center; justify-content:space-between;
      gap:12px;
    }
    .wa-strip strong{display:block}
    .wa-strip small{color:var(--muted)}
    .wa-strip a{
      flex:0 0 auto;
      padding:10px 14px;
      border-radius: 14px;
      background: rgba(37,211,102,.18);
      border:1px solid rgba(37,211,102,.35);
      font-weight:900;
      display:inline-flex; align-items:center; gap:10px;
    }

    /* Contact */
    .contact-wrap{
      display:grid;
      grid-template-columns: 1.2fr .8fr;
      gap:12px;
    }
    .contact-card{
      border-radius: 18px;
      padding:16px;
      background: rgba(255,255,255,.02);
      border:1px solid rgba(255,255,255,.08);
      box-shadow: 0 14px 40px rgba(0,0,0,.20);
    }
    .contact-card h3{margin:0 0 10px}
    .contact-item{
      display:flex; align-items:center; justify-content:space-between;
      gap:12px;
      padding:12px;
      border-radius: 14px;
      background: rgba(255,255,255,.02);
      border:1px solid rgba(255,255,255,.06);
      margin-bottom:10px;
      font-weight:800;
    }
    .contact-item span{color:var(--muted); font-weight:800}
    .cta-row2{display:flex; gap:10px; flex-wrap:wrap; margin-top:10px}

    footer{
      padding:18px 0 80px;
      color:var(--muted);
      text-align:center;
      border-top:1px solid rgba(255,255,255,.06);
      margin-top:16px;
    }

    /* Floating WA */
    .float-wa{
      position:fixed;
      right:16px;
      bottom:16px;
      z-index:9999;
      width:56px;height:56px;
      border-radius:18px;
      display:grid; place-items:center;
      background: linear-gradient(135deg, rgba(37,211,102,.22), rgba(255,255,255,.03));
      border:1px solid rgba(37,211,102,.40);
      box-shadow: 0 18px 50px rgba(0,0,0,.40);
    }
    .float-wa svg{width:26px;height:26px}

    /* Responsive */
    @media (max-width: 980px){
      h1{font-size:36px}
      .hero-grid{grid-template-columns:1fr}
      .grid{grid-template-columns:1fr 1fr}
      .contact-wrap{grid-template-columns:1fr}
      nav .nav-link{display:none}
    }
    @media (max-width: 520px){
      h1{font-size:30px}
      .grid{grid-template-columns:1fr}
      .brand-title strong{max-width: 210px}
    }
  </style>
</head>
<body>

  <!-- Topbar -->
  <header class="topbar">
    <div class="container">
      <div class="topbar-inner">
        <a class="brand" href="#top">
          <div class="brand-logo">
            <!-- Small DA icon -->
            <svg viewBox="0 0 64 64" width="26" height="26" aria-hidden="true">
              <path fill="rgba(240,212,138,.95)" d="M14 48V16h18c11 0 18 6.7 18 16s-7 16-18 16H14zm10-8h8c6 0 10-3.5 10-8s-4-8-10-8h-8v16z"/>
            </svg>
          </div>
          <div class="brand-title">
            <strong>DESHPANDE ASSOCIATES</strong>
            <span>Tax & Financial Consultants</span>
          </div>
        </a>

        <nav>
          <a class="nav-link" href="#services">Services</a>
          <a class="nav-link" href="#pricing">Pricing</a>
          <a class="nav-link" href="#contact">Contact</a>
          <a class="wa-btn" href="https://wa.me/916360886409" target="_blank" rel="noopener">
            <svg class="wa-ico" viewBox="0 0 32 32" fill="none" aria-hidden="true">
              <path fill="rgba(37,211,102,.95)" d="M16 3C9.4 3 4 8.2 4 14.7c0 2.4.7 4.6 2 6.6L4 29l8-2.6c1.8 1 3.9 1.6 6 1.6 6.6 0 12-5.2 12-11.7S22.6 3 16 3z"/>
              <path fill="#06120b" d="M12.8 10.2c-.2-.5-.4-.5-.7-.5h-.6c-.2 0-.6.1-.9.5-.3.4-1.2 1.1-1.2 2.8s1.2 3.3 1.4 3.5c.2.2 2.4 3.8 5.9 5.2 2.9 1.2 3.5 1 4.1.9.6-.1 2-1 2.3-1.9.3-.9.3-1.6.2-1.8-.1-.2-.3-.3-.7-.5-.4-.2-2.3-1.1-2.6-1.2-.3-.1-.6-.2-.9.2-.3.4-1 1.2-1.2 1.4-.2.2-.4.3-.8.1-.4-.2-1.7-.6-3.2-1.9-1.2-1-2-2.2-2.2-2.6-.2-.4 0-.6.2-.8.2-.2.4-.4.6-.7.2-.2.2-.4.3-.6.1-.2 0-.4-.1-.6-.1-.2-.8-2.1-1.1-2.7z"/>
            </svg>
            WhatsApp
          </a>
        </nav>
      </div>
    </div>
  </header>

  <!-- Hero -->
  <main id="top" class="hero">
    <div class="container">
      <div class="hero-grid">
        <div class="hero-left">
          <div class="badge"><span class="dot"></span> PAN-India Service • Payment After Work</div>
          <h1>GST • ITR • FSSAI • MSME<br/><span class="gold">Registration & Filing</span></h1>
          <p class="sub">
            Professional and fast service for registrations and filings.
            Transparent pricing, quick response on WhatsApp, and support within 24 hours.
          </p>

          <div class="cta-row">
            <a class="btn wa" href="https://wa.me/916360886409" target="_blank" rel="noopener">
              WhatsApp Now
            </a>
            <a class="btn primary" href="#pricing">View Pricing</a>
            <a class="btn" href="tel:+916360886409">Call</a>
            <a class="btn" href="#contact">Contact</a>
          </div>

          <div class="wa-strip">
            <div>
              <strong>Need all services list?</strong>
              <small>Ask on WhatsApp — we will send full pricing.</small>
            </div>
            <a href="https://wa.me/916360886409" target="_blank" rel="noopener">
              <svg class="wa-ico" viewBox="0 0 32 32" fill="none" aria-hidden="true">
                <path fill="rgba(37,211,102,.95)" d="M16 3C9.4 3 4 8.2 4 14.7c0 2.4.7 4.6 2 6.6L4 29l8-2.6c1.8 1 3.9 1.6 6 1.6 6.6 0 12-5.2 12-11.7S22.6 3 16 3z"/>
                <path fill="#06120b" d="M12.8 10.2c-.2-.5-.4-.5-.7-.5h-.6c-.2 0-.6.1-.9.5-.3.4-1.2 1.1-1.2 2.8s1.2 3.3 1.4 3.5c.2.2 2.4 3.8 5.9 5.2 2.9 1.2 3.5 1 4.1.9.6-.1 2-1 2.3-1.9.3-.9.3-1.6.2-1.8-.1-.2-.3-.3-.7-.5-.4-.2-2.3-1.1-2.6-1.2-.3-.1-.6-.2-.9.2-.3.4-1 1.2-1.2 1.4-.2.2-.4.3-.8.1-.4-.2-1.7-.6-3.2-1.9-1.2-1-2-2.2-2.2-2.6-.2-.4 0-.6.2-.8.2-.2.4-.4.6-.7.2-.2.2-.4.3-.6.1-.2 0-.4-.1-.6-.1-.2-.8-2.1-1.1-2.7z"/>
              </svg>
              WhatsApp Now
            </a>
          </div>
        </div>

        <aside class="hero-right">
          <div class="logo-wrap">
            <!-- YOUR LOGO (uploaded by you) -->
            <img class="logo-img" src="logo.png" alt="Deshpande & Associates Logo"/>
          </div>

          <div class="info">
            <div class="row">
              <div class="pill">
                <svg viewBox="0 0 24 24" fill="none" aria-hidden="true">
                  <path d="M12 2C8.1 2 5 5.1 5 9c0 5.3 7 13 7 13s7-7.7 7-13c0-3.9-3.1-7-7-7zm0 9.5A2.5 2.5 0 1 1 12 6a2.5 2.5 0 0 1 0 5.5z" fill="rgba(240,212,138,.95)"/>
                </svg>
                PAN-India Support
              </div>
              <div class="pill">
                <svg viewBox="0 0 24 24" fill="none" aria-hidden="true">
                  <path d="M12 1.5a10.5 10.5 0 1 0 0 21 10.5 10.5 0 0 0 0-21zm1 11H7v-2h6V6h2v6.5z" fill="rgba(240,212,138,.95)"/>
                </svg>
                Within 24 Hours
              </div>
            </div>

            <div class="row">
              <div class="k">WhatsApp</div>
              <div class="v">+91 6360886409</div>
            </div>
            <div class="row">
              <div class="k">Email</div>
              <div class="v">deshpandeassociates16@gmail.com</div>
            </div>
          </div>
        </aside>
      </div>
    </div>
  </main>

  <!-- Services -->
  <section id="services">
    <div class="container">
      <h2 class="section-title">Services</h2>
      <p class="section-sub">Popular services with transparent pricing.</p>

      <div class="grid">
        <div class="card">
          <span class="tag">Fast</span>
          <h3>GST Registration</h3>
          <p>New GST registration for business & individuals. PAN-India support.</p>
          <div class="price"><span>Price</span><b>₹499</b></div>
        </div>

        <div class="card">
          <span class="tag">Best</span>
          <h3>GST Return Filing</h3>
          <p>Monthly / Quarterly filing support. Accurate & quick processing.</p>
          <div class="price"><span>Price</span><b>₹299</b></div>
        </div>

        <div class="card">
          <span class="tag">Quick</span>
          <h3>FSSAI Registration</h3>
          <p>Basic / State / Central (as per requirement). Fast documentation.</p>
          <div class="price"><span>Price</span><b>₹499</b></div>
        </div>

        <div class="card">
          <span class="tag">Easy</span>
          <h3>ITR Filing</h3>
          <p>Individuals & business ITR. Clean, correct and timely filing.</p>
          <div class="price"><span>Price</span><b>₹299</b></div>
        </div>

        <div class="card">
          <span class="tag">Low</span>
          <h3>MSME / Udyam</h3>
          <p>Udyam certificate generation & update support.</p>
          <div class="price"><span>Price</span><b>₹249</b></div>
        </div>

        <div class="card">
          <span class="tag">Help</span>
          <h3>PAN-India Support</h3>
          <p>Online consultation, document verification & process guidance.</p>
          <div class="price"><span>Support</span><b>Available</b></div>
        </div>

        <div class="card">
          <span class="tag">Safe</span>
          <h3>Payment After Work</h3>
          <p>Pay after work is completed. Terms depend on case requirements.</p>
          <div class="price"><span>Policy</span><b>Yes</b></div>
        </div>

        <div class="card">
          <span class="tag">24H</span>
          <h3>Quick Response</h3>
          <p>We respond on WhatsApp quickly and process within 24 hours.</p>
          <div class="price"><span>Speed</span><b>Fast</b></div>
        </div>
      </div>
    </div>
  </section>

  <!-- Pricing -->
  <section id="pricing">
    <div class="container">
      <h2 class="section-title">Pricing</h2>
      <p class="section-sub">Simple pricing — no confusion.</p>

      <div class="grid">
        <div class="card">
          <h3>GST Registration</h3>
          <p>New registration support with documentation guidance.</p>
          <div class="price"><span>Price</span><b>₹499</b></div>
        </div>

        <div class="card">
          <h3>GST Return Filing</h3>
          <p>Monthly / Quarterly filing support.</p>
          <div class="price"><span>Price</span><b>₹299</b></div>
        </div>

        <div class="card">
          <h3>FSSAI Registration</h3>
          <p>Fast processing with complete checklist support.</p>
          <div class="price"><span>Price</span><b>₹499</b></div>
        </div>

        <div class="card">
          <h3>ITR Filing</h3>
          <p>Individuals & business ITR filing.</p>
          <div class="price"><span>Price</span><b>₹299</b></div>
        </div>

        <div class="card">
          <h3>MSME / Udyam</h3>
          <p>Udyam certificate generation.</p>
          <div class="price"><span>Price</span><b>₹249</b></div>
        </div>

        <div class="card">
          <h3>Within 24 Hours</h3>
          <p>Fast response and processing.</p>
          <div class="price"><span>Support</span><b>Available</b></div>
        </div>

        <div class="card">
          <h3>Payment After Work</h3>
          <p>Work first, payment after completion (terms apply).</p>
          <div class="price"><span>Policy</span><b>Yes</b></div>
        </div>

        <div class="card">
          <h3>WhatsApp Support</h3>
          <p>Quick contact and follow-up on WhatsApp.</p>
          <div class="price"><span>WhatsApp</span><b>24×7</b></div>
        </div>
      </div>

      <div class="wa-strip" style="margin-top:16px">
        <div>
          <strong>Want full services list?</strong>
          <small>Message us on WhatsApp and we will share everything.</small>
        </div>
        <a href="https://wa.me/916360886409" target="_blank" rel="noopener">
          <svg class="wa-ico" viewBox="0 0 32 32" fill="none" aria-hidden="true">
            <path fill="rgba(37,211,102,.95)" d="M16 3C9.4 3 4 8.2 4 14.7c0 2.4.7 4.6 2 6.6L4 29l8-2.6c1.8 1 3.9 1.6 6 1.6 6.6 0 12-5.2 12-11.7S22.6 3 16 3z"/>
            <path fill="#06120b" d="M12.8 10.2c-.2-.5-.4-.5-.7-.5h-.6c-.2 0-.6.1-.9.5-.3.4-1.2 1.1-1.2 2.8s1.2 3.3 1.4 3.5c.2.2 2.4 3.8 5.9 5.2 2.9 1.2 3.5 1 4.1.9.6-.1 2-1 2.3-1.9.3-.9.3-1.6.2-1.8-.1-.2-.3-.3-.7-.5-.4-.2-2.3-1.1-2.6-1.2-.3-.1-.6-.2-.9.2-.3.4-1 1.2-1.2 1.4-.2.2-.4.3-.8.1-.4-.2-1.7-.6-3.2-1.9-1.2-1-2-2.2-2.2-2.6-.2-.4 0-.6.2-.8.2-.2.4-.4.6-.7.2-.2.2-.4.3-.6.1-.2 0-.4-.1-.6-.1-.2-.8-2.1-1.1-2.7z"/>
          </svg>
          WhatsApp Now
        </a>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact">
    <div class="container">
      <h2 class="section-title">Contact</h2>
      <p class="section-sub">Call or WhatsApp us for quick support.</p>

      <div class="contact-wrap">
        <div class="contact-card">
          <h3>Quick Contact</h3>

          <div class="contact-item">
            <span>Call / WhatsApp</span>
            <b>+91 6360886409</b>
          </div>

          <div class="contact-item">
            <span>Email</span>
            <b>deshpandeassociates16@gmail.com</b>
          </div>

          <div class="cta-row2">
            <a class="btn wa" href="https://wa.me/916360886409" target="_blank" rel="noopener">WhatsApp</a>
            <a class="btn" href="tel:+916360886409">Call</a>
          </div>
        </div>

        <div class="contact-card">
          <h3>About</h3>
          <p style="margin:0;color:var(--muted);line-height:1.9">
            Deshpande Associates provides PAN-India support for GST, ITR, FSSAI, MSME and other registrations.
            We focus on fast processing, clear pricing and trusted consultant support.
          </p>
          <div style="margin-top:14px; padding-top:14px; border-top:1px solid rgba(255,255,255,.06); font-size:13px; color:rgba(255,255,255,.65)">
            Note: Payment After Work available. Terms depend on case requirements.
          </div>
        </div>
      </div>
    </div>
  </section>

  <footer>
    © <span id="year"></span> Deshpande Associates • All Rights Reserved
  </footer>

  <!-- Floating WhatsApp -->
  <a class="float-wa" href="https://wa.me/916360886409" target="_blank" rel="noopener" aria-label="Chat on WhatsApp">
    <svg viewBox="0 0 32 32" fill="none" aria-hidden="true">
      <path fill="rgba(37,211,102,.95)" d="M16 3C9.4 3 4 8.2 4 14.7c0 2.4.7 4.6 2 6.6L4 29l8-2.6c1.8 1 3.9 1.6 6 1.6 6.6 0 12-5.2 12-11.7S22.6 3 16 3z"/>
      <path fill="#06120b" d="M12.8 10.2c-.2-.5-.4-.5-.7-.5h-.6c-.2 0-.6.1-.9.5-.3.4-1.2 1.1-1.2 2.8s1.2 3.3 1.4 3.5c.2.2 2.4 3.8 5.9 5.2 2.9 1.2 3.5 1 4.1.9.6-.1 2-1 2.3-1.9.3-.9.3-1.6.2-1.8-.1-.2-.3-.3-.7-.5-.4-.2-2.3-1.1-2.6-1.2-.3-.1-.6-.2-.9.2-.3.4-1 1.2-1.2 1.4-.2.2-.4.3-.8.1-.4-.2-1.7-.6-3.2-1.9-1.2-1-2-2.2-2.2-2.6-.2-.4 0-.6.2-.8.2-.2.4-.4.6-.7.2-.2.2-.4.3-.6.1-.2 0-.4-.1-.6-.1-.2-.8-2.1-1.1-2.7z"/>
    </svg>
  </a>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>
