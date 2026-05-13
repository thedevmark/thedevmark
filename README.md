# Hi, I'm Mark

App developer, streamer, photographer. I build at the seam between AI products and live-video infrastructure — the engineering notes below explain the trade-offs behind each project. For recruiting / employment context, see [dev.deutschmark.online](https://dev.deutschmark.online).

## What I'm working on

**[P.A.T.H.O.S.](https://yourpathos.app)** — AI-driven SaaS career platform. Resume tailoring against job descriptions with *deterministic* ATS scoring (no hallucinated LLM scores), truth-constrained AI rewriting, ghost-job detection, recruiter-email auto-sync. Built solo: blank repo to 100+ monthly active users in the first month of public release.

**[Stream Toolset](https://toolset.deutschmark.online)** ([repo](https://github.com/thedeutschmark/toolset)) — Open-source pack of OBS browser-source overlays and companion apps for Twitch streamers. One login, no subscriptions. Config hot-swaps live to the browser source over a Durable Object websocket fanout. Powers chat box, song requests, BRB scene, video shout-out, emote rain, death counter, subathon timer, lurk peek.

**[ForgetMeNot](https://github.com/thedeutschmark/forgetmenot)** — Local-first Twitch chat bot with persistent memory. Remembers community lore in a local SQLite database; replies via Gemini or OpenAI using your own API key. Ships as a single Windows executable — no shared backend, no chat data leaves your computer.

**[Twitch Collab Planner](https://github.com/thedeutschmark/collab-planner)** — Scheduling tool that pulls VOD history from the Twitch Helix API, detects past collaborations through multi-signal confidence ranking, and suggests optimal times based on streaming-pattern analysis. Live at [collab.deutschmark.online](https://collab.deutschmark.online).

**[Alert! Alert!](https://github.com/thedeutschmark/alert-alert)** — Desktop app for creating stream-alert assets from video. Loads remote URLs from YouTube / Instagram / TikTok (or a local file), trims, crops, zooms, applies aspect-ratio presets, separates and normalizes audio, and exports the result ready to drop into OBS. Python + Flask + PySide6 + FFmpeg + yt-dlp.

**[Clipline](https://github.com/thedeutschmark/clipline)** — Desktop app that turns livestream VOD moments into shortform clips. Pulls Twitch VODs, in-stream markers, and clip metadata; batch-renders with preset crops; transcribes captions via faster-whisper (optional speaker diarization via pyannote); stitches sequences for longform. Exports burn-in captions or sidecar ASS/SRT.

## Technical writing

Long-form notes on the harder problems behind these projects, in **[engineering-notes](https://github.com/thedeutschmark/engineering-notes)**:

- **[Scaling streaming toolsets on Cloudflare](https://github.com/thedeutschmark/engineering-notes/tree/main/scaling-streaming-toolsets)** — designing a per-user multi-overlay platform on Workers + KV + Durable Objects so cost-per-user stays roughly flat as user count grows. Edge push over server-mediated polling, hibernatable WebSockets, Twitch EventSub. ~99.6% read reduction on the hot path.
- **[Collab detection](https://github.com/thedeutschmark/engineering-notes/tree/main/collab-detection)** — 4-tier confidence hierarchy for detecting Twitch collaborations from VOD titles, stream overlap, and event data.
- **[How I built P.A.T.H.O.S.](https://github.com/thedeutschmark/engineering-notes/tree/main/how-i-built-pathos)** — deterministic ATS scoring, voice-preserving AI rewriting, ghost-job detection, and the AI arms race in hiring.
- **[Glass Box transparency](https://github.com/thedeutschmark/engineering-notes/tree/main/glass-box-transparency)** — three-layer transparency for persona state, resume optimization, and inbound job intel.
- **[Email sync](https://github.com/thedeutschmark/engineering-notes/tree/main/email-sync)** — auto-detecting recruiter responses from forwarded emails with confidence-gated automation and one-click undo.
- **[ML prediction](https://github.com/thedeutschmark/engineering-notes/tree/main/ml-prediction)** — logistic regression from scratch in JS, Platt scaling, time-aware evaluation, consent-gated training.
- **[Chat bot memory](https://github.com/thedeutschmark/engineering-notes/tree/main/chat-bot-memory)** — persistent memory for a Twitch bot without storing chat logs. Session compression, per-user lore, local-first storage.

Practical streamer-facing guides live at [toolset.deutschmark.online/docs](https://toolset.deutschmark.online/docs) — covers EBU R128 loudness in the browser, balancing audio in OBS, Twitch IRC vs EventSub, hot-swap overlay config with Durable Objects, and the streamer-side tutorials for each tool.

## Stack

TypeScript · React · Zustand · Next.js · Python · C# · Supabase · Prisma · Postgres · Cloudflare Workers · KV · Durable Objects · Stripe · Gemini · OpenAI · FFmpeg · faster-whisper · pyannote · Twitch IRC + EventSub + Helix · Spotify Web API · Streamer.bot

## Surfaces

- **[deutschmark.online](https://deutschmark.online)** — marketing root, 3D carousel
- **[toolset.deutschmark.online](https://toolset.deutschmark.online)** — overlays + companion apps + docs
- **[collab.deutschmark.online](https://collab.deutschmark.online)** — stream collab scheduler
- **[yourpathos.app](https://yourpathos.app)** — P.A.T.H.O.S.
- **[dev.deutschmark.online](https://dev.deutschmark.online)** — recruiter-facing portfolio
- **[twitch.tv/thedeutschmark](https://twitch.tv/thedeutschmark)** · **[Discord](https://discord.com/invite/hQEQE9myXX)**
