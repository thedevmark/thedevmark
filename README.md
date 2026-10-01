# Hi, I'm Mark

App developer, streamer, and photographer with over a decade of experience. I build job-search software, streaming tools, and creative applications.

## Projects

<table>
<tr><td align="center" width="56"><img src="assets/icons/pathos.svg" width="44" alt=""></td><td><a href="https://yourpathos.app"><b>Pathos</b></a><br>Worker-side job search with source-linked roles, evidence-checked resumes, and application tracking.</td></tr>
<tr><td align="center" width="56"><img src="assets/icons/markskill.svg" width="44" alt=""></td><td><a href="https://github.com/thedevmark/markskill"><b>Markskill</b></a><br>A product-engineering skill for AI agents: trace behavior to its owner, fix root causes, shape interfaces around real tasks, and verify claims with evidence.</td></tr>
<tr><td align="center" width="56"><img src="assets/icons/alert-alert.svg" width="39" alt=""></td><td><a href="https://github.com/thedevmark/alert-alert"><b>Alert! Alert!</b></a><br>Turn a video URL or local file into a cropped, trimmed stream alert.</td></tr>
<tr><td align="center" width="56"><img src="assets/icons/auto-iphone-uploader.svg" width="39" alt=""></td><td><a href="https://github.com/thedevmark/auto-iphone-uploader"><b>Auto iPhone Uploader</b></a><br>Write a video's title and captions once on your PC, then post it from the real apps on your iPhone. Early preview.</td></tr>
<tr><td align="center" width="56"><img src="assets/icons/streamer-online.svg" width="44" alt=""></td><td><a href="https://streamer.deutschmark.online"><b>Streamer Online</b></a><br>Build OBS scenes and browser-source overlays with connected streamer tools.</td></tr>
<tr><td align="center" width="56"><img src="assets/icons/forgetmenot.png" width="32" alt=""></td><td><a href="https://github.com/thedevmark/forgetmenot"><b>ForgetMeNot</b></a><br>A local-first Twitch bot that remembers regulars, callbacks, and stream lore.</td></tr>
</table>

## Pathos Chrome extension

The [Pathos Chrome extension](https://chromewebstore.google.com/detail/ecniiinpnbhcjicagdhipdogcajohdip) fills supported application fields, attaches a reviewed resume for the role, and drafts answers grounded in the candidate's information. It leaves uncertain and sensitive fields for review and lets the candidate submit the application.

## Engineering notes

Selected write-ups from **[engineering-notes](https://github.com/thedevmark/engineering-notes)**:

| Paper | Description | Tech |
|---|---|---|
| [4K60 Native Ingest](https://github.com/thedevmark/engineering-notes/tree/main/4k60-native-ingest) | What I found across 40+ short-form video tests of codecs, bitrates, resolutions, a Chrome extension, and native iPhone uploads. | iPhone, video encoding, short-form platforms |
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
