# Joe Cunnell — Portfolio

Multi-page static portfolio (HTML/CSS + light JS). Night / dusk purple theme. No build step.

Designed for GitHub Pages **user site** [`nightelm664.github.io`](https://nightelm664.github.io) — publish files at the **repo root**.

## Open locally

```bash
cd joe-portfolio
python3 -m http.server 8080
# or: npx serve .
```

Then open `http://localhost:8080` (or the URL shown). Or open `index.html` directly in a browser.

## Site map

| Path | Page |
|------|------|
| `index.html` | Home — hero, proof strip, featured work, brands, about teaser, mega CTA |
| `work.html` | Full work grid |
| `work/*.html` | Detailed case studies (8) |
| `what-i-do.html` | Process & services |
| `about.html` | Story, values, timeline |
| `contact.html` | Email + socials |
| `styles.css` | Shared dusk-purple theme |
| `script.js` | Mobile nav + year |
| `research/` | Work audit + Katie structure notes (not linked in nav) |

### Case studies

1. `work/echo-rwf.html` — Echo Race to World First (25M+ views from CV; AMD)
2. `work/nightelm-wow-forever.html` — WoW Forever soundtrack meme (144K views)
3. `work/venomous-abyss.html` — Venomous Abyss 8/8 wrap (111K)
4. `work/twin-fangs.html` — World First Twin Fangs Mythic (108K)
5. `work/nightelm-virality.html` — Personal virality / nostalgia strategy
6. `work/corsair-partner.html` — Corsair Scimitar partner reel (30.5K)
7. `work/moncada-visit.html` — Moncada RWF visit (39.7K)
8. `work/giantx-era.html` — GIANTX era highlights (CV metrics)

## Design

- Backgrounds: `#0a0614`, `#12081f`, `#1a0f2e`
- Accents: `#a855f7`, `#c084fc`, `#e879f9` (+ sparingly `#fb923c` / `#f472b6`)
- Fonts: Fraunces (titles) + DM Sans (body) via Google Fonts

## Metrics policy

Campaign totals from the CV are labelled **(from CV)**. Per-post likes/views are public Instagram/X figures from the Oct 2026 work audit. Nothing invented.

## Deploy (GitHub Pages user site)

1. Push this folder’s contents to the **root** of `nightelm664.github.io` (or the user-site repo).
2. Settings → Pages → Deploy from branch `main` → folder `/` (root).
3. Site live at `https://nightelm664.github.io/`.

No Node/npm build required.

## Licence

Content and code for Joe’s personal use. Keep brand/campaign claims aligned with approved CV details before sharing publicly.
