Site content language: English
Conversation with the user: Spanish
(Code and internal docs: English.)

# titosolano.com — Tito's own website

System rules: `/Volumes/KINGSTON/Work/repos/_system/work-rules.md`. They apply here unless this file says otherwise.

## What it is
- Production site **titosolano.com** (portfolio: home, case studies, contact). Scope **titosolano**. Rebuilt from Webflow to code in 2026.
- Stack: Astro + React islands, TypeScript, GSAP, Swiper; content from **Sanity** (`@sanity/client`; studio in `sanity/`); contact endpoint in `api/contact.js`. Deployed on **Vercel** (project `ts2026-astro`, linked in `.vercel/`, gitignored).
- Commands: `npm install` · `npm run dev` · `npm run build` (verified from this folder 2026-11-11: 9 pages, no errors).
- `.env` (gitignored, local only) holds the required values; never commit it.

## Claude config
- `.claude/` is its **own git repo** (`titosolano/titosolano-claude-config`), ignored by this one. Skills: `project`, `animate`.
- `.claude/settings.json` blocks the claude.ai Webflow, Composio and Semrush connectors (they hold clients' accounts; this site doesn't use them). `.claude/settings.local.json` (gitignored): `additionalDirectories`.

## Projects
- `projects/2026-11-site-screenshots/`: recover or create clean screenshots of Tito's websites for the next redesign (not urgent).

## Identity and links
- Repo: `/Volumes/KINGSTON/Work/repos/titosolano/titosolano-com` · Files: `/Volumes/KINGSTON/Work/files/titosolano/titosolano-com` (Drive: titosolano Google account):
  - `design-2026/`: design working files of the current site (Affinity mockups, project images, backgrounds, OG image; was `~/Documents/Tito Solano/Planning/TitoS Process`). The mockups will age fast.
  - `sanity-studio-backup/`: earlier standalone Sanity studio (code only; `node_modules`/`dist` left out).
  - `webflow-export-ts2026/`: export of the previous Webflow build. `1779805381246.png`: loose image from the old folder.
- GitHub: `titosolano/titosolano-com` (renamed from `ts2026-astro` 2026-11-11). **Public on purpose:** needed for free Vercel hosting. Never commit secrets or private contact details here; the Vercel project keeps its old name `ts2026-astro` and follows the repo by ID.
- ClickUp: space **Tito Solano** › list **`titosolano.com`** (`901423199258`), the site backlog. New ideas, fixes and mini projects for the site go there as tasks.

## Path-bound config
- **Active location: this repo** since 2026-11-11. Old folder `~/Documents/Tito Solano/website v2` = archive; deleting it is Tito's call.
- Vercel and Sanity don't depend on the local path. Scheduled tasks: none.
