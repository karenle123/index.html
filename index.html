<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Herencia de Cuero</title>
  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,600;1,300;1,400&family=Raleway:wght@300;400;500;600&display=swap" rel="stylesheet"/>
  <style>
    *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

    :root {
      --navy: #0b1829;
      --navy-mid: #112240;
      --navy-light: #1a3355;
      --gold: #c9a84c;
      --gold-light: #e2c97e;
      --white: #f5f2ed;
      --gray: #9aacbd;
      --black: #060d18;
    }

    html { scroll-behavior: smooth; }

    body {
      font-family: 'Raleway', sans-serif;
      background: var(--navy);
      color: var(--white);
      overflow-x: hidden;
      cursor: none;
    }

    /* Custom cursor */
    .cursor {
      width: 10px; height: 10px;
      background: var(--gold);
      border-radius: 50%;
      position: fixed;
      top: 0; left: 0;
      pointer-events: none;
      z-index: 9999;
      transition: transform 0.15s ease, background 0.2s;
      transform: translate(-50%, -50%);
    }
    .cursor-ring {
      width: 36px; height: 36px;
      border: 1px solid var(--gold);
      border-radius: 50%;
      position: fixed;
      top: 0; left: 0;
      pointer-events: none;
      z-index: 9998;
      transform: translate(-50%, -50%);
      transition: all 0.25s ease;
      opacity: 0.6;
    }
    a:hover ~ .cursor, button:hover ~ .cursor { transform: translate(-50%, -50%) scale(2.5); }

    /* NAV */
    nav {
      position: fixed;
      top: 0; left: 0; right: 0;
      z-index: 100;
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1.4rem 5vw;
      background: linear-gradient(to bottom, rgba(6,13,24,0.92), transparent);
      backdrop-filter: blur(2px);
      transition: background 0.4s;
    }
    nav.scrolled { background: rgba(6,13,24,0.97); }

    .nav-logo {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.5rem;
      font-weight: 300;
      letter-spacing: 0.18em;
      color: var(--gold);
      text-decoration: none;
    }
    .nav-logo span { font-style: italic; color: var(--white); }

    .nav-links {
      display: flex;
      gap: 2.5rem;
      list-style: none;
    }
    .nav-links a {
      color: var(--gray);
      text-decoration: none;
      font-size: 0.75rem;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      font-weight: 500;
      transition: color 0.3s;
      position: relative;
    }
    .nav-links a::after {
      content: '';
      position: absolute;
      bottom: -4px; left: 0;
      width: 0; height: 1px;
      background: var(--gold);
      transition: width 0.3s ease;
    }
    .nav-links a:hover { color: var(--gold); }
    .nav-links a:hover::after { width: 100%; }

    /* HERO */
    #inicio {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: flex-start;
      padding: 0 8vw;
      position: relative;
      overflow: hidden;
    }

    .hero-bg {
      position: absolute;
      inset: 0;
      background:
        radial-gradient(ellipse 70% 60% at 75% 50%, rgba(17,34,64,0.8) 0%, transparent 70%),
        radial-gradient(ellipse 40% 80% at 10% 50%, rgba(201,168,76,0.06) 0%, transparent 60%),
        linear-gradient(135deg, var(--black) 0%, var(--navy) 50%, var(--navy-mid) 100%);
    }

    .hero-texture {
      position: absolute;
      inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg width='60' height='60' viewBox='0 0 60 60' xmlns='http://www.w3.org/2000/svg'%3E%3Cg fill='none' fill-rule='evenodd'%3E%3Cg fill='%23c9a84c' fill-opacity='0.03'%3E%3Cpath d='M36 34v-4h-2v4h-4v2h4v4h2v-4h4v-2h-4zm0-30V0h-2v4h-4v2h4v4h2V6h4V4h-4zM6 34v-4H4v4H0v2h4v4h2v-4h4v-2H6zM6 4V0H4v4H0v2h4v4h2V6h4V4H6z'/%3E%3C/g%3E%3C/g%3E%3C/svg%3E");
      opacity: 0.4;
    }

    .hero-line {
      position: absolute;
      right: 12vw; top: 15vh;
      width: 1px;
      height: 50vh;
      background: linear-gradient(to bottom, transparent, var(--gold), transparent);
      opacity: 0.3;
      animation: fadeInLine 2s ease 0.8s both;
    }

    @keyframes fadeInLine { from { opacity: 0; transform: scaleY(0); } to { opacity: 0.3; transform: scaleY(1); } }

    .hero-eyebrow {
      font-size: 0.7rem;
      letter-spacing: 0.4em;
      text-transform: uppercase;
      color: var(--gold);
      font-weight: 400;
      margin-bottom: 1.5rem;
      opacity: 0;
      animation: fadeUp 0.9s ease 0.3s forwards;
    }

    .hero-title {
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(3.5rem, 8vw, 7.5rem);
      font-weight: 300;
      line-height: 0.95;
      letter-spacing: -0.01em;
      color: var(--white);
      opacity: 0;
      animation: fadeUp 1s ease 0.5s forwards;
    }
    .hero-title em {
      font-style: italic;
      color: var(--gold-light);
    }

    .hero-sub {
      margin-top: 2rem;
      max-width: 440px;
      font-size: 0.9rem;
      line-height: 1.8;
      color: var(--gray);
      font-weight: 300;
      opacity: 0;
      animation: fadeUp 1s ease 0.7s forwards;
    }

    .hero-cta {
      margin-top: 3rem;
      display: flex;
      gap: 1.5rem;
      align-items: center;
      opacity: 0;
      animation: fadeUp 1s ease 0.9s forwards;
    }

    .btn-primary {
      background: var(--gold);
      color: var(--black);
      padding: 0.85rem 2.2rem;
      text-decoration: none;
      font-size: 0.72rem;
      letter-spacing: 0.22em;
      text-transform: uppercase;
      font-weight: 600;
      transition: all 0.3s;
      position: relative;
      overflow: hidden;
    }
    .btn-primary::before {
      content: '';
      position: absolute;
      inset: 0;
      background: var(--gold-light);
      transform: translateX(-100%);
      transition: transform 0.35s ease;
    }
    .btn-primary:hover::before { transform: translateX(0); }
    .btn-primary span { position: relative; z-index: 1; }

    .btn-ghost {
      color: var(--white);
      text-decoration: none;
      font-size: 0.72rem;
      letter-spacing: 0.2em;
      text-transform: uppercase;
      font-weight: 400;
      border-bottom: 1px solid rgba(245,242,237,0.3);
      padding-bottom: 2px;
      transition: color 0.3s, border-color 0.3s;
    }
    .btn-ghost:hover { color: var(--gold); border-color: var(--gold); }

    @keyframes fadeUp {
      from { opacity: 0; transform: translateY(28px); }
      to { opacity: 1; transform: translateY(0); }
    }

    /* DIVIDER */
    .section-divider {
      display: flex;
      align-items: center;
      gap: 1.2rem;
      margin-bottom: 1.2rem;
    }
    .section-divider::before {
      content: '';
      width: 40px; height: 1px;
      background: var(--gold);
    }
    .section-divider span {
      font-size: 0.65rem;
      letter-spacing: 0.35em;
      text-transform: uppercase;
      color: var(--gold);
      font-weight: 500;
    }

    /* SECTION BASE */
    section {
      padding: 8rem 8vw;
    }

    .section-title {
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(2.2rem, 5vw, 4rem);
      font-weight: 300;
      line-height: 1.1;
      color: var(--white);
      margin-bottom: 1rem;
    }
    .section-title em { font-style: italic; color: var(--gold-light); }

    /* PRODUCTOS */
    #productos {
      background: var(--black);
      position: relative;
      overflow: hidden;
    }
    #productos::before {
      content: '';
      position: absolute;
      top: -1px; left: 0; right: 0;
      height: 120px;
      background: linear-gradient(to bottom, var(--navy), transparent);
      pointer-events: none;
    }

    .productos-intro {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 6vw;
      align-items: end;
      margin-bottom: 5rem;
    }
    .productos-desc {
      font-size: 0.9rem;
      line-height: 1.9;
      color: var(--gray);
      font-weight: 300;
    }

    .products-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 1.5px;
    }

    .product-card {
      position: relative;
      background: var(--navy-mid);
      padding: 3rem 2rem;
      overflow: hidden;
      cursor: pointer;
      transition: background 0.4s;
      border: 1px solid rgba(201,168,76,0.08);
    }
    .product-card::after {
      content: '';
      position: absolute;
      bottom: 0; left: 0;
      width: 0; height: 2px;
      background: var(--gold);
      transition: width 0.4s ease;
    }
    .product-card:hover { background: var(--navy-light); }
    .product-card:hover::after { width: 100%; }

    .product-icon {
      font-size: 2.4rem;
      margin-bottom: 1.5rem;
      display: block;
      transition: transform 0.4s ease;
    }
    .product-card:hover .product-icon { transform: scale(1.1) rotate(-5deg); }

    .product-name {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.4rem;
      font-weight: 400;
      color: var(--white);
      margin-bottom: 0.6rem;
      letter-spacing: 0.02em;
    }
    .product-desc-card {
      font-size: 0.8rem;
      color: var(--gray);
      line-height: 1.7;
      font-weight: 300;
    }
    .product-num {
      position: absolute;
      top: 1.2rem; right: 1.5rem;
      font-family: 'Cormorant Garamond', serif;
      font-size: 3.5rem;
      font-weight: 300;
      color: rgba(201,168,76,0.06);
      line-height: 1;
      transition: color 0.4s;
    }
    .product-card:hover .product-num { color: rgba(201,168,76,0.12); }

    /* NOSOTROS */
    #nosotros {
      background: var(--navy);
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 8vw;
      align-items: center;
    }

    .nosotros-visual {
      position: relative;
    }
    .nosotros-box {
      width: 100%;
      aspect-ratio: 3/4;
      background: linear-gradient(135deg, var(--navy-mid), var(--navy-light));
      border: 1px solid rgba(201,168,76,0.15);
      display: flex;
      align-items: center;
      justify-content: center;
      position: relative;
      overflow: hidden;
    }
    .nosotros-box::before {
      content: '';
      position: absolute;
      inset: 12px;
      border: 1px solid rgba(201,168,76,0.1);
    }
    .nosotros-monogram {
      font-family: 'Cormorant Garamond', serif;
      font-size: 8rem;
      font-weight: 300;
      font-style: italic;
      color: rgba(201,168,76,0.12);
      letter-spacing: -0.05em;
      user-select: none;
    }
    .nosotros-badge {
      position: absolute;
      bottom: -1.5rem; right: -1.5rem;
      width: 110px; height: 110px;
      background: var(--gold);
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
      text-align: center;
    }
    .nosotros-badge strong {
      font-family: 'Cormorant Garamond', serif;
      font-size: 2rem;
      font-weight: 600;
      color: var(--black);
      line-height: 1;
    }
    .nosotros-badge span {
      font-size: 0.55rem;
      text-transform: uppercase;
      letter-spacing: 0.12em;
      color: var(--black);
      font-weight: 600;
    }

    .nosotros-text p {
      font-size: 0.9rem;
      line-height: 1.9;
      color: var(--gray);
      font-weight: 300;
      margin-bottom: 1.5rem;
    }

    .valores {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1.5rem;
      margin-top: 2.5rem;
    }
    .valor {
      border-left: 2px solid var(--gold);
      padding-left: 1rem;
    }
    .valor h4 {
      font-size: 0.75rem;
      letter-spacing: 0.15em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 0.3rem;
      font-weight: 500;
    }
    .valor p {
      font-size: 0.8rem;
      color: var(--gray);
      line-height: 1.5;
      margin: 0;
    }

    /* CONTACTO */
    #contacto {
      background: var(--black);
      text-align: center;
      position: relative;
      overflow: hidden;
    }
    #contacto::before {
      content: 'HC';
      position: absolute;
      top: 50%; left: 50%;
      transform: translate(-50%, -50%);
      font-family: 'Cormorant Garamond', serif;
      font-size: 28vw;
      font-weight: 300;
      font-style: italic;
      color: rgba(201,168,76,0.025);
      pointer-events: none;
      white-space: nowrap;
      user-select: none;
    }

    .contacto-inner {
      position: relative;
      z-index: 1;
      max-width: 680px;
      margin: 0 auto;
    }

    .contacto-grid {
      display: grid;
      grid-template-columns: repeat(3, 1fr);
      gap: 2px;
      margin: 4rem 0;
    }
    .contacto-item {
      padding: 2.5rem 1.5rem;
      background: var(--navy-mid);
      border: 1px solid rgba(201,168,76,0.08);
      transition: background 0.3s, border-color 0.3s;
    }
    .contacto-item:hover {
      background: var(--navy-light);
      border-color: rgba(201,168,76,0.2);
    }
    .contacto-item .icon { font-size: 1.6rem; margin-bottom: 0.8rem; display: block; }
    .contacto-item h4 {
      font-size: 0.65rem;
      letter-spacing: 0.25em;
      text-transform: uppercase;
      color: var(--gold);
      margin-bottom: 0.5rem;
      font-weight: 500;
    }
    .contacto-item p {
      font-size: 0.82rem;
      color: var(--gray);
      line-height: 1.5;
    }

    .contacto-cta {
      font-family: 'Cormorant Garamond', serif;
      font-size: clamp(1.6rem, 3.5vw, 2.6rem);
      font-weight: 300;
      color: var(--white);
      line-height: 1.3;
      margin-bottom: 2.5rem;
    }
    .contacto-cta em { font-style: italic; color: var(--gold-light); }

    /* FOOTER */
    footer {
      background: var(--black);
      border-top: 1px solid rgba(201,168,76,0.12);
      padding: 2.5rem 8vw;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .footer-logo {
      font-family: 'Cormorant Garamond', serif;
      font-size: 1.1rem;
      font-weight: 300;
      letter-spacing: 0.15em;
      color: var(--gold);
    }
    .footer-copy {
      font-size: 0.72rem;
      color: rgba(154,172,189,0.5);
      letter-spacing: 0.1em;
    }

    /* SCROLL REVEAL */
    .reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.8s ease, transform 0.8s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }
    .reveal-delay-1 { transition-delay: 0.15s; }
    .reveal-delay-2 { transition-delay: 0.3s; }
    .reveal-delay-3 { transition-delay: 0.45s; }
    .reveal-delay-4 { transition-delay: 0.6s; }
    .reveal-delay-5 { transition-delay: 0.75s; }
    .reveal-delay-6 { transition-delay: 0.9s; }

    /* MOBILE */
    @media (max-width: 768px) {
      nav { padding: 1.2rem 6vw; }
      .nav-links { display: none; }
      .hero-title { font-size: clamp(2.8rem, 12vw, 4.5rem); }
      .productos-intro { grid-template-columns: 1fr; }
      .products-grid { grid-template-columns: 1fr; }
      #nosotros { grid-template-columns: 1fr; padding: 5rem 6vw; }
      .nosotros-visual { display: none; }
      .contacto-grid { grid-template-columns: 1fr; }
      footer { flex-direction: column; gap: 1rem; text-align: center; }
    }
  </style>
</head>
<body>

  <!-- Custom cursor -->
  <div class="cursor" id="cursor"></div>
  <div class="cursor-ring" id="cursorRing"></div>

  <!-- NAV -->
  <nav id="navbar">
    <a href="#inicio" class="nav-logo">Herencia <span>de Cuero</span></a>
    <ul class="nav-links">
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#productos">Productos</a></li>
      <li><a href="#nosotros">Nosotros</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>

  <!-- HERO -->
  <section id="inicio">
    <div class="hero-bg"></div>
    <div class="hero-texture"></div>
    <div class="hero-line"></div>

    <p class="hero-eyebrow">Artesanía · Estilo · Calidad</p>
    <h1 class="hero-title">
      Herencia<br><em>de Cuero</em>
    </h1>
    <p class="hero-sub">
      Accesorios de moda con carácter. Cada pieza refleja dedicación al detalle y un estilo que perdura en el tiempo.
    </p>
    <div class="hero-cta">
      <a href="#productos" class="btn-primary"><span>Ver Colección</span></a>
      <a href="#nosotros" class="btn-ghost">Nuestra Historia</a>
    </div>
  </section>

  <!-- PRODUCTOS -->
  <section id="productos">
    <div class="productos-intro reveal">
      <div>
        <div class="section-divider"><span>Colección</span></div>
        <h2 class="section-title">Nuestros <em>Productos</em></h2>
      </div>
      <p class="productos-desc">
        Selección cuidadosa de accesorios para quienes valoran la calidad y el estilo. Desde correas hasta bolsos, cada artículo está pensado para durar y lucir impecable.
      </p>
    </div>

    <div class="products-grid">
      <div class="product-card reveal reveal-delay-1">
        <span class="product-num">01</span>
        <span class="product-icon">🎗️</span>
        <h3 class="product-name">Correas & Cinturones</h3>
        <p class="product-desc-card">Variedad de estilos, tallas y colores. Acabados precisos para complementar cualquier outfit.</p>
      </div>
      <div class="product-card reveal reveal-delay-2">
        <span class="product-num">02</span>
        <span class="product-icon">👜</span>
        <h3 class="product-name">Bolsos para Dama</h3>
        <p class="product-desc-card">Diseños modernos y elegantes. Funcionales, espaciosos y con materiales de primera.</p>
      </div>
      <div class="product-card reveal reveal-delay-3">
        <span class="product-num">03</span>
        <span class="product-icon">💼</span>
        <h3 class="product-name">Billeteras</h3>
        <p class="product-desc-card">Para dama y caballero. Billeteras delgadas y portadocumentos con diseño refinado.</p>
      </div>
      <div class="product-card reveal reveal-delay-4">
        <span class="product-num">04</span>
        <span class="product-icon">🧢</span>
        <h3 class="product-name">Gorras</h3>
        <p class="product-desc-card">Estilos casuales y urbanos. El accesorio perfecto para completar tu look del día.</p>
      </div>
      <div class="product-card reveal reveal-delay-5">
        <span class="product-num">05</span>
        <span class="product-icon">🧦</span>
        <h3 class="product-name">Medias</h3>
        <p class="product-desc-card">Comodidad y estilo desde la base. Distintos diseños para cada ocasión.</p>
      </div>
      <div class="product-card reveal reveal-delay-6">
        <span class="product-num">06</span>
        <span class="product-icon">✨</span>
        <h3 class="product-name">Accesorios</h3>
        <p class="product-desc-card">Los pequeños detalles marcan la diferencia. Encuentra lo que tu estilo necesita.</p>
      </div>
    </div>
  </section>

  <!-- NOSOTROS -->
  <section id="nosotros">
    <div class="nosotros-visual reveal">
      <div class="nosotros-box">
        <span class="nosotros-monogram">HC</span>
      </div>
      <div class="nosotros-badge">
        <strong>100%</strong>
        <span>Calidad<br>Garantizada</span>
      </div>
    </div>

    <div class="nosotros-text">
      <div class="section-divider reveal"><span>Quiénes Somos</span></div>
      <h2 class="section-title reveal">Una tienda con <em>alma propia</em></h2>
      <p class="reveal">
        En Herencia de Cuero creemos que los accesorios son más que complementos: son una expresión de identidad. Nacimos con la misión de ofrecer productos de calidad con precios accesibles y atención personalizada.
      </p>
      <p class="reveal">
        Cada artículo en nuestra colección es seleccionado con cuidado, pensando en personas que aprecian el buen gusto y la durabilidad. Porque la moda pasa, pero el estilo permanece.
      </p>
      <div class="valores reveal">
        <div class="valor">
          <h4>Calidad</h4>
          <p>Materiales seleccionados y acabados duraderos en cada producto.</p>
        </div>
        <div class="valor">
          <h4>Estilo</h4>
          <p>Diseños actuales que se adaptan a todos los looks.</p>
        </div>
        <div class="valor">
          <h4>Servicio</h4>
          <p>Atención cercana y personalizada para cada cliente.</p>
        </div>
        <div class="valor">
          <h4>Confianza</h4>
          <p>Compromiso con la satisfacción en cada compra.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CONTACTO -->
  <section id="contacto">
    <div class="contacto-inner">
      <div class="section-divider reveal" style="justify-content:center;"><span>Contáctanos</span></div>
      <p class="contacto-cta reveal">¿Listo para encontrar<br>tu próximo <em>accesorio favorito?</em></p>

      <div class="contacto-grid">
        <div class="contacto-item reveal reveal-delay-1">
          <span class="icon">📱</span>
          <h4>WhatsApp</h4>
          <p>Escríbenos directamente para consultas y pedidos</p>
        </div>
        <div class="contacto-item reveal reveal-delay-2">
          <span class="icon">📍</span>
          <h4>Ubicación</h4>
          <p>Visítanos en nuestra tienda física</p>
        </div>
        <div class="contacto-item reveal reveal-delay-3">
          <span class="icon">📸</span>
          <h4>Instagram</h4>
          <p>Síguenos y descubre las novedades</p>
        </div>
      </div>

      <a href="#" class="btn-primary reveal"><span>Contactar por WhatsApp</span></a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <span class="footer-logo">Herencia de Cuero</span>
    <span class="footer-copy">© 2024 · Todos los derechos reservados</span>
  </footer>

  <script>
    // Cursor
    const cursor = document.getElementById('cursor');
    const ring = document.getElementById('cursorRing');
    let mx = 0, my = 0, rx = 0, ry = 0;
    document.addEventListener('mousemove', e => { mx = e.clientX; my = e.clientY; cursor.style.left = mx + 'px'; cursor.style.top = my + 'px'; });
    (function animRing() {
      rx += (mx - rx) * 0.12;
      ry += (my - ry) * 0.12;
      ring.style.left = rx + 'px';
      ring.style.top = ry + 'px';
      requestAnimationFrame(animRing);
    })();

    // Navbar scroll
    const navbar = document.getElementById('navbar');
    window.addEventListener('scroll', () => {
      navbar.classList.toggle('scrolled', window.scrollY > 60);
    });

    // Scroll reveal
    const revealEls = document.querySelectorAll('.reveal');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach(e => { if (e.isIntersecting) { e.target.classList.add('visible'); } });
    }, { threshold: 0.12 });
    revealEls.forEach(el => observer.observe(el));
  </script>
</body>
</html>
