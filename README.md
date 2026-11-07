<h1 align="center">Hi, I'm Jeffrey Yellowman</h1>

<p align="center">
  <b>Full-stack engineer</b> · I build the tools I use every day, then self-host them
</p>

<p align="center">
  <a href="https://jeffrey0117.github.io/"><b>📖 Project pages</b></a> ·
  <a href="https://jeffrey0117.github.io/SpeakSlow/">SpeakSlow</a> ·
  <a href="https://www.npmjs.com/package/newebpay-kit">npm</a>
</p>

<div align="center">

![GitHub chart](https://ghchart.rshah.org/Jeffrey0117)

</div>

---

## Start here

| Project | What it is |
|---------|------------|
| [**SpeakSlow 聲聲慢**](https://github.com/Jeffrey0117/SpeakSlow) · [site](https://jeffrey0117.github.io/SpeakSlow/) | The fastest local voice input built for Chinese. 100% on-device, free and open source — talk, and the text lands at your cursor. |
| [**ClaudeBot**](https://github.com/Jeffrey0117/ClaudeBot) | A command center on your phone for Claude Code — Telegram bot with plugins, multi-bot, queue, streaming and hot-reload. |
| [**newebpay-kit**](https://github.com/Jeffrey0117/newebpay-kit) · [site](https://jeffrey0117.github.io/newebpay-kit/) | Zero-dependency Node SDK for NewebPay (藍新金流), including recurring credit-card billing. `npm i newebpay-kit` |
| [**Pokkit**](https://github.com/Jeffrey0117/Pokkit) · [site](https://jeffrey0117.github.io/pokkit/) | Your own cloud drive — share links with password and expiry, chunked uploads for big files, per-project API keys. |

---

## The self-hosted ecosystem

50+ services I run myself, deployed by `git push` and controlled from one Telegram bot. Projects without a link are private for now; the ones with a **site** have a full intro page.

```
CloudPipe (deploy platform, private)
├── Auth & Payments ── LetMeUse · PayGate · newebpay-kit · paywall-kit
├── Data & Storage ─── Selfize · SelfBase · Pokkit
├── Content & AI ───── ReelScript · ReelMaker · Workr · RawTxt
└── Apps ───────────── takeENGLISH · PDFluv · Tunebox · Makee
```

### Auth & Payments

| Project | Description |
|---------|-------------|
| [**LetMeUse**](https://github.com/Jeffrey0117/LetMeUse) | Auth-as-a-service — drop-in login widget, per-app users, cross-app SSO |
| **PayGate** · [site](https://jeffrey0117.github.io/paygate/) | One checkout for every product — subscriptions, renewals, auto-downgrade on expiry, webhooks with retry |
| [**newebpay-kit**](https://github.com/Jeffrey0117/newebpay-kit) · [site](https://jeffrey0117.github.io/newebpay-kit/) | NewebPay SDK — MPG checkout, recurring mandates, notify decryption |
| [**paywall-kit**](https://github.com/Jeffrey0117/paywall-kit) | Tier gates, quotas, upgrade paths and pricing-page templates for SaaS |
| [**skills**](https://github.com/Jeffrey0117/skills) · [**cli**](https://github.com/Jeffrey0117/cli) | Taiwan payment gateway skills for AI agents, and a CLI (NewebPay, ECPay, PAYUNi) |

### Data & Storage

| Project | Description |
|---------|-------------|
| [**Selfize**](https://github.com/Jeffrey0117/Selfize) · [site](https://jeffrey0117.github.io/selfize/) | Self-hosted SQLite REST API with dynamic collections — like PocketBase, but Node.js |
| [**SelfBase**](https://github.com/Jeffrey0117/SelfBase) · [site](https://jeffrey0117.github.io/selfbase/) | PostgreSQL backup, restore and retention + Redis health, behind one small API |
| [**Pokkit**](https://github.com/Jeffrey0117/Pokkit) · [site](https://jeffrey0117.github.io/pokkit/) | Self-hosted cloud drive and file API |
| [**chunked-upload-kit**](https://github.com/Jeffrey0117/chunked-upload-kit) | Resumable chunked uploads that get past proxy body limits (e.g. Cloudflare 100 MB) |

### Content, Video & AI

| Project | Description |
|---------|-------------|
| [**ReelMaker**](https://github.com/Jeffrey0117/ReelMaker) | Video production — mind-map scripts, storyboards, recording, teleprompter |
| [**Workr**](https://github.com/Jeffrey0117/Workr) | Job queue for background work (thumbnails, transcoding, async tasks) |
| [**RawTxt**](https://github.com/Jeffrey0117/RawTxt) | Paste text, get a URL, feed it to an LLM |
| [**pdfluv2**](https://github.com/Jeffrey0117/pdfluv2) | Drop in an English PDF, get back a typeset Chinese one |
| [**takeenglish**](https://github.com/Jeffrey0117/takeenglish) | Search English phrases and watch them spoken in real film clips |
| [**Ytify**](https://github.com/Jeffrey0117/Ytify) | Self-hosted YouTube download server |
| [**Sherpa_ASR**](https://github.com/Jeffrey0117/Sherpa_ASR) | Offline Chinese ASR — Paraformer + 2× speedup + VAD + punctuation |
| [**meei**](https://github.com/Jeffrey0117/meei) | One API for DeepSeek, OpenAI, Gemini, Qwen and Groq |

### Desktop apps

| Project | Description |
|---------|-------------|
| [**RePic**](https://github.com/Jeffrey0117/RePic) · [**ReVid**](https://github.com/Jeffrey0117/ReVid) | Image and video viewers with spatial crop — auto-updating sibling apps |
| [**MemoryGuy**](https://github.com/Jeffrey0117/MemoryGuy) | System resource monitor with memory-leak detection |
| [**better-agent-terminal2**](https://github.com/Jeffrey0117/better-agent-terminal2) | Multi-workspace terminal with Claude Code integration |
| [**PyClick**](https://github.com/Jeffrey0117/PyClick) | Image-recognition auto-clicker for Windows |
| [**whereismywindow**](https://github.com/Jeffrey0117/whereismywindow) | Multi-monitor focused-window tracker (Rust) |

---

## Kits — reusable, zero-dependency building blocks

Cross-cutting pieces pulled out of real projects, managed by [**kit-kit**](https://github.com/Jeffrey0117/kit-kit) (the kit that makes kits). Fix a kit once and every project gets it.

| Kit | Does |
|-----|------|
| [auth-kit](https://github.com/Jeffrey0117/auth-kit) | PBKDF2 password hashing + HMAC JWT, timing-safe |
| [ratelimit-kit](https://github.com/Jeffrey0117/ratelimit-kit) | Sliding-window rate limit per key |
| [retry-kit](https://github.com/Jeffrey0117/retry-kit) | Exponential backoff for fetch / any async |
| [media-gate](https://github.com/Jeffrey0117/media-gate) | Signed tokens and HLS auth so media can't be hot-linked past a paywall |
| [funnel-kit](https://github.com/Jeffrey0117/funnel-kit) | First-party conversion funnel analytics on SQLite |
| [supabase-guard](https://github.com/Jeffrey0117/supabase-guard) | Scans Supabase with the anon key for RLS leaks, blocks the push |
| [claude-session-kit](https://github.com/Jeffrey0117/claude-session-kit) | Persistent Claude Agent SDK sessions for prompt-cache efficiency |
| [blocks-kit](https://github.com/Jeffrey0117/blocks-kit) | Cross-project UI block vault — harvest and seed components |

---

## Dev environment

| Project | Description |
|---------|-------------|
| [**DevFault**](https://github.com/Jeffrey0117/DevFault) | Rebuild your whole dev environment with one command |
| [**ZeroSetup**](https://github.com/Jeffrey0117/ZeroSetup) | One-click installers for any GitHub project |
| [**smart-install**](https://github.com/Jeffrey0117/smart-install) | npm install that survives native-binary postinstall failures |
| [**cmdx**](https://github.com/Jeffrey0117/cmdx) · [**wcmd**](https://github.com/Jeffrey0117/wcmd) · [**winbat**](https://github.com/Jeffrey0117/winbat) | Linux commands on Windows, Windows commands on Linux, and my Windows CLI toolkit |

<details>
<summary>Userscripts, small tools and older experiments</summary>

| Project | Description |
|---------|-------------|
| [tampermonkey-lurl-download](https://github.com/Jeffrey0117/tampermonkey-lurl-download) | One-click media downloads from lurl.cc |
| [tampermonkey-xpost-card](https://github.com/Jeffrey0117/tampermonkey-xpost-card) | Translate X posts to Chinese as a highlight card |
| [tampermonkey-md-copy](https://github.com/Jeffrey0117/tampermonkey-md-copy) | Ctrl + right click → copy link as `[text](url)` |
| [OG-og](https://github.com/Jeffrey0117/OG-og) | Paste a URL, pick a template, export a 1200×630 OG image |
| [igcrop](https://github.com/Jeffrey0117/igcrop) | Drag a frame, get IG-perfect crops |
| [areyoubot](https://github.com/Jeffrey0117/areyoubot) | Self-hosted proof-of-work CAPTCHA |
| [ver2](https://github.com/Jeffrey0117/ver2) | Auto `?v=hash` cache-busting for static HTML |
| [modern-fs](https://github.com/Jeffrey0117/modern-fs) · [modern-crypto](https://github.com/Jeffrey0117/modern-crypto) · [modern-proxy](https://github.com/Jeffrey0117/modern-proxy) | Modern-API Node.js helpers |
| [react-beginner-challenges](https://github.com/Jeffrey0117/react-beginner-challenges) | React interview muscle memory — 30+ drills |

</details>

---

<p align="center">250+ repos · updated 2026-11-07</p>
