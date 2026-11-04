# Profile README redesign: 11 options

Each folder holds a complete `README.md`. To use one, copy its contents into the root `README.md`.

| # | Design | Vibe | External deps | Preview |
|---|---|---|---|---|
| 01 | [Neon Terminal](./01-neon-terminal) | Dark, animated, `whoami` C# class, snake | capsule-render, typing-svg, skillicons, streak, summary-cards, snake Action | [png](./previews/01-neon-terminal.png) |
| 02 | [Minimal Mono](./02-minimal-mono) | Senior-engineer plain text, zero widgets | none | [png](./previews/02-minimal-mono.png) |
| 03 | [Neofetch Card](./03-neofetch-card) | One custom SVG, auto light/dark | **none** (self-hosted SVG) | [png](./previews/03-neofetch-card.png) |
| 04 | [Bento Dashboard](./04-bento-dashboard) | Card grid, grouped stack, stats, projects table | capsule-render, typing-svg, shields, streak, summary-cards | [png](./previews/04-bento-dashboard.png) |
| 05 | [Recruiter Portfolio](./05-recruiter-portfolio) | Headline, projects-as-proof, experience, CTA | capsule-render, shields, skillicons, streak, summary-cards | [png](./previews/05-recruiter-portfolio.png) |
| 06 | [Aurora Glass](./06-aurora-glass) | Frosted-glass cards over drifting aurora blobs (animated) | **none** (self-hosted SVG) + shields badges | [png](./previews/06-aurora-glass.png) |
| 07 | [Synthwave Arcade](./07-synthwave) | 80s neon sunset, moving grid, "Player 1" stat card | **none** (self-hosted SVG) | [png](./previews/07-synthwave.png) |
| 08 | [Code Editor](./08-code-editor) | Profile as a VS Code window, lines type in, `dotnet run` intro | **none** (self-hosted SVG) | [png](./previews/08-code-editor.png) |
| 09 | [Bento Tiles](./09-bento-tiles) | Apple-keynote tile grid, auto light/dark | **none** (self-hosted SVG) | [dark](./previews/09-bento-tiles.png) · [light](./previews/09-bento-tiles-light.png) |
| 10 | [Editorial](./10-editorial) | Magazine cover, big serif name, pull quote, auto light/dark | **none** (self-hosted SVG) | [dark](./previews/10-editorial.png) · [light](./previews/10-editorial-light.png) |
| 11 | [**Merged 03 + 05 + 09**](./11-merged-3-5-9) | All-black: Bento tiles, terminal session, grouped icon panel, activity; no repeated content | own SVGs (icons embedded) + shields, streak, summary-cards | [dark](./previews/11-merged-3-5-9.png) · [light](./previews/11-merged-3-5-9-light.png) |

## Before you ship any of them
1. Replace every `YOUR_LINKEDIN_ID` with your real LinkedIn slug. The current README links to `linkedin.com/in/harsh desai`, which contains a space and is broken.
2. Replace `project-one`, `project-two` and `project-three` with real repos. Give each one a sentence and a number.
3. **Design 01 only:** copy `01-neon-terminal/.github/workflows/snake.yml` to `/.github/workflows/snake.yml`, then run it once from the Actions tab. Until you do, the snake image shows as broken.
4. **Designs 03 and 06–10:** copy that folder's `.svg` files to the repo root next to `README.md`. All text lives inside the SVGs, so edit them to change anything. They need no outside service, so they can't break.

## Widgets deliberately NOT used (checked 2026-11-04)
- `github-readme-stats.vercel.app` returned **503**. The public instance is overloaded, so self-host it on Vercel if you want it.
- `github-readme-activity-graph.vercel.app` returned **402**.
- `github-profile-trophy.vercel.app` returned **402**.

A broken image on your profile looks worse than having no image at all.
