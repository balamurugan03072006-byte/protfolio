<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Balamurugan S — ECE Engineer</title>
  <link href="https://fonts.googleapis.com/css2?family=Space+Mono:wght@400;700&family=Syne:wght@400;600;800&family=Barlow+Condensed:ital,wght@1,800&display=swap" rel="stylesheet"/>
  <style>
    :root {
      --bg: #0a0a0f;
      --surface: #111118;
      --card: #16161f;
      --border: #1f1f2e;
      --accent: #00e5c0;
      --accent2: #ff5e5e;
      --accent3: #7b6fff;
      --text: #e8e8f0;
      --muted: #6b6b88;
      --mono: 'Space Mono', monospace;
      --sans: 'Syne', sans-serif;
    }

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      background: var(--bg);
      color: var(--text);
      font-family: var(--sans);
      overflow-x: hidden;
      cursor: none;
    }

    /* Custom cursor */
    .cursor {
      width: 12px; height: 12px;
      background: var(--accent);
      border-radius: 50%;
      position: fixed; top: 0; left: 0;
      pointer-events: none;
      z-index: 9999;
      transition: transform 0.15s ease, background 0.2s;
      mix-blend-mode: difference;
    }
    .cursor-ring {
      width: 36px; height: 36px;
      border: 1.5px solid var(--accent);
      border-radius: 50%;
      position: fixed; top: 0; left: 0;
      pointer-events: none;
      z-index: 9998;
      transition: transform 0.35s cubic-bezier(.23,1,.32,1), border-color 0.2s;
      opacity: 0.6;
    }

    /* Noise overlay */
    body::before {
      content: '';
      position: fixed; inset: 0;
      background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.04'/%3E%3C/svg%3E");
      pointer-events: none; z-index: 0; opacity: 0.35;
    }

    /* NAV */
    nav {
      position: fixed; top: 0; width: 100%;
      padding: 20px 48px;
      display: flex; justify-content: space-between; align-items: center;
      z-index: 100;
      background: linear-gradient(to bottom, rgba(10,10,15,0.95), transparent);
      backdrop-filter: blur(4px);
    }
    .nav-logo {
      font-family: var(--mono);
      font-size: 13px;
      color: var(--accent);
      letter-spacing: 2px;
      text-transform: uppercase;
    }
    .nav-links { display: flex; gap: 32px; }
    .nav-links a {
      font-family: var(--mono);
      font-size: 11px;
      color: var(--muted);
      text-decoration: none;
      text-transform: uppercase;
      letter-spacing: 2px;
      transition: color 0.2s;
      position: relative;
    }
    .nav-links a::after {
      content: '';
      position: absolute; bottom: -4px; left: 0;
      width: 0; height: 1px;
      background: var(--accent);
      transition: width 0.3s;
    }
    .nav-links a:hover { color: var(--accent); }
    .nav-links a:hover::after { width: 100%; }

    /* HERO */
    #hero {
      min-height: 100vh;
      display: flex; align-items: center;
      padding: 140px 48px 80px;
      position: relative;
      overflow: hidden;
    }

    .hero-grid-bg {
      position: absolute; inset: 0;
      background-image:
        linear-gradient(rgba(0,229,192,0.04) 1px, transparent 1px),
        linear-gradient(90deg, rgba(0,229,192,0.04) 1px, transparent 1px);
      background-size: 60px 60px;
      mask-image: radial-gradient(ellipse 80% 80% at 50% 50%, black 30%, transparent 80%);
    }

    .hero-orb {
      position: absolute;
      border-radius: 50%;
      filter: blur(80px);
      pointer-events: none;
    }
    .orb1 { width: 500px; height: 500px; background: rgba(0,229,192,0.07); top: -100px; right: -100px; animation: drift1 8s ease-in-out infinite; }
    .orb2 { width: 350px; height: 350px; background: rgba(123,111,255,0.07); bottom: 0; left: 10%; animation: drift2 10s ease-in-out infinite; }

    @keyframes drift1 { 0%,100% { transform: translate(0,0); } 50% { transform: translate(-30px, 30px); } }
    @keyframes drift2 { 0%,100% { transform: translate(0,0); } 50% { transform: translate(20px, -20px); } }

    .hero-content { position: relative; z-index: 1; max-width: 800px; }

    .hero-tag {
      display: inline-flex; align-items: center; gap: 8px;
      font-family: var(--mono);
      font-size: 11px;
      color: var(--accent);
      letter-spacing: 3px;
      text-transform: uppercase;
      margin-bottom: 24px;
      padding: 6px 14px;
      border: 1px solid rgba(0,229,192,0.25);
      border-radius: 2px;
      animation: fadeSlideUp 0.6s ease both;
    }
    .hero-tag .dot {
      width: 6px; height: 6px;
      background: var(--accent);
      border-radius: 50%;
      animation: pulse 2s ease infinite;
    }
    @keyframes pulse { 0%,100% { opacity: 1; transform: scale(1); } 50% { opacity: 0.4; transform: scale(0.7); } }

    .hero-name {
      font-family: 'Barlow Condensed', sans-serif;
      font-style: italic;
      font-size: clamp(64px, 10vw, 130px);
      font-weight: 800;
      line-height: 0.9;
      letter-spacing: -1px;
      margin-bottom: 24px;
      animation: fadeSlideUp 0.6s 0.1s ease both;
    }
    .hero-name .line2 { color: transparent; -webkit-text-stroke: 1px rgba(232,232,240,0.3); }

    .hero-desc {
      font-family: var(--mono);
      font-size: 14px;
      color: var(--muted);
      line-height: 1.8;
      max-width: 480px;
      margin-bottom: 40px;
      animation: fadeSlideUp 0.6s 0.2s ease both;
    }
    .hero-desc span { color: var(--accent); }

    .hero-cta {
      display: flex; gap: 16px; flex-wrap: wrap;
      animation: fadeSlideUp 0.6s 0.3s ease both;
    }
    .btn {
      font-family: var(--mono);
      font-size: 11px;
      letter-spacing: 2px;
      text-transform: uppercase;
      padding: 14px 28px;
      border-radius: 2px;
      text-decoration: none;
      transition: all 0.25s;
      cursor: none;
    }
    .btn-primary {
      background: var(--accent);
      color: var(--bg);
      font-weight: 700;
    }
    .btn-primary:hover { background: #00ffd4; transform: translateY(-2px); box-shadow: 0 8px 24px rgba(0,229,192,0.25); }
    .btn-outline {
      border: 1px solid var(--border);
      color: var(--muted);
    }
    .btn-outline:hover { border-color: var(--accent); color: var(--accent); transform: translateY(-2px); }

    .hero-scroll {
      position: absolute; bottom: 40px; left: 48px;
      display: flex; align-items: center; gap: 12px;
      font-family: var(--mono); font-size: 10px;
      color: var(--muted); letter-spacing: 2px;
      text-transform: uppercase;
      animation: fadeSlideUp 0.6s 0.5s ease both;
    }
    .scroll-line { width: 40px; height: 1px; background: var(--muted); }

    @keyframes fadeSlideUp {
      from { opacity: 0; transform: translateY(20px); }
      to   { opacity: 1; transform: translateY(0); }
    }

    /* SECTION COMMON */
    section { padding: 100px 48px; position: relative; }
    .section-label {
      font-family: var(--mono);
      font-size: 10px;
      color: var(--accent);
      letter-spacing: 4px;
      text-transform: uppercase;
      margin-bottom: 12px;
    }
    .section-title {
      font-size: clamp(32px, 5vw, 56px);
      font-weight: 800;
      letter-spacing: -1.5px;
      margin-bottom: 60px;
      line-height: 1;
    }
    .section-title .accent { color: var(--accent); }

    .divider {
      width: 100%; height: 1px;
      background: linear-gradient(to right, transparent, var(--border), transparent);
    }

    /* ABOUT */
    #about { background: var(--surface); }
    .about-grid {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 80px;
      align-items: start;
    }
    .about-text p {
      font-family: var(--mono);
      font-size: 14px;
      color: var(--muted);
      line-height: 1.9;
      margin-bottom: 20px;
    }
    .about-text p strong { color: var(--text); }
    .about-stats {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 2px;
    }
    .stat-card {
      background: var(--card);
      padding: 28px 24px;
      border: 1px solid var(--border);
      transition: border-color 0.3s, transform 0.3s;
    }
    .stat-card:hover { border-color: var(--accent); transform: translateY(-4px); }
    .stat-number {
      font-size: 42px;
      font-weight: 800;
      color: var(--accent);
      line-height: 1;
      margin-bottom: 6px;
    }
    .stat-label {
      font-family: var(--mono);
      font-size: 11px;
      color: var(--muted);
      letter-spacing: 1px;
    }

    /* SKILLS */
    #skills {}
    .skills-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 2px;
    }
    .skill-group {
      background: var(--card);
      padding: 32px;
      border: 1px solid var(--border);
      transition: border-color 0.3s, transform 0.3s;
      position: relative;
      overflow: hidden;
    }
    .skill-group::before {
      content: '';
      position: absolute; top: 0; left: 0;
      width: 3px; height: 0;
      background: var(--accent);
      transition: height 0.4s;
    }
    .skill-group:hover::before { height: 100%; }
    .skill-group:hover { border-color: rgba(0,229,192,0.3); }
    .skill-group-icon {
      font-size: 28px; margin-bottom: 16px;
      display: block;
    }
    .skill-group-title {
      font-family: var(--mono);
      font-size: 11px;
      color: var(--accent);
      letter-spacing: 2px;
      text-transform: uppercase;
      margin-bottom: 16px;
    }
    .skill-tags { display: flex; flex-wrap: wrap; gap: 8px; }
    .skill-tag {
      font-family: var(--mono);
      font-size: 11px;
      color: var(--muted);
      background: rgba(255,255,255,0.04);
      padding: 5px 10px;
      border-radius: 2px;
      border: 1px solid var(--border);
      transition: color 0.2s, border-color 0.2s;
    }
    .skill-group:hover .skill-tag { color: var(--text); border-color: rgba(0,229,192,0.2); }

    /* PROJECTS */
    #projects { background: var(--surface); }
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(340px, 1fr));
      gap: 2px;
    }
    .project-card {
      background: var(--card);
      padding: 36px 32px;
      border: 1px solid var(--border);
      transition: border-color 0.3s, transform 0.3s;
      position: relative;
      overflow: hidden;
    }
    .project-card::after {
      content: '';
      position: absolute; inset: 0;
      background: linear-gradient(135deg, rgba(0,229,192,0.04), transparent);
      opacity: 0;
      transition: opacity 0.4s;
    }
    .project-card:hover { border-color: rgba(0,229,192,0.4); transform: translateY(-6px); }
    .project-card:hover::after { opacity: 1; }
    .project-index {
      font-family: var(--mono);
      font-size: 11px;
      color: rgba(0,229,192,0.4);
      letter-spacing: 2px;
      margin-bottom: 20px;
    }
    .project-title {
      font-size: 16px;
      font-weight: 600;
      line-height: 1.3;
      margin-bottom: 16px;
      color: var(--text);
    }
    .project-desc {
      font-family: var(--mono);
      font-size: 12px;
      color: var(--muted);
      line-height: 1.8;
      margin-bottom: 24px;
    }
    .project-points {
      list-style: none;
      display: flex; flex-direction: column; gap: 8px;
    }
    .project-points li {
      font-family: var(--mono);
      font-size: 11px;
      color: var(--muted);
      padding-left: 16px;
      position: relative;
    }
    .project-points li::before {
      content: '→';
      position: absolute; left: 0;
      color: var(--accent);
    }

    /* EDUCATION */
    #education {}
    .education-timeline { position: relative; }
    .education-timeline::before {
      content: '';
      position: absolute; left: 0; top: 0; bottom: 0;
      width: 1px;
      background: linear-gradient(to bottom, var(--accent), var(--border), transparent);
    }
    .edu-item {
      padding: 0 0 48px 48px;
      position: relative;
    }
    .edu-item::before {
      content: '';
      position: absolute; left: -4px; top: 6px;
      width: 9px; height: 9px;
      border: 2px solid var(--accent);
      border-radius: 50%;
      background: var(--bg);
    }
    .edu-period {
      font-family: var(--mono);
      font-size: 11px;
      color: var(--accent);
      letter-spacing: 2px;
      margin-bottom: 8px;
    }
    .edu-degree {
      font-size: 22px;
      font-weight: 700;
      margin-bottom: 4px;
    }
    .edu-school {
      font-family: var(--mono);
      font-size: 13px;
      color: var(--muted);
      margin-bottom: 8px;
    }
    .edu-score {
      display: inline-block;
      font-family: var(--mono);
      font-size: 11px;
      color: var(--accent);
      padding: 4px 12px;
      border: 1px solid rgba(0,229,192,0.3);
      border-radius: 2px;
    }

    /* CONTACT */
    #contact {
      background: var(--surface);
      text-align: center;
    }
    .contact-intro {
      font-family: var(--mono);
      font-size: 14px;
      color: var(--muted);
      max-width: 500px;
      margin: 0 auto 48px;
      line-height: 1.8;
    }
    .contact-links {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 16px;
      margin-bottom: 60px;
    }
    .contact-link {
      display: flex; align-items: center; gap: 10px;
      font-family: var(--mono);
      font-size: 12px;
      color: var(--muted);
      text-decoration: none;
      padding: 14px 24px;
      border: 1px solid var(--border);
      border-radius: 2px;
      transition: all 0.25s;
      cursor: none;
    }
    .contact-link:hover {
      color: var(--accent);
      border-color: var(--accent);
      transform: translateY(-3px);
      box-shadow: 0 8px 24px rgba(0,229,192,0.1);
    }
    .contact-link svg { width: 16px; height: 16px; fill: currentColor; }

    /* FOOTER */
    footer {
      padding: 24px 48px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      border-top: 1px solid var(--border);
    }
    footer p {
      font-family: var(--mono);
      font-size: 11px;
      color: var(--muted);
      letter-spacing: 1px;
    }
    .footer-accent { color: var(--accent); }

    /* SCROLL REVEAL */
    .reveal {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.7s ease, transform 0.7s ease;
    }
    .reveal.visible {
      opacity: 1;
      transform: translateY(0);
    }

    /* RESPONSIVE */
    @media (max-width: 768px) {
      nav { padding: 16px 24px; }
      .nav-links { display: none; }
      section { padding: 80px 24px; }
      #hero { padding: 120px 24px 80px; }
      .hero-scroll { left: 24px; }
      .about-grid { grid-template-columns: 1fr; gap: 48px; }
      footer { flex-direction: column; gap: 8px; text-align: center; }
    }
  </style>
</head>
<body>

  <div class="cursor" id="cursor"></div>
  <div class="cursor-ring" id="cursorRing"></div>

  <!-- NAV -->
  <nav>
    <div class="nav-logo">B.S</div>
    <div class="nav-links">
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
      <a href="#education">Education</a>
      <a href="#contact">Contact</a>
    </div>
  </nav>

  <!-- HERO -->
  <section id="hero">
    <div class="hero-grid-bg"></div>
    <div class="hero-orb orb1"></div>
    <div class="hero-orb orb2"></div>

    <div class="hero-content">
      <div class="hero-tag">
        <span class="dot"></span>
        ECE Student · Embedded Systems · IoT
      </div>
      <h1 class="hero-name">
        Bala<br>
        <span class="line2">murugan S</span>
      </h1>
      <p class="hero-desc">
        Electronics &amp; Communication Engineer from <span>Anna University</span>.<br>
        Building circuits, code, and connected systems that matter.
      </p>
      <div class="hero-cta">
        <a href="#projects" class="btn btn-primary">View Projects</a>
        <a href="#contact" class="btn btn-outline">Get in Touch</a>
      </div>
    </div>

    <div class="hero-scroll">
      <div class="scroll-line"></div>
      Scroll down
    </div>
  </section>

  <div class="divider"></div>

  <!-- ABOUT -->
  <section id="about">
    <div class="section-label">// 01 About</div>
    <h2 class="section-title reveal">Who I <span class="accent">Am</span></h2>
    <div class="about-grid">
      <div class="about-text reveal">
        <p>
          I'm a <strong>motivated ECE student</strong> at Anna University, Coimbatore, with a deep interest in core electronics, PCB design, and IoT technologies.
        </p>
        <p>
          Skilled in <strong>C, C++, and Python</strong> through academic coursework, I build solutions that bridge hardware and software — from smart home systems to machine learning applications.
        </p>
        <p>
          I'm a <strong>quick learner</strong> with strong analytical skills and a passion for applying technical knowledge to real-time engineering problems. I love making things work — cleanly, efficiently, and intelligently.
        </p>
      </div>
      <div class="about-stats reveal">
        <div class="stat-card">
          <div class="stat-number">5+</div>
          <div class="stat-label">Projects Completed</div>
        </div>
        <div class="stat-card">
          <div class="stat-number">7.23</div>
          <div class="stat-label">CGPA at Anna University</div>
        </div>
        <div class="stat-card">
          <div class="stat-number">4+</div>
          <div class="stat-label">Tools & Platforms</div>
        </div>
        <div class="stat-card">
          <div class="stat-number">2027</div>
          <div class="stat-label">Graduating Year</div>
        </div>
      </div>
    </div>
  </section>

  <div class="divider"></div>

  <!-- SKILLS -->
  <section id="skills">
    <div class="section-label">// 02 Skills</div>
    <h2 class="section-title reveal">Technical <span class="accent">Stack</span></h2>
    <div class="skills-grid">
      <div class="skill-group reveal">
        <span class="skill-group-icon">⌨️</span>
        <div class="skill-group-title">Programming</div>
        <div class="skill-tags">
          <span class="skill-tag">C</span>
          <span class="skill-tag">C++</span>
          <span class="skill-tag">Python</span>
        </div>
      </div>
      <div class="skill-group reveal">
        <span class="skill-group-icon">🔌</span>
        <div class="skill-group-title">Embedded & IoT</div>
        <div class="skill-tags">
          <span class="skill-tag">Arduino IDE</span>
          <span class="skill-tag">ESP32</span>
          <span class="skill-tag">Verilog HDL</span>
        </div>
      </div>
      <div class="skill-group reveal">
        <span class="skill-group-icon">⚡</span>
        <div class="skill-group-title">Electronics</div>
        <div class="skill-tags">
          <span class="skill-tag">Digital Electronics</span>
          <span class="skill-tag">Circuit Design</span>
          <span class="skill-tag">PCB Design</span>
        </div>
      </div>
      <div class="skill-group reveal">
        <span class="skill-group-icon">🛠️</span>
        <div class="skill-group-title">Tools & Software</div>
        <div class="skill-tags">
          <span class="skill-tag">LTSpice</span>
          <span class="skill-tag">ThingSpeak</span>
          <span class="skill-tag">Keil</span>
          <span class="skill-tag">Tinkercad</span>
          <span class="skill-tag">GitHub</span>
          <span class="skill-tag">MS Office</span>
        </div>
      </div>
    </div>
  </section>

  <div class="divider"></div>

  <!-- PROJECTS -->
  <section id="projects">
    <div class="section-label">// 03 Projects</div>
    <h2 class="section-title reveal">What I've <span class="accent">Built</span></h2>
    <div class="projects-grid">

      <div class="project-card reveal">
        <div class="project-index">01 / ML</div>
        <div class="project-title">Predicting Customer Churn Using Machine Learning</div>
        <ul class="project-points">
          <li>Built a scalable, accurate, and interpretable ML model</li>
          <li>Predicts churn and uncovers why customers may leave</li>
          <li>Helps businesses tailor retention strategies</li>
        </ul>
      </div>

      <div class="project-card reveal">
        <div class="project-index">02 / EMI</div>
        <div class="project-title">Visualization of Electromagnetic Interference Between Devices</div>
        <ul class="project-points">
          <li>Studied EMI fundamentals &amp; wave propagation principles</li>
          <li>Identified interference sources experimentally</li>
          <li>Measured using Oscilloscope, Spectrum Analyzer, EMI receiver</li>
        </ul>
      </div>

      <div class="project-card reveal">
        <div class="project-index">03 / Hardware</div>
        <div class="project-title">Smart Low Power 12-Bit Multiplexer Using Ultrasonic Sensor</div>
        <ul class="project-points">
          <li>Designed a 12-bit multiplier circuit</li>
          <li>Integrated an ultrasonic sensor for smart input</li>
          <li>Implemented smart switching logic for low power</li>
        </ul>
      </div>

      <div class="project-card reveal">
        <div class="project-index">04 / IoT</div>
        <div class="project-title">IoT Based Home Automation System</div>
        <ul class="project-points">
          <li>Developed a smart home control system</li>
          <li>Enabled internet connectivity for remote access</li>
          <li>Improved real-time monitoring &amp; enhanced security</li>
        </ul>
      </div>

      <div class="project-card reveal">
        <div class="project-index">05 / IoT</div>
        <div class="project-title">IoT Enabled Smart Gardening System</div>
        <ul class="project-points">
          <li>Developed automated irrigation system</li>
          <li>Monitors soil &amp; environmental conditions in real time</li>
          <li>Enables remote control and improves water efficiency</li>
        </ul>
      </div>

    </div>
  </section>

  <div class="divider"></div>

  <!-- EDUCATION -->
  <section id="education">
    <div class="section-label">// 04 Education</div>
    <h2 class="section-title reveal">Academic <span class="accent">Journey</span></h2>
    <div class="education-timeline">
      <div class="edu-item reveal">
        <div class="edu-period">09/2023 – 05/2027</div>
        <div class="edu-degree">B.E. Electronics &amp; Communication Engineering</div>
        <div class="edu-school">Anna University · Coimbatore, India</div>
        <span class="edu-score">CGPA: 7.23</span>
      </div>
      <div class="edu-item reveal">
        <div class="edu-period">06/2022 – 05/2023</div>
        <div class="edu-degree">HSC (Higher Secondary Certificate)</div>
        <div class="edu-school">Sri Ramakrishna Matric Boys Hr.Sec.School · Perambalur, India</div>
        <span class="edu-score">76.9%</span>
      </div>
      <div class="edu-item reveal">
        <div class="edu-period">Workshop</div>
        <div class="edu-degree">SoC Course Using Verilog HDL</div>
        <div class="edu-school">Maven Silicon · Anna University, Coimbatore</div>
      </div>
    </div>
  </section>

  <div class="divider"></div>

  <!-- CONTACT -->
  <section id="contact">
    <div class="section-label" style="text-align:center">// 05 Contact</div>
    <h2 class="section-title reveal" style="text-align:center">Let's <span class="accent">Connect</span></h2>
    <p class="contact-intro reveal">
      I'm open to collaborations, internships, and project discussions. Feel free to reach out — I'd love to hear from you.
    </p>
    <div class="contact-links reveal">
      <a href="mailto:balamurugan03072006@gmail.com" class="contact-link">
        <svg viewBox="0 0 24 24"><path d="M20 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4-8 5-8-5V6l8 5 8-5v2z"/></svg>
        balamurugan03072006@gmail.com
      </a>
      <a href="https://github.com/balamurugan03072006-byte" target="_blank" class="contact-link">
        <svg viewBox="0 0 24 24"><path d="M12 0C5.37 0 0 5.37 0 12c0 5.3 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61-.546-1.385-1.335-1.755-1.335-1.755-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 21.795 24 17.295 24 12c0-6.63-5.37-12-12-12z"/></svg>
        GitHub
      </a>
      <a href="https://www.linkedin.com/in/bala-murugan-9335813b0/" target="_blank" class="contact-link">
        <svg viewBox="0 0 24 24"><path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/></svg>
        LinkedIn
      </a>
      <a href="tel:+917305244365" class="contact-link">
        <svg viewBox="0 0 24 24"><path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z"/></svg>
        +91 73052 44365
      </a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer>
    <p>© 2024 <span class="footer-accent">Balamurugan S</span> · Perambalur, Tamil Nadu, India</p>
    <p>Built with <span class="footer-accent">♥</span> &amp; raw HTML</p>
  </footer>

  <script>
    // Custom cursor
    const cursor = document.getElementById('cursor');
    const ring = document.getElementById('cursorRing');
    let mx = 0, my = 0, rx = 0, ry = 0;
    document.addEventListener('mousemove', e => { mx = e.clientX; my = e.clientY; });
    function animCursor() {
      cursor.style.transform = `translate(${mx - 6}px, ${my - 6}px)`;
      rx += (mx - rx) * 0.12;
      ry += (my - ry) * 0.12;
      ring.style.transform = `translate(${rx - 18}px, ${ry - 18}px)`;
      requestAnimationFrame(animCursor);
    }
    animCursor();
    document.querySelectorAll('a, button').forEach(el => {
      el.addEventListener('mouseenter', () => { cursor.style.transform += ' scale(2)'; ring.style.opacity = '0.2'; });
      el.addEventListener('mouseleave', () => { ring.style.opacity = '0.6'; });
    });

    // Scroll reveal
    const reveals = document.querySelectorAll('.reveal');
    const observer = new IntersectionObserver((entries) => {
      entries.forEach((entry, i) => {
        if (entry.isIntersecting) {
          setTimeout(() => entry.target.classList.add('visible'), i * 80);
        }
      });
    }, { threshold: 0.12, rootMargin: '0px 0px -40px 0px' });
    reveals.forEach(el => observer.observe(el));
  </script>
</body>
</html>
