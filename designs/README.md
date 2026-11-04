# Profile README redesign: 5 options

Each folder holds a complete `README.md`. To use one, copy its contents into the root `README.md`.

| # | Design | Vibe | External deps | Preview |
|---|---|---|---|---|
| 01 | [Neon Terminal](./01-neon-terminal) | Dark, animated, `whoami` C# class, snake | capsule-render, typing-svg, skillicons, streak, summary-cards, snake Action | [png](./previews/01-neon-terminal.png) |
| 02 | [Minimal Mono](./02-minimal-mono) | Senior-engineer plain text, zero widgets | none | [png](./previews/02-minimal-mono.png) |
| 03 | [Neofetch Card](./03-neofetch-card) | One custom SVG, auto light/dark | **none** (self-hosted SVG) | [png](./previews/03-neofetch-card.png) |
| 04 | [Bento Dashboard](./04-bento-dashboard) | Card grid, grouped stack, stats, projects table | capsule-render, typing-svg, shields, streak, summary-cards | [png](./previews/04-bento-dashboard.png) |
| 05 | [Recruiter Portfolio](./05-recruiter-portfolio) | Headline, projects-as-proof, experience, CTA | capsule-render, shields, skillicons, streak, summary-cards | [png](./previews/05-recruiter-portfolio.png) |

## Before you ship any of them
1. Replace every `YOUR_LINKEDIN_ID` with your real LinkedIn slug. The current README links to `linkedin.com/in/harsh desai`, which contains a space and is broken.
2. Replace `project-one`, `project-two` and `project-three` with real repos. Give each one a sentence and a number.
3. **Design 01 only:** copy `01-neon-terminal/.github/workflows/snake.yml` to `/.github/workflows/snake.yml`, then run it once from the Actions tab. Until you do, the snake image shows as broken.
4. **Design 03 only:** copy `dark_mode.svg` and `light_mode.svg` to the repo root next to `README.md`. To change any text, edit the SVGs.

## Widgets deliberately NOT used (checked 2026-11-04)
- `github-readme-stats.vercel.app` returned **503**. The public instance is overloaded, so self-host it on Vercel if you want it.
- `github-readme-activity-graph.vercel.app` returned **402**.
- `github-profile-trophy.vercel.app` returned **402**.

A broken image on your profile looks worse than having no image at all.
