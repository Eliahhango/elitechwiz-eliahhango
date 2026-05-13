
<!-- HEADER DESIGN -->
<div align="center">
  <img src="vercel.app" width="100%" alt="Header" />
</div>

<br />

<!-- TERMINAL DASHBOARD COMPONENT -->
```xml
<svg fill="none" viewBox="0 0 800 420" width="100%" xmlns="w3.org">
  <foreignObject width="100%" height="100%">
    <div xmlns="w3.org">
      <style>
        .terminal-container {
          background-color: #05070B;
          border: 1px solid #00F2FE;
          border-radius: 12px;
          padding: 20px;
          font-family: 'JetBrains Mono', 'Fira Code', monospace;
          color: #FFFFFF;
          box-shadow: 0px 4px 30px rgba(0, 242, 254, 0.15);
        }
        .window-header {
          display: flex;
          justify-content: space-between;
          align-items: center;
          border-bottom: 1px solid #1E293B;
          padding-bottom: 12px;
          margin-bottom: 20px;
        }
        .dots { display: flex; gap: 6px; }
        .dot { width: 12px; height: 12px; border-radius: 50%; }
        .dot-r { background-color: #FF5F56; }
        .dot-y { background-color: #FFBD2E; }
        .dot-g { background-color: #27C93F; }
        .window-title { color: #64748B; font-size: 13px; }
        .badge-tag { background: rgba(0, 242, 254, 0.1); border: 1px solid #00F2FE; color: #00F2FE; font-size: 11px; padding: 2px 8px; border-radius: 12px; }
        
        .dashboard-layout { display: grid; grid-template-columns: 1.1fr 1.2fr; gap: 24px; }
        .cmd-line { margin-bottom: 16px; font-size: 14px; }
        .cmd-input { color: #9B51E0; font-weight: bold; }
        .cmd-output { color: #A0AEC0; margin-top: 4px; padding-left: 12px; }
        
        .profile-card { background: rgba(13, 17, 23, 0.7); border: 1px solid #1E293B; border-radius: 8px; padding: 16px; }
        .card-title { color: #00F2FE; font-size: 15px; font-weight: bold; margin-bottom: 14px; text-transform: uppercase; letter-spacing: 1px; }
        .info-row { display: grid; grid-template-columns: 80px 1fr; margin-bottom: 10px; font-size: 13px; align-items: baseline; }
        .info-key { color: #9B51E0; font-weight: bold; }
        .info-val { color: #E2E8F0; }
        .accent-text { color: #00F2FE; font-weight: bold; }
        
        .cursor { display: inline-block; width: 8px; height: 15px; background: #00F2FE; animation: blink 1s infinite; margin-left: 4px; vertical-align: middle; }
        @keyframes blink { 0%, 49% { opacity: 1; } 50%, 100% { opacity: 0; } }
      </style>

      <div class="terminal-container">
        <div class="window-header">
          <div class="dots"><div class="dot dot-r"></div><div class="dot dot-y"></div><div class="dot dot-g"></div></div>
          <div class="window-title">Eliahhango @ EliTechWiz</div>
          <div class="badge-tag">CYBERPUNK MINIMALIST</div>
        </div>

        <div class="dashboard-layout">
          <!-- LEFT SIDE: ACTIVE TERMINAL -->
          <div>
            <div class="cmd-line">
              <span class="cmd-input">$ whoami</span>
              <div class="cmd-output">Eliahhango</div>
            </div>
            <div class="cmd-line">
              <span class="cmd-input">$ git config user.name</span>
              <div class="cmd-output">Eliahhango</div>
            </div>
            <div class="cmd-line">
              <span class="cmd-input">$ git config user.email</span>
              <div class="cmd-output">hangoeliah@gmail.com</div>
            </div>
            <div class="cmd-line">
              <span class="cmd-input">$ system_status --live</span>
              <div class="cmd-output" style="color: #27C93F;">● Building clean UI & solid logic...<span class="cursor"></span></div>
            </div>
          </div>

          <!-- RIGHT SIDE: DATA PROFILE DOCK -->
          <div class="profile-card">
            <div class="card-title">🚀 Profile Snapshot</div>
            <div class="info-row"><span class="info-key">NAME</span><span class="info-val">: Eliahhango (<span class="accent-text">EliTechWiz</span>)</span></div>
            <div class="info-row"><span class="info-key">ROLE</span><span class="info-val">: Full Stack Developer</span></div>
            <div class="info-row"><span class="info-key">STACK</span><span class="info-val" style="color: #00F2FE;">: JS, PY, TS, SQL, REACT, NODE</span></div>
            <div class="info-row"><span class="info-key">TOOLS</span><span class="info-val">: MongoDB, PostgreSQL, Tailwind, Figma</span></div>
            <div class="info-row"><span class="info-key">STYLE</span><span class="info-val">: Clean UI, Solid Logic, Good DX</span></div>
          </div>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>
```

```markdown
<br />

<!-- TECH STACK BADGES -->
<h3 align="left">🛠️ Tech Stack & Ecosystem</h3>

<p align="left">
  <img src="shields.io" alt="JavaScript" />
  <img src="shields.io" alt="TypeScript" />
  <img src="shields.io" alt="Python" />
  <img src="shields.io" alt="PostgreSQL" />
  <img src="shields.io" alt="React" />
  <img src="shields.io" alt="Node.js" />
  <img src="shields.io" alt="Express" />
  <img src="shields.io" alt="MongoDB" />
  <img src="shields.io" alt="Tailwind" />
  <img src="shields.io" alt="Figma" />
</p>

<br />

<!-- GITHUB GRAPH STATS SECTION -->
<h3 align="left">📊 GitHub Metrics</h3>

<p align="center">
  <img src="vercel.app" width="48%" alt="GitHub Stats" />
  <img src="herokuapp.com" width="48%" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="vercel.app" width="60%" alt="Top Languages" />
</p>

<br />

<!-- FOOTER -->
<div align="center">
  <p>💡 <i>"Turning complex logic into beautiful, responsive web ecosystems."</i></p>
  <p>📬 Get in touch: <b>hangoeliah@gmail.com</b></p>
</div>
```

If you want to tweak any colors, add a **custom GitHub project showcase section**, or implement **social media icon links** at the bottom, just let me know!
