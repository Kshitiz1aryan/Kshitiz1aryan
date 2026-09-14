<div align="center">

![Header](https://capsule-render.vercel.app/api?type=waving&color=0:0A101F,100:7C3AED&height=220&section=header&text=Kshitiz%20Aryan&fontSize=48&fontColor=E5E7EB&animation=fadeIn&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20AI%20Engineer%20%7C%20Building%20XYRA&descAlignY=58&descSize=18)

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=A78BFA&center=true&vCenter=true&width=560&lines=Full-Stack+Developer;AI%2FML+Engineer;Building+the+XYRA+Suite;Electron+%2B+Real-Time+Systems" alt="Typing SVG" />
</a>

![B.Tech CSE](https://img.shields.io/badge/B.Tech-CSE-7C3AED?style=flat-square&labelColor=0A101F)
![Location](https://img.shields.io/badge/Location-Jharkhand%2C%20India-22D3EE?style=flat-square&labelColor=0A101F)
[![Portfolio](https://img.shields.io/badge/Portfolio-kshitiz1gg.netlify.app-10B981?style=flat-square&labelColor=0A101F)](https://kshitiz1gg.netlify.app)
[![Email](https://img.shields.io/badge/Email-kshitizaryan007%40gmail.com-EA4335?style=flat-square&labelColor=0A101F&logo=gmail&logoColor=white)](mailto:kshitizaryan007@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-Kshitiz1aryan-181717?style=flat-square&labelColor=0A101F&logo=github&logoColor=white)](https://github.com/Kshitiz1aryan)

![Profile Views](https://komarev.com/ghpvc/?username=Kshitiz1aryan&style=flat-square&color=7C3AED&label=Profile+Views)
![Followers](https://img.shields.io/github/followers/Kshitiz1aryan?style=flat-square&color=7C3AED&labelColor=0A101F)
![Stars](https://img.shields.io/github/stars/Kshitiz1aryan?style=flat-square&color=7C3AED&labelColor=0A101F)

</div>

---

### About Me

I'm a full-stack developer and AI engineer from Jharkhand, India, currently pursuing a B.Tech in Computer Science. I build a suite of interconnected products under my own brand, **XYRA** — spanning encrypted real-time communication, a custom Electron IDE, AI-backed chat and study tools, and Discord ecosystem software.

My work leans toward self-contained, dependency-light builds — I favor single-file architectures where possible, real-time systems (WebRTC, Supabase Realtime), and integrating AI (Groq) into practical tools rather than demos. I care about products that work end-to-end: auth, data security, and UI polish, not just a working prototype.

```yaml
Currently:
  Building: XYRA suite (Xyralyn, Xenon IDE, RPC Studio, landing page)
  Learning: Deeper AI/ML integration, distributed real-time systems
  Open to: Freelance full-stack + AI engineering work
```

---

### Tech Stack

**Languages**
![JavaScript](https://skillicons.dev/icons?i=js) ![TypeScript](https://skillicons.dev/icons?i=ts) ![Python](https://skillicons.dev/icons?i=python) ![HTML5](https://skillicons.dev/icons?i=html) ![CSS3](https://skillicons.dev/icons?i=css)

**Frontend**
![React](https://skillicons.dev/icons?i=react) ![Vite](https://skillicons.dev/icons?i=vite) ![TailwindCSS](https://skillicons.dev/icons?i=tailwind) ![ThreeJS](https://skillicons.dev/icons?i=threejs) ![Electron](https://skillicons.dev/icons?i=electron)

**Backend & Database**
![NodeJS](https://skillicons.dev/icons?i=nodejs) ![Supabase](https://skillicons.dev/icons?i=supabase) ![Firebase](https://skillicons.dev/icons?i=firebase) ![SQLite](https://skillicons.dev/icons?i=sqlite)

**Cloud, DevOps & Tooling**
![Vercel](https://skillicons.dev/icons?i=vercel) ![Netlify](https://skillicons.dev/icons?i=netlify) ![Git](https://skillicons.dev/icons?i=git) ![GitHub](https://skillicons.dev/icons?i=github) ![VSCode](https://skillicons.dev/icons?i=vscode) ![Figma](https://skillicons.dev/icons?i=figma)

---

### AI / ML Expertise

| Domain | Proficiency | Details |
|---|---|---|
| LLM Integration | Advanced | Groq API across chatbots, study tools, and support systems |
| Real-Time AI Chat | Advanced | Streaming responses, multi-session history, markdown rendering |
| Secure API Architecture | Intermediate | Supabase Edge Functions as proxy layers for key rotation/security |
| Applied AI Tooling | Advanced | Built production chatbots (healthcare, study assistant, general-purpose) rather than demos |

---

### Featured Projects

<details>
<summary><b>Xyralyn — Encrypted Real-Time Communication Platform</b></summary>
<br>

Firebase-based encrypted chat application with WebRTC voice/video calling and screen sharing.

| Stack | Scale | Performance | Security | Impact |
|---|---|---|---|---|
| Firebase, WebRTC, JS | Multi-user real-time | Low-latency call/screen-share pipeline | Encrypted messaging | Full peer-to-peer comms platform |

Solved renegotiation issues in screen sharing, group-call overlay rendering, contact search (RLS/GRANT permission issues), and audio routing inside WebRTC `ontrack` handlers.

</details>

<details>
<summary><b>Xenon IDE — Electron-Based Development Environment</b></summary>
<br>

A custom Electron IDE with an in-app browser, encrypted password vault, and a heavily customized UI layer.

| Stack | Scale | Performance | Security | Impact |
|---|---|---|---|---|
| Electron, Monaco, Supabase | Full desktop app | Native-level UI responsiveness | AES-GCM encrypted vault, PBKDF2 key derivation | Personal dev environment with vault, browser, and media system |

Built a multi-tab in-app browser via Electron `<webview>`, per-device sign-in personalization stored in IndexedDB, unified sound settings, and shadcn/magicui-inspired UI components. Resolved sandbox-mode `require()` restrictions by passing paths through `additionalArguments`.

</details>

<details>
<summary><b>NexaCare — Healthcare Chatbot & Admin Portal</b></summary>
<br>

AI-powered healthcare chatbot with a full admin management portal.

| Stack | Scale | Performance | Security | Impact |
|---|---|---|---|---|
| Groq, Supabase Edge Functions, Realtime | Admin + patient-facing | Proxy-secured AI responses | Custom admin table, Discord webhook OTP | Replaced broken auth system, restored chatbot after model deprecation |

Migrated a broken Supabase Auth setup to a custom `admins` table secured with Discord webhook OTP, added Supabase Realtime subscriptions and bulk doctor management, and routed all AI calls through a secure Groq proxy Edge Function.

</details>

<details>
<summary><b>XYRA RPC Studio — Discord Rich Presence Manager</b></summary>
<br>

Electron + React desktop app for managing custom Discord Rich Presence profiles.

| Stack | Scale | Performance | Security | Impact |
|---|---|---|---|---|
| Electron, React, TypeScript | Desktop utility | Auto process detection | Local profile storage | System-tray Rich Presence manager with glassmorphic UI |

</details>

<details>
<summary><b>Aether — AI Chatbot</b></summary>
<br>

Full-featured AI chatbot in a single self-contained HTML file.

| Stack | Scale | Performance | Security | Impact |
|---|---|---|---|---|
| Groq API, Vanilla JS | Single-file deployable | Streaming responses | Client-side session handling | Portable, dependency-free AI chat tool |

Includes multi-session history, streaming responses, markdown rendering, and a model switcher.

</details>

<details>
<summary><b>Xenon Guardian Bot — Discord Moderation & Music Bot</b></summary>
<br>

Discord bot combining music playback with server safety tooling.

| Stack | Scale | Performance | Security | Impact |
|---|---|---|---|---|
| Discord.js, DisTube, SQLite | Multi-server bot | Slash-command driven | Anti-spam, anti-raid, banned-word filtering | Full moderation + logging suite for Discord communities |

Includes an autolog system tracking member, voice, and message events with SQLite persistence.

</details>

<details>
<summary><b>XYRA Landing Page</b></summary>
<br>

Brand landing page for the XYRA product suite.

| Stack | Scale | Performance | Security | Impact |
|---|---|---|---|---|
| Three.js, Single-file HTML | Marketing site | WebGL rendering | N/A | Brand identity front door for the XYRA suite |

Built with a transmissive glass icosahedron, orbiting rings, an aurora background, and orbiting nodes labeled with each XYRA project.

</details>

<details>
<summary><b>Study Assistant</b></summary>
<br>

Groq-backed study tool with a terminal-inspired interface.

| Stack | Scale | Performance | Security | Impact |
|---|---|---|---|---|
| Groq API, JS | Single-page tool | Fast AI responses | N/A | Terminal/hacker-aesthetic study aid with theme switching |

Features a tab system, 3D tilt cards, and a JetBrains Mono terminal aesthetic.

</details>

---

### GitHub Analytics

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com?user=Kshitiz1aryan&theme=dark&hide_border=true&background=0A101F&ring=7C3AED&fire=22D3EE&currStreakLabel=A78BFA)

<img src="https://github-readme-stats.vercel.app/api?username=Kshitiz1aryan&show_icons=true&theme=dark&hide_border=true&bg_color=0A101F&title_color=7C3AED&icon_color=22D3EE&text_color=E5E7EB&hide_rank=true" width="49%" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kshitiz1aryan&layout=compact&theme=dark&hide_border=true&bg_color=0A101F&title_color=7C3AED&text_color=E5E7EB" width="49%" />

</div>

> **Note:** `hide_rank=true` is used deliberately — the star-weighted rank score skews against newer accounts and doesn't reflect actual skill or activity level.

---

### GitHub Trophies

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=Kshitiz1aryan&theme=algolia&no-frame=true&column=7&margin-w=8&margin-h=8)

</div>

---

### Contribution Activity

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=Kshitiz1aryan&theme=react-dark&bg_color=0A101F&color=A78BFA&line=7C3AED&point=22D3EE&hide_border=true)

</div>

---

### Contribution Snake

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Kshitiz1aryan/Kshitiz1aryan/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Kshitiz1aryan/Kshitiz1aryan/output/github-contribution-grid-snake.svg">
  <img alt="Contribution Snake" src="https://raw.githubusercontent.com/Kshitiz1aryan/Kshitiz1aryan/output/github-contribution-grid-snake.svg">
</picture>

</div>

> Add this only after the `snake.yml` Action has run successfully once — the `output` branch doesn't exist before that.

---

### Connect With Me

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0A101F)](mailto:kshitizaryan007@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=0A101F)](https://github.com/Kshitiz1aryan)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0A101F)](https://instagram.com/1ost.kshitiz)
[![Portfolio](https://img.shields.io/badge/Portfolio-10B981?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0A101F)](https://kshitiz1gg.netlify.app)

</div>

---

<div align="center">

*Shipping products end-to-end, not just prototypes.*

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,100:0A101F&height=120&section=footer)

</div>
