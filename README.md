
<h1 align="center">Developer & Builder</h1>

<p align="center">
  <strong>Software Engineering • Local-first Architecture • Interactive 3D</strong><br/>
  <em>« Build sharp. Keep it local. Ship clean. »</em>
</p>

<div align="center">
  
[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=00E5FF&center=true&vCenter=true&width=720&lines=Systems+engineering+%26+simulation;Local-first+%26+Web+Crypto;Three.js+%2F+R3F+real-time+UI;Accessible+neumorphism;Minimal+deps%2C+max+craft)](#)

</div>

<!-- ===== HERO NEON CARD (inline SVG, responsive) ===== -->
<p align="center">
<svg width="100%" height="200" viewBox="0 0 940 200" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Franck — Artist Dev">
  <defs>
    <linearGradient id="g1" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#00E5FF"/>
      <stop offset="50%" stop-color="#7A5CFF"/>
      <stop offset="100%" stop-color="#FF2ED1"/>
    </linearGradient>
    <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="6" result="b"/>
      <feMerge>
        <feMergeNode in="b"/>
        <feMergeNode in="b"/>
        <feMergeNode in="b"/>
      </feMerge>
    </filter>
    <filter id="inner" x="-50%" y="-50%" width="200%" height="200%">
      <!-- Inner shadow for neumorphism -->
      <feOffset dx="0" dy="2"/>
      <feGaussianBlur stdDeviation="4" result="o"/>
      <feComposite in="o" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="i"/>
      <feColorMatrix in="i" type="matrix" values="0 0 0 0 0  0 0 0 0 0  0 0 0 0 0  0 0 0 0.45 0"/>
      <feBlend in="SourceGraphic" mode="multiply"/>
    </filter>
  </defs>

  <!-- frame -->
  <rect x="10" y="10" rx="18" ry="18" width="920" height="180" fill="#0B0E12" />
  <rect x="10" y="10" rx="18" ry="18" width="920" height="180" fill="none" stroke="url(#g1)" stroke-width="2" filter="url(#glow)"/>

  <!-- title with faux neon -->
  <g transform="translate(40, 70)">
    <text x="0" y="0" font-family="JetBrains Mono, Consolas, monospace" font-size="44" fill="#0ff" opacity="0.15" filter="url(#glow)"></text>
    <text x="0" y="42" font-family="Inter, Segoe UI, Arial" font-size="18" fill="#AAB2C0">Artist Developer — code, design & sound</text>
  </g>

  <!-- right badge -->
  <g transform="translate(720, 50)">
    <rect x="0" y="0" rx="12" ry="12" width="190" height="48" fill="#0F141B" filter="url(#inner)"/>
    <text x="16" y="30" font-family="JetBrains Mono, monospace" font-size="14" fill="#E6F1FF">local-first • PBKDF2</text>
  </g>
</svg>
</p>

---

### Engineering

I design and build software around **interactive computation, local-first systems and sensory interfaces**. 

My work spans simulation, geospatial processing, real-time 3D and developer tooling — projects where correctness, architecture and runtime behaviour matter as much as the interface. I favour explicit system boundaries, observable behaviour and technical decisions justified by evidence rather than convention.

---

### Technical scope

| Domain | Practice |
|---|---|
| **Languages** | TypeScript / JavaScript, C#, Python |
| **UI/3D & Visualization** | React (explicit hooks), R3F / Three.js, Canvas, scientific interfaces |
| **Security** | IndexedDB + PBKDF2, Web Crypto, encrypted local storage, zero-cloud by default |
| **Systems & Data** | Data-driven simulation, geospatial pipelines (OSM/GeoJSON), runtime integration |
| **Tooling & Quality** | Vite, pnpm, PowerShell, ESLint, Playwright, static analysis |
| **Design** | Accessible neumorphism, clear contrast, focus states, minimalist dependencies |

---

### Engineering principles

**Correctness before convenience.**
Critical behaviour should be understood, measurable and testable.

**Architecture before accumulation.**
A codebase should expose its responsibilities instead of hiding them behind incidental complexity.

**Evidence before assumption.**
Scientific, security and performance decisions deserve references, measurements or reproducible tests.

**Refactoring is part of engineering.**
A system should evolve when a better understanding of the problem invalidates earlier abstractions.

---

<!-- ===== SKILL PILLS (inline SVG neumorphic tags, responsive) ===== -->
<p align="center">
<svg width="100%" height="96" viewBox="0 0 940 96" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Skills">
  <defs>
    <filter id="pillInner" x="-50%" y="-50%" width="200%" height="200%">
      <feOffset dx="0" dy="2"/>
      <feGaussianBlur stdDeviation="3" result="o"/>
      <feComposite in="o" in2="SourceAlpha" operator="arithmetic" k2="-1" k3="1" result="i"/>
      <feColorMatrix in="i" type="matrix" values="0 0 0 0 0  0 0 0 0 0  0 0 0 0 0  0 0 0 0.45 0"/>
      <feBlend in="SourceGraphic" mode="multiply"/>
    </filter>
    <linearGradient id="pillStroke" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#00E5FF"/>
      <stop offset="100%" stop-color="#7A5CFF"/>
    </linearGradient>
  </defs>

  <!-- utility: functionally a grid of pills -->
  <g font-family="JetBrains Mono, monospace" font-size="13" fill="#DDE6F7">
    <g transform="translate(20,22)">
      <g transform="translate(0,0)">
        <rect x="0" y="0" rx="12" ry="12" width="150" height="36" fill="#0F141B" filter="url(#pillInner)" stroke="url(#pillStroke)"/>
        <text x="16" y="24">TypeScript / React</text>
      </g>
      <g transform="translate(170,0)">
        <rect x="0" y="0" rx="12" ry="12" width="138" height="36" fill="#0F141B" filter="url(#pillInner)" stroke="url(#pillStroke)"/>
        <text x="16" y="24">R3F / Three.js</text>
      </g>
      <g transform="translate(328,0)">
        <rect x="0" y="0" rx="12" ry="12" width="168" height="36" fill="#0F141B" filter="url(#pillInner)" stroke="url(#pillStroke)"/>
        <text x="16" y="24">IndexedDB + PBKDF2</text>
      </g>
      <g transform="translate(506,0)">
        <rect x="0" y="0" rx="12" ry="12" width="110" height="36" fill="#0F141B" filter="url(#pillInner)" stroke="url(#pillStroke)"/>
        <text x="16" y="24">Python</text>
      </g>
      <g transform="translate(626,0)">
        <rect x="0" y="0" rx="12" ry="12" width="88" height="36" fill="#0F141B" filter="url(#pillInner)" stroke="url(#pillStroke)"/>
        <text x="16" y="24">C#</text>
      </g>
      <g transform="translate(724,0)">
        <rect x="0" y="0" rx="12" ry="12" width="176" height="36" fill="#0F141B" filter="url(#pillInner)" stroke="url(#pillStroke)"/>
        <text x="16" y="24">Neumorphisme a11y</text>
      </g>
    </g>
  </g>
</svg>
</p>

---

### 🔗 Contact
[![LinkedIn](https://img.shields.io/badge/LinkedIn-000?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](LIEN_LINKEDIN)
[![Portfolio](https://img.shields.io/badge/Portfolio-000?style=for-the-badge&logo=vercel&logoColor=white)](LIEN_PORTFOLIO)
[![Email](https://img.shields.io/badge/Email-000?style=for-the-badge&logo=gmail&logoColor=EA4335)](mailto:EMAIL)

---
