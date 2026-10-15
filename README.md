<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="theme-color" content="#183044">
<meta name="description" content="Propuesta externa de colaboración profesional pro bono para explorar innovación digital, procesos y hábitat digno con organizaciones de impacto social.">
<title>IMPACTA SOCIAL | Propuesta de colaboración</title>
<style>
:root{
  --navy:#183044;--navy-2:#24465a;--cream:#F7F5F0;--stone:#D8D7D2;
  --terra:#C96F50;--green:#73846D;--ink:#1e2c34;--muted:#647078;
  --white:#fff;--line:rgba(24,48,68,.14);--radius:22px;
  --shadow:0 18px 55px rgba(24,48,68,.10);--max:1180px;
}
*{box-sizing:border-box}
html{scroll-behavior:smooth;scroll-padding-top:86px}
body{margin:0;background:var(--cream);color:var(--ink);font-family:Inter,ui-sans-serif,system-ui,-apple-system,BlinkMacSystemFont,"Segoe UI",sans-serif;line-height:1.6}
a{color:inherit}
img{max-width:100%;display:block}
button,a{ -webkit-tap-highlight-color:transparent}
a:focus-visible,button:focus-visible{outline:3px solid var(--terra);outline-offset:4px}
.skip-link{position:absolute;left:-9999px;top:auto}.skip-link:focus{left:1rem;top:1rem;background:#fff;padding:.8rem;z-index:1000}
.container{width:min(var(--max),calc(100% - 48px));margin-inline:auto}
.eyebrow{display:flex;align-items:center;gap:.65rem;text-transform:uppercase;letter-spacing:.14em;font-size:.73rem;font-weight:800;color:var(--terra)}
.eyebrow:before{content:"";width:26px;height:2px;background:currentColor}
h1,h2,h3,p{margin-top:0}
h1,h2,h3{letter-spacing:-.04em;line-height:1.08}
h1{font-size:clamp(3.6rem,9vw,7.8rem);max-width:900px;margin:.7rem 0 1.1rem}
h2{font-size:clamp(2.2rem,5vw,4.4rem);margin:1rem 0 1.2rem}
h3{font-size:1.35rem;margin-bottom:.65rem}
p{color:var(--muted)}
.lead{font-size:clamp(1.08rem,2vw,1.32rem);max-width:700px;line-height:1.7}
.section{padding:108px 0}
.section-heading{max-width:780px;margin-bottom:46px}
.section-heading p{font-size:1.08rem;max-width:650px}
.topbar{position:sticky;top:0;z-index:100;background:rgba(247,245,240,.92);backdrop-filter:blur(16px);border-bottom:1px solid var(--line)}
.nav{min-height:76px;display:flex;align-items:center;justify-content:space-between;gap:24px}
.brand{display:flex;align-items:center;gap:12px;text-decoration:none;font-weight:850;letter-spacing:-.03em;color:var(--navy)}
.brand-mark{width:36px;height:36px;border-radius:50% 50% 50% 8px;background:var(--terra);display:grid;place-items:center;color:white;font-size:.78rem;font-weight:900;transform:rotate(-4deg)}
.nav-links{display:flex;align-items:center;gap:22px}
.nav-links a{text-decoration:none;color:#4f5d65;font-size:.86rem;font-weight:700}
.nav-links a:hover{color:var(--terra)}
.nav-cta,.button{display:inline-flex;align-items:center;justify-content:center;gap:10px;border:0;border-radius:999px;padding:14px 21px;font:inherit;font-size:.92rem;font-weight:800;text-decoration:none;cursor:pointer;transition:transform .2s ease,background .2s ease}
.nav-cta,.button-primary{background:var(--navy);color:white}
.nav-cta:hover,.button-primary:hover{background:var(--navy-2);transform:translateY(-2px)}
.button-secondary{border:1px solid rgba(255,255,255,.42);color:white;background:rgba(255,255,255,.08)}
.button-secondary:hover{background:rgba(255,255,255,.16)}
.menu-toggle{display:none;background:transparent;border:1px solid var(--line);border-radius:12px;padding:10px;color:var(--navy);font:inherit}
.hero{background:var(--navy);color:white;position:relative;overflow:hidden;padding:86px 0 72px}
.hero:after{content:"";position:absolute;width:560px;height:560px;border:1px solid rgba(255,255,255,.12);border-radius:50%;right:-150px;top:-140px;box-shadow:0 0 0 55px rgba(255,255,255,.025),0 0 0 110px rgba(255,255,255,.02);pointer-events:none}
.hero-grid{display:grid;grid-template-columns:1.05fr .95fr;align-items:center;gap:50px;position:relative;z-index:1}
.hero .eyebrow{color:#efad92}
.hero h1 span{color:#efad92}
.hero .lead{color:rgba(255,255,255,.78)}
.hero-meta{margin:28px 0 30px;color:rgba(255,255,255,.65);font-size:.9rem}
.hero-actions{display:flex;flex-wrap:wrap;gap:12px}
.hero-art{position:relative;min-height:460px;border-radius:180px 180px 26px 26px;overflow:hidden;background:#2b4b5c}
.hero-art img{width:100%;height:100%;min-height:460px;object-fit:cover;opacity:.82;filter:saturate(.82)}
.hero-art:after{content:"";position:absolute;inset:0;background:linear-gradient(180deg,rgba(24,48,68,.02),rgba(24,48,68,.65))}
.art-label{position:absolute;z-index:2;bottom:26px;left:26px;right:26px;color:white}
.art-label strong{display:block;font-size:1.4rem;letter-spacing:-.03em;max-width:320px;line-height:1.2}
.art-label span{display:block;color:rgba(255,255,255,.75);font-size:.82rem;margin-top:9px}
.hero-bottom{display:flex;align-items:center;justify-content:space-between;gap:20px;margin-top:52px;padding-top:22px;border-top:1px solid rgba(255,255,255,.18);color:rgba(255,255,255,.65);font-size:.83rem}
.scroll-cue{display:flex;align-items:center;gap:10px;color:white;text-decoration:none;font-weight:700}
.scroll-cue span{display:grid;place-items:center;border:1px solid rgba(255,255,255,.35);width:30px;height:30px;border-radius:50%}
.intro-grid{display:grid;grid-template-columns:.8fr 1.2fr;gap:80px;align-items:start}
.statement{font-size:clamp(1.8rem,3.5vw,3.3rem);line-height:1.18;letter-spacing:-.045em;color:var(--navy);font-weight:750}
.statement em{color:var(--terra);font-style:normal}
.intro-copy p{font-size:1.08rem}
.principles{display:grid;grid-template-columns:repeat(3,1fr);gap:14px;margin-top:42px}
.principle{border-top:1px solid var(--line);padding-top:18px}
.principle b{display:block;color:var(--navy);font-size:1rem;margin-bottom:7px}
.principle span{color:var(--muted);font-size:.9rem}
.dark-section{background:#e9e8e1}
.opportunity-grid{display:grid;grid-template-columns:repeat(3,1fr);gap:18px}
.opportunity{background:#fff;border-radius:var(--radius);padding:28px;min-height:390px;display:flex;flex-direction:column;box-shadow:0 8px 30px rgba(24,48,68,.04)}
.op-number{font-size:.76rem;font-weight:850;letter-spacing:.12em;color:var(--terra);margin-bottom:28px}
.op-icon{width:52px;height:52px;border-radius:16px;display:grid;place-items:center;background:#f5e5de;color:var(--navy);margin-bottom:22px}
.op-icon svg{width:25px;height:25px}
.opportunity p{font-size:.94rem}
.opportunity ul{padding-left:1.1rem;margin:.2rem 0 1.2rem;color:var(--muted);font-size:.9rem}
.opportunity li{margin:.35rem 0}
.metric{margin-top:auto;border-top:1px solid var(--line);padding-top:17px;font-size:.82rem;color:var(--navy)}
.metric strong{display:block;font-size:.72rem;text-transform:uppercase;letter-spacing:.09em;color:var(--green);margin-bottom:4px}
.note{padding:18px 22px;background:rgba(115,132,109,.12);border-left:3px solid var(--green);border-radius:0 12px 12px 0;color:#425448;margin-top:22px}
.timeline{display:grid;grid-template-columns:repeat(4,1fr);gap:0;position:relative}
.timeline:before{content:"";position:absolute;top:24px;left:5%;right:5%;height:1px;background:var(--stone)}
.phase{position:relative;padding:0 22px 0 0}
.phase-dot{position:relative;z-index:1;width:49px;height:49px;border-radius:50%;display:grid;place-items:center;background:var(--navy);color:white;font-weight:850;margin-bottom:23px;box-shadow:0 0 0 8px var(--cream)}
.phase small{color:var(--terra);font-weight:850;text-transform:uppercase;letter-spacing:.1em}
.phase h3{margin-top:10px}
.phase p{font-size:.92rem}
.deliverable{font-size:.83rem!important;color:var(--navy)!important;border-top:1px solid var(--line);padding-top:13px;margin-top:16px}
.team-grid{display:grid;grid-template-columns:1fr 1fr;gap:18px}
.person{padding:34px;border-radius:var(--radius);background:white;display:grid;grid-template-columns:70px 1fr;gap:20px;box-shadow:0 8px 30px rgba(24,48,68,.04)}
.avatar{width:70px;height:70px;border-radius:50% 50% 50% 10px;display:grid;place-items:center;background:#e8e9e1;color:var(--navy);font-size:1.1rem;font-weight:900}
.person .role{font-size:.77rem;text-transform:uppercase;letter-spacing:.09em;color:var(--terra);font-weight:850}
.person p{font-size:.94rem}
.skill-tags{display:flex;flex-wrap:wrap;gap:7px;margin-top:14px}
.skill-tags span{font-size:.75rem;border:1px solid var(--line);padding:5px 9px;border-radius:999px;color:#52616a}
.complement{margin-top:24px;background:var(--navy);border-radius:var(--radius);padding:30px;color:white;display:flex;align-items:center;justify-content:space-between;gap:28px}
.complement p{color:rgba(255,255,255,.72);margin:0;max-width:700px}
.complement strong{color:#efad92}
.metrics-layout{display:grid;grid-template-columns:.9fr 1.1fr;gap:60px;align-items:start}
.metric-list{display:grid;grid-template-columns:1fr 1fr;gap:12px}
.metric-card{background:white;border:1px solid var(--line);border-radius:16px;padding:19px}
.metric-card .mini{font-size:.72rem;text-transform:uppercase;letter-spacing:.08em;color:var(--green);font-weight:850}
.metric-card b{display:block;font-size:1.05rem;color:var(--navy);margin:8px 0}
.metric-card span{font-size:.82rem;color:var(--muted)}
.sim-label{display:inline-flex;background:#f7e7df;color:#87462f;padding:6px 10px;border-radius:999px;font-size:.73rem;font-weight:850;margin-bottom:15px}
.bar-chart{background:white;padding:28px;border-radius:var(--radius);border:1px solid var(--line)}
.bar-row{display:grid;grid-template-columns:115px 1fr 38px;gap:12px;align-items:center;margin:18px 0;font-size:.82rem;color:var(--muted)}
.bar-track{height:10px;background:#ecebe5;border-radius:99px;overflow:hidden}
.bar-fill{height:100%;border-radius:99px;background:var(--green)}
.bar-row:nth-of-type(3) .bar-fill{background:var(--terra)}
.bar-row:nth-of-type(4) .bar-fill{background:var(--navy)}
.bar-foot{font-size:.78rem;margin:20px 0 0}
.commit-grid{display:grid;grid-template-columns:1fr 1fr;gap:20px}
.commit-card{padding:30px;border:1px solid var(--line);border-radius:var(--radius);background:rgba(255,255,255,.55)}
.commit-card h3{display:flex;align-items:center;gap:10px}
.commit-card h3 svg{width:22px;height:22px;color:var(--green)}
.commit-card ul{padding-left:1.2rem;color:var(--muted);font-size:.93rem}
.commit-card li{margin:.5rem 0}
.final-cta{background:var(--navy);color:white;padding:100px 0;position:relative;overflow:hidden}
.final-cta:after{content:"";position:absolute;width:450px;height:450px;border:1px solid rgba(255,255,255,.15);border-radius:50%;right:-130px;bottom:-230px;box-shadow:0 0 0 50px rgba(255,255,255,.025),0 0 0 100px rgba(255,255,255,.025)}
.cta-grid{display:grid;grid-template-columns:1.2fr .8fr;gap:60px;align-items:center;position:relative;z-index:1}
.final-cta .eyebrow{color:#efad92}
.final-cta h2{max-width:760px}
.final-cta p{color:rgba(255,255,255,.73);font-size:1.08rem;max-width:690px}
.cta-panel{border:1px solid rgba(255,255,255,.2);border-radius:20px;padding:26px;background:rgba(255,255,255,.045)}
.cta-panel b{display:block;font-size:1.1rem;margin-bottom:8px}
.cta-panel p{font-size:.9rem}
.cta-panel .button{width:100%;margin-top:8px}
.contact-placeholder{font-size:.85rem!important;color:rgba(255,255,255,.85)!important;margin-top:14px!important}
.footer{padding:26px 0;background:#102534;color:rgba(255,255,255,.62);font-size:.78rem}
.footer-inner{display:flex;justify-content:space-between;gap:22px;align-items:center}
.footer a{color:white}
.footer p{margin:0;font-size:.78rem}
.disclaimer{max-width:760px}
.print-button{position:fixed;right:20px;bottom:20px;z-index:80;border:1px solid var(--line);background:white;color:var(--navy);box-shadow:var(--shadow);border-radius:999px;padding:12px 16px;font:inherit;font-weight:800;cursor:pointer}
@media(max-width:900px){
 .hero-grid,.intro-grid,.metrics-layout,.cta-grid{grid-template-columns:1fr}
 .hero-grid{gap:36px}.hero-art{min-height:360px;border-radius:140px 140px 24px 24px}.hero-art img{min-height:360px}
 .intro-grid{gap:25px}.opportunity-grid{grid-template-columns:1fr}.opportunity{min-height:0}
 .timeline{grid-template-columns:1fr 1fr;gap:35px 12px}.timeline:before{display:none}
 .team-grid{grid-template-columns:1fr}.cta-grid{gap:32px}
}
@media(max-width:700px){
 .container{width:min(var(--max),calc(100% - 32px))}
 .section{padding:76px 0}.hero{padding:62px 0 38px}
 .nav{min-height:68px}.menu-toggle{display:block}.nav-cta{display:none}
 .nav-links{display:none;position:absolute;top:68px;left:0;right:0;background:var(--cream);padding:18px 24px 24px;border-bottom:1px solid var(--line);flex-direction:column;align-items:stretch;gap:15px}
 .nav-links.open{display:flex}.nav-links a{padding:7px 0}
 .hero-art{min-height:310px}.hero-art img{min-height:310px}
 .hero-bottom{align-items:flex-start;flex-direction:column}
 .principles{grid-template-columns:1fr;gap:22px}
 .timeline{grid-template-columns:1fr;gap:32px}
 .phase{padding-right:0;padding-left:5px;display:grid;grid-template-columns:54px 1fr;column-gap:16px}
 .phase-dot{grid-row:1 / span 3;margin-bottom:0}
 .phase small,.phase h3,.phase p,.phase .deliverable{grid-column:2}
 .phase h3{margin:8px 0}.phase p{margin-bottom:0}
 .person{grid-template-columns:54px 1fr;padding:23px;gap:15px}.avatar{width:54px;height:54px}
 .complement{align-items:flex-start;flex-direction:column}
 .metric-list{grid-template-columns:1fr}
 .bar-row{grid-template-columns:92px 1fr 30px;gap:8px}
 .commit-grid{grid-template-columns:1fr}
 .final-cta{padding:76px 0}
 .footer-inner{align-items:flex-start;flex-direction:column}
 .print-button{right:12px;bottom:12px}
}
@media(prefers-reduced-motion:reduce){
 html{scroll-behavior:auto}
 *,*:before,*:after{transition:none!important;animation:none!important}
}
@media print{
 @page{size:A4;margin:14mm}
 body{background:white;color:#222;font-size:10pt}
 .topbar,.hero-actions,.scroll-cue,.print-button,.footer{display:none!important}
 .hero,.final-cta{background:#183044!important;color:white!important;-webkit-print-color-adjust:exact;print-color-adjust:exact}
 .hero{padding:24px 0}.hero-grid{grid-template-columns:1.1fr .9fr;gap:18px}
 h1{font-size:42pt}.hero-art,.hero-art img{min-height:250px;height:250px}
 .section{padding:28px 0;break-inside:avoid}
 h2{font-size:27pt}.opportunity-grid,.team-grid,.commit-grid{grid-template-columns:repeat(2,1fr)}
 .opportunity{min-height:0;padding:18px;break-inside:avoid}.opportunity-grid .opportunity:last-child{grid-column:1/-1}
 .timeline{grid-template-columns:repeat(4,1fr)}.timeline:before{display:block}
 .phase{padding-right:10px}.phase-dot{box-shadow:none}
 .person,.metric-card,.commit-card,.bar-chart{break-inside:avoid;box-shadow:none}
 .cta-grid{grid-template-columns:1.2fr .8fr;gap:24px}
 a{text-decoration:none}
}
</style>
</head>
<body>
<a class="skip-link" href="#contenido">Saltar al contenido</a>
<header class="topbar">
  <div class="container nav">
    <a class="brand" href="#inicio" aria-label="IMPACTA SOCIAL, inicio">
      <span class="brand-mark" aria-hidden="true">IS</span><span>IMPACTA SOCIAL</span>
    </a>
    <button class="menu-toggle" id="menuToggle" aria-expanded="false" aria-controls="navLinks">Menú ☰</button>
    <nav class="nav-links" id="navLinks" aria-label="Navegación principal">
      <a href="#proposito">Propósito</a><a href="#oportunidades">Oportunidades</a><a href="#piloto">Piloto</a><a href="#equipo">Equipo</a><a href="#compromiso">Compromiso</a>
    </nav>
    <a class="nav-cta" href="#conversemos">Coordinar reunión <span aria-hidden="true">↗</span></a>
  </div>
</header>

<main id="contenido">
<section class="hero" id="inicio">
  <div class="container">
    <div class="hero-grid">
      <div>
        <div class="eyebrow">Propuesta de colaboración externa</div>
        <h1>IMPACTA <span>SOCIAL</span></h1>
        <p class="lead">Innovación digital, gestión eficiente y hábitat digno.</p>
        <p class="lead">Convertimos la intención de ayudar en acciones concretas, sostenibles y medibles.</p>
        <p class="hero-meta">Una propuesta de colaboración profesional pro bono impulsada por Red Soluciones TI y Arq. Bárbara Torres para explorar soluciones digitales, automatización y diseño al servicio del impacto social.</p>
        <div class="hero-actions">
          <a class="button button-primary" href="#conversemos">Explorar una colaboración <span aria-hidden="true">↗</span></a>
          <a class="button button-secondary" href="#piloto">Conocer la propuesta ↓</a>
        </div>
      </div>
      <div class="hero-art">
        <img src="https://images.unsplash.com/photo-1469571486292-0ba58a3f068b?auto=format&fit=crop&w=1200&q=85" alt="Personas colaborando en una actividad comunitaria" fetchpriority="high">
        <div class="art-label"><strong>La tecnología y el diseño al servicio de las organizaciones sociales.</strong><span>Una propuesta para escuchar, cocrear y medir.</span></div>
      </div>
    </div>
    <div class="hero-bottom">
      <span>Propuesta impulsada por Red Soluciones TI y la Arq. Bárbara Torres</span>
      <a class="scroll-cue" href="#proposito"><span aria-hidden="true">↓</span> Explorar la propuesta</a>
    </div>
  </div>
</section>

<section class="section" id="proposito">
  <div class="container intro-grid">
    <div>
      <div class="eyebrow">01 / Propósito compartido</div>
      <h2>Más capacidad para hacer que las cosas pasen.</h2>
    </div>
    <div class="intro-copy">
      <p class="statement">No llegamos con una solución predeterminada. <em>Empezamos escuchando.</em></p>
      <p>Es una propuesta externa de colaboración profesional pro bono que busca poner capacidades de tecnología, automatización de procesos, sistemas y diseño al servicio de una necesidad real que la organización decida priorizar.</p>
      <p>La intención es trabajar de manera complementaria con el equipo de su ONG: comprender el contexto, identificar una oportunidad concreta y probar una solución acotada que pueda evaluarse con criterios acordados.</p>
      <div class="principles">
        <div class="principle"><b>Escuchar antes de diseñar</b><span>Las prioridades se definen junto con el equipo organizador y las comunidades.</span></div>
        <div class="principle"><b>Resolver algo concreto</b><span>Un piloto pequeño, útil y con alcance claramente definido.</span></div>
        <div class="principle"><b>Medir y transferir</b><span>Documentación y capacitación para que la solución sea autosostenible.</span></div>
      </div>
    </div>
  </div>
</section>

<section class="section dark-section" id="oportunidades">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">02 / Líneas posibles</div>
      <h2>Tres caminos. Una prioridad compartida.</h2>
      <p>Estas son áreas potenciales para explorar, no necesidades preatribuidas. La línea definitiva se seleccionará tras conversar con el equipo responsable.</p>
    </div>
    <div class="opportunity-grid">
      <article class="opportunity">
        <div class="op-number">LÍNEA A / 01</div>
        <div class="op-icon" aria-hidden="true"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7"><path d="M16 21v-2a4 4 0 0 0-4-4H6a4 4 0 0 0-4 4v2"/><circle cx="9" cy="7" r="4"/><path d="M20 8v6m3-3h-6"/></svg></div>
        <h3>CONECTA & PARTICIPACIÓN</h3>
        <p>Explorar cómo optimizar la incorporación y flujo de personas interesadas en colaborar o participar (voluntarios, aliados, beneficiarios).</p>
        <ul><li>Formularios e integraciones inteligentes</li><li>Confirmaciones y automatización de correos/mensajes</li><li>Seguimiento de registro e inscripciones</li></ul>
        <div class="metric"><strong>Indicador posible</strong>Reducción de tiempos de registro o incremento en tasa de respuesta.</div>
      </article>
      <article class="opportunity">
        <div class="op-number">LÍNEA B / 02</div>
        <div class="op-icon" aria-hidden="true"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7"><path d="M14 2H6a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V8z"/><polyline points="14 2 14 8 20 8"/><line x1="16" y1="13" x2="8" y2="13"/><line x1="16" y1="17" x2="8" y2="17"/><polyline points="10 9 9 9 8 9"/></svg></div>
        <h3>GESTIÓN & PROCESOS INTERNOS</h3>
        <p>Explorar la simplificación operativa del equipo para liberar tiempo y enfocar recursos en la misión de la organización.</p>
        <ul><li>Automatización de reportes y tableros de gestión</li><li>Organización y centralización de datos clave</li><li>Integración entre herramientas internas y CRM</li></ul>
        <div class="metric"><strong>Indicador posible</strong>Ahorro de horas hombre semanales en tareas repetitivas.</div>
      </article>
      <article class="opportunity">
        <div class="op-number">LÍNEA C / 03</div>
        <div class="op-icon" aria-hidden="true"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.7"><path d="m3 10 9-7 9 7"/><path d="M5 9v12h14V9M9 21v-7h6v7"/><path d="M2 21h20"/></svg></div>
        <h3>DISEÑO & HÁBITAT</h3>
        <p>Explorar aportes de arquitectura y diseño vinculados a la funcionalidad de espacios comunitarios y proyectos de infraestructura social.</p>
        <ul><li>Diagnóstico espacial y funcional</li><li>Alternativas preliminares de distribución y uso de espacio</li><li>Presentaciones de propuesta para comunidades</li></ul>
        <div class="metric"><strong>Indicador posible</strong>Proyectos espaciales optimizados y validados con los usuarios.</div>
      </article>
    </div>
    <div class="note"><strong>Importante:</strong> estas líneas son hipótesis iniciales. No presuponen deficiencias en la organización ni obligan a implementar una solución específica.</div>
  </div>
</section>

<section class="section" id="piloto">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">03 / Método de trabajo</div>
      <h2>Un piloto pequeño, diseñado para aprender.</h2>
      <p>Proponemos implementar un piloto ágil de cuatro a seis semanas, sujeto a diagnóstico, disponibilidad y aprobación previa.</p>
    </div>
    <div class="timeline">
      <article class="phase">
        <div class="phase-dot">01</div><small>Semana 1</small><h3>Escuchar</h3>
        <p>Reunión de inicio, comprensión de prioridades, revisión del flujo actual y definición de metas.</p>
        <p class="deliverable"><b>Entregable:</b> diagnóstico breve y alcance conjunto del piloto.</p>
      </article>
      <article class="phase">
        <div class="phase-dot">02</div><small>Semana 2</small><h3>Diseñar</h3>
        <p>Mapear la solución, seleccionar herramientas, definir métricas y acordar criterios de éxito.</p>
        <p class="deliverable"><b>Entregable:</b> diseño o prototipo aprobado.</p>
      </article>
      <article class="phase">
        <div class="phase-dot">03</div><small>Semanas 3–4</small><h3>Implementar</h3>
        <p>Configuración técnica/espacial de la propuesta, pruebas piloto y ajustes según retroalimentación.</p>
        <p class="deliverable"><b>Entregable:</b> piloto operativo dentro del alcance acordado.</p>
      </article>
      <article class="phase">
        <div class="phase-dot">04</div><small>Semana 5–6</small><h3>Medir y transferir</h3>
        <p>Revisión de resultados, capacitación al equipo para asegurar autonomía y entrega de documentación.</p>
        <p class="deliverable"><b>Entregable:</b> manual de uso y reporte de impacto.</p>
      </article>
    </div>
    <div class="note">El calendario es flexible según la disponibilidad de ambas partes. El alcance definitivo se establecerá formalmente antes de iniciar.</div>
  </div>
</section>

<section class="section dark-section" id="equipo">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">04 / Quiénes proponemos colaborar</div>
      <h2>Dos perspectivas que se complementan.</h2>
      <p>La combinación de arquitectura orientada a las personas y tecnología aplicada a procesos permite abordar soluciones integrales y eficientes.</p>
    </div>
    <div class="team-grid">
      <article class="person">
        <div class="avatar" aria-hidden="true">BT</div>
        <div>
          <div class="role">Arquitectura · Diseño de Espacios · Proyectos</div>
          <h3>Bárbara Torres Salas</h3>
          <p>Arquitecta y diseñadora de interiores, egresada de la Universidad Ricardo Palma. Su enfoque integra el diseño funcional, la optimización espacial y la atención a las necesidades humanas y comunitarias.</p>
          <div class="skill-tags"><span>Diseño de espacios</span><span>Funcionalidad urbana</span><span>Diagnóstico espacial</span><span>Proyectos habitacionales</span></div>
        </div>
      </article>
      <article class="person">
        <div class="avatar" aria-hidden="true">GB</div>
        <div>
          <div class="role">Automatización · IA · Sistemas</div>
          <h3>Gabriel Barrero</h3>
          <p>Especialista en automatización de procesos y tecnología aplicada desde <strong>Red Soluciones TI</strong>. Encamina la integración de herramientas digitales, flujos de trabajo, sistemas de mensajería y optimización operativa.</p>
          <div class="skill-tags"><span>Red Soluciones TI</span><span>n8n · Make · Zapier</span><span>Integraciones API</span><span>CRM y Consultas</span><span>Dashboards</span></div>
        </div>
      </article>
    </div>
    <div class="complement">
      <p><strong>Diseño orientado a las personas.</strong> Tecnología que optimiza los procesos. Una alianza estratégica profesional para soluciones sostenibles.</p>
      <span style="font-weight:850;white-space:nowrap">Personas + Procesos + Tecnología</span>
    </div>
  </div>
</section>

<section class="section" id="medicion">
  <div class="container metrics-layout">
    <div>
      <div class="eyebrow">05 / Aprender con evidencia</div>
      <h2>El impacto se acuerda y se mide.</h2>
      <p>Antes de implementar, definiremos en conjunto qué constituye una mejora útil para la organización. No prometemos cifras preconcebidas; establecemos metas realistas basadas en datos.</p>
      <p>Los indicadores dependerán directamente del área de trabajo elegida.</p>
      <div class="note">La representación gráfica es una simulación visual conceptual y no refleja datos actuales de la ONG.</div>
    </div>
    <div>
      <div class="bar-chart">
        <span class="sim-label">SIMULACIÓN ILUSTRATIVA · SIN DATOS REALES</span>
        <h3>Ejemplo de tablero de seguimiento</h3>
        <p style="font-size:.88rem">Indicadores tipo a coordinar con el equipo asignado.</p>
        <div class="bar-row"><span>Tiempo de gestión</span><div class="bar-track"><div class="bar-fill" style="width:72%"></div></div><b>—</b></div>
        <div class="bar-row"><span>Tareas manuales</span><div class="bar-track"><div class="bar-fill" style="width:56%"></div></div><b>—</b></div>
        <div class="bar-row"><span>Respuestas a tiempo</span><div class="bar-track"><div class="bar-fill" style="width:64%"></div></div><b>—</b></div>
        <div class="bar-row"><span>Entregables</span><div class="bar-track"><div class="bar-fill" style="width:84%"></div></div><b>—</b></div>
        <p class="bar-foot">Estructura de referencia para medir avances. Se adaptará según las necesidades elegidas.</p>
      </div>
      <div class="metric-list" style="margin-top:14px">
        <div class="metric-card"><div class="mini">Proceso</div><b>Tiempo por tarea</b><span>Comparación de agilidad del flujo.</span></div>
        <div class="metric-card"><div class="mini">Calidad</div><b>Reducción de errores</b><span>Sistematización de actividades manuales.</span></div>
        <div class="metric-card"><div class="mini">Efectividad</div><b>Nivel de participación</b><span>Si aplica a la línea de trabajo.</span></div>
        <div class="metric-card"><div class="mini">Autonomía</div><b>Transferencia tecnológica</b><span>Grado de apropiación por parte del equipo.</span></div>
      </div>
    </div>
  </div>
</section>

<section class="section dark-section" id="compromiso">
  <div class="container">
    <div class="section-heading">
      <div class="eyebrow">06 / Compromiso y transparencia</div>
      <h2>Pro bono, con alcance claro.</h2>
      <p>Aportamos nuestro tiempo y competencias profesionales para asegurar un proyecto de alto valor, medible y fácil de mantener en el tiempo.</p>
    </div>
    <div class="commit-grid">
      <article class="commit-card">
        <h3><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" aria-hidden="true"><path d="m5 12 4 4L19 6"/></svg>Qué proponemos</h3>
        <ul><li>Asumir pro bono los honorarios profesionales del proyecto acordado.</li><li>Trabajar con un enlace designado por la ONG y metas claras.</li><li>Documentar los procesos desarrollados y capacitar al personal.</li><li>Presentar un balance final sin compromisos de permanencia.</li></ul>
      </article>
      <article class="commit-card">
        <h3><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="1.8" aria-hidden="true"><path d="M12 3v18M3 12h18"/></svg>Qué acordaremos antes</h3>
        <ul><li>Alcance del piloto, cronograma y responsables del proyecto.</li><li>Costos de licencias, plataformas de terceros o insumos físicos (si fueran estrictamente necesarios).</li><li>Seguridad de datos, permisos y confidencialidad.</li><li>Autorización explícita sobre el uso institucional de nombres o imágenes.</li></ul>
      </article>
    </div>
    <div class="note"><strong>Privacidad y ética:</strong> Priorizamos entornos seguros, datos mínimos y ambientes de prueba. No compartiremos ni procesaremos información sensible en plataformas de IA sin aprobación previa de la ONG.</div>
  </div>
</section>

<section class="final-cta" id="conversemos">
  <div class="container cta-grid">
    <div>
      <div class="eyebrow">07 / El primer paso</div>
      <h2>El primer paso es escuchar.</h2>
      <p>Nos encantaría coordinar una breve reunión de 30 minutos para conocer sus metas prioritarias, identificar oportunidades puntuales y evaluar la viabilidad de un proyecto pro bono.</p>
      <p>Sin ningún compromiso. Comenzamos con una simple conversación.</p>
    </div>
    <aside class="cta-panel">
      <b>¿Conversamos?</b>
      <p>Póngase en contacto directamente con nosotros para agendar un espacio en la agenda.</p>
      <a class="button button-primary" href="https://wa.me/51905858566" target="_blank" rel="noopener noreferrer">Contactar por WhatsApp <span aria-hidden="true">↗</span></a>
      <p class="contact-placeholder"><strong>Gabriel Barrero</strong> · Red Soluciones TI<br>Teléfono / WhatsApp: 905858566</p>
      <p class="contact-placeholder"><strong>Arq. Bárbara Torres Salas</strong><br>Arquitectura y Diseño Espacial</p>
    </aside>
  </div>
</section>
</main>

<footer class="footer">
  <div class="container footer-inner">
    <div><strong>IMPACTA SOCIAL</strong><p>Innovación digital, gestión eficiente y hábitat digno.</p></div>
    <p class="disclaimer">Propuesta profesional externa e independiente. Sujeta a diálogo, evaluación previa y acuerdo entre las partes.</p>
  </div>
</footer>

<button class="print-button" id="printButton" type="button" aria-label="Imprimir o guardar la propuesta como PDF">↧ Guardar / imprimir PDF</button>
<script>
(function(){
  const toggle=document.getElementById('menuToggle');
  const nav=document.getElementById('navLinks');
  toggle.addEventListener('click',function(){
    const open=nav.classList.toggle('open');
    toggle.setAttribute('aria-expanded',String(open));
    toggle.textContent=open?'Cerrar ×':'Menú ☰';
  });
  nav.querySelectorAll('a').forEach(function(link){
    link.addEventListener('click',function(){
      nav.classList.remove('open');
      toggle.setAttribute('aria-expanded','false');
      toggle.textContent='Menú ☰';
    });
  });
  document.getElementById('printButton').addEventListener('click',function(){window.print();});
})();
</script>
</body>
</html>
