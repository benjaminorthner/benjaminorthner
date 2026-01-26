# Hey, I'm Benjamin 👋

<a href="https://github.com/benjaminorthner" target="_blank">
<img src=https://img.shields.io/badge/github-%2324292e.svg?&style=for-the-badge&logo=github&logoColor=white alt=github style="margin-bottom: 5px;" />
</a>
<a href="https://instagram.com/benjaminorthner" target="_blank">
<img src=https://img.shields.io/badge/instagram-%23000000.svg?&style=for-the-badge&logo=instagram&logoColor=white alt=instagram style="margin-bottom: 5px;" />
</a>

Physics student in Vienna. For the past two months, I've gone completely down the rabbit hole of AI-assisted coding—and I've never been more productive in my life.

<br/>

## The Shift

I used to code as a side hobby between physics lectures. I had this idea for a simple app to coordinate climbing sessions with friends—something I'd been putting off for years because the scope felt too big for a side project.

Then AI coding tools clicked. What was supposed to be a quick MVP for my friend group has grown into a full production-ready app with worldwide ambitions. The tooling has gotten *that* good, and most people have no idea what's becoming possible.

There's this insane urge to create right now, while the window is open. While the tools are powerful but not yet commoditized. While you can still build things that feel like magic.

<br/>

## 🧗 What I'm Building: ClimbSync (Private Repo)

**A mobile app for coordinating climbing gym sessions with friends.**

Built entirely with AI-assisted development (Claude Code, Cursor). What started as "I wish I knew when my friends were climbing" turned into a full production app.

<table>
<tr>
<td width="50%" valign="top">

### Tech Stack
| Layer | Technology |
|-------|------------|
| Frontend | React Native, Expo, TypeScript |
| State | TanStack Query, Zustand |
| UI | React Native Paper (MD3) |
| Backend | Supabase (PostgreSQL 17) |
| Auth | Email, Google, Apple SSO |
| Maps | Mapbox GL + PostGIS |
| i18n | EN, DE, FR, ZH |
| Docs | Mintlify |

</td>
<td width="50%" valign="top">

### Key Features
- 📅 **Calendar View** — Sessions at a glance
- 🗳️ **Time Polls** — Group coordination
- 🔒 **Privacy Controls** — Granular visibility
- 👥 **Friend System** — Requests, blocking, nicknames
- 🗺️ **Gym Discovery** — Interactive map
- 📊 **Activity Heatmap** — GitHub-style stats
- ⚡ **Real-time** — Live updates via Supabase

</td>
</tr>
</table>

**The codebase:** 80k lines TypeScript, 23k lines SQL, 27k lines of documentation—built in 2 months.

**Privacy is enforced at the database layer, not the UI.** RPC functions return different fields based on your relationship to each user (self/friend/stranger/blocked). This was a recent security hardening pass—the kind of architectural decision that AI helps you implement correctly the first time.

<br/>

## 🤖 AI-First Development

**Context. Context. Context.** That's the whole game. Rich project documentation, well-structured skills files, MCP servers that give agents access to your actual systems—this is what separates "AI can't do X" from "I just handed X to an agent and it worked."

The hardest part isn't technical. It's unlearning your assumptions about what's possible. Every time I think "this is too complex to delegate," I'm usually wrong. The bottleneck is having the creative energy to believe something can be handed off—and then actually trying it.

Also, I now mass-refresh my API usage dashboard. AI credit anxiety is real.

<br/>

## Languages and Tools

<div align="center">
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/react-original-wordmark.svg" alt="React" height="50" />
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/typescript-original.svg" alt="TypeScript" height="50" />
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/postgresql-original-wordmark.svg" alt="PostgreSQL" height="50" />
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/python-original.svg" alt="Python" height="50" />
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/git-scm-icon.svg" alt="Git" height="50" />
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/linux-original.svg" alt="Linux" height="50" />
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/cplusplus-original.svg" alt="C++" height="50" />
<img style="margin: 10px" src="https://profilinator.rishav.dev/skills-assets/latex.png" alt="LaTeX" height="50" />
</div>

<br/>

## Other Projects

### [QQuant Learn](https://github.com/benjaminorthner/qquant-learn) — [Live Demo](https://q-quant.vercel.app/)

Interactive web app for learning quantitative finance. Built in a day with Claude Code to help my girlfriend study for her Quant Finance exam. Turns lecture slides full of formulas into hands-on calculators where you drag sliders and watch things update in real-time. Bonds, portfolio theory, CAPM, efficient frontiers—all running in the browser.

<br/>

![Profile views counter](https://komarev.com/ghpvc/?username=benjaminorthner&&style=flat-square)

---

<sub>Last updated January 2026. If you're reading this from the future, things have probably gotten even weirder.</sub>
