# anujarora8.github.io

Personal site for **Anuj Arora** — built as a parody **2007-era Facebook profile**.

🔗 Live: **https://anujarora8.github.io/**

---

## What this is

A single, self-contained HTML page styled to look like a vintage Facebook profile circa 2007 — but the content is real: bio, roles (Ada, Accenture, AI Leverage, Queen's), an activity feed, a "Change Log," and contact links. It's responsive and works on mobile.

No build step, no framework, no dependencies. All CSS is inline in `index.html`.

## Structure

| File | Purpose |
|---|---|
| `index.html` | The entire site (markup + inline CSS) |
| `headshot.jpg` | Profile photo |
| `ada.png`, `ail.png`, `accenture.png`, `queens.png` | Network/affiliation logos |
| `favicon.png`, `apple-touch-icon.png` | Site icons (2007 FB glossy "f") |
| `archive/` | Snapshot of the **previous** personal site (dark, monospace), kept as a restore point |

## Editing

1. Edit `index.html` directly.
2. Commit and push to `main`.
3. GitHub Pages auto-deploys in ~30–60s. Hard-refresh to bypass the CDN cache.

> Image assets are cached aggressively by filename. To force a new photo/logo to show, either rename it or wait for the CDN to expire.

## Deployment

Served by **GitHub Pages** from the `main` branch root (`/`). No Actions or CI — push and it ships.

## Restoring the old site

The previous version lives at `archive/index.html` (also reachable at `/archive/`). To bring it back, copy `archive/index.html` over the root `index.html` and push. The full history is in git regardless.

---

*A parody profile. Not affiliated with Meta / Facebook.*
