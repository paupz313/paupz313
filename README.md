## Hi, I'm Pierre

I build small, complete things and get them shipped — a site, an app, a game, a
physical object. Solo, end to end: product decisions, design, backend, deploys.

Four recent ones, deliberately on four different stacks:

### [noproblemo](https://github.com/paupz313/noproblemo) — running a shared family home
Mobile-first PWA. Arrival and closure checklists per house feature, a shared
calendar of stays with email invites and roles, and an AI concierge that finds
official tourism and town-hall sources near the house and extracts local events.

`React` `TypeScript` `Vite` `Tailwind` `Firebase` `Gemini` `GitHub Actions`

### [lagalere](https://github.com/paupz313/lagalere) — *Quelle Galère !*
A satirical public counter where French users file, browse and upvote their most
absurd administrative experiences, complete with a Windows 98 ticket machine.
Passwordless magic-link sign-in, an automatic filter that strips personal details
before publication, and GDPR pages.

Every write rule lives in the database as row-level security, not in the client —
the browser only ever holds the public key.

`Supabase` `PostgreSQL` `RLS` `Netlify` · static HTML/CSS/JS, no build step

### [morse-telegraph](https://github.com/paupz313/morse-telegraph) — a telegraph that actually works
Send a Telegram message, hear it beeped in Morse on a 2 cm cube across the room.
Tap the cube's button back and your Morse arrives in Telegram as readable text.

Same Morse engine three times — Python, Web Audio, and C on an ESP32 — ported
symbol-for-symbol so the timing matches to the millisecond.

`ESP32` `Arduino` `I2S audio` `Python` `Web Audio API`

### pigeon-mayhem-3d
A browser game: Three.js, one HTML file, no build step, one adaptive codebase
for desktop and phone driven by a quality-tier system.

---

Mostly working in **French and English**, mostly on things I wanted to exist.
