<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>GitHub Profile README – Rd27p</title>
  <link href="https://fonts.googleapis.com/css2?family=Syne:wght@400;500;700;800&family=JetBrains+Mono:wght@400;500&display=swap" rel="stylesheet"/>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: 'Syne', sans-serif;
      background: #0d1117;
      color: #e6edf3;
      min-height: 100vh;
      padding: 2rem 1rem;
    }

    .profile-root {
      max-width: 860px;
      margin: 0 auto;
    }

    /* ── HERO ── */
    .hero {
      display: grid;
      grid-template-columns: 1fr auto;
      gap: 2rem;
      align-items: start;
      margin-bottom: 3rem;
      padding-bottom: 2rem;
      border-bottom: 0.5px solid rgba(255,255,255,0.08);
    }

    .hero-name {
      font-size: 13px;
      font-family: 'JetBrains Mono', monospace;
      color: #7d8590;
      margin-bottom: 6px;
      letter-spacing: 0.1em;
    }

    .hero-title {
      font-size: 34px;
      font-weight: 800;
      line-height: 1.1;
      margin-bottom: 16px;
      letter-spacing: -0.02em;
    }

    .hero-title span { color: #7F77DD; }

    .hero-desc {
      font-size: 15px;
      line-height: 1.7;
      color: #7d8590;
      max-width: 520px;
    }

    .badge-col {
      display: flex;
      flex-direction: column;
      align-items: flex-end;
      gap: 8px;
      padding-top: 4px;
    }

    .status-badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      background: #161b22;
      border: 0.5px solid rgba(255,255,255,0.1);
      border-radius: 100px;
      padding: 6px 14px;
      font-size: 12px;
      font-family: 'JetBrains Mono', monospace;
      color: #7d8590;
      white-space: nowrap;
    }

    .dot-online {
      width: 7px; height: 7px;
      border-radius: 50%;
      background: #1D9E75;
      flex-shrink: 0;
    }

    /* ── SECTION LABEL ── */
    .section-label {
      font-size: 11px;
      font-family: 'JetBrains Mono', monospace;
      letter-spacing: 0.12em;
      color: #484f58;
      text-transform: uppercase;
      margin-bottom: 16px;
    }

    /* ── TECH STACK ── */
    .tech-section { margin-bottom: 3rem; }

    .tech-grid {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .tech-tag {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 5px 12px;
      border-radius: 6px;
      font-size: 12px;
      font-family: 'JetBrains Mono', monospace;
      font-weight: 500;
      border: 0.5px solid rgba(255,255,255,0.08);
      background: #161b22;
      color: #7d8590;
      transition: border-color 0.15s, color 0.15s;
      cursor: default;
    }

    .tech-tag:hover {
      border-color: #AFA9EC;
      color: #e6edf3;
    }

    .dot-sm {
      width: 5px; height: 5px;
      border-radius: 50%;
      flex-shrink: 0;
    }

    /* ── STATS ── */
    .stats-section { margin-bottom: 3rem; }

    .stats-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 12px;
    }

    .stat-card {
      background: #0d1117;
      border: 0.5px solid rgba(255,255,255,0.08);
      border-radius: 12px;
      overflow: hidden;
    }

    .stat-card img {
      width: 100%;
      display: block;
    }

    .stat-card-label {
      padding: 10px 14px;
      font-size: 12px;
      font-family: 'JetBrains Mono', monospace;
      color: #484f58;
      border-top: 0.5px solid rgba(255,255,255,0.06);
    }

    /* ── CONTRIBUTIONS ── */
    .contrib-section { margin-bottom: 3rem; }

    .contrib-section img {
      width: 100%;
      border-radius: 12px;
      border: 0.5px solid rgba(255,255,255,0.08);
    }

    /* ── QUOTE ── */
    .quote-section { margin-bottom: 3rem; }

    .quote-block {
      padding: 1.5rem;
      border-left: 2px solid #7F77DD;
      background: #161b22;
      border-radius: 0 8px 8px 0;
    }

    .quote-block img {
      width: 100%;
      border-radius: 6px;
    }

    /* ── FOOTER ── */
    .footer-row {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding-top: 2rem;
      border-top: 0.5px solid rgba(255,255,255,0.08);
      flex-wrap: wrap;
      gap: 12px;
    }

    .footer-note {
      font-size: 12px;
      font-family: 'JetBrains Mono', monospace;
      color: #484f58;
    }

    .footer-note a {
      color: #7F77DD;
      text-decoration: none;
    }

    .copy-btn {
      font-family: 'JetBrains Mono', monospace;
      font-size: 12px;
      padding: 6px 16px;
      border-radius: 6px;
      border: 0.5px solid rgba(255,255,255,0.12);
      background: transparent;
      color: #e6edf3;
      cursor: pointer;
      transition: background 0.15s, border-color 0.15s;
    }

    .copy-btn:hover { background: #161b22; border-color: #AFA9EC; }

    /* ── RESPONSIVE ── */
    @media (max-width: 600px) {
      .hero { grid-template-columns: 1fr; }
      .badge-col { align-items: flex-start; }
      .hero-title { font-size: 26px; }
    }
  </style>
</head>
<body>
<div class="profile-root">

  <!-- HERO -->
  <div class="hero">
    <div>
      <p class="hero-name">// Rd27p · Telkom University</p>
      <h1 class="hero-title">Software Engineer<br><span>in the making.</span></h1>
      <p class="hero-desc">Third-year student passionate about web development — building interactive, visually appealing, and user-centered digital experiences. Focused on leveling up in Frontend development.</p>
    </div>
    <div class="badge-col">
      <div class="status-badge"><span class="dot-online"></span>Open to opportunities</div>
      <div class="status-badge">📍 Bandung, Indonesia</div>
    </div>
  </div>

  <!-- TECH STACK -->
  <div class="tech-section">
    <p class="section-label">// tech stack</p>
    <div class="tech-grid">
      <span class="tech-tag"><span class="dot-sm" style="background:#E34F26"></span>HTML5</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#1572B6"></span>CSS3</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#F7DF1E"></span>JavaScript</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#61DAFB"></span>React</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#38B2AC"></span>Tailwind CSS</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#3670A0"></span>Python</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#239120"></span>C#</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#00599C"></span>C++</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#00ADD8"></span>Go</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#ED8B00"></span>Java</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#5C2D91"></span>.NET</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#6DB33F"></span>Spring</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#4479A1"></span>MySQL</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#4ea94b"></span>MongoDB</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#013243"></span>NumPy</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#150458"></span>Pandas</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#3F4F75"></span>Plotly</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#F24E1E"></span>Figma</span>
      <span class="tech-tag"><span class="dot-sm" style="background:#00C4CC"></span>Canva</span>
    </div>
  </div>

  <!-- GITHUB STATS -->
  <div class="stats-section">
    <p class="section-label">// github stats</p>
    <div class="stats-grid">
      <div class="stat-card">
        <img src="https://github-readme-stats.vercel.app/api?username=Rd27p&theme=transparent&hide_border=true&include_all_commits=false&count_private=false" alt="GitHub Stats" loading="lazy"/>
        <div class="stat-card-label">activity overview</div>
      </div>
      <div class="stat-card">
        <img src="https://nirzak-streak-stats.vercel.app/?user=Rd27p&theme=transparent&hide_border=true" alt="Streak Stats" loading="lazy"/>
        <div class="stat-card-label">streak</div>
      </div>
      <div class="stat-card">
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Rd27p&theme=transparent&hide_border=true&include_all_commits=false&count_private=false&layout=compact" alt="Top Languages" loading="lazy"/>
        <div class="stat-card-label">top languages</div>
      </div>
    </div>
  </div>

  <!-- CONTRIBUTIONS -->
  <div class="contrib-section">
    <p class="section-label">// top contributions</p>
    <img src="https://github-contributor-stats.vercel.app/api?username=Rd27p&limit=5&theme=transparent&combine_all_yearly_contributions=true" alt="Top Contributed Repos" loading="lazy"/>
  </div>

  <!-- QUOTE -->
  <div class="quote-section">
    <p class="section-label">// random dev quote</p>
    <div class="quote-block">
      <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=transparent" alt="Dev Quote" loading="lazy"/>
    </div>
  </div>

  <!-- FOOTER -->
  <div class="footer-row">
    <span class="footer-note">profile views → <a href="https://visitcount.itsvg.in" target="_blank">itsvg.in</a></span>
    <button class="copy-btn" onclick="copyMarkdown()">Copy Markdown ↗</button>
  </div>

</div>

<script>
function copyMarkdown() {
  const md = `# 💫 About Me

Third-year Software Engineering student at Telkom University — passionate about web development, building interactive, visually appealing, and user-centered digital experiences. Focused on leveling up in Frontend development.

---

## 🛠 Tech Stack

\`HTML5\` \`CSS3\` \`JavaScript\` \`React\` \`Tailwind CSS\` \`Python\` \`C#\` \`C++\` \`Go\` \`Java\` \`.NET\` \`Spring\` \`MySQL\` \`MongoDB\` \`NumPy\` \`Pandas\` \`Plotly\` \`Figma\` \`Canva\`

---

## 📊 GitHub Stats

![Stats](https://github-readme-stats.vercel.app/api?username=Rd27p&theme=transparent&hide_border=true&include_all_commits=false&count_private=false)
![Streak](https://nirzak-streak-stats.vercel.app/?user=Rd27p&theme=transparent&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Rd27p&theme=transparent&hide_border=true&include_all_commits=false&count_private=false&layout=compact)

---

## 🏆 Top Contributions

![Contributions](https://github-contributor-stats.vercel.app/api?username=Rd27p&limit=5&theme=transparent&combine_all_yearly_contributions=true)

---

## ✍️ Dev Quote

![Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=transparent)

---

[![Profile Views](https://visitcount.itsvg.in/api?id=Rd27p&icon=0&color=1)](https://visitcount.itsvg.in)
`;
  navigator.clipboard.writeText(md).then(() => {
    const btn = document.querySelector('.copy-btn');
    btn.textContent = 'Copied!';
    setTimeout(() => btn.textContent = 'Copy Markdown ↗', 2000);
  });
}
</script>
</body>
</html>
