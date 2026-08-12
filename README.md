<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Natalia Katerina Morales Corico</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&family=Work+Sans:wght@300;400;500;600&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{--bg:#F6F2FB;--paper:#FFFFFF;--deep:#2A1B45;--deep-2:#3B2361;--primary:#7C4DBF;--accent:#C9A6E8;--line:#B79AD9;--ink:#241536;--ink-soft:#5B4A78;--mono-tag:#8B5FBF;}
*{box-sizing:border-box;}
html{scroll-behavior:smooth;}
body{margin:0;background:var(--bg);color:var(--ink);font-family:'Work Sans',sans-serif;overflow-x:hidden;}
h1,h2,h3{font-family:'Space Grotesk',sans-serif;color:var(--deep);margin:0;}
.mono,.tag,.eyebrow,.ru-tag,.card .meta,.lang-bar-label,.contact-links a,.foot-note{font-family:'JetBrains Mono',monospace;}
a{color:var(--primary);}
.bg-grid{position:fixed;inset:0;z-index:-1;background-image:linear-gradient(var(--line) 1px,transparent 1px),linear-gradient(90deg,var(--line) 1px,transparent 1px);background-size:48px 48px;opacity:.05;}
.wrap{max-width:920px;margin:0 auto;padding:0 28px;}

/* Banner superior */
.top-banner{text-align:center;padding:44px 20px 8px;}
.top-banner .site-title{font-family:'Space Grotesk',sans-serif;font-size:clamp(38px,7vw,64px);font-weight:700;letter-spacing:.06em;background:linear-gradient(90deg,var(--deep) 0%,var(--primary) 55%,var(--accent) 100%);-webkit-background-clip:text;background-clip:text;color:transparent;margin:0;line-height:1.05;}
.top-banner .site-sub{margin-top:12px;font-size:14px;color:var(--ink-soft);letter-spacing:.02em;}

/* Hero */
header.hero{position:relative;padding:72px 0 96px;background:linear-gradient(180deg,var(--deep) 0%,var(--deep-2) 100%);color:#F2ECFB;overflow:hidden;}
header.hero::before{content:"";position:absolute;top:-120px;right:-120px;width:420px;height:420px;border-radius:50%;background:radial-gradient(circle at 30% 30%,rgba(201,166,232,.35),transparent 70%);}
.hero-inner{position:relative;z-index:1;display:flex;align-items:center;gap:44px;flex-wrap:wrap;}
.portrait-frame{flex:0 0 auto;width:190px;height:190px;border-radius:50%;padding:4px;background:conic-gradient(from 180deg,var(--accent),var(--primary),var(--accent));}
.portrait-frame img{width:100%;height:100%;border-radius:50%;object-fit:cover;display:block;border:4px solid var(--deep);}
.hero-text{flex:1 1 340px;}
.eyebrow{font-size:13px;letter-spacing:.08em;color:var(--accent);text-transform:uppercase;margin-bottom:14px;}
h1.name{font-size:clamp(32px,5vw,48px);font-weight:700;line-height:1.1;color:#FFFFFF;}
.role{margin-top:10px;font-size:18px;color:var(--accent);}
.tag-row{display:flex;flex-wrap:wrap;align-items:center;gap:10px;}
.ru-tag,.hero-extra-tag{display:inline-flex;align-items:center;padding:6px 12px;border:1px solid rgba(201,166,232,.45);border-radius:4px;font-size:13px;line-height:1;color:#E4D8F7;letter-spacing:.03em;box-sizing:border-box;}

/* Secciones */
main{position:relative;}
section{position:relative;padding:64px 0;}
section:not(:last-of-type){border-bottom:1px solid rgba(123,79,191,.12);}
.section-head{display:flex;align-items:baseline;gap:14px;margin-bottom:28px;}
.tag{font-size:12px;color:var(--mono-tag);background:rgba(124,77,191,.08);padding:4px 9px;border-radius:4px;letter-spacing:.05em;}
h2.section-title{font-size:26px;font-weight:600;}
p.lead{font-size:17px;line-height:1.7;color:var(--ink-soft);max-width:62ch;}

/* Tarjetas */
.card-row{display:grid;grid-template-columns:repeat(auto-fit,minmax(230px,1fr));gap:20px;margin-top:28px;}
.card{background:var(--paper);border:1px solid rgba(123,79,191,.14);border-radius:10px;padding:22px 22px 24px;position:relative;transition:transform .2s ease,box-shadow .2s ease;}
.card:hover{transform:translateY(-3px);box-shadow:0 12px 28px rgba(60,30,100,.10);}
.card::before{content:"";position:absolute;top:22px;left:-1px;width:3px;height:22px;background:var(--accent);border-radius:0 3px 3px 0;}
.card h3{font-size:17px;font-weight:600;margin-bottom:8px;}
.card p{font-size:14.5px;line-height:1.6;color:var(--ink-soft);margin:0;}
.card .meta{display:block;margin-top:10px;font-size:12px;color:var(--mono-tag);}

/* Barra de idioma */
.lang-bar-wrap{margin-top:6px;}
.lang-bar-label{display:flex;justify-content:space-between;font-size:13px;color:var(--ink-soft);margin-bottom:6px;}
.lang-bar{height:8px;background:rgba(123,79,191,.12);border-radius:999px;overflow:hidden;}
.lang-bar-fill{height:100%;background:linear-gradient(90deg,var(--primary),var(--accent));border-radius:999px;}

/* Footer */
footer{padding:56px 0 72px;background:var(--deep);color:#E4D8F7;text-align:center;}
footer .tag{background:rgba(201,166,232,.12);color:var(--accent);}
footer h2{color:#fff;font-size:24px;margin:14px 0 10px;}
footer p{color:#C6B4E2;max-width:46ch;margin:0 auto 26px;line-height:1.6;}
.contact-links{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;}
.contact-links a{display:inline-flex;align-items:center;gap:8px;padding:10px 18px;border:1px solid rgba(201,166,232,.35);border-radius:999px;color:#F2ECFB;text-decoration:none;font-size:14px;transition:background .2s ease,border-color .2s ease;}
.contact-links a:hover{background:rgba(201,166,232,.14);border-color:var(--accent);}
.foot-note{margin-top:40px;font-size:12px;color:rgba(196,180,226,.6);}

@media (max-width:600px){.hero-inner{flex-direction:column;text-align:center;}.tag-row{justify-content:center;}.section-head{flex-direction:column;align-items:flex-start;gap:8px;}}
@media (prefers-reduced-motion:reduce){*{transition:none !important;scroll-behavior:auto !important;}}
</style>
</head>
<body>
<div class="bg-grid"></div>

<div class="top-banner">
  <p class="site-title">SITIO WEB</p>
  <p class="site-sub">Te cuento un poco sobre mí</p>
</div>

<header class="hero">
  <div class="wrap hero-inner">
    <div class="portrait-frame"><img src="natalia.jpg" alt="Foto de Natalia Katerina Morales Corico"></div>
    <div class="hero-text">
      <div class="eyebrow">Perfil académico</div>
      <h1 class="name">Natalia Katerina<br>Morales Corico</h1>
      <div class="role">Estudiante de Ingeniería Electrónica</div>
      <div class="tag-row" style="margin-top:18px;">
        <div class="ru-tag">RU 1814663</div>
        <span class="hero-extra-tag">CI: 13247989 LP.</span>
        <span class="hero-extra-tag">La Paz - Bolivia</span>
      </div>
    </div>
  </div>
</header>

<main>
  <div class="wrap">
    <section id="perfil">
      <div class="section-head"><span class="tag">01 · Perfil</span><h2 class="section-title">Sobre mí</h2></div>
      <p class="lead">Soy boliviana, tengo 24 años y curso la carrera de Ingeniería Electrónica desde el segundo semestre de 2021. Además de mis materias de especialidad, participo activamente en la vida universitaria dentro de la mención de Sistemas de Computación, y complemento mi formación con el estudio del idioma inglés en el CETI.</p>
      <p class="lead" style="margin-top:16px;">Terminé el colegio en la Unidad Educativa María Auxiliadora en 2019. Fuera de lo académico, uno de mis hobbies favoritos es jugar volleyball.</p>
    </section>

    <section id="formacion">
      <div class="section-head"><span class="tag">02 · Formación</span><h2 class="section-title">Trayectoria académica</h2></div>
      <div class="card-row">
        <div class="card"><h3>Ingeniería Electrónica</h3><p>Carrera principal en curso, con ingreso en el semestre 2/2021.</p><span class="meta">DESDE 2021 · EN CURSO</span></div>
        <div class="card"><h3>Mención en Sistemas de Computación</h3><p>Participación activa en la facultad dentro de esta mención, ampliando el enfoque hacia el área de software y sistemas.</p><span class="meta">FACULTAD · ACTIVA</span></div>
        <div class="card"><h3>Inglés · CETI</h3><p>CETI significa Centro de Enseñanza y Traducción de Idiomas. Curso ahí el idioma inglés como parte de mi formación complementaria.</p><span class="meta">CETI · EN CURSO</span></div>
      </div>
    </section>

    <section id="habilidades">
      <div class="section-head"><span class="tag">03 · Habilidades</span><h2 class="section-title">Mis habilidades</h2></div>
      <div class="card-row">
        <div class="card"><h3>Programación</h3><p>Desarrollo con Python y C/C++, aplicando lógica de programación al diseño de sistemas electrónicos.</p></div>
        <div class="card"><h3>IoT</h3><p>Integración de sensores y microcontroladores para automatizar procesos y conectar dispositivos entre sí.</p></div>
        <div class="card"><h3>Electrónica</h3><p>Diseño y análisis de circuitos, trabajo con microcontroladores, sistemas digitales y sistemas embebidos.</p></div>
        <div class="card"><h3>Telecomunicaciones</h3><p>Nociones de sistemas de comunicación, procesamiento de señales y tecnologías relacionadas al área.</p></div>
      </div>
    </section>

    <section id="proyectos">
      <div class="section-head"><span class="tag">04 · Proyectos</span><h2 class="section-title">Proyectos</h2></div>
      <div class="card-row">
        <div class="card"><h3>Proyectos universitarios</h3><p>A lo largo de la carrera diseñé, simulé y analicé circuitos y sistemas electrónicos apoyándome en distintas herramientas de desarrollo y simulación.</p></div>
        <div class="card"><h3>Sistemas con microcontroladores</h3><p>Desarrollé proyectos que combinan microcontroladores, sensores y circuitos electrónicos como parte de mi formación en la universidad.</p></div>
      </div>
    </section>

    <section id="idioma">
      <div class="section-head"><span class="tag">05 · Idiomas</span><h2 class="section-title">Inglés en progreso</h2></div>
      <p class="lead" style="margin-bottom:22px;">Avanzando de forma constante en el idioma a través del CETI, como complemento a mi perfil técnico.</p>
      <div class="lang-bar-wrap" style="max-width:420px;">
        <div class="lang-bar-label"><span>Inglés</span><span>En curso</span></div>
        <div class="lang-bar"><div class="lang-bar-fill" style="width:55%;"></div></div>
      </div>
    </section>

    <section id="actividad">
      <div class="section-head"><span class="tag">06 · Vida universitaria</span><h2 class="section-title">Participación activa</h2></div>
      <p class="lead">Soy estudiante activa dentro de la facultad, involucrada en las actividades propias de la mención de Sistemas de Computación, además de mis cursos regulares de Ingeniería Electrónica.</p>
    </section>
  </div>
</main>

<footer>
  <div class="wrap">
    <span class="tag mono">07 · Contacto</span>
    <h2>Hablemos</h2>
    <p>Sitio Web creado para la materia Bases de Datos ETN-1000.</p>
    <div class="contact-links">
      <a href="mailto:nkmorales@umsa.bo">✉ nkmorales@umsa.bo</a>
      <a href="tel:+59177271181">☎ +591 77271181</a>
    </div>
    <div class="foot-note">Ingeniería Electrónica · 2026</div>
  </div>
</footer>
</body>
</html>
