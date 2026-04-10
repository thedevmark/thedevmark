# Hi I'm deutschmark

App developer, streamer, photographer. Building tools that solve problems I ran into and couldn't find good answers for.

## What I'm working on

**[P.A.T.H.O.S.](https://github.com/thedeutschmark/pathosapp)** — Resume optimizer that uses deterministic ATS scoring (not hallucinated LLM scores) and truth-constrained AI rewriting. Detects ghost jobs before you waste time applying. Syncs recruiter emails to auto-update your pipeline. Has a three-tier AI companion that ranges from professional to genuinely unhinged.

**[deutschmark.online](https://github.com/thedeutschmark/deutschmark.online)** — Portfolio site with a procedural 3D homepage (8 models built from Three.js primitives, zero imported assets), streaming overlays, and a Spotify widget system. Ships as a static export to Cloudflare Pages with Workers handling auth and API.

**[Twitch Collab Planner](https://github.com/thedeutschmark/TwitchCollabOrganizer)** — Scheduling tool that pulls VOD history from the Twitch Helix API, detects past collaborations through [multi-signal confidence ranking](https://github.com/thedeutschmark/engineering-notes/tree/main/hybrid-collab-detection), and suggests optimal times based on streaming pattern analysis.

**[Alert! Alert!](https://github.com/thedeutschmark/alert-alert)** — Desktop app for stream alerts and VOD-to-shorts video editing. Python/Flask/FFmpeg with Whisper-based captioning and batch export.

**[DM Toolkit](https://github.com/thedeutschmark/toolkit)** — Streaming dashboard with music controls, OBS overlays, clip playback, and widget configuration. Authenticates through a shared Twitch identity across subdomains.

## Technical writing

I document the harder problems in **[engineering-notes](https://github.com/thedeutschmark/engineering-notes)**:

- [Building 3D objects for the web](https://github.com/thedeutschmark/engineering-notes/tree/main/unified-webgl-scene) — Procedural models, PS1 vertex shaders, the orientation bug that cost me hours, and unifying two renderers into one canvas
- [Multi-signal collab detection](https://github.com/thedeutschmark/engineering-notes/tree/main/hybrid-collab-detection) — 4-tier confidence hierarchy for detecting Twitch collaborations from VOD titles, stream overlap, and event data
- [How I built P.A.T.H.O.S.](https://github.com/thedeutschmark/engineering-notes/tree/main/resume-optimization) — Deterministic ATS scoring, voice-preserving AI rewriting, ghost job detection, and the AI arms race in hiring
- [Inbound email sync](https://github.com/thedeutschmark/engineering-notes/tree/main/inbound-email-sync) — Auto-detecting recruiter responses from forwarded emails with Guardian confidence scoring and hard guardrails

## Stack

TypeScript, React, Next.js, Python, Three.js, Supabase, Prisma, Cloudflare Workers/KV, Gemini, FFmpeg

## Links

[deutschmark.online](https://deutschmark.online) · [Twitch](https://twitch.tv/thedeutschmark) · [Discord](https://discord.com/invite/hQEQE9myXX)
