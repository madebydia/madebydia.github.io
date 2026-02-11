# meimakes.com

Personal homepage for [mei makes](https://meimakes.com) — a Mondrian-inspired tile grid layout.

## Features

- **Responsive grid** with 5 randomized layout templates that shuffle on each page load
- **Light/dark mode** via `prefers-color-scheme` with CSS custom properties
- **Avatar column** spanning all rows with gradient overlay
- **Live clock tile** with 144-square minute grid (one per 10 min of day) and blinking current indicator
- **Season tile** with animated particle effects — snow (winter), petals (spring), fireflies (summer), leaves (autumn)
- **Greeting tile** with time-of-day greetings in English and Japanese, sun/moon SVG watermarks
- **Project cards** for GitHub repos with star counts and fork indicators
- **Mobile layout** collapses to single column at 768px
- **Self-contained** — single HTML file, no external dependencies, system fonts only

## Tech

Pure HTML/CSS/JS. No frameworks, no build tools, no external assets. The avatar is base64-encoded inline.

## Color Palette

Light mode uses warm earth tones: cream (#FFF9F0), salmon (#f0be8a), sage (#7a8660), chocolate (#3d2c22) on a stone background (#C3BEB2).

Dark mode shifts to deep warm browns with the same accent palette (#bf6945).
