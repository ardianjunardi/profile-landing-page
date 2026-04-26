# Profile Landing Page

Personal portfolio landing page for **Ardian Junardi** — Solutions Architect & Lead Backend Engineer.

Live site deployed on [Cloudflare Pages](https://pages.cloudflare.com/).

## Tech Stack

- HTML5, CSS3, vanilla JavaScript (single file — `index.html`)
- [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) via Google Fonts CDN
- [Tailwind CSS](https://tailwindcss.com/) via CDN (with inline config override)
- [Font Awesome 6.5.0](https://fontawesome.com/) via CDN
- [AOS – Animate On Scroll 2.3.1](https://michalsnik.github.io/aos/) via CDN

## Sections

- **Nav** — floating glassmorphism navbar with mobile hamburger menu
- **Hero** — name, title, availability badge, stats grid, CTA buttons
- **What I Solve** — 6 problem-area cards in asymmetric bento grid (first card spans 2 columns)
- **Experience** — timeline with 5 roles (Delos, Verein Tech, Freshbox, Rebelworks, Carsurin)
- **Projects** — 6 client work cards (Orxa, Astro, Custos, Soechi, The Dome, Dots)
- **Core Stack** — tech skill tags across 7 categories
- **Why Me** — 4 differentiator cards with Font Awesome icons
- **CTA / Footer** — contact call-to-action

## Design

Dark glassmorphism aesthetic (`#06060f` background) with Plus Jakarta Sans typography, 2-color gradient accents (blue-to-purple), inner refraction glass cards, noise/grain texture overlay, and custom cubic-bezier transitions. All CSS is embedded in `index.html`.

## Development

No build step required. Open `index.html` in a browser.

## Deployment

Auto-deploys to Cloudflare Pages on push to `main`.
