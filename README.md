# Hi, I'm Mark

App developer, streamer, photographer. Over a decade of experience. I build at the seam between AI products and live-video infrastructure — the engineering notes below explain the trade-offs behind each project. For recruiting / employment context, see [dev.deutschmark.online](https://dev.deutschmark.online).

| | Tool | What it is |
|:---:|------|------------|
| <img src="assets/icons/pathos.svg" width="44"> | **[Pathos](https://yourpathos.app)** | Worker-side job search: find roles, tailor from real experience, and track applications in one place. |
| <img src="assets/icons/markskill.svg" width="44" alt="Markskill"> | **[Markskill](https://github.com/thedevmark/markskill)** | A product-engineering skill for AI agents: trace behavior to its owner, fix root causes, shape interfaces around real tasks, and verify claims with evidence. |
| <img src="assets/icons/alert-alert.svg" width="39"> | **[Alert! Alert!](https://github.com/thedevmark/alert-alert)** | Make clean stream-alert clips from any video source. |
| <img src="assets/icons/clipline.svg" width="44"> | **[Clipline](https://github.com/thedevmark/clipline)** | Turn livestream VODs into shortform clips with auto-captions. |
| <img src="assets/icons/toolset.svg" width="44"> | **[The Stream Toolset](https://toolset.deutschmark.online)** | OBS overlays + companion apps. One login, no subscriptions. |
| <img src="assets/icons/forgetmenot.png" width="32"> | **[ForgetMeNot](https://github.com/thedevmark/forgetmenot)** | A Twitch chat bot that remembers your regulars. |
| <img src="assets/icons/film-lab.svg" width="39"> | **[Film Lab](https://github.com/thedevmark/film-lab)** | Put a real film look on digital photos — measured Kodak Gold, grain, halation. |

## Pathos Chrome extension

The [Pathos Chrome extension](https://chromewebstore.google.com/detail/ecniiinpnbhcjicagdhipdogcajohdip) fills supported application fields, attaches a reviewed resume for the role, and drafts answers grounded in the candidate's information. It leaves uncertain and sensitive fields for review and lets the candidate submit the application.

## Technical Papers

Some notes on the harder problems I ran into over the years, in **[engineering-notes](https://github.com/thedevmark/engineering-notes)**:



| Paper | Description | Tech |
|---|---|---|
| [RLS silently disabled my GIN index](https://github.com/thedevmark/engineering-notes/tree/main/rls-fts-planner) | A public text search that 500'd for anonymous users only. Row security will not push a non-LEAKPROOF operator below its barrier, `@@` is not one, so the GIN index was refused and every anon search became a 10s seq scan over 87k rows | PostgreSQL 17, RLS, GIN, tsvector, Supabase |
| [Scaling streaming toolsets on Cloudflare](https://github.com/thedevmark/engineering-notes/tree/main/scaling-streaming-toolsets) | Designing a per-user multi-overlay platform so cost-per-user stays roughly flat as you grow — edge push, Hibernatable WebSockets, EventSub | Cloudflare Workers, KV, Durable Objects, Hibernatable WebSockets, EventSub |
| [Chat bot memory](https://github.com/thedevmark/engineering-notes/tree/main/chat-bot-memory) | Persistent memory for a Twitch chat bot without storing raw chat logs | C#, Streamer.bot, Gemini Flash |
| [Building Pathos](https://github.com/thedevmark/engineering-notes/tree/main/how-i-built-pathos) | A worker-side job-search system connecting source-linked roles, evidence-backed resumes, application tracking, and a review-first browser extension | React 19, Vite, Supabase, Cloudflare Workers, Chrome MV3 |
| [Inbound job-status sync](https://github.com/thedevmark/engineering-notes/tree/main/email-sync) | Privacy-first status detection from emails users choose to forward, with guarded updates and review | Supabase Edge Functions, TypeScript, Resend |

## Stack

TypeScript · JavaScript · React · Vite · Zustand · Supabase · PostgreSQL · Cloudflare Pages and Workers · Chrome Manifest V3 · Stripe · Gemini · Python · C# · FFmpeg · Twitch EventSub and Helix · Streamer.bot

## Links

- **[deutschmark.online](https://deutschmark.online)** — marketing root, 3D carousel
- **[toolset.deutschmark.online](https://toolset.deutschmark.online)** — overlays + companion apps + docs
- **[yourpathos.app](https://yourpathos.app)** — Pathos - Your job search, connected
- **[dev.deutschmark.online](https://dev.deutschmark.online)** — recruiter-facing portfolio
- **[twitch.tv/thedeutschmark](https://twitch.tv/thedeutschmark)** · **[Discord](https://discord.com/invite/hQEQE9myXX)**
