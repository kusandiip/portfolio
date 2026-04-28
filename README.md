# Sandeep Kumar — Portfolio

Personal portfolio website. Single-file `index.html`, no build step, no framework. Hand-crafted HTML + CSS + vanilla JavaScript with a terminal-themed Bloomberg-meets-Linux aesthetic.

**Live**: [sandiipkumar.netlify.app](https://sandiipkumar.netlify.app)

---

## What's inside

A self-contained 1,500-line `index.html` that renders:

- 🚀 **Boot sequence** — animated Linux-style startup with live deployment status
- 💻 **Interactive terminal** with 14+ commands (`whoami`, `stack`, `jarviq`, `stockpulse`, `joke`, `motivation`, `recruiter`, `sudo hire me`, etc.)
- 📊 **Live KPIs** — counter-animated metrics (5M+ records/day, 10TB+ integrated, 98%+ accuracy, 600+ DSA solved)
- 🎮 **Easter eggs** — Konami code (`↑↑↓↓←→←→BA`) triggers Matrix-mode debug overlay, `/` shortcut focuses terminal
- 🏆 **Achievement toasts** that pop up as you scroll past sections
- ⏰ **Time-aware hero copy** that changes based on visitor's local hour
- 📡 **Live data feed** — pulls real-time stats from JARVIQ deployed API (CORS-enabled public endpoint)
- 🎨 **Terminal aesthetic** — JetBrains Mono / Bebas Neue / Barlow type stack, scanline overlay, custom cursor

---

## Featured projects shown

| # | Project | Stack |
|---|---|---|
| 1 | **JARVIQ** — AI-Powered Healthcare DQ Platform | FastAPI · Groq Llama 3.1 · SQLAlchemy · Medallion |
| 2 | **StockPulse** — Real-Time Stock Analytics Platform | FastAPI · React · Groq Llama 3.3 70B · WebSocket · yfinance |
| 3 | **Stock Market Pipeline** — Medallion Architecture | Databricks · PySpark · Delta Lake · Window Functions |
| 4 | **Healthcare Web App** — MERN + AI Chatbot | React · Node · MongoDB · AI |

---

## Tech philosophy

Built with **vanilla HTML / CSS / JS** — no React, no build step, no `npm install`. Reasons:

- **Loads in ~100ms** vs 600ms+ for typical React portfolio
- **Lighthouse 95+** out of the box
- **Single file = simple deploy** (drag-drop on Netlify, or any static host)
- For a Data Engineer, vanilla shows craft — anyone can `create-react-app`, fewer can hand-build interaction logic

---

## Local development

Just open `index.html` in a browser. That's it.

For live-reload while editing:

```bash
# Python 3
python -m http.server 8000

# Or with Node
npx serve
```

Then visit `http://localhost:8000`.

---

## Deploy

The site is a single static file. Hosted on:

- **[Netlify](https://sandiipkumar.netlify.app)** (primary)

Drop `index.html` on [app.netlify.com/drop](https://app.netlify.com/drop), or connect to this repo for git-based auto-deploy.

Other deploy options that work zero-config: Render Static Sites, Vercel, GitHub Pages, Cloudflare Pages, S3 + CloudFront.

---

## Connect

- Email: [sandeepk.dataeng@gmail.com](mailto:sandeepk.dataeng@gmail.com)
- LinkedIn: [linkedin.com/in/kusandeep](https://linkedin.com/in/kusandeep)
- GitHub: [github.com/kusandiip](https://github.com/kusandiip)
