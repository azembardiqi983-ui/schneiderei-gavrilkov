# schneiderei-gavrilkov

<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="description" content="Änderungsschneiderei Gavrilkov in Eckernförde. Kontakt und Informationen zu Änderungsarbeiten.">
<title>Änderungsschneiderei Gavrilkov | Eckernförde</title>
<style>
:root{--dark:#151513;--gold:#d9b775;--cream:#f7f4ee;--muted:#c9c4bb}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;font-family:Arial,Helvetica,sans-serif;background:var(--cream);color:#191919}
button,a{-webkit-tap-highlight-color:transparent}
button{font:inherit;cursor:pointer}
a{color:inherit}
header{background:var(--dark);color:white;padding:20px 6%;display:flex;justify-content:space-between;align-items:center;gap:18px;flex-wrap:wrap}
.brand{font-family:Georgia,serif;font-size:22px;color:var(--gold);font-weight:bold;letter-spacing:1px}
nav{display:flex;gap:8px;flex-wrap:wrap}
nav button{background:transparent;border:0;color:white;padding:10px;font-size:14px}
nav button:hover,nav button:focus{color:var(--gold)}
.hero{background:linear-gradient(110deg,#171715 0%,#24211c 65%,#393025 100%);color:white;padding:85px 8%;min-height:390px;display:flex;align-items:center}
.hero-inner{max-width:750px}
.eyebrow{color:var(--gold);font-size:12px;letter-spacing:3px;font-weight:bold}
h1,h2{font-family:Georgia,'Times New Roman',serif;font-weight:normal}
h1{font-size:clamp(40px,7vw,76px);line-height:1.06;margin:20px 0}
h2{font-size:clamp(30px,4vw,44px);margin:12px 0 20px}
h3{margin-top:0}
.gold{color:var(--gold)}
p{line-height:1.75}
.hero p{max-width:590px;color:#e6e1d8}
.btn{display:inline-block;background:var(--gold);color:#171511;border:1px solid var(--gold);border-radius:28px;padding:14px 22px;font-weight:bold;text-decoration:none;margin:10px 8px 0 0}
.btn:hover{filter:brightness(1.08)}
.btn.secondary{background:transparent;color:var(--gold)}
section{padding:70px 8%}
.section-head{max-width:650px}
.center{text-align:center;margin:0 auto}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(210px,1fr));gap:18px;margin-top:32px}
.card{background:#fff;border:1px solid #e9e3d8;border-radius:12px;padding:26px;text-align:left}
button.card{width:100%;color:#191919;transition:transform .2s,box-shadow .2s}
button.card:hover{transform:translateY(-3px);box-shadow:0 9px 24px #00000010}
.symbol{font-size:30px;color:#b38c4b;margin-bottom:18px}
.card p{font-size:14px;color:#615d56}
.card .more{color:#9b7335;font-weight:bold;font-size:14px}
.dark-section{background:var(--dark);color:white}
.dark-section p{color:#d0ccc4}
.feature-list{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:20px;margin-top:30px}
.feature{border-top:1px solid #48443c;padding-top:18px}
.feature strong{color:var(--gold)}
.contact-grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:18px;margin-top:30px}
.contact-box{background:white;border:1px solid #e9e3d8;border-radius:12px;padding:25px}
.map-link{display:block;margin-top:15px;color:#795b2b;font-weight:bold}
.notice{font-size:12px;color:#6e685e}
footer{background:#10100f;color:#bdb8af;padding:30px 7%;text-align:center}
footer button{border:0;background:none;color:var(--gold);padding:8px}
.page{display:none}
.page.active{display:block}
.detail{min-height:55vh}
.detail-actions{margin-top:24px}
@media(max-width:600px){
 header{padding:18px 5%}
 nav{width:100%;gap:2px}
 nav button{padding:9px 7px;font-size:13px}
 .hero{padding:65px 6%;min-height:390px}
 section{padding:55px 6%}
 .grid{grid-template-columns:1fr}
}
</style>
</head>
<body>

<header>
  <div class="brand">✂ GAVRILKOV</div>
  <nav aria-label="Hauptnavigation">
    <button onclick="showPage('home')">Startseite</button>
    <button onclick="showPage('services')">Leistungen</button>
    <button onclick="showPage('about')">Über uns</button>
    <button onclick="showPage('contact')">Kontakt</button>
  </nav>
</header>

<main>
<div id="home" class="page active">
  <div class="hero">
    <div class="hero-inner">
      <div class="eyebrow">ÄNDERUNGSSCHNEIDEREI · ECKERNFÖRDE</div>
      <h1>Ihre Kleidung.<br><span class="gold">Ihr Stil.</span></h1>
      <p>Willkommen bei der Änderungsschneiderei Gavrilkov. Informieren Sie sich über unser Angebot und sprechen Sie Ihre Änderungswünsche persönlich mit uns ab.</p>
      <button class="btn" onclick="showPage('services')">Leistungen entdecken →</button>
      <button class="btn secondary" onclick="showPage('contact')">Kontakt aufnehmen</button>
    </div>
  </div>

  <section>
    <div class="section-head center">
      <div class="eyebrow">UNSER ANGEBOT</div>
      <h2>Was dürfen wir für Sie tun?</h2>
      <p>Wählen Sie eine Kategorie aus, um weitere Informationen zu erhalten.</p>
    </div>
    <div class="grid">
      <button class="card" onclick="showPage('hosen')">
        <div class="symbol">✂</div><h3>Hosenänderungen</h3>
        <p>Fragen Sie nach möglichen Anpassungen.</p><span class="more">Mehr erfahren →</span>
      </button>
      <button class="card" onclick="showPage('kleider')">
        <div class="symbol">◇</div><h3>Kleider</h3>
        <p>Besprechen Sie Ihre individuellen Änderungswünsche.</p><span class="more">Mehr erfahren →</span>
      </button>
      <button class="card" onclick="showPage('jacken')">
        <div class="symbol">♧</div><h3>Jacken & Mäntel</h3>
        <p>Erkundigen Sie sich nach möglichen Anpassungen.</p><span class="more">Mehr erfahren →</span>
      </button>
      <button class="card" onclick="showPage('repair')">
        <div class="symbol">⌁</div><h3>Reparaturen</h3>
        <p>Fragen Sie nach Reparaturen und Näharbeiten.</p><span class="more">Mehr erfahren →</span>
      </button>
    </div>
    <div class="center" style="margin-top:28px">
      <button class="btn" onclick="showPage('services')">Alle Leistungen ansehen →</button>
    </div>
  </section>

  <section class="dark-section">
    <div class="eyebrow">PERSÖNLICH FÜR SIE DA</div>
    <h2>Handwerk mit Liebe zum Detail.</h2>
    <p>Sie möchten ein Kleidungsstück ändern lassen? Besprechen Sie Ihre Wünsche persönlich mit der Änderungsschneiderei.</p>
    <button class="btn" onclick="showPage('contact')">Kontakt & Anfahrt →</button>
  </section>
</div>

<div id="services" class="page">
  <section>
    <div class="eyebrow">UNSER ANGEBOT</div>
    <h2>Leistungen im Überblick</h2>
    <p>Tippen Sie auf eine Kategorie, um mehr zu erfahren. Das konkrete Leistungsangebot bitte vor Veröffentlichung vom Betrieb bestätigen lassen.</p>
    <div class="grid">
      <button class="card" onclick="showPage('hosen')"><h3>Hosenänderungen →</h3><p>Mögliche Anpassungen besprechen.</p></button>
      <button class="card" onclick="showPage('kleider')"><h3>Kleider →</h3><p>Individuelle Änderungswünsche.</p></button>
      <button class="card" onclick="showPage('jacken')"><h3>Jacken & Mäntel →</h3><p>Nach Änderungsmöglichkeiten fragen.</p></button>
      <button class="card" onclick="showPage('repair')"><h3>Reparaturen →</h3><p>Informationen zu Näharbeiten.</p></button>
    </div>
    <button class="btn secondary" onclick="showPage('home')">← Zur Startseite</button>
  </section>
</div>

<div id="hosen" class="page detail">
  <section>
    <div class="eyebrow">LEISTUNGEN</div><h2>Hosenänderungen</h2>
    <p>Sie möchten Ihre Hose anpassen lassen? Fragen Sie direkt nach, welche Änderungen für Ihr Kleidungsstück möglich sind.</p>
    <div class="detail-actions">
      <button class="btn" onclick="showPage('contact')">Kontakt aufnehmen →</button>
      <button class="btn secondary" onclick="showPage('services')">← Alle Leistungen</button>
    </div>
  </section>
</div>

<div id="kleider" class="page detail">
  <section>
    <div class="eyebrow">LEISTUNGEN</div><h2>Kleider</h2>
    <p>Besprechen Sie Ihre Wünsche für Änderungen an Kleidungsstücken direkt mit der Schneiderei.</p>
    <div class="detail-actions">
      <button class="btn" onclick="showPage('contact')">Kontakt aufnehmen →</button>
      <button class="btn secondary" onclick="showPage('services')">← Alle Leistungen</button>
    </div>
  </section>
</div>

<div id="jacken" class="page detail">
  <section>
    <div class="eyebrow">LEISTUNGEN</div><h2>Jacken & Mäntel</h2>
    <p>Fragen Sie nach möglichen Änderungen und individuellen Anpassungen für Ihre Kleidungsstücke.</p>
    <div class="detail-actions">
      <button class="btn" onclick="showPage('contact')">Kontakt aufnehmen →</button>
      <button class="btn secondary" onclick="showPage('services')">← Alle Leistungen</button>
    </div>
  </section>
</div>

<div id="repair" class="page detail">
  <section>
    <div class="eyebrow">LEISTUNGEN</div><h2>Reparaturen</h2>
    <p>Sie benötigen eine Reparatur? Kontaktieren Sie die Schneiderei, um Ihr Anliegen persönlich zu besprechen.</p>
    <div class="detail-actions">
      <button class="btn" onclick="showPage('contact')">Kontakt aufnehmen →</button>
      <button class="btn secondary" onclick="showPage('services')">← Alle Leistungen</button>
    </div>
  </section>
</div>

<div id="about" class="page">
  <section class="dark-section">
    <div class="eyebrow">ÜBER UNS</div>
    <h2>Änderungsschneiderei Gavrilkov</h2>
    <p>Wir laden Sie ein, Ihre Änderungswünsche persönlich mit uns zu besprechen. Informationen über Erfahrung und konkrete Leistungen werden nach Rücksprache mit dem Betrieb ergänzt.</p>
    <button class="btn" onclick="showPage('contact')">Kontakt & Anfahrt →</button>
    <button class="btn secondary" onclick="showPage('home')">← Startseite</button>
  </section>
</div>

<div id="contact" class="page">
  <section>
    <div class="eyebrow">KONTAKT</div>
    <h2>So erreichen Sie uns</h2>
    <p>Bitte prüfen Sie die Kontaktdaten vor Veröffentlichung.</p>
    <div class="contact-grid">
      <div class="contact-box">
        <h3>Telefon</h3><p>04351 486684</p>
        <a class="btn" href="tel:+494351486684">Jetzt anrufen</a>
      </div>
      <div class="contact-box">
        <h3>Adresse</h3><p>Kieler Straße 63<br>24340 Eckernförde</p>
        <a class="btn" href="https://www.google.com/maps/search/?api=1&query=Kieler+Strasse+63+24340+Eckernfoerde" target="_blank" rel="noopener">Route planen ↗</a>
      </div>
    </div>
    <p class="notice">Öffnungszeiten bitte beim Betrieb erfragen. Impressum und Datenschutzerklärung müssen vor der Veröffentlichung ergänzt werden.</p>
    <button class="btn secondary" onclick="showPage('home')">← Zur Startseite</button>
  </section>
</div>
</main>

<footer>
  <div class="brand">GAVRILKOV</div>
  <p>Änderungsschneiderei · Eckernförde</p>
  <button onclick="showPage('home')">Startseite</button>
  <button onclick="showPage('services')">Leistungen</button>
  <button onclick="showPage('contact')">Kontakt</button>
  <p class="notice">Demo-Webseite – Inhalte und Angaben vor Veröffentlichung bestätigen.</p>
</footer>

<script>
function showPage(id){
  document.querySelectorAll('.page').forEach(function(page){
    page.classList.remove('active');
  });
  var selected=document.getElementById(id);
  if(selected){
    selected.classList.add('active');
    window.scrollTo(0,0);
  }
}
</script>
</body>
</html>
