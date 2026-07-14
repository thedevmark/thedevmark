# Hi, I'm Mark

App developer, streamer, photographer. Over a decade of experience. I build at the seam between AI products and live-video infrastructure — the engineering notes below explain the trade-offs behind each project. For recruiting / employment context, see [dev.deutschmark.online](https://dev.deutschmark.online).

| | Tool | What it is |
|:---:|------|------------|
| <img src="assets/icons/pathos.svg" width="44"> | **[P.A.T.H.O.S.](https://yourpathos.app)** | Optimizes your resume per role and automatically tracks it all |
| <img src="assets/icons/alert-alert.svg" width="44"> | **[Alert! Alert!](https://github.com/thedeutschmark/alert-alert)** | Make clean stream-alert clips from any video source. |
| <img src="assets/icons/clipline.svg" width="44"> | **[Clipline](https://github.com/thedeutschmark/clipline)** | Turn livestream VODs into shortform clips with auto-captions. |
| <img src="assets/icons/toolset.svg" width="44"> | **[The Stream Toolset](https://toolset.deutschmark.online)** | OBS overlays + companion apps. One login, no subscriptions. |
| <img src="assets/icons/forgetmenot.png" width="32"> | **[ForgetMeNot](https://github.com/thedeutschmark/forgetmenot)** | A Twitch chat bot that remembers your regulars. |
| <img src="assets/icons/collab.svg" width="44"> | **[Collab Planner](https://collab.deutschmark.online)** | Auto-detect collab windows from streamers' broadcast history. |



## Technical Papers

Some notes on the harder problems I ran into over the years, in **[engineering-notes](https://github.com/thedeutschmark/engineering-notes)**:



| Paper | Description | Tech |
|---|---|---|
| [Scaling streaming toolsets on Cloudflare](scaling-streaming-toolsets/) | Designing a per-user multi-overlay platform so cost-per-user stays roughly flat as you grow — edge push, Hibernatable WebSockets, EventSub | Cloudflare Workers, KV, Durable Objects, Hibernatable WebSockets, EventSub |
| [Chat bot memory](chat-bot-memory/) | Persistent memory for a Twitch chat bot without storing raw chat logs | C#, Streamer.bot, Gemini Flash |
| [Collab detection](collab-detection/) | Confidence-ranked collab detection for Twitch from several imperfect signals | Twitch Helix API, Prisma, PostgreSQL |
| [How I built P.A.T.H.O.S.](how-i-built-pathos/) | Building a job-search system around deterministic scoring, constrained AI, and pipeline intelligence | React 19, Supabase, Gemini |
| [Glass Box transparency](glass-box-transparency/) | Glass Box transparency for persona state, optimizer stages, and inbound job intelligence | React 19, Supabase, Gemini |
| [Email sync](email-sync/) | Deterministic-first inbound email sync for job-search pipelines with review and undo | Supabase Edge Functions, TypeScript, LLM Fallback |
| [ML prediction](ml-prediction/) | Adding a learned prediction layer without replacing the deterministic scoring engine | JavaScript, Supabase, PostgreSQL |

[toolset.deutschmark.online/docs](https://toolset.deutschmark.online/docs) — keeping your stream loudness sane so chat doesn't get ear-blasted, balancing OBS audio across scenes and sources, when to use Twitch IRC vs EventSub, hot-swapping overlay config live with Durable Objects, and a tutorial for every tool in the kit.

## Stack

TypeScript · React · Zustand · Next.js · Python · C# · Supabase · Prisma · Postgres · Cloudflare Workers · KV · Durable Objects · Stripe · Gemini · OpenAI · FFmpeg · faster-whisper · pyannote · Twitch IRC + EventSub + Helix · Spotify Web API · Streamer.bot

## Links

- **[deutschmark.online](https://deutschmark.online)** — marketing root, 3D carousel
- **[toolset.deutschmark.online](https://toolset.deutschmark.online)** — overlays + companion apps + docs
- **[collab.deutschmark.online](https://collab.deutschmark.online)** — stream collab scheduler
- **[yourpathos.app](https://yourpathos.app)** — Personalized Application Tracking & Hiring Optimization System
- **[dev.deutschmark.online](https://dev.deutschmark.online)** — recruiter-facing portfolio
- **[twitch.tv/thedeutschmark](https://twitch.tv/thedeutschmark)** · **[Discord](https://discord.com/invite/hQEQE9myXX)**
