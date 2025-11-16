<!--
  FULL ANIMATION README for AmirReza Neghabi
  Paste this into README.md in your profile repo (repo name should match your GitHub username)
  Replace placeholders: your-email@example.com, your-linkedin-url, yourusername
-->

<!-- ===================== HERO: FULL ANIMATED BANNER ===================== -->
<div align="center" style="background: radial-gradient(circle at 10% 10%, #071028 0%, #05020a 35%, #0b0014 100%); padding:28px; border-radius:14px; box-shadow: 0 18px 60px rgba(0,0,0,0.7);">

  <!-- Large animated SVG banner -->
  <svg width="920" height="220" viewBox="0 0 920 220" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <defs>
      <linearGradient id="gradA" x1="0" x2="1">
        <stop offset="0" stop-color="#00f0ff"/>
        <stop offset="0.5" stop-color="#9b59ff"/>
        <stop offset="1" stop-color="#ff2d95"/>
      </linearGradient>

      <filter id="bigGlow">
        <feGaussianBlur stdDeviation="6" result="g1"/>
        <feMerge><feMergeNode in="g1"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>

      <linearGradient id="gridGrad" x1="0" x2="1">
        <stop offset="0" stop-color="#001827"/>
        <stop offset="1" stop-color="#070119"/>
      </linearGradient>
    </defs>

    <!-- background circuit lines (animated opacity) -->
    <rect x="0" y="0" width="920" height="220" fill="url(#gridGrad)"/>
    <g stroke="#00ffd5" stroke-opacity="0.06" stroke-width="1">
      <!-- repeating vertical lines -->
      <g>
        <!-- many lines -->
        <line x1="40" x2="40" y1="0" y2="220"/><line x1="80" x2="80" y1="0" y2="220"/><line x1="120" x2="120" y1="0" y2="220"/>
        <line x1="160" x2="160" y1="0" y2="220"/><line x1="200" x2="200" y1="0" y2="220"/><line x1="240" x2="240" y1="0" y2="220"/>
        <line x1="280" x2="280" y1="0" y2="220"/><line x1="320" x2="320" y1="0" y2="220"/><line x1="360" x2="360" y1="0" y2="220"/>
        <line x1="400" x2="400" y1="0" y2="220"/><line x1="440" x2="440" y1="0" y2="220"/><line x1="480" x2="480" y1="0" y2="220"/>
        <line x1="520" x2="520" y1="0" y2="220"/><line x1="560" x2="560" y1="0" y2="220"/><line x1="600" x2="600" y1="0" y2="220"/>
        <line x1="640" x2="640" y1="0" y2="220"/><line x1="680" x2="680" y1="0" y2="220"/><line x1="720" x2="720" y1="0" y2="220"/>
        <line x1="760" x2="760" y1="0" y2="220"/><line x1="800" x2="800" y1="0" y2="220"/><line x1="840" x2="840" y1="0" y2="220"/>
      </g>
      <g>
        <!-- horizontal lines -->
        <line x1="0" x2="920" y1="30" y2="30"/><line x1="0" x2="920" y1="60" y2="60"/><line x1="0" x2="920" y1="90" y2="90"/>
        <line x1="0" x2="920" y1="120" y2="120"/><line x1="0" x2="920" y1="150" y2="150"/><line x1="0" x2="920" y1="180" y2="180"/>
      </g>
    </g>

    <!-- holographic name with animated stroke -->
    <g transform="translate(36,72)">
      <text x="0" y="0" font-family="Segoe UI, Roboto, Arial" font-size="44" fill="none" stroke="url(#gradA)" stroke-width="1.6" paint-order="stroke">
        AmirReza Neghabi
      </text>
      <text x="0" y="44" font-family="Segoe UI, Roboto, Arial" font-size="14" fill="#aeefff" opacity="0.95">
        Junior Backend Developer • Python • Django • FastAPI • Docker
      </text>

      <!-- glowing underline that pulses -->
      <rect x="0" y="52" width="420" height="4" rx="2" fill="url(#gradA)" filter="url(#bigGlow)" opacity="0.85">
        <animate attributeName="opacity" values="0.5;1;0.5" dur="3.6s" repeatCount="indefinite"/>
        <animate attributeName="width" values="0;420;0" dur="9s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- animated floating project boxes -->
    <g transform="translate(540,36)">
      <!-- card 1 -->
      <g transform="translate(0,0)">
        <rect x="0" y="0" rx="12" ry="12" width="340" height="76" fill="#041226" stroke="#0ef0d1" stroke-opacity="0.08"/>
        <text x="16" y="24" font-size="16" fill="#cfefff" font-family="Segoe UI">Bookstore (Django + Docker)</text>
        <text x="16" y="44" font-size="12" fill="#9bdcff">Auth, Admin, Cart — Dockerized</text>
        <animateTransform attributeName="transform" type="translate" values="0 0; 0 -6; 0 0" dur="6s" repeatCount="indefinite"/>
      </g>

      <!-- card 2 -->
      <g transform="translate(0,90)">
        <rect x="0" y="0" rx="12" ry="12" width="340" height="76" fill="#061029" stroke="#ff62c9" stroke-opacity="0.06"/>
        <text x="16" y="24" font-size="16" fill="#ffdff7">E-Commerce / Store</text>
        <text x="16" y="44" font-size="12" fill="#ffdff7">Product management, filters, admin</text>
        <animateTransform attributeName="transform" type="translate" values="0 0; 0 6; 0 0" dur="5.6s" repeatCount="indefinite"/>
      </g>
    </g>

    <!-- rotating cyber badge -->
    <g transform="translate(820,24)">
      <circle cx="40" cy="40" r="36" fill="#001a1e" stroke="#00ffd5" stroke-width="1.4" opacity="0.95"/>
      <g transform="translate(40,40)" fill="#00ffd5" opacity="0.95">
        <path d="M-8 -10 h16 v4 h-16 z" />
        <rect x="-10" y="6" width="20" height="4" rx="2"/>
      </g>
      <animateTransform attributeName="transform" type="rotate" values="0 40 40; 360 40 40" dur="14s" repeatCount="indefinite"/>
    </g>
  </svg>

  <!-- CTA neon line -->
  <p style="color:#bfefff; margin-top:10px; font-family: Inter, Roboto, sans-serif;">
    I build deployable backend services — honest, learning, and focused on results. Open to collaboration & mentorship.
  </p>
</div>

<!-- ===================== MAIN CONTENT ===================== -->

<div style="margin-top:18px; display:flex; gap:18px; flex-wrap:wrap; justify-content:center;">

  <!-- Skill card column -->
  <div style="width:460px; border-radius:12px; padding:14px; background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border:1px solid rgba(255,255,255,0.04); box-shadow: 0 8px 30px rgba(3,6,30,0.6);">
    <h3 style="color:#9ef2ff; font-family: Inter, Roboto, sans-serif; margin:6px 0 12px 0;">🛠 Skills — Honest & Categorized</h3>

    <!-- Programming Languages -->
    <div style="margin-bottom:10px;">
      <h4 style="color:#b9ffef; margin:0 0 6px 0;">🔹 Programming Languages</h4>
      <p style="color:#dffbff; margin:0 0 10px 0;">
        <strong>Python</strong> — main development language. Used for backend logic, scripting and small data tasks.<br/>
        <strong>C++</strong> — core fundamentals, OOP and algorithmic tasks experience.
      </p>
    </div>

    <!-- Frameworks -->
    <div style="margin-bottom:10px;">
      <h4 style="color:#ffb1f0; margin:0 0 6px 0;">🧩 Frameworks</h4>
      <p style="color:#ffe7fb; margin:0 0 10px 0;">
        <strong>Django</strong> — built blog, ecommerce and bookstore projects with admin, auth and forms.<br/>
        <strong>FastAPI</strong> — designed fast APIs, async endpoints and OpenAPI docs for service-to-service use.
      </p>
    </div>

    <!-- Databases -->
    <div style="margin-bottom:10px;">
      <h4 style="color:#bff7c9; margin:0 0 6px 0;">🗄 Databases</h4>
      <p style="color:#ecffef; margin:0 0 10px 0;">
        <strong>SQLite</strong> — development / small apps.<br/>
        <strong>PostgreSQL</strong> — production preference; transactions & reliability.<br/>
        <strong>MySQL</strong> — used for structured apps and basic administration.
      </p>
    </div>

    <!-- Tools & Libraries -->
    <div>
      <h4 style="color:#9be4ff; margin:0 0 6px 0;">🧰 Tools & Libraries</h4>
      <p style="color:#e8ffff; margin:0;">
        <strong>Git & GitHub</strong> — version control and repo best practices.<br/>
        <strong>Docker</strong> — containerization for reproducible dev/test/deploy.<br/>
        <strong>NumPy</strong>, <strong>Pandas</strong> — numerical and data processing utilities.<br/>
        <strong>HTML & CSS</strong> — frontend basics to connect UI and backend.
      </p>
    </div>
  </div>

  <!-- Animated skill meters column -->
  <div style="width:420px; border-radius:12px; padding:14px; background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.0)); border:1px solid rgba(255,255,255,0.03); box-shadow: 0 8px 30px rgba(3,6,30,0.6);">
    <h3 style="color:#ffd3ff; margin:6px 0 12px 0;">📈 Skill Meters (animated)</h3>

    <!-- Each meter is SVG animated -->
    <div style="margin-bottom:10px;">
      <!-- Python meter -->
      <svg width="360" height="36" viewBox="0 0 360 36" xmlns="http://www.w3.org/2000/svg">
        <rect x="0" y="6" rx="10" ry="10" width="360" height="24" fill="#071026"/>
        <rect x="0" y="6" rx="10" ry="10" width="252" height="24" fill="#00f0ff" opacity="0.95">
          <animate attributeName="width" values="0;252" dur="1.6s" fill="freeze"/>
        </rect>
        <text x="10" y="22" font-size="12" fill="#00151a" font-family="Segoe UI">Python — 70%</text>
      </svg>
    </div>

    <div style="margin-bottom:10px;">
      <svg width="360" height="36" viewBox="0 0 360 36" xmlns="http://www.w3.org/2000/svg">
        <rect x="0" y="6" rx="10" ry="10" width="360" height="24" fill="#071026"/>
        <rect x="0" y="6" rx="10" ry="10" width="198" height="24" fill="#9b59ff" opacity="0.95">
          <animate attributeName="width" values="0;198" dur="1.6s" fill="freeze"/>
        </rect>
        <text x="10" y="22" font-size="12" fill="#0b0014">Django — 55%</text>
      </svg>
    </div>

    <div style="margin-bottom:10px;">
      <svg width="360" height="36" viewBox="0 0 360 36" xmlns="http://www.w3.org/2000/svg">
        <rect x="0" y="6" rx="10" ry="10" width="360" height="24" fill="#071026"/>
        <rect x="0" y="6" rx="10" ry="10" width="180" height="24" fill="#00d4b8" opacity="0.95">
          <animate attributeName="width" values="0;180" dur="1.6s" fill="freeze"/>
        </rect>
        <text x="10" y="22" font-size="12" fill="#00221f">FastAPI — 50%</text>
      </svg>
    </div>

    <div style="margin-bottom:10px;">
      <svg width="360" height="36" viewBox="0 0 360 36" xmlns="http://www.w3.org/2000/svg">
        <rect x="0" y="6" rx="10" ry="10" width="360" height="24" fill="#071026"/>
        <rect x="0" y="6" rx="10" ry="10" width="168" height="24" fill="#2496ed" opacity="0.95">
          <animate attributeName="width" values="0;168" dur="1.8s" fill="freeze"/>
        </rect>
        <text x="10" y="22" font-size="12" fill="#021533">Docker — 47%</text>
      </svg>
    </div>

    <div style="margin-bottom:8px;">
      <svg width="360" height="36" viewBox="0 0 360 36" xmlns="http://www.w3.org/2000/svg">
        <rect x="0" y="6" rx="10" ry="10" width="360" height="24" fill="#071026"/>
        <rect x="0" y="6" rx="10" ry="10" width="156" height="24" fill="#2ecc71" opacity="0.95">
          <animate attributeName="width" values="0;156" dur="1.8s" fill="freeze"/>
        </rect>
        <text x="10" y="22" font-size="12" fill="#042414">PostgreSQL — 43%</text>
      </svg>
    </div>

  </div>
</div>

<!-- ===================== PROJECT SECTION: FULL ANIMATED CARDS ===================== -->

<div style="margin-top:18px; display:flex; gap:16px; flex-wrap:wrap; justify-content:center;">

  <!-- Project card 1 (animated) -->
  <div style="width:300px; border-radius:12px; padding:14px; background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border:1px solid rgba(255,255,255,0.04); box-shadow: 0 10px 40px rgba(3,6,30,0.6); transform:translateY(0);">
    <svg width="280" height="120" viewBox="0 0 280 120" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="p1" x1="0" x2="1"><stop offset="0" stop-color="#00f0ff"/><stop offset="1" stop-color="#ff2d95"/></linearGradient>
        <filter id="g3"><feGaussianBlur stdDeviation="3"/></filter>
      </defs>
      <rect x="0" y="0" width="280" height="120" rx="10" fill="#041026"/>
      <rect x="12" y="12" width="256" height="96" rx="8" fill="#071229" stroke="url(#p1)" stroke-opacity="0.09"/>
      <text x="24" y="36" font-size="14" fill="#bfefff">Bookstore — Django + Docker</text>
      <text x="24" y="56" font-size="11" fill="#9bdcff">Auth • Admin • Cart • Docker</text>

      <!-- little animated server icon -->
      <g transform="translate(200,28)">
        <rect x="0" y="0" width="52" height="24" rx="4" fill="#001620"/>
        <rect x="4" y="4" width="44" height="6" rx="2" fill="#00ffd5">
          <animate attributeName="x" values="4;6;4" dur="2.4s" repeatCount="indefinite"/>
        </rect>
        <rect x="4" y="16" width="44" height="6" rx="2" fill="#9b59ff">
          <animate attributeName="x" values="4;2;4" dur="2.6s" repeatCount="indefinite"/>
        </rect>
      </g>
    </svg>
    <p style="color:#cfefff; margin:10px 0 0 0; font-size:13px;">Containerized & ready to run. Can provide docker-compose + example .env.</p>
  </div>

  <!-- Project card 2 -->
  <div style="width:300px; border-radius:12px; padding:14px; background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border:1px solid rgba(255,255,255,0.04); box-shadow: 0 10px 40px rgba(3,6,30,0.6);">
    <svg width="280" height="120" viewBox="0 0 280 120" xmlns="http://www.w3.org/2000/svg">
      <defs><linearGradient id="p2" x1="0" x2="1"><stop offset="0" stop-color="#ff8af2"/><stop offset="1" stop-color="#00f0ff"/></linearGradient></defs>
      <rect x="0" y="0" width="280" height="120" rx="10" fill="#041026"/>
      <rect x="12" y="12" width="256" height="96" rx="8" fill="#071229" stroke="url(#p2)" stroke-opacity="0.09"/>
      <text x="24" y="36" font-size="14" fill="#ffdff7">E-Commerce / Store — Django</text>
      <text x="24" y="56" font-size="11" fill="#ffdff7">Products • Categories • Filters • Admin</text>

      <!-- animated filter icon -->
      <g transform="translate(200,32)">
        <rect x="0" y="0" width="20" height="4" rx="2" fill="#ffdff7"/>
        <rect x="0" y="10" width="14" height="4" rx="2" fill="#ffdff7"/>
        <rect x="0" y="20" width="8" height="4" rx="2" fill="#ffdff7"/>
        <animateTransform attributeName="transform" type="translate" values="0 0; 0 -4; 0 0" dur="3s" repeatCount="indefinite"/>
      </g>
    </svg>
    <p style="color:#ffdff7; margin:10px 0 0 0; font-size:13px;">Backend focused, secure forms and basic unit tests included.</p>
  </div>

  <!-- Project card 3 -->
  <div style="width:300px; border-radius:12px; padding:14px; background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border:1px solid rgba(255,255,255,0.04); box-shadow: 0 10px 40px rgba(3,6,30,0.6);">
    <svg width="280" height="120" viewBox="0 0 280 120" xmlns="http://www.w3.org/2000/svg">
      <rect x="0" y="0" width="280" height="120" rx="10" fill="#041026"/>
      <rect x="12" y="12" width="256" height="96" rx="8" fill="#071229" stroke="#00f0ff" stroke-opacity="0.06"/>
      <text x="24" y="36" font-size="14" fill="#cfefff">Blog Platform — Django</text>
      <text x="24" y="56" font-size="11" fill="#9bdcff">CRUD • Tags • Draft/Publish • Admin</text>

      <!-- little pen icon animation -->
      <g transform="translate(208,28)">
        <path d="M0 20 L12 4 L20 12 L8 28 z" fill="#9bdcff">
          <animateTransform attributeName="transform" type="rotate" values="0 10 16; 8 10 16; 0 10 16" dur="3.6s" repeatCount="indefinite"/>
        </path>
      </g>
    </svg>
    <p style="color:#cfefff; margin:10px 0 0 0; font-size:13px;">Simple, documented, and ready for incremental improvements.</p>
  </div>

</div>

<!-- ===================== HONEST PROFILE NOTE ===================== -->
<div align="center" style="margin-top:18px; padding:14px; border-radius:12px; background: linear-gradient(90deg, rgba(255,255,255,0.01), rgba(255,255,255,0.0)); border:1px solid rgba(255,255,255,0.03);">
  <p style="color:#d8ffff; max-width:900px;">
    <strong>Status:</strong> <em>Junior / Learning</em> — I have built deployable projects with Django & FastAPI, containerized with Docker, and used PostgreSQL / MySQL / SQLite.  
    I am honest about my level: I ship working features, write readable code, and I improve quickly with feedback. If you want a motivated developer to take ownership of backend tasks while learning best practices — let's talk.
  </p>
</div>

<!-- ===================== CONTACT & BADGES ===================== -->
<div align="center" style="margin-top:18px; display:flex; gap:10px; justify-content:center; flex-wrap:wrap;">

  <!-- badges (replace yourusername) -->
  <img src="https://img.shields.io/badge/Email-your-email%40example.com-blue?style=for-the-badge" alt="email"/>
  <img src="https://img.shields.io/badge/LinkedIn-your-linkedin-url-blueviolet?style=for-the-badge" alt="linkedin"/>
  <img src="https://img.shields.io/badge/GitHub-amirNeghabi-181717?style=for-the-badge&logo=github" alt="github"/>
  <img src="https://img.shields.io/badge/TopLangs-Python%20%7C%20Django-orange?style=for-the-badge" alt="top langs"/>

</div>

<!-- ===================== FOOTER: QUICK ACTIONS ===================== -->
<div align="center" style="margin-top:18px; padding:16px; border-radius:10px; background:linear-gradient(180deg, rgba(255,255,255,0.01), rgba(255,255,255,0.02)); border:1px solid rgba(255,255,255,0.02);">
  <p style="color:#cfefff; margin:0 0 6px 0;">Want these extra additions?</p>
  <p style="color:#9bdcff; margin:0;">
    • I can add GitHub stats & top-langs badges using your username.  
    • I can create full READMEs for each project (docker-compose, env examples, run steps).  
    • I can translate this to Persian or make a separate minimal version for mobile viewers.
  </p>

  <p style="margin-top:8px;">
    <strong style="color:#ffd7ff;">Email:</strong> <span style="color:#dffbff;">your-email@example.com</span> &nbsp; • &nbsp;
    <strong style="color:#ffd7ff;">LinkedIn:</strong> <span style="color:#dffbff;">your-linkedin-url</span>
  </p>
</div>

