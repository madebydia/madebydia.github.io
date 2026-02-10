# meimakes.com

Personal site for [Mei Park](https://x.com/meimakes). A terminal-style homepage built with Catppuccin Mocha theming.

## What It Does

The site loads as an interactive terminal that auto-runs two commands:

1. `cat about.md` — bio and links
2. `ls projects` — browsable directory of all projects

Visitors can click project names to navigate, or type commands:

- `cd <project>` / `open <project>` — open a project
- `man <project>` — project details
- `cat about.md` — bio
- `ls` — list projects
- `help` — available commands
- Tab completion, command history (↑/↓), and a few easter eggs

## Stack

- Single `index.html`, no dependencies, no build step
- [Catppuccin Mocha](https://github.com/catppuccin/catppuccin) color palette
- [JetBrains Mono](https://www.jetbrains.com/lp/mono/) font
- Hosted on GitHub Pages with custom domain

## Local Development

```bash
open index.html
```

That's it.

## License

MIT
