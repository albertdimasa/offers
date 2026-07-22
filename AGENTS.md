# AGENTS.md — Offers

## What this repo is

Collection of standalone landing page demos (offer sites) for different local businesses. Each lives in its own directory.

## Directories

| Path | Content |
|---|---|
| `aqiqah/` | Aqiqah & Qurban catering (Surabaya) |
| `zottex/` | ZOTTEX — custom apparel & sablon kaos |
| `ac/` | reserved / placeholder |
| `ac/` | CV. Vivi Aris — AC service Surabaya |

Add a new demo by creating a new directory with an `index.html`.

## Tech

- Vanilla HTML + Tailwind CSS (via CDN `cdn.tailwindcss.com`) + vanilla JS
- FontAwesome 6.4 (CDN) and Google Fonts where needed
- No npm, no build tools, no tests, no linter, no typechecker

## Local dev

Open any `index.html` in a browser. No server needed.

## Deploy

Push to `main` → GitHub Actions (SSH port 2341) deploys whole repo to `/home/ubuntu/apps/offers` on VPS.

## Conventions

- `<html class="scroll-smooth" lang="id">`
- Tailwind theme configured inline in a `<script>` block
- JSON-LD structured data in `<head>` for SEO
- All content in Indonesian
- No comments in code

## License

© 2026 Syirkah Aqiqah Dan Qurban Surabaya
