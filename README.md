<!DOCTYPE html>
<html lang="de">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Formatec 3D - AG · Design trifft Präzision</title>
<meta name="description" content="Personalisierte Unikate, 3D-Druck nach Maß und präzise Lasergravur auf Holz, Leder und Metall. Anfrage per WhatsApp oder E-Mail.">
<style>
:root{
  --paper:#f4f5f2; --ink:#1c2026; --muted:#5b626c; --line:#d9dcd6;
  --blue:#2450ff; --yellow:#ffc62e; --card:#ffffff;
  --font:system-ui,-apple-system,"Segoe UI",Roboto,Arial,sans-serif;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth}
body{margin:0;background:var(--paper);color:var(--ink);font-family:var(--font);line-height:1.6}
a{color:inherit}
:focus-visible{outline:3px solid var(--blue);outline-offset:3px}
.wrap{max-width:1080px;margin:0 auto;padding:0 20px}
h1,h2,h3{hyphens:auto;overflow-wrap:break-word;line-height:1.15}

header{border-bottom:1px solid var(--line);background:var(--paper);position:sticky;top:0;z-index:5}
header .wrap{display:flex;align-items:center;justify-content:space-between;height:60px}
.logo{font-weight:700;text-decoration:none;font-size:1.1rem}
.logo span{color:var(--blue)}
nav a{margin-left:20px;text-decoration:none;font-size:.95rem;color:var(--muted)}
nav a:hover{color:var(--ink)}

.hero{padding:72px 0 56px;border-bottom:1px solid var(--line);
  background:repeating-linear-gradient(to bottom,transparent 0 9px,rgba(36,80,255,.10) 9px 10px),var(--paper)}
.kicker{font-weight:700;color:var(--blue);letter-spacing:.06em;text-transform:uppercase;font-size:.85rem;margin:0 0 10px}
.hero h1{font-size:clamp(2.2rem,6.5vw,4rem);margin:0 0 18px;letter-spacing:-.03em;max-width:15ch}
.hero p.lead{font-size:1.15rem;color:var(--muted);max-width:56ch;margin:0 0 28px}
.btn{display:inline-block;padding:13px 22px;border-radius:6px;font:inherit;font-weight:700;text-decoration:none;border:2px solid var(--ink);cursor:pointer;background:transparent;color:var(--ink)}
.btn.main{background:var(--blue);border-color:var(--blue);color:#fff}
.btn.main:hover{background:#1a3fd6}
.btn:hover{background:var(--ink);color:#fff}
.hero .btn+.btn{margin-left:10px}

section{padding:64px 0}
h2{font-size:clamp(1.6rem,4vw,2.2rem);margin:0 0 8px;letter-spacing:-.02em}
.sub{color:var(--muted);margin:0 0 28px;max-width:62ch}
.alt{background:var(--card);border-top:1px solid var(--line);border-bottom:1px solid var(--line)}

/* Leistungen */
.services{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:18px;padding:0;margin:0;list-style:none}
.services li{border-top:3px solid var(--ink);padding-top:12px}
.services strong{display:block;margin-bottom:4px}
.services span{color:var(--muted);font-size:.95rem}
.projekt{margin-top:32px;padding:20px;border-left:4px solid var(--yellow);background:var(--paper);max-width:70ch}

/* Bilder mit Platzhalter (Schichtlinien), falls die Datei noch fehlt */
.ph{position:relative;background:repeating-linear-gradient(to bottom,var(--c,#8fb4ff) 0 6px,color-mix(in srgb,var(--c,#8fb4ff) 80%,#000) 6px 7px)}
.ph img{position:absolute;inset:0;width:100%;height:100%;object-fit:cover;display:block}

/* Produkte */
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(230px,1fr));gap:18px}
.card{background:var(--card);border:1px solid var(--line);border-radius:10px;overflow:hidden;display:flex;flex-direction:column}
.card .ph{height:190px}
.card .body{padding:16px;display:flex;flex-direction:column;flex:1}
.card h3{margin:0 0 10px;font-size:1.02rem}
.price{font-weight:700;margin:auto 0 12px}
.card .btn{text-align:center;padding:10px 14px;font-size:.92rem}

/* Bestseller */
.best{display:grid;grid-template-columns:1fr 1fr;gap:0;border:1px solid var(--line);border-radius:10px;overflow:hidden;background:var(--card)}
.best .ph{min-height:280px}
.best .txt{padding:32px;display:flex;flex-direction:column;justify-content:center;align-items:flex-start}
.best .tag{background:var(--yellow);font-weight:700;font-size:.8rem;padding:3px 10px;border-radius:99px;margin-bottom:12px}
.best h3{font-size:1.5rem;margin:0 0 8px}
.best .price{margin:0 0 18px;font-size:1.2rem}

/* Banner + Galerie */
.banner{text-align:center;padding:72px 0;background:var(--ink);color:#fff}
.banner h2{font-size:clamp(1.8rem,5vw,3rem);margin:0 0 12px}
.banner p{max-width:52ch;margin:0 auto 24px;color:#c9ced6}
.banner .btn{border-color:#fff;color:#fff}
.banner .btn:hover{background:#fff;color:var(--ink)}
.gallery{display:grid;grid-template-columns:repeat(auto-fill,minmax(200px,1fr));gap:12px}
.gallery .ph{aspect-ratio:1/1;border-radius:8px;overflow:hidden}

.contact{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:24px}
.contact b{display:block;margin-bottom:2px}
footer{padding:32px 0;color:var(--muted);font-size:.92rem;text-align:center}
footer a{margin:0 8px}
footer .links{margin-bottom:8px}

@media (max-width:700px){
  .best{grid-template-columns:1fr}
  .best .ph{min-height:200px}
  nav a{margin-left:12px;font-size:.88rem}
  .hero .btn+.btn{margin:10px 0 0}
}
</style>
</head>
<body>

<header>
  <div class="wrap">
    <a class="logo" href="#top">Formatec <span>3D</span> - AG</a>
    <nav aria-label="Hauptnavigation">
      <a href="#katalog">Katalog</a>
      <a href="#galerie">Galerie</a>
      <a href="#kontakt">Kontakt</a>
    </nav>
  </div>
</header>

<main id="top">
  <div class="hero">
    <div class="wrap">
      <p class="kicker">Design trifft Präzision</p>
      <h1>Willkommen! Aus deinen Ideen werden Unikate.</h1>
      <p class="lead">Individuell. Kreativ. Präzise gefertigt. Ob persönliche Geschenkidee, graviertes Einzelstück oder maßgefertigtes Ersatzteil aus dem 3D-Drucker: Wir fertigen exakt nach deinen Vorstellungen.</p>
      <a class="btn main" href="#katalog">Zum Katalog</a>
      <a class="btn" href="#kontakt">Projekt anfragen</a>
    </div>
  </div>

  <section id="leistungen">
    <div class="wrap">
      <h2>Unsere Leistungen im Überblick</h2>
      <p class="sub">Durch die Kombination aus modernem 3D-Druck und präziser Lasergravur verarbeiten wir Kunststoffe sowie Holz, Leder und beschichtetes Metall zu echten Unikaten.</p>
      <ul class="services">
        <li><strong>Personalisierte Unikate</strong><span>Gravuren von Namen, Texten, Logos und eigenen Designs.</span></li>
        <li><strong>3D-Druck nach Maß</strong><span>Halterungen, Zubehör, Prototypen und individuelle Modelle.</span></li>
        <li><strong>Präzise Lasergravur</strong><span>Hochwertige Veredelung auf Holz, Leder und Metall.</span></li>
        <li><strong>Ersatzteile &amp; Sonderanfertigungen</strong><span>Wenn es das passende Teil nirgendwo zu kaufen gibt.</span></li>
        <li><strong>Kreative Geschenkideen</strong><span>Einzigartige Präsente für jeden Anlass.</span></li>
      </ul>
      <div class="projekt">
        <strong>Du hast ein spezielles Projekt im Kopf?</strong><br>
        Egal ob vage Idee oder fertige Skizze: Schick uns einfach deine Vorstellungen. Wir beraten dich persönlich und prüfen direkt die Umsetzung.
      </div>
    </div>
  </section>

  <section id="katalog" class="alt">
    <div class="wrap">
      <h2>Katalog</h2>
      <p class="sub">Unsere beliebtesten Produkte. Alle Preise in Euro; Farben, Motive und Gravuren stimmen wir mit dir ab.</p>
      <div class="grid" id="grid"></div>
    </div>
  </section>

  <section id="bestseller">
    <div class="wrap">
      <div class="best">
        <div class="ph" style="--c:#1c2026" data-img="img/schluesselhalter.jpg"></div>
        <div class="txt">
          <span class="tag">Bestseller</span>
          <h3>Schlüsselhalter mit Magnet-Präzision</h3>
          <p class="price">38 €</p>
          <button class="btn main order" type="button" data-name="Schlüsselhalter mit Magnet-Präzision">Anfragen</button>
        </div>
      </div>
    </div>
  </section>

  <div class="banner">
    <div class="wrap">
      <h2>Minimalismus in Perfektion</h2>
      <p>Klare Linien. Durchdachte Details. Zeitlose Formen. Die perfekte Balance aus Ästhetik und Funktionalität für deinen Alltag.</p>
      <a class="btn" href="#katalog">Jetzt einkaufen</a>
    </div>
  </div>

  <section id="galerie">
    <div class="wrap">
      <h2>Galerie</h2>
      <p class="sub">Eine Auswahl unserer Arbeiten. Mehr davon findest du auf Instagram: <a href="https://www.instagram.com/3d_printbygeorg/" target="_blank" rel="noopener">@3d_printbygeorg</a></p>
      <div class="gallery" id="gallery"></div>
    </div>
  </section>

  <section id="kontakt" class="alt">
    <div class="wrap">
      <h2>Kontakt</h2>
      <p class="sub">Schreib uns, wir antworten so schnell wie möglich.</p>
      <div class="contact">
        <div><b>WhatsApp</b><a id="wa" href="#">+00 000 000 000</a></div>
        <div><b>E-Mail</b><a id="mail" href="#">deine@email.de</a></div>
        <div><b>Instagram</b><a href="https://www.instagram.com/3d_printbygeorg/" target="_blank" rel="noopener">@3d_printbygeorg</a></div>
      </div>
    </div>
  </section>
</main>

<footer>
  <div class="wrap">
    <div class="links"><a href="agb.html">AGB</a><a href="faq.html">FAQ</a><a href="datenschutz.html">Datenschutz</a><a href="impressum.html">Impressum</a></div>
    <div>© <span id="year"></span> Formatec 3D - AG</div>
  </div>
</footer>

<script>
/* === DATEN DEINES SHOPS: hier anpassen === */
var WHATSAPP = "490000000000";   // Nummer mit Landesvorwahl, ohne + und Leerzeichen
var EMAIL    = "deine@email.de";

/* Stripe-Zahlungslinks (optional): Produktname -> Link. Ohne Link erscheint "Anfragen". */
var STRIPE_LINKS = {
  // "Schiefer Untersetzer": "https://buy.stripe.com/XXXXXXXX"
};

/* Produkte: Bilddateien legst du in den Ordner img/ */
var PRODUCTS = [
  {name:"Handyhülle mit personalisierter Gravur", price:"30,00 €", img:"img/handyhuelle.jpg", c:"#8fb4ff"},
  {name:"Schiefer Untersetzer", price:"25,00 €", img:"img/untersetzer.jpg", c:"#7a8088"},
  {name:"Personalisierter Holz-Schlüsselanhänger – Lasergravur", price:"9,50 €", img:"img/schluesselanhaenger.jpg", c:"#d9a066"},
  {name:"Personalisierte Edelstahl-Trinkflasche mit Logo oder Gravur", price:"48,00 €", img:"img/trinkflasche.jpg", c:"#b7c4d1"}
];

function esc(s){return s.replace(/"/g,"&quot;");}

document.getElementById("year").textContent = new Date().getFullYear();
document.getElementById("wa").href = "https://wa.me/" + WHATSAPP;
document.getElementById("mail").href = "mailto:" + EMAIL;
document.getElementById("mail").textContent = EMAIL;

/* Produktkarten aufbauen */
document.getElementById("grid").innerHTML = PRODUCTS.map(function(p){
  var link = STRIPE_LINKS[p.name];
  var btn = link
    ? '<a class="btn main" href="'+link+'" target="_blank" rel="noopener">Zahlungspflichtig bestellen</a>'
    : '<button class="btn main order" type="button" data-name="'+esc(p.name)+'">Anfragen</button>';
  return '<article class="card"><div class="ph" style="--c:'+p.c+'" data-img="'+p.img+'"></div>'+
    '<div class="body"><h3>'+p.name+'</h3><div class="price">'+p.price+'</div>'+btn+'</div></article>';
}).join("");

/* Galerie: img/galerie-1.jpg bis galerie-8.jpg */
var g = "";
for (var i = 1; i <= 8; i++) g += '<div class="ph" data-img="img/galerie-'+i+'.jpg"></div>';
document.getElementById("gallery").innerHTML = g;

/* Bilder einsetzen; fehlt die Datei, bleibt der Platzhalter sichtbar */
document.querySelectorAll("[data-img]").forEach(function(el){
  var im = new Image();
  im.alt = "";
  im.loading = "lazy";
  im.onload = function(){ el.appendChild(im); };
  im.src = el.dataset.img;
});

/* "Anfragen": WhatsApp mit vorbereiteter Nachricht */
document.addEventListener("click", function(e){
  var b = e.target.closest(".order");
  if (!b) return;
  var msg = "Hallo, ich interessiere mich für: " + b.dataset.name + ". Könnt ihr mir mehr Informationen geben?";
  window.open("https://wa.me/" + WHATSAPP + "?text=" + encodeURIComponent(msg), "_blank", "noopener");
});
</script>
</body>
</html>
