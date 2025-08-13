<!--
  Tip: this README lives in a repo named exactly like your GitHub username.
  Many sections below auto-adapt to dark/light mode and look great on mobile.
-->

<p align="center">
 <!-- assets/banner-gradient.svg -->
<svg viewBox="0 0 1200 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Henry Ngan — I build delightful digital experiences">
  <defs>
    <!-- shadcn-ish neutrals + subtle emerald/cyan accent -->
    <radialGradient id="bg" cx="50%" cy="50%" r="75%">
      <stop offset="0" stop-color="#0a0a0b"/>
      <stop offset="1" stop-color="#000000"/>
    </radialGradient>

    <linearGradient id="accent" x1="0" y1="0" x2="1" y2="0">
      <!-- tweak these two colors to change the vibe -->
      <stop offset="0" stop-color="#22c55e"/>
      <stop offset="1" stop-color="#06b6d4"/>
    </linearGradient>

    <!-- soft glow for the hairline accent -->
    <filter id="softGlow">
      <feGaussianBlur stdDeviation="6" result="b"/>
      <feMerge>
        <feMergeNode in="b"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <!-- ultra-subtle film grain -->
    <filter id="grain">
      <feTurbulence type="fractalNoise" baseFrequency="0.9" numOctaves="2" stitchTiles="stitch"/>
      <feColorMatrix type="saturate" values="0"/>
      <feComponentTransfer>
        <feFuncA type="table" tableValues="0 0.035"/>
      </feComponentTransfer>
    </filter>
  </defs>

  <!-- background -->
  <rect width="1200" height="260" fill="url(#bg)"/>

  <!-- card -->
  <g>
    <rect x="20" y="18" width="1160" height="224" rx="16" fill="#0a0a0b" />
    <!-- hairline border + iris highlight -->
    <rect x="20" y="18" width="1160" height="224" rx="16" fill="none" stroke="#ffffff" stroke-opacity="0.06"/>
    <rect x="20" y="18" width="1160" height="224" rx="16" fill="none" stroke="url(#accent)" stroke-opacity="0.12"/>

    <!-- accent hairline -->
    <rect x="32" y="210" width="1136" height="1.2" fill="url(#accent)" opacity="0.35" filter="url(#softGlow)"/>

    <!-- text -->
    <text x="56" y="120"
      font-family="Inter, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial"
      font-weight="800" font-size="56" fill="#e5e7eb">Henry Ngan</text>

    <text x="56" y="155"
      font-family="Inter, ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial"
      font-size="20" fill="#a1a1aa">I build delightful digital experiences</text>

    <text x="56" y="185"
      font-family="JetBrains Mono, ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace"
      font-size="14" fill="#9ca3af" opacity="0.9">
      React · TypeScript · Spring Boot · PostgreSQL · Toronto 🏙️
    </text>
  </g>

  <!-- whisper of grain -->
  <rect width="1200" height="260" fill="#000" opacity="0" filter="url(#grain)"/>
</svg>

</p>

<h1 align="center">hey, i'm henry <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="28" height="28" alt="wave"></h1>

<p align="center">
  Software Engineer • Toronto lover • ex-Rally Cry full-stack • hackathon winner (2021) 🏆
</p>

<p align="center">
  <a href="https://henry-ngan.com"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-henry--ngan.com-0ea5e9?style=for-the-badge&logo=vercel&logoColor=white"></a>
  <a href="mailto:henrynganwork@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-henrynganwork%40gmail.com-c14438?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/henryngan"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-henryngan-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
</p>

---

### about me

- 🧑🏽‍💻 used to work full-stack at **Rally Cry** 
- 🧠 learning about **Three.js** and exploring AI integrations.
- 🏀 🏐 big on **basketball** and **volleyball** — ask me about pick-up games!!
- 🎒 huge **Pokémon** nerd
- 🏙️ based in **downtown Toronto**
- 🎂 turning **27** this year
- 💡 always down to jam on ideas — **got one? let’s talk!**

---

### what i’m building now

> **Project:** a tool that helps **young people invest** confidently with **AI**  
> **Status:** early build (naming TBD) — looking for feedback + collaborators  
> **Pitch:** think “friendly co-pilot” that explains, simulates, and nudges good habits

If this sounds interesting, open a discussion or DM me. 🤝

---

### featured work

<!-- Replace repo names after you pin or create them -->
- 🧭 **AI Investing Co-Pilot** — WIP: onboarding flows, risk profiling, and explainer UI  
  `react · typescript · vercel · playwright`
- 🏆 **Hackathon 2021 Winner** — fast prototype → polished demo → 🥇  
  `react · node · postgresql`
- 🕹️ **Rally Cry projects** — selected features & learnings (write-up / case study)  
  `spring boot · react · material ui · team play`

> Tip: pin your repos to match these. Add screenshots (in `/assets`) and link to write-ups.


### let’s connect

Got an idea or want to hoop in Toronto? DM me or shoot an email.  
<strong>Open to collabs, mentorship chats, and cool web experiments.</strong>
