# Nicolas Mateus

**Full-stack developer from Brazil.**<br />
I build local-first AI tools, desktop apps and product web apps — things that run on your machine instead of someone else's cloud.

## About me

- 🖥️ Right now: **GoLive LAN**, peer-to-peer 1080p60 screen sharing over your own LAN — built because Discord's Go Live got suspended in Brazil in August 2026.
- 🛒 Alongside it, **Primeira Venda**, a desktop app that runs AI locally (Ollama + Qwen3-VL) to write product listings from a photo, track real profit per marketplace, and chase down suppliers for small online sellers.
- 🎭 Also shipping **cosplay-decide** (recommends characters to cosplay from a few photos, then generates you dressed as the one you pick) and **sales-ai** (forecasts whether sales are trending up or down, per channel and region).
- 🔬 Before that, **MangaLens** — cuts a manga/anime character into animatable layers from a plain-language prompt, entirely on-device.
- 🧰 Day to day that means **Python** for anything with a model in it, **TypeScript/React/Next.js** on the front, **Node/Bun/Electron** behind it, and local-first storage (SQLite, Markdown, your own GPU) over a cloud dependency whenever that's an option.
- 🦈 Built a *Sharks from Space* entry for the 2025 Space Apps Challenge.
- 📫 Reach me at **nicolasmateusdecastrosilva@gmail.com**

---

## Agora

### [GoLive LAN](https://github.com/NickB0ss/golive) · [site](https://github.com/NickB0ss/golive-website)
Screen sharing in 1080p60 between friends, PC to PC over a virtual LAN (Radmin VPN or Tailscale). No cloud server, no account, nobody in the middle watching the stream — built the week Discord's Go Live got suspended in Brazil.

`TypeScript` `Node.js` `Native addon (C++)`

### Primeira Venda *(private)*
Desktop app for running a one-person online store: photograph the product and a local AI researches competitors and writes the listing, pulls in sales from each marketplace, computes real profit after fees, chases suppliers, and keeps a "second brain" of notes in Markdown. The AI (Ollama + Qwen3-VL) runs entirely on the user's machine, swappable for Claude's API if they want sharper answers.

`TypeScript` `Electron` `SQLite` `Ollama`

### [cosplay-decide](https://github.com/NickB0ss/cosplay-decide)
Local app that reads a few photos of a person, recommends characters to cosplay across two lists (wig-only vs. full look), and generates an image of them dressed as whichever one they pick. A vision-language model builds the character catalog offline; an image model does the generation — the two never run at once, so they don't fight over VRAM.

`Python` `VLM` `SDXL`

### sales-ai *(private)*
Forecasts whether sales are trending up or down over the next week and month, broken out by sales channel and region, from ~885k rows of transaction history. Same web UI handles training new models and showing predictions with a confidence level.

`Python` `Pandas` `Scikit-learn`

---

## Produtos & sites

### portfolio-nubinho *(v2 public, v3 in progress — private)*
A Persona 3 Reload-styled portfolio for a motion designer — a stylized hub screen linking to real routes (works, reel, about, contact), with an admin panel that publishes content straight to the repo via the GitHub API.

`Next.js` `TypeScript` `Playwright`

### estantedemanga *(private)*
Manga collection tool in Portuguese: which edition to buy, what's missing from your shelf, where each story arc starts and ends, and how hard each volume is to find. Static Next.js site monetized through Amazon Associates.

`Next.js` `TypeScript` `Vitest`

### plurall-tutor *(private)*
Chrome extension that reads the question open on Plurall, sends it to a model on Groq's API, and shows the reasoning behind each answer choice in a side panel — deliberately never fills in or submits an answer itself.

`TypeScript` `Chrome Extension (MV3)` `Groq API`

### [InvestHub](https://github.com/NickB0ss/investhub) · [live](https://investhub-navigator.vercel.app)
Portfolio tracker for Brazilian stocks. Average price, profit/loss and ROI per position, real-time market data, operation history and JWT auth on a serverless API.

`React` `TypeScript` `Vite` `Express` `MongoDB`

### [ecommerce-hair](https://github.com/NickB0ss/ecommerce-hair) · [live](https://ecommerce-hair-frontend.vercel.app)
Decoupled e-commerce monorepo: an Express + Supabase REST API, a React storefront, and a separate admin panel for products, categories and users.

`React` `TypeScript` `Express` `Supabase` `Tailwind`

### [nutri4kids](https://github.com/NickB0ss/nutri4kids-one-landing-page) · [live](https://nutri4kids-one-landing-page.vercel.app)
Single-page landing built for a nutrition brand.

`TypeScript` `React` `Tailwind`

---

## Antes disso

- **MangaLens** *(private)* — open-vocabulary detection (Grounding DINO) into pixel-level segmentation (SAM) to cut a character into layers, with hardware profiles down to a 4GB GPU. `Python` `FastAPI` `PyTorch` `OpenCV`
- **[AgentScope](https://github.com/NickB0ss/agentscope)** — observability for AI agents: prompts, responses, execution flow, tool calls, token usage, cost and errors. `Bun` `TypeScript` `PostgreSQL` `Docker`
- **[morse-training](https://github.com/NickB0ss/morse-training)** — client-side trainer for receiving and sending Morse code, with wrist-timing analysis. `TypeScript` `Vite`
- **sharks-flow** *(private)* — *Sharks from Space* entry for the 2025 Space Apps Challenge. `Python`

---

## Tech I reach for

<div>
  <img align="center" alt="Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
  <img align="center" alt="PyTorch" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pytorch/pytorch-original.svg">
  <img align="center" alt="FastAPI" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/fastapi/fastapi-original.svg">
  <img align="center" alt="OpenCV" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/opencv/opencv-original.svg">
  <img align="center" alt="TypeScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg">
  <img align="center" alt="JavaScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg">
  <img align="center" alt="React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
  <img align="center" alt="Next.js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nextjs/nextjs-original.svg">
  <img align="center" alt="Node.js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
  <img align="center" alt="Bun" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bun/bun-original.svg">
  <img align="center" alt="Electron" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/electron/electron-original.svg">
  <img align="center" alt="PostgreSQL" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg">
  <img align="center" alt="SQLite" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/sqlite/sqlite-original.svg">
  <img align="center" alt="Supabase" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/supabase/supabase-original.svg">
  <img align="center" alt="MongoDB" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg">
  <img align="center" alt="Tailwind CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-original.svg">
  <img align="center" alt="Docker" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg">
  <img align="center" alt="Git" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/git/git-original.svg">
</div>

<br>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/top-langs?username=NickB0ss&layout=compact&langs_count=8&hide_title=true&hide_border=true&card_width=340&bg_color=00000000&text_color=e6edf3" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=NickB0ss&layout=compact&langs_count=8&hide_title=true&hide_border=true&card_width=340&bg_color=00000000&text_color=1f2328" alt="Most used languages" />
</picture>

---

*"Get excited."* — **Senku Ishigami**

<sub>Senku doesn't wait for the world to be ready — he builds the thing from scratch until it exists. Same idea here.</sub>
