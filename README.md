# Hi I'm Mark

App developer, streamer, photographer. Building tools that solve problems I ran into and couldn't find good answers for.

## What I'm working on

**[P.A.T.H.O.S.](https://yourpathos.app)** — Resume optimizer that uses deterministic ATS scoring (not hallucinated LLM scores) and truth-constrained AI rewriting. Detects ghost jobs before you waste time applying. Syncs recruiter emails to auto-update your pipeline. Has a three-tier AI companion that ranges from professional to genuinely unhinged.

**[deutschmark.online](https://deutschmark.online)** — Portfolio site with a procedural 3D homepage (8 models built from Three.js primitives, zero imported assets), streaming overlays, and a Spotify widget system. Ships as a static export to Cloudflare Pages with Workers handling auth and API.

**[Twitch Collab Planner](https://github.com/thedeutschmark/TwitchCollabOrganizer)** — Scheduling tool that pulls VOD history from the Twitch Helix API, detects past collaborations through multi-signal confidence ranking, and suggests optimal times based on streaming pattern analysis.

**[Alert! Alert!](https://github.com/thedeutschmark/alert-alert)** — Desktop app for stream alerts and VOD-to-shorts video editing. Python/Flask/FFmpeg with Whisper-based captioning and batch export.

**[DM Toolkit](https://github.com/thedeutschmark/toolkit)** — Streaming dashboard with music controls, OBS overlays, clip playback, and widget configuration. Authenticates through a shared Twitch identity across subdomains.

**[Persistent Memory Chat Bot](https://github.com/thedeutschmark/persistence_bot)** — AI chat companion for Twitch with persistent memory. Compresses each stream session into a local summary so the bot remembers what happened last time. Captures streamer speech via STT for full-context memory. Runs in Streamer.bot with your own API key.

## Technical writing

I document the harder problems in **[engineering-notes](https://github.com/thedeutschmark/engineering-notes)**:

- [3d on the web](https://github.com/thedeutschmark/engineering-notes/tree/main/3d-on-the-web) — Procedural models, PS1 vertex shaders, the orientation bug that cost me hours, and unifying two renderers into one canvas
- [Collab detection](https://github.com/thedeutschmark/engineering-notes/tree/main/collab-detection) — 4-tier confidence hierarchy for detecting Twitch collaborations from VOD titles, stream overlap, and event data
- [How I built P.A.T.H.O.S.](https://github.com/thedeutschmark/engineering-notes/tree/main/how-i-built-pathos) — Deterministic ATS scoring, voice-preserving AI rewriting, ghost job detection, and the AI arms race in hiring
- [Glass Box transparency](https://github.com/thedeutschmark/engineering-notes/tree/main/glass-box-transparency) — Three-layer transparency for persona state, resume optimization, and inbound job intel
- [Email sync](https://github.com/thedeutschmark/engineering-notes/tree/main/email-sync) — Auto-detecting recruiter responses from forwarded emails with confidence-gated automation and one-click undo
- [ML prediction](https://github.com/thedeutschmark/engineering-notes/tree/main/ml-prediction) — Logistic regression from scratch in JS, Platt scaling, time-aware evaluation, consent-gated training
- [Chat bot memory](https://github.com/thedeutschmark/engineering-notes/tree/main/chat-bot-memory) — Persistent memory for a Twitch bot without storing chat logs — session compression, per-user lore, local-first storage

## Stack

TypeScript, React, Next.js, Python, C#, Three.js, Supabase, Prisma, PostgreSQL, Cloudflare Workers/KV, Stripe, Gemini, FFmpeg, Whisper, Streamer.bot

## Links

[deutschmark.online](https://deutschmark.online) · [Twitch](https://twitch.tv/thedeutschmark) · [Discord](https://discord.com/invite/hQEQE9myXX)
