<h1 align="center">Hi there, I'm a Backend Web Developer 👋</h1>

<p align="center">
  Fokus di pengembangan <b>backend</b> dengan Node.js, Express, dan Prisma. <br/>
  Berpengalaman membangun REST API untuk aplikasi production.
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=DecoPrasetya&label=Profile%20views&color=0e75b6&style=flat" alt="profile views" />
</p>

---

### 🚀 Tentang Saya

- 🔧 Spesialisasi: **Backend Development**
- 🛠️ Sedang membangun REST API dengan **Express + Prisma + TypeScript**
- 📦 Proyek yang pernah dikerjakan:
  - [andantemusik.id](https://andantemusik.id)
  - [harmonyindoraya.com](https://harmonyindoraya.com)
  - [nuasama.com](https://nuasama.com)

---

### 🧰 Tech Stack

**Bahasa & Runtime**

<p align="left">
  <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" title="JavaScript"><img src="https://skillicons.dev/icons?i=js" alt="JavaScript" /></a>
  <a href="https://www.typescriptlang.org/" title="TypeScript"><img src="https://skillicons.dev/icons?i=ts" alt="TypeScript" /></a>
  <a href="https://nodejs.org/" title="Node.js"><img src="https://skillicons.dev/icons?i=nodejs" alt="Node.js" /></a>
</p>

**Backend Framework & Tools**

<p align="left">
  <a href="https://expressjs.com/" title="Express.js"><img src="https://skillicons.dev/icons?i=express" alt="Express.js" /></a>
  <a href="https://www.prisma.io/" title="Prisma"><img src="https://skillicons.dev/icons?i=prisma" alt="Prisma" /></a>
</p>

**Database**

<p align="left">
  <a href="https://www.postgresql.org/" title="PostgreSQL"><img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" /></a>
  <a href="https://www.mysql.com/" title="MySQL"><img src="https://skillicons.dev/icons?i=mysql" alt="MySQL" /></a>
  <a href="https://www.mongodb.com/" title="MongoDB"><img src="https://skillicons.dev/icons?i=mongodb" alt="MongoDB" /></a>
</p>

**Frontend (pendamping)**

<p align="left">
  <a href="https://nextjs.org/" title="Next.js"><img src="https://skillicons.dev/icons?i=nextjs" alt="Next.js" /></a>
  <a href="https://react.dev/" title="React"><img src="https://skillicons.dev/icons?i=react" alt="React" /></a>
</p>

**Tools & Lainnya**

<p align="left">
  <a href="https://git-scm.com/" title="Git"><img src="https://skillicons.dev/icons?i=git" alt="Git" /></a>
  <a href="https://github.com/" title="GitHub"><img src="https://skillicons.dev/icons?i=github" alt="GitHub" /></a>
  <a href="https://code.visualstudio.com/" title="VS Code"><img src="https://skillicons.dev/icons?i=vscode" alt="VS Code" /></a>
  <a href="https://www.postman.com/" title="Postman"><img src="https://skillicons.dev/icons?i=postman" alt="Postman" /></a>
  <a href="https://www.docker.com/" title="Docker"><img src="https://skillicons.dev/icons?i=docker" alt="Docker" /></a>
  <a href="https://www.npmjs.com/" title="npm"><img src="https://skillicons.dev/icons?i=npm" alt="npm" /></a>
</p>

---

### 📦 Library & Package Andalan

| Kategori | Package |
|---|---|
| Web Framework | `express` |
| ORM | `@prisma/client`, `prisma` |
| Auth & Security | `bcrypt`, `jsonwebtoken`, `cookie-parser`, `cors` |
| Validasi | `zod`, `express-validator` |
| Konfigurasi | `dotenv` |
| Dev Tools | `nodemon`, `tsx`, `rimraf` |

---

### ⚙️ Setup Cepat (Backend Init)

```bash
function backend-init {
	mkdir backend;
	cd backend;
	npm init -y;
	npm i express cors bcrypt cookie-parser zod express-validator jsonwebtoken dotenv @prisma/client@6;
	npm i -D prisma@6 nodemon rimraf tsx @types/bcrypt @types/jsonwebtoken @types/cookie-parser @types/cors @types/express;
	npx prisma init;
	npm pkg set scripts.start="node dist/server.js";
	npm pkg set scripts.dev="tsx watch src/server";
	npm pkg set scripts.clean="rimraf dist";
	npm pkg set scripts.build="npm run clean && tsc";
	npm pkg set scripts.seed="tsx prisma/seed.ts";
	mkdir src
}
```

---

### 📊 Stats

<head>
<meta charset="UTF-8">
<title>Kemana Perginya Waktuku</title>
<style>
  body {
    margin: 0;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #0d1117;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
  }
  .card {
    background: #161b22;
    border: 1px solid #30363d;
    border-radius: 16px;
    padding: 32px 40px;
    display: flex;
    align-items: center;
    gap: 36px;
    box-shadow: 0 8px 24px rgba(0,0,0,0.4);
  }
  h1 {
    color: #e6edf3;
    font-size: 18px;
    margin: 0 0 20px 0;
    text-align: center;
  }
  .chart-wrap {
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  .legend {
    display: flex;
    flex-direction: column;
    gap: 12px;
  }
  .legend-item {
    display: flex;
    align-items: center;
    gap: 10px;
    color: #c9d1d9;
    font-size: 14px;
  }
  .dot {
    width: 28px;
    height: 28px;
    border-radius: 8px;
    flex-shrink: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 16px;
  }
  .pct {
    font-weight: 700;
    color: #f0f6fc;
    margin-left: auto;
    padding-left: 16px;
  }
  svg { filter: drop-shadow(0 4px 10px rgba(0,0,0,0.35)); }
  .slice { transition: transform 0.2s ease; transform-origin: 150px 150px; cursor: pointer; }
  .slice:hover { transform: scale(1.04); }
  .center-label {
    fill: #e6edf3;
    font-size: 13px;
    text-anchor: middle;
  }
</style>
</head>
<body>
  <div class="card">
    <div class="chart-wrap">
      <h1>🥧 Kemana Perginya Waktuku</h1>
      <svg viewBox="0 0 300 300" width="300" height="300">
        <path class="slice" d="M150,150 L150,30 A120,120 0 1,1 35.873,112.918 Z" fill="#3178c6"/>
        <path class="slice" d="M150,150 L35.873,112.918 A120,120 0 0,1 79.466,52.918 Z" fill="#f2c14e"/>
        <path class="slice" d="M150,150 L79.466,52.918 A120,120 0 0,1 112.918,35.873 Z" fill="#3fb950"/>
        <path class="slice" d="M150,150 L112.918,35.873 A120,120 0 0,1 150,30 Z" fill="#8b949e"/>
        <circle cx="150" cy="150" r="55" fill="#161b22"/>
        <text x="150" y="146" class="center-label" font-size="15" font-weight="700">Distribusi</text>
        <text x="150" y="164" class="center-label">Waktu Harian</text>
      </svg>
    </div>
    <div class="legend">
      <div class="legend-item"><span class="dot" style="background:#3178c6">🔷</span>TypeScript<span class="pct">80%</span></div>
      <div class="legend-item"><span class="dot" style="background:#f2c14e">🍜</span>Mie Ayam<span class="pct">10%</span></div>
      <div class="legend-item"><span class="dot" style="background:#3fb950">💰</span>Uang<span class="pct">5%</span></div>
      <div class="legend-item"><span class="dot" style="background:#8b949e">📦</span>Lain-lain<span class="pct">5%</span></div>
    </div>
  </div>
</body>
</html>

---

### 📫 Kontak Saya

<p align="left">
  <a href="mailto:decoakbar30@gmail.com"><img src="https://skillicons.dev/icons?i=gmail" alt="email" /></a>
  <a href="https://linkedin.com/in/deco-prasetya-446945374"><img src="https://skillicons.dev/icons?i=linkedin" alt="linkedin" /></a>
  <a href="https://instagram.com/decomposisi"><img src="https://skillicons.dev/icons?i=instagram" alt="instagram" /></a>
</p>
