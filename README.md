<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=190&section=header&text=Leon%20Wydra&fontSize=52&fontColor=ffffff&fontAlignY=34&desc=Full-Stack%20Engineer%20%C2%B7%20TypeScript%20from%20the%20data%20model%20to%20the%20interface&descAlignY=56&descSize=17" width="100%" alt="Leon Wydra — Full-Stack Engineer" />

<a href="https://readme-typing-svg.demolab.com">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=900&color=3178C6&center=true&vCenter=true&width=620&lines=SvelteKit+%2B+Supabase+%2B+Capacitor;Next.js+%2B+NestJS+%2B+PostgreSQL;Hybrid+RAG+search+over+pgvector;Row+Level+Security+enforced+in+the+database" alt="SvelteKit + Supabase + Capacitor · Next.js + NestJS + PostgreSQL · Hybrid RAG search over pgvector" />
</a>

<br />

<a href="https://www.linkedin.com/in/leon-wydra/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://notebook.dmn-software.com"><img src="https://img.shields.io/badge/NotebookLM_clone-3FCF8E?style=for-the-badge&logo=googledocs&logoColor=white" alt="NotebookLM clone — live" /></a>
<a href="https://minigames.dmn-software.com"><img src="https://img.shields.io/badge/Minigames-FF6B00?style=for-the-badge&logo=gamejolt&logoColor=white" alt="Minigames — live" /></a>

</div>

---

## Who I am

I build web applications in TypeScript across the whole stack — schema, API, interface, deployment.
Lately that means **SvelteKit and Supabase**, shipped as a real product to real users rather than a
prototype. I like the systems where the hard part sits in the data layer: retrieval, access control,
migrations that survive contact with production.

- 🏗️ Currently building a **platform for care professionals** — SvelteKit, Supabase, Capacitor, live as a native iOS and Android app
- 🔍 Side project: a **self-hosted NotebookLM** with hybrid vector + full-text retrieval → [try it](https://notebook.dmn-software.com)
- 🎮 Also running: **twelve minigames** whose leaderboard [cannot be lied to](https://github.com/DMN-Software/dmn_minigame) — the server replays your inputs and computes the score itself
- 🧭 Previously **technical coordination** for an LMS (Laravel/React) and an identity-verification app used by ~130 German public health offices
- 💼 Freelancing as **DMN Software** (sole proprietorship) — client work in Lua, React and Vue
- 📫 Best reached on [LinkedIn](https://www.linkedin.com/in/leon-wydra/)

---

## Tech I reach for

<table>
<tr>
<td valign="top" width="50%">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**

![SvelteKit](https://img.shields.io/badge/SvelteKit-FF3E00?style=flat-square&logo=svelte&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vue](https://img.shields.io/badge/Vue-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</td>
<td valign="top" width="50%">

**Backend & data**

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)

**Platform**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

</td>
</tr>
</table>

---

## Selected work

### 📓 [notebooklm-clone](https://github.com/Demonisreal/notebooklm-clone) &nbsp;·&nbsp; [live demo ↗](https://notebook.dmn-software.com)

> Upload your sources, chat with them, and trace every sentence of the answer back to the passage it came from.

A self-hosted NotebookLM. The interesting part is not the chat window — it is the retrieval path,
and the fact that authorisation is enforced by the database rather than by the API layer.

|  |  |
|---|---|
| **Retrieval** | Hybrid search — vector similarity *and* full text, merged with Reciprocal Rank Fusion ([write-up](https://github.com/Demonisreal/notebooklm-clone/blob/main/docs/hybrid-search.md)) |
| **Citations** | Numbered, clickable, scroll straight to the highlighted passage in the source |
| **Security** | Row Level Security in Postgres; the browser never touches the database directly |
| **Ingestion** | PDF, DOCX, TXT, Markdown, URLs, pasted text — processed in the background, status streamed over Supabase Realtime |
| **Studio** | Generated briefings, FAQs, study guides, mind maps and AI-voiced audio overviews |
| **Stack** | Next.js 16 · NestJS 11 · PostgreSQL 17 + pgvector 0.8 · Supabase · Gemini · Tailwind 4 |

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![MIT](https://img.shields.io/badge/License-MIT-informational?style=flat-square)

### 🎮 [dmn_minigame](https://github.com/DMN-Software/dmn_minigame) &nbsp;·&nbsp; [play it ↗](https://minigames.dmn-software.com)

> Twelve minigames with a leaderboard that cannot be lied to.

A browser leaderboard is normally an invitation — `POST /score {"score": 999999}`. The usual
defences still validate a number the client made up. Here that number does not exist: the client
submits **the inputs it pressed**, and the server replays the run to compute the score itself.

|  |  |
|---|---|
| **Anti-cheat** | Server-issued seed, client returns a delta-compressed input log, `replay()` produces the score — no score ever crosses the wire |
| **Determinism** | Hand-rolled mulberry32 PRNG instead of `Math.random`, fixed 60 Hz ticks, no wall clock, no transcendental maths — client and server must agree bit for bit |
| **One contract** | Every game is a `Sim` with `step(input)`, `score`, `over`. The UI only draws; the API never draws |
| **Privacy** | IPs are only ever stored and rate-limited as `sha256(ip + salt)`; `trustProxy` deliberately scoped so `X-Forwarded-For` cannot be spoofed |
| **Lean by choice** | 2 prod dependencies in the API, 2 in the frontend, `node:sqlite` from the standard library, no ORM, no build step on the server |

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Source available](https://img.shields.io/badge/Source-available-lightgrey?style=flat-square)

---

## Where I have shipped

|  | Role | What it was | Stack |
|---|---|---|---|
| **Now** | Full-Stack Developer | Platform for care professionals — in daily use, shipped as a native iOS and Android app | SvelteKit · Supabase · Capacitor |
| **Before** | Technical coordination | Learning management system | Laravel · React |
| **Before** | Technical coordination | Identity-verification app running at ~130 public health offices across Germany | Laravel · React |
| **Alongside** | Owner, DMN Software | Individual client projects | Lua · React · Vue |

---

## How I work

- **The schema comes first.** Constraints, foreign keys and Row Level Security in the database, so a bug in the API layer cannot turn into a data leak.
- **Ship it, then read the logs.** The care platform went to the store and gets used every day; that feedback beats any staging environment.
- **Write down the parts that are hard to re-derive.** Why the retrieval is hybrid, why RRF and not a weighted score — [that kind of thing](https://github.com/Demonisreal/notebooklm-clone/blob/main/docs/hybrid-search.md).
- **One codebase, both platforms.** Capacitor over a separate Swift and Kotlin app, as long as the product does not need the difference.

---

<div align="center">

### Open to interesting work

Product engineering in TypeScript — ideally somewhere the database is treated as part of the design.

<a href="https://www.linkedin.com/in/leon-wydra/"><img src="https://img.shields.io/badge/Let%27s_talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Let's talk on LinkedIn" /></a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=110&section=footer" width="100%" alt="" />

</div>
