# Hi, I'm Mark

App developer, streamer, photographer. I build at the seam between AI products and live-video infrastructure — the engineering notes below explain the trade-offs behind each project. For recruiting / employment context, see [dev.deutschmark.online](https://dev.deutschmark.online).

## Stream tools

Tools for livestreamers — they work together: pull a clip, cut it, run your overlays, remember your chat, plan collabs.

| | Tool | What it is |
|---|------|------------|
| <img src="assets/icons/alert-alert.svg" width="44"> | **[Alert! Alert!](https://github.com/thedeutschmark/alert-alert)** | Make clean stream-alert clips from any video source. |
| <img src="assets/icons/clipline.svg" width="44"> | **[Clipline](https://github.com/thedeutschmark/clipline)** | Turn livestream VODs into shortform clips with auto-captions. |
| <img src="assets/icons/toolset.svg" width="44"> | **[The Stream Toolset](https://toolset.deutschmark.online)** | OBS overlays + companion apps. One login, no subscriptions. |
| <img src="assets/icons/forgetmenot.png" width="44"> | **[ForgetMeNot](https://github.com/thedeutschmark/forgetmenot)** | A Twitch chat bot that remembers your regulars. |
| <img src="assets/icons/collab.svg" width="44"> | **[Collab Planner](https://collab.deutschmark.online)** | Auto-detect collab windows from streamers' broadcast history. |

## Career

| | Tool | What it is |
|---|------|------------|
| <img src="assets/icons/pathos.svg" width="44"> | **[P.A.T.H.O.S.](https://yourpathos.app)** | AI career platform — resume tailoring, ATS scoring, gamified missions. |

## Technical writing

Long-form notes on the harder problems behind these projects, in **[engineering-notes](https://github.com/thedeutschmark/engineering-notes)**:

- **[Scaling streaming toolsets on Cloudflare](https://github.com/thedeutschmark/engineering-notes/tree/main/scaling-streaming-toolsets)** — designing a per-user multi-overlay platform on Workers + KV + Durable Objects so cost-per-user stays roughly flat as user count grows. Edge push over server-mediated polling, hibernatable WebSockets, Twitch EventSub. ~99.6% read reduction on the hot path.
- **[Collab detection](https://github.com/thedeutschmark/engineering-notes/tree/main/collab-detection)** — 4-tier confidence hierarchy for detecting Twitch collaborations from VOD titles, stream overlap, and event data.
- **[How I built P.A.T.H.O.S.](https://github.com/thedeutschmark/engineering-notes/tree/main/how-i-built-pathos)** — deterministic ATS scoring, voice-preserving AI rewriting, ghost-job detection, and the AI arms race in hiring.
- **[Glass Box transparency](https://github.com/thedeutschmark/engineering-notes/tree/main/glass-box-transparency)** — three-layer transparency for persona state, resume optimization, and inbound job intel.
- **[Email sync](https://github.com/thedeutschmark/engineering-notes/tree/main/email-sync)** — auto-detecting recruiter responses from forwarded emails with confidence-gated automation and one-click undo.
- **[ML prediction](https://github.com/thedeutschmark/engineering-notes/tree/main/ml-prediction)** — logistic regression from scratch in JS, Platt scaling, time-aware evaluation, consent-gated training.
- **[Chat bot memory](https://github.com/thedeutschmark/engineering-notes/tree/main/chat-bot-memory)** — persistent memory for a Twitch bot without storing chat logs. Session compression, per-user lore, local-first storage.

[toolset.deutschmark.online/docs](https://toolset.deutschmark.online/docs) — keeping your stream loudness sane so chat doesn't get ear-blasted, balancing OBS audio across scenes and sources, when to use Twitch IRC vs EventSub, hot-swapping overlay config live with Durable Objects, and a tutorial for every tool in the kit.

## Stack

TypeScript · React · Zustand · Next.js · Python · C# · Supabase · Prisma · Postgres · Cloudflare Workers · KV · Durable Objects · Stripe · Gemini · OpenAI · FFmpeg · faster-whisper · pyannote · Twitch IRC + EventSub + Helix · Spotify Web API · Streamer.bot

## Surfaces

- **[deutschmark.online](https://deutschmark.online)** — marketing root, 3D carousel
- **[toolset.deutschmark.online](https://toolset.deutschmark.online)** — overlays + companion apps + docs
- **[collab.deutschmark.online](https://collab.deutschmark.online)** — stream collab scheduler
- **[yourpathos.app](https://yourpathos.app)** — P.A.T.H.O.S.
- **[dev.deutschmark.online](https://dev.deutschmark.online)** — recruiter-facing portfolio
- **[twitch.tv/thedeutschmark](https://twitch.tv/thedeutschmark)** · **[Discord](https://discord.com/invite/hQEQE9myXX)**
