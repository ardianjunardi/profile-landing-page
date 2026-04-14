# Profile Landing Page

Personal portfolio landing page for **Ardian Junardi** — Solutions Architect & Lead Backend Engineer.

Live site deployed on [Cloudflare Pages](https://pages.cloudflare.com/).

## Tech Stack

- HTML5, CSS3, vanilla JavaScript (single file — `index.html`)
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Font Awesome 6.5.0](https://fontawesome.com/) via CDN
- [AOS – Animate On Scroll 2.3.1](https://michalsnik.github.io/aos/) via CDN

## Sections

- **Hero** — name, title, availability badge, stats grid, CTA buttons
- **What I Solve** — 7 problem-area cards (System Bottlenecks, Cloud Architecture, etc.)
- **Experience** — timeline with 5 roles (Delos, Verein Tech, Freshbox, Rebelworks, Carsurin)
- **Core Stack** — tech skill tags across 5 categories
- **Why Me** — 4 differentiator cards
- **CTA / Footer** — contact call-to-action

## Design

Glassmorphism cards, gradient text, animated mesh background, floating navbar with blur. All CSS is embedded in `index.html`.

## Development

No build step required. Open `index.html` in a browser.

## Deployment

Auto-deploys to [Cloudflare Workers](https://workers.cloudflare.com/) on push to `main`. Configuration in `wrangler.jsonc` (worker name: `www`, static assets served from root).
