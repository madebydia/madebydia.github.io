# meimakes.com

Personal homepage for [meimakes.com](https://meimakes.com) — editorial landing page for Raising Pixels and Build With Your Kid.

Built by [@meimakes](https://x.com/intent/user?screen_name=meimakes)

## Design

Editorial split-screen layout inspired by magazine covers and brutalist web design.

- **Left panel** (sticky on desktop) — MEI MAKES in Anton display font, bio in Newsreader serif, profile photo, social links
- **Right panel** — Two full-height link blocks for Raising Pixels (newsletter) and Build With Your Kid (book & curriculum)
- **Hover states** — RP block fills teal, BWYK block fills coral
- **Dark mode** via `prefers-color-scheme` — muted titles, dimmed photo, warm tones
- **Mobile** — stacks vertically with cropped landscape photo strip matching desktop crop
- **Fonts** — Anton (display), Newsreader (bio), Inter (body)
- **Colors** — coral `#FF4858`, teal `#14B9A7`, ink `#0A0A0A`, bg `#F7F7F5`

## Tech

- Single HTML file, no build step, no dependencies beyond Google Fonts
- JSON-LD Person schema + `llms.txt` for LLM discovery
- Open Graph + Twitter Card meta with `og.png`
- Plausible analytics (privacy-friendly, no cookies)
- GitHub Pages on branch `mein`

## Files

- `index.html` — the whole site
- `og.png` — Open Graph image (1200×630, coral bg + Anton type + profile)
- `profile.png` — avatar
- `rp-logo.png` — Raising Pixels logo
- `bwyk-logo.png` — Build With Your Kid logo
- `favicon.ico` / `favicon-*.png` / `apple-touch-icon.png` — favicons
- `llms.txt` — LLM-readable site summary
