# Hi, I'm Mark

App developer, streamer, and photographer with over a decade of experience. I build job-search software, streaming tools, and creative applications.

## Projects

| | Project | What it does |
|:---:|------|------------|
| <img src="assets/icons/pathos.svg" width="44" alt=""> | **[Pathos](https://yourpathos.app)** | Worker-side job search with source-linked roles, evidence-checked resumes, and application tracking. |
| <img src="assets/icons/markskill.svg" width="44" alt=""> | **[Markskill](https://github.com/thedevmark/markskill)** | A product-engineering skill for AI agents: trace behavior to its owner, fix root causes, shape interfaces around real tasks, and verify claims with evidence. |
| <img src="assets/icons/alert-alert.svg" width="39" alt=""> | **[Alert! Alert!](https://github.com/thedevmark/alert-alert)** | Turn a video URL or local file into a cropped, trimmed stream alert. |
| <img src="assets/icons/clipline.svg" width="44" alt=""> | **[Clipline](https://github.com/thedevmark/clipline)** | Turn Twitch VOD moments into captioned vertical clips and compilations. |
| <img src="assets/icons/toolset.svg" width="44" alt=""> | **[The Stream Toolset](https://toolset.deutschmark.online)** | Build OBS scenes and browser-source overlays with connected streamer tools. |
| <img src="assets/icons/forgetmenot.png" width="32" alt=""> | **[ForgetMeNot](https://github.com/thedevmark/forgetmenot)** | A local-first Twitch bot that remembers regulars, callbacks, and stream lore. |
| <img src="assets/icons/film-lab.svg" width="39" alt=""> | **[Film Lab](https://github.com/thedevmark/film-lab)** | Film emulation for JPEG and RAW photos, including a measured Kodak Gold 200 preset, grain, and halation. |

## Pathos Chrome extension

The [Pathos Chrome extension](https://chromewebstore.google.com/detail/ecniiinpnbhcjicagdhipdogcajohdip) fills supported application fields, attaches a reviewed resume for the role, and drafts answers grounded in the candidate's information. It leaves uncertain and sensitive fields for review and lets the candidate submit the application.

## Engineering notes

Selected write-ups from **[engineering-notes](https://github.com/thedevmark/engineering-notes)**:

| Paper | Description | Tech |
|---|---|---|
| [RLS silently disabled my GIN index](https://github.com/thedevmark/engineering-notes/tree/main/rls-fts-planner) | Why anonymous search ignored a GIN index under row-level security, and how the query plan exposed the cause. | PostgreSQL 17, RLS, GIN, tsvector, Supabase |
| [Scaling streaming toolsets on Cloudflare](https://github.com/thedevmark/engineering-notes/tree/main/scaling-streaming-toolsets) | An event-driven overlay architecture using WebSockets for live state and KV for cold persistence. | Cloudflare Workers, KV, Durable Objects, Hibernatable WebSockets, EventSub |
| [Chat bot memory](https://github.com/thedevmark/engineering-notes/tree/main/chat-bot-memory) | Local memory for chatters and running jokes without retaining raw chat logs. | SQLite, Gemini, Twitch |
| [Building Pathos](https://github.com/thedevmark/engineering-notes/tree/main/how-i-built-pathos) | How role discovery, resume safeguards, application tracking, and a review-first extension fit together. | React 19, Vite, Supabase, Cloudflare Workers, Chrome MV3 |
| [Inbound job-status sync](https://github.com/thedevmark/engineering-notes/tree/main/email-sync) | Detecting job-status changes from selected forwarded emails, with uncertain matches held for review. | Supabase Edge Functions, TypeScript, Resend |

## Stack

- **Applications:** TypeScript, JavaScript, React, Vite, Zustand, Chrome Manifest V3
- **Data and infrastructure:** PostgreSQL, Supabase, Cloudflare Pages and Workers, Stripe
- **Media and automation:** Python, C#, FFmpeg, Gemini, Twitch EventSub and Helix, Streamer.bot

## Links

[Website](https://deutschmark.online) · [Portfolio](https://dev.deutschmark.online) · [Twitch](https://twitch.tv/thedeutschmark) · [Discord](https://discord.com/invite/hQEQE9myXX)
