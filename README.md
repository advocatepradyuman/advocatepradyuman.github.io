# advocatepradyuman.github.io
:root{
  --navy:#14213d;
  --navy-2:#1d2f55;
  --gold:#b8892b;
  --gold-soft:#f3e6c8;
  --ink:#1f2430;
  --muted:#667085;
  --bg:#faf8f4;
  --card:#ffffff;
  --line:#e6e1d6;
  --radius:10px;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:"Segoe UI",Roboto,Helvetica,Arial,sans-serif;color:var(--ink);background:var(--bg);line-height:1.65}
h1,h2,h3{font-family:Georgia,"Times New Roman",serif;color:var(--navy);line-height:1.25}
a{color:var(--navy-2);text-decoration:none}
img{max-width:100%;display:block}
.container{width:min(1100px,92%);margin-inline:auto}

/* Header / nav */
header.site{background:var(--navy);color:#fff;position:sticky;top:0;z-index:50;box-shadow:0 2px 12px rgba(0,0,0,.15)}
.nav{display:flex;align-items:center;justify-content:space-between;padding:14px 0}
.brand{display:flex;flex-direction:column;color:#fff}
.brand strong{font-family:Georgia,serif;font-size:1.25rem;letter-spacing:.3px}
.brand span{font-size:.72rem;letter-spacing:2px;text-transform:uppercase;color:var(--gold-soft)}
nav ul{list-style:none;display:flex;gap:26px}
nav a{color:#e9ecf5;font-size:.95rem;padding:6px 0;border-bottom:2px solid transparent;transition:.2s}
nav a:hover,nav a.active{color:#fff;border-bottom-color:var(--gold)}
#nav-toggle{display:none}
.burger{display:none;cursor:pointer;font-size:1.7rem;color:#fff}

/* Hero */
.hero{background:linear-gradient(120deg,var(--navy) 0%,var(--navy-2) 60%,#2b4272 100%);color:#fff;padding:96px 0 88px}
.hero .container{display:grid;grid-template-columns:1.3fr 1fr;gap:48px;align-items:center}
.hero h1{color:#fff;font-size:clamp(2rem,4.6vw,3.2rem);margin-bottom:16px}
.hero p.lead{color:#d9dfef;font-size:1.1rem;max-width:560px;margin-bottom:28px}
.tag{display:inline-block;background:rgba(184,137,43,.2);color:var(--gold-soft);border:1px solid var(--gold);padding:4px 14px;border-radius:30px;font-size:.78rem;letter-spacing:1.5px;text-transform:uppercase;margin-bottom:18px}
.portrait{aspect-ratio:4/5;border-radius:var(--radius);background:linear-gradient(160deg,#2b4272,#0e1730);border:1px solid rgba(255,255,255,.15);display:grid;place-items:center;text-align:center;color:var(--gold-soft);padding:20px;font-size:.9rem}
.portrait big{display:block;font-family:Georgia,serif;font-size:4rem;color:var(--gold)}

.btn{display:inline-block;padding:12px 26px;border-radius:6px;font-weight:600;font-size:.95rem;transition:.2s;border:2px solid var(--gold)}
.btn-gold{background:var(--gold);color:#fff}
.btn-gold:hover{background:#9c7120;border-color:#9c7120}
.btn-line{color:#fff;margin-left:10px}
.btn-line:hover{background:rgba(255,255,255,.1)}

/* Sections */
section{padding:72px 0}
section.alt{background:#fff;border-block:1px solid var(--line)}
.section-head{text-align:center;max-width:680px;margin:0 auto 44px}
.section-head h2{font-size:2rem;margin-bottom:10px}
.section-head p{color:var(--muted)}
.rule{width:56px;height:3px;background:var(--gold);margin:12px auto 0;border-radius:2px}

.grid{display:grid;gap:24px}
.g3{grid-template-columns:repeat(3,1fr)}
.g2{grid-template-columns:repeat(2,1fr)}
.g4{grid-template-columns:repeat(4,1fr)}

.card{background:var(--card);border:1px solid var(--line);border-radius:var(--radius);padding:28px;transition:.25s}
.card:hover{transform:translateY(-4px);box-shadow:0 12px 28px rgba(20,33,61,.1);border-color:var(--gold)}
.card .icon{font-size:1.8rem;margin-bottom:12px}
.card h3{font-size:1.2rem;margin-bottom:8px}
.card p,.card li{color:var(--muted);font-size:.95rem}
.card ul{padding-left:18px;margin-top:10px}

.stats{background:var(--navy);color:#fff;padding:46px 0}
.stats .grid{text-align:center}
.stats strong{display:block;font-family:Georgia,serif;font-size:2.3rem;color:var(--gold)}
.stats span{color:#cfd6e8;font-size:.9rem}

/* Page banner */
.banner{background:var(--navy);color:#fff;padding:60px 0;text-align:center}
.banner h1{color:#fff;font-size:2.4rem}
.banner p{color:#cfd6e8;margin-top:8px}

/* About */
.about-grid{display:grid;grid-template-columns:1fr 2fr;gap:44px;align-items:start}
.timeline{border-left:3px solid var(--gold);padding-left:24px;margin-top:20px}
.timeline .item{margin-bottom:22px;position:relative}
.timeline .item::before{content:"";position:absolute;left:-33px;top:6px;width:13px;height:13px;border-radius:50%;background:var(--gold)}
.timeline small{color:var(--gold);font-weight:700;letter-spacing:1px}
.timeline h3{font-size:1.05rem;margin:2px 0}
.timeline p{color:var(--muted);font-size:.93rem}

/* Insights */
.post .meta{font-size:.78rem;color:var(--gold);letter-spacing:1px;text-transform:uppercase;font-weight:700;margin-bottom:6px}
.post a.more{display:inline-block;margin-top:12px;font-weight:600;color:var(--gold)}

/* Contact */
.contact-grid{display:grid;grid-template-columns:1fr 1.2fr;gap:40px}
.info-row{display:flex;gap:14px;margin-bottom:20px}
.info-row .ic{font-size:1.4rem}
.info-row h4{font-family:Georgia,serif;color:var(--navy)}
.info-row p{color:var(--muted);font-size:.95rem}
form label{display:block;font-weight:600;font-size:.88rem;margin:14px 0 6px;color:var(--navy)}
form input,form select,form textarea{width:100%;padding:12px 14px;border:1px solid var(--line);border-radius:6px;font:inherit;background:#fff}
form input:focus,form select:focus,form textarea:focus{outline:2px solid var(--gold);border-color:var(--gold)}
form button{margin-top:20px;cursor:pointer;border:none}
.map{margin-top:10px;border-radius:var(--radius);overflow:hidden;border:1px solid var(--line);min-height:220px;background:#eef0f4;display:grid;place-items:center;color:var(--muted)}

/* CTA */
.cta{background:linear-gradient(120deg,var(--gold),#d4a64a);text-align:center;padding:56px 0;color:#fff}
.cta h2{color:#fff;margin-bottom:10px}
.cta .btn{background:var(--navy);border-color:var(--navy);color:#fff;margin-top:14px}

/* Footer */
footer.site{background:#0c1429;color:#aab3c8;padding:48px 0 20px;font-size:.9rem}
footer .cols{display:grid;grid-template-columns:2fr 1fr 1fr;gap:36px;margin-bottom:28px}
footer h4{color:#fff;font-family:Georgia,serif;margin-bottom:10px}
footer a{color:#aab3c8;display:block;margin-bottom:6px}
footer a:hover{color:var(--gold)}
.disclaimer{border-top:1px solid rgba(255,255,255,.12);padding-top:16px;font-size:.78rem;line-height:1.6}

/* Responsive */
@media(max-width:860px){
  .hero .container,.about-grid,.contact-grid,.g2,.g3,footer .cols{grid-template-columns:1fr}
  .g4{grid-template-columns:repeat(2,1fr)}
  .burger{display:block}
  nav{position:absolute;top:100%;left:0;right:0;background:var(--navy-2);max-height:0;overflow:hidden;transition:max-height .3s}
  nav ul{flex-direction:column;gap:0;padding:8px 4%}
  nav li a{display:block;padding:12px 0}
  #nav-toggle:checked ~ nav{max-height:320px}
  .portrait{max-width:300px}
  .btn-line{margin:10px 0 0}
}
