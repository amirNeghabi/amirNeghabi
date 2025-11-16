<!--
  Dark Neon Cyberpunk README for AmirReza Neghabi
  Paste this into README.md in your profile repo (repo name should match your GitHub username)
  Replace placeholders: your-email@example.com, your-linkedin-url, yourusername
-->

<!-- Gradient background block (works in many GitHub README viewers) -->
<div align="center" style="background: linear-gradient(135deg,#070617 0%, #0f0428 40%, #021628 100%); padding: 32px; border-radius: 12px; box-shadow: 0 10px 30px rgba(2,6,30,0.6);">

  <!-- Neon animated header banner (SVG) -->
  <svg width="900" height="140" viewBox="0 0 900 140" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <defs>
      <linearGradient id="neonA" x1="0" x2="1">
        <stop offset="0" stop-color="#00f0ff"/>
        <stop offset="0.5" stop-color="#9b59ff"/>
        <stop offset="1" stop-color="#ff2d95"/>
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="4.5" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
      <filter id="soft">
        <feGaussianBlur stdDeviation="1.2"/>
      </filter>
    </defs>

    <!-- Background grid -->
    <g opacity="0.12">
      <rect x="0" y="0" width="900" height="140" fill="#000"/>
      <g stroke="#00ffea" stroke-opacity="0.06" stroke-width="0.8">
        <!-- vertical lines -->
        <g>
          <!-- generate a subtle grid -->
          <line x1="0" y1="0" x2="0" y2="140"/>
          <line x1="50" y1="0" x2="50" y2="140"/>
          <line x1="100" y1="0" x2="100" y2="140"/>
          <line x1="150" y1="0" x2="150" y2="140"/>
          <line x1="200" y1="0" x2="200" y2="140"/>
          <line x1="250" y1="0" x2="250" y2="140"/>
          <line x1="300" y1="0" x2="300" y2="140"/>
          <line x1="350" y1="0" x2="350" y2="140"/>
          <line x1="400" y1="0" x2="400" y2="140"/>
          <line x1="450" y1="0" x2="450" y2="140"/>
          <line x1="500" y1="0" x2="500" y2="140"/>
          <line x1="550" y1="0" x2="550" y2="140"/>
          <line x1="600" y1="0" x2="600" y2="140"/>
          <line x1="650" y1="0" x2="650" y2="140"/>
          <line x1="700" y1="0" x2="700" y2="140"/>
          <line x1="750" y1="0" x2="750" y2="140"/>
          <line x1="800" y1="0" x2="800" y2="140"/>
          <line x1="850" y1="0" x2="850" y2="140"/>
          <line x1="900" y1="0" x2="900" y2="140"/>
        </g>
      </g>
    </g>

    <!-- Neon text -->
    <g transform="translate(30,88)">
      <text x="0" y="0" font-family="Segoe UI, Roboto, Helvetica, Arial" font-size="40" fill="url(#neonA)" filter="url(#glow)">
        AmirReza Neghabi
      </text>
      <text x="0" y="38" font-family="Segoe UI, Roboto, Helvetica, Arial" font-size="14" fill="#9bdcff" opacity="0.95">
        Backend Developer — Python • Django • FastAPI • Docker
      </text>

      <!-- animated underline -->
      <rect x="0" y="46" width="360" height="3" fill="url(#neonA)" opacity="0.9">
        <animate attributeName="width" values="0;360;0" dur="6s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- cyber icon (rotating) -->
    <g transform="translate(780,10) scale(0.8)" fill="#00ffd7" opacity="0.85">
      <circle cx="30" cy="30" r="28" stroke="#39ffa8" stroke-width="1"/>
      <g transform="translate(20,20)">
        <rect x="6" y="2" width="18" height="2" rx="1" fill="#fff"/>
        <rect x="6" y="8" width="12" height="2" rx="1" fill="#fff"/>
      </g>
      <animateTransform attributeName="transform" type="rotate" values="0 30 30; 360 30 30" dur="18s" repeatCount="indefinite"/>
    </g>
  </svg>

  <!-- short tagline -->
  <p style="color:#9bdcff; font-family: Inter, Roboto, sans-serif; margin-top: 8px;">
    I build practical backend systems — honest, learning, and focused on deploying real projects.
  </p>

</div>

---

<!-- main content area -->
<div align="center" style="margin-top: 18px;">

### 🚀 About
I'm a **Backend Developer** working primarily with **Python**.  
I build, containerize and deploy backend services using **Django** and **FastAPI**.  
I consider myself a **junior developer (learning)** — I have built real projects and I'm committed to continuous improvement.

</div>

---

<!-- Skills neon cards -->
<div align="center" style="display:flex; gap:14px; flex-wrap:wrap; justify-content:center; margin:18px 0;">

<!-- card template: copy/modify for each category -->
<div style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border:1px solid rgba(255,255,255,0.04); padding:14px; width:300px; border-radius:12px; box-shadow: 0 6px 20px rgba(3,6,30,0.6);">
  <h4 style="color:#8ef0ff; margin:0 0 8px 0; font-family: Inter, Roboto, sans-serif;">🔹 Programming Languages</h4>
  <p style="color:#d7f7ff; margin:0; font-family: Inter, Roboto, sans-serif;">
    <strong>Python</strong> — main development language, used in web backends and data tasks.<br/>
    <strong>C++</strong> — fundamentals, OOP and algorithmic tasks experience.
  </p>
</div>

<div style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border:1px solid rgba(255,255,255,0.04); padding:14px; width:300px; border-radius:12px; box-shadow: 0 6px 20px rgba(3,6,30,0.6);">
  <h4 style="color:#ff8af2; margin:0 0 8px 0; font-family: Inter, Roboto, sans-serif;">🧩 Frameworks</h4>
  <p style="color:#ffdff7; margin:0; font-family: Inter, Roboto, sans-serif;">
    <strong>Django</strong> — built blog, store and bookshop projects with admin and auth.<br/>
    <strong>FastAPI</strong> — built fast APIs, async endpoints and OpenAPI docs.
  </p>
</div>

<div style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border:1px solid rgba(255,255,255,0.04); padding:14px; width:300px; border-radius:12px; box-shadow: 0 6px 20px rgba(3,6,30,0.6);">
  <h4 style="color:#a0ffb4; margin:0 0 8px 0; font-family: Inter, Roboto, sans-serif;">🗄 Databases</h4>
  <p style="color:#eaffed; margin:0; font-family: Inter, Roboto, sans-serif;">
    <strong>SQLite</strong> — development and small apps.<br/>
    <strong>PostgreSQL</strong> — recommended for production setups.<br/>
    <strong>MySQL</strong> — structural knowledge and queries.
  </p>
</div>

<div style="background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01)); border:1px solid rgba(255,255,255,0.04); padding:14px; width:300px; border-radius:12px; box-shadow: 0 6px 20px rgba(3,6,30,0.6);">
  <h4 style="color:#9bdcff; margin:0 0 8px 0; font-family: Inter, Roboto, sans-serif;">🛠 Tools & Libraries</h4>
  <p style="color:#dff8ff; margin:0; font-family: Inter, Roboto, sans-serif;">
    <strong>Git & GitHub</strong> — source control and profile best practices.<br/>
    <strong>Docker</strong> — containerization for reproducible environments.<br/>
    <strong>NumPy</strong>, <strong>Pandas</strong> — numerical and data manipulation.<br/>
    <strong>HTML & CSS</strong> — frontend basics to connect UI and backend.
  </p>
</div>

</div>

---

<!-- Animated neon skill bars (SVG) -->
<div align="center" style="margin-top:18px;">
  <svg width="880" height="220" viewBox="0 0 880 220" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <defs>
      <linearGradient id="g1" x1="0" x2="1"><stop offset="0" stop-color="#00f0ff"/><stop offset="1" stop-color="#ff2d95"/></linearGradient>
      <filter id="glow2"><feGaussianBlur stdDeviation="3.2" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
    </defs>

    <!-- Labels -->
    <g font-family="Segoe UI, Roboto, Arial" font-size="12" fill="#cfefff" opacity="0.95" transform="translate(8,28)">
      <text x="0" y="0">Python</text>
      <text x="0" y="40">Django</text>
      <text x="0" y="80">FastAPI</text>
      <text x="0" y="120">Docker</text>
      <text x="0" y="160">PostgreSQL</text>
    </g>

    <!-- Bars -->
    <g transform="translate(120,12)">
      <!-- Python bar (animated neon) -->
      <rect x="0" y="4" rx="8" ry="8" width="600" height="20" fill="#051022" stroke="#062434" stroke-width="1.2"/>
      <rect x="0" y="4" rx="8" ry="8" width="420" height="20" fill="url(#g1)" filter="url(#glow2)">
        <animate attributeName="width" values="0;420" dur="1.4s" fill="freeze"/>
      </rect>

      <!-- Django -->
      <rect x="0" y="44" rx="8" ry="8" width="600" height="20" fill="#051022" stroke="#062434" stroke-width="1.2"/>
      <rect x="0" y="44" rx="8" ry="8" width="330" height="20" fill="#9b59ff" opacity="0.95">
        <animate attributeName="width" values="0;330" dur="1.6s" fill="freeze"/>
      </rect>

      <!-- FastAPI -->
      <rect x="0" y="84" rx="8" ry="8" width="600" height="20" fill="#051022" stroke="#062434" stroke-width="1.2"/>
      <rect x="0" y="84" rx="8" ry="8" width="300" height="20" fill="#00d4b8" opacity="0.95">
        <animate attributeName="width" values="0;300" dur="1.6s" fill="freeze"/>
      </rect>

      <!-- Docker -->
      <rect x="0" y="124" rx="8" ry="8" width="600" height="20" fill="#051022" stroke="#062434" stroke-width="1.2"/>
      <rect x="0" y="124" rx="8" ry="8" width="280" height="20" fill="#2496ed" opacity="0.95">
        <animate attributeName="width" values="0;280" dur="1.8s" fill="freeze"/>
      </rect>

      <!-- PostgreSQL -->
      <rect x="0" y="164" rx="8" ry="8" width="600" height="20" fill="#051022" stroke="#062434" stroke-width="1.2"/>
      <rect x="0" y="164" rx="8" ry="8" width="260" height="20" fill="#2ecc71" opacity="0.95">
        <animate attributeName="width" values="0;260" dur="1.8s" fill="freeze"/>
      </rect>
    </g>

    <!-- numeric values -->
    <g font-family="Segoe UI, Roboto" font-size="11" fill="#aeefff" transform="translate(740,22)">
      <text x="0" y="0">70%</text>
      <text x="0" y="40">55%</text>
      <text x="0" y="80">50%</text>
      <text x="0" y="120">46%</text>
      <text x="0" y="160">43%</text>
    </g>
  </svg>
</div>

---

## ⭐ Highlighted Projects
> Projects are honest representations of what I built — simple, deployable, and documented.

- **Bookstore Website** — Django + Docker: Authentication, admin, product pages, cart (Docker-ready).  
- **E-Commerce / Store** — Django: Product management, categories, filters.  
- **Blog Platform** — Django: CRUD posts, tags, draft/publish workflow.

(If you'd like, I can create a dedicated README for each project with `docker-compose`, run steps, and example env files.)

---

## 🧭 Current level & approach
I identify as **Junior / Learning**:  
- I complete projects end-to-end and focus on deployability and documentation.  
- I welcome feedback and follow best practices as I improve.  
If you want a developer who is responsible, growing quickly, and focused on practical outcomes — let's work together.

---

## 📬 Contact
- Email: **your-email@example.com**  
- LinkedIn: **your-linkedin-url**  
- GitHub: https://github.com/amirNeghabi

(Replace placeholders with your real contact details.)

---

<!-- footer neon signature -->
<div align="center" style="margin-top:18px; padding:12px; border-radius:10px; background:linear-gradient(90deg, rgba(255,255,255,0.01), rgba(255,255,255,0.0));">
  <svg width="420" height="40" viewBox="0 0 420 40" xmlns="http://www.w3.org/2000/svg" aria-hidden="true">
    <defs>
      <linearGradient id="sig" x1="0" x2="1"><stop offset="0" stop-color="#00f0ff"/><stop offset="1" stop-color="#ff2d95"/></linearGradient>
      <filter id="sglow"><feGaussianBlur stdDeviation="2.2"/></filter>
    </defs>
    <text x="10" y="26" font-family="Segoe UI, Roboto" font-size="16" fill="url(#sig)" filter="url(#sglow)">Made with ⚡ Dark Neon • Junior Backend Dev</text>
    <animate xlink:href="#sig" attributeName="x" from="0" to="1" dur="4s" repeatCount="indefinite"/>
  </svg>
</div>


