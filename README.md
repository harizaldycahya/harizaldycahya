
<h2 class="sr-only">Preview GitHub profile README untuk fullstack developer</h2>
<style>
  .tab-bar { display: flex; gap: 0; border-bottom: 0.5px solid var(--color-border-tertiary); margin-bottom: 0; }
  .tab { padding: 10px 18px; font-size: 13px; cursor: pointer; color: var(--color-text-secondary); border-bottom: 2px solid transparent; background: transparent; border-top: none; border-left: none; border-right: none; }
  .tab.active { color: var(--color-text-primary); border-bottom: 2px solid var(--color-text-primary); font-weight: 500; }
  .panel { display: none; }
  .panel.active { display: block; }
  .preview-wrap { background: var(--color-background-secondary); border-radius: var(--border-radius-lg); padding: 1.5rem; margin-top: 12px; }
  .gh-name { font-size: 22px; font-weight: 500; color: var(--color-text-primary); margin: 0 0 4px; }
  .gh-sub { font-size: 14px; color: var(--color-text-secondary); margin: 0 0 16px; }
  .badge-row { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 16px; }
  .gh-badge { height: 22px; border-radius: 4px; display: inline-flex; align-items: center; padding: 0 10px; font-size: 11px; font-weight: 500; gap: 6px; }
  .b-laravel { background: #FF2D20; color: #fff; }
  .b-next { background: #000; color: #fff; }
  .b-express { background: #2C2C2A; color: #fff; }
  .b-mysql { background: #00618A; color: #fff; }
  .b-php { background: #4F5D95; color: #fff; }
  .b-js { background: #F7DF1E; color: #412402; }
  .b-ts { background: #3178C6; color: #fff; }
  .b-tailwind { background: #06B6D4; color: #fff; }
  .gh-section-label { font-size: 11px; font-weight: 500; text-transform: uppercase; letter-spacing: 0.06em; color: var(--color-text-secondary); margin: 16px 0 8px; }
  .stat-row { display: flex; gap: 8px; flex-wrap: wrap; margin-bottom: 12px; }
  .stat-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 10px 14px; flex: 1; min-width: 120px; }
  .stat-num { font-size: 18px; font-weight: 500; color: var(--color-text-primary); }
  .stat-lbl { font-size: 11px; color: var(--color-text-secondary); }
  .info-row { display: flex; flex-wrap: wrap; gap: 16px; margin-bottom: 12px; }
  .info-item { font-size: 13px; color: var(--color-text-secondary); display: flex; align-items: center; gap: 5px; }
  .dot { width: 6px; height: 6px; border-radius: 50%; background: var(--color-text-tertiary); flex-shrink: 0; }
  .divider { border: none; border-top: 0.5px solid var(--color-border-tertiary); margin: 14px 0; }
  .code-wrap { background: var(--color-background-secondary); border-radius: var(--border-radius-lg); padding: 12px 14px; margin-top: 12px; font-family: var(--font-mono); font-size: 11.5px; color: var(--color-text-primary); overflow-x: auto; white-space: pre; line-height: 1.8; }
  .copy-btn { background: transparent; border: 0.5px solid var(--color-border-secondary); border-radius: var(--border-radius-md); padding: 7px 14px; font-size: 13px; color: var(--color-text-primary); cursor: pointer; margin-top: 10px; }
  .copy-btn:hover { background: var(--color-background-secondary); }
  .note { font-size: 12px; color: var(--color-text-secondary); margin-top: 10px; line-height: 1.6; }
  .highlight { background: #FAEEDA; color: #633806; padding: 1px 6px; border-radius: 4px; font-size: 11.5px; font-family: var(--font-mono); }
</style>

<div style="padding: 1rem 0;">

<div class="tab-bar">
  <button class="tab active" onclick="switchTab('preview')">Preview</button>
  <button class="tab" onclick="switchTab('code')">Kode README</button>
</div>

<div id="tab-preview" class="panel active">
  <div class="preview-wrap">
    <p class="gh-name">Halo! Saya seorang Fullstack Developer 👋</p>
    <p class="gh-sub">Membangun web apps yang cepat, scalable, dan mudah dipelihara — dari database sampai UI.</p>

    <div class="info-row">
      <span class="info-item"><span class="dot"></span>Jakarta, Indonesia</span>
      <span class="info-item"><span class="dot"></span>Terbuka untuk kolaborasi & freelance</span>
      <span class="info-item"><span class="dot"></span>Sedang belajar: Docker & CI/CD</span>
    </div>

    <hr class="divider">
    <div class="gh-section-label">Tech stack</div>
    <div class="badge-row">
      <span class="gh-badge b-laravel">Laravel</span>
      <span class="gh-badge b-next">Next.js</span>
      <span class="gh-badge b-express">Express.js</span>
      <span class="gh-badge b-mysql">MySQL</span>
      <span class="gh-badge b-php">PHP</span>
      <span class="gh-badge b-js">JavaScript</span>
      <span class="gh-badge b-ts">TypeScript</span>
      <span class="gh-badge b-tailwind">Tailwind CSS</span>
    </div>

    <hr class="divider">
    <div class="gh-section-label">GitHub stats</div>
    <div class="stat-row">
      <div class="stat-card">
        <div class="stat-num">⭐ Stats</div>
        <div class="stat-lbl">github-readme-stats widget</div>
      </div>
      <div class="stat-card">
        <div class="stat-num">🔥 Streak</div>
        <div class="stat-lbl">streak-stats widget</div>
      </div>
      <div class="stat-card">
        <div class="stat-num">📊 Langs</div>
        <div class="stat-lbl">top languages widget</div>
      </div>
    </div>
    <p style="font-size: 12px; color: var(--color-text-secondary); margin: 4px 0 0;">Widget di atas akan tampil sebagai gambar dinamis di GitHub, diisi otomatis dari data akun-mu.</p>
  </div>
</div>

<div id="tab-code" class="panel">
  <div class="code-wrap" id="readme-code">## Halo! Saya seorang Fullstack Developer 👋

Saya membangun web apps yang cepat, scalable, dan mudah dipelihara —
dari database sampai tampilan UI.

- 📍 Jakarta, Indonesia
- 💼 Terbuka untuk kolaborasi & freelance
- 🌱 Sedang belajar: Docker & CI/CD
- 📫 Hubungi saya: **email@kamu.com**

---

### 🛠️ Tech Stack

**Backend**

![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=flat&logo=express&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-4F5D95?style=flat&logo=php&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat&logo=tailwind-css&logoColor=white)

**Database & Tools**

![MySQL](https://img.shields.io/badge/MySQL-00618A?style=flat&logo=mysql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

---

### 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=USERNAME&show_icons=true&theme=tokyonight&hide_border=true)

![GitHub Streak](https://streak-stats.demolab.com?user=USERNAME&theme=tokyonight&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=USERNAME&layout=compact&theme=tokyonight&hide_border=true)

---

### 🤝 Terhubung dengan saya

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/USERNAME)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white)](https://instagram.com/USERNAME)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=vercel&logoColor=white)](https://portfoliokamu.com)
</div>
  <button class="copy-btn" onclick="copyCode()">Salin kode</button>
  <p class="note">Ganti semua <span class="highlight">USERNAME</span> dengan username GitHub-mu. Ganti juga email, link LinkedIn, Instagram, dan portfolio sesuai milikmu.</p>
</div>

</div>

<script>
function switchTab(name) {
  document.querySelectorAll('.tab').forEach(t => t.classList.remove('active'));
  document.querySelectorAll('.panel').forEach(p => p.classList.remove('active'));
  event.target.classList.add('active');
  document.getElementById('tab-' + name).classList.add('active');
}
function copyCode() {
  const text = document.getElementById('readme-code').innerText;
  navigator.clipboard.writeText(text).then(() => {
    const btn = document.querySelector('.copy-btn');
    btn.textContent = 'Tersalin!';
    setTimeout(() => btn.textContent = 'Salin kode', 2000);
  });
}
</script>
