# Joe Cunnell — Personal Portfolio

Bold, gaming-inspired single-page portfolio (static HTML/CSS + light JS). No build step.

## Open locally

1. Open the folder in a file browser, or from a terminal:
   ```bash
   cd joe-portfolio
   open index.html        # macOS
   # or: xdg-open index.html   # Linux
   # or: start index.html      # Windows
   ```
2. Or serve it with any static server, e.g.:
   ```bash
   npx serve .
   # or: python3 -m http.server 8080
   ```
   Then visit the URL shown (often `http://localhost:3000` or `:8080`).

## Files

| File         | Purpose                          |
|--------------|----------------------------------|
| `index.html` | Page structure & content         |
| `styles.css` | Layout, theme, responsive styles |
| `script.js`  | Mobile nav + footer year         |
| `README.md`  | This file                        |

## Colour palette

- Background: `#07070c`
- Surfaces: `#10101a` / `#161625`
- Text: `#e8e8f0` / muted `#9a9ab0`
- Neon cyan: `#00f0ff`
- Magenta: `#ff2bd6`
- Lime accent (badges): `#b8ff3c`

## Content status

- **Identity / hero / experience / contact:** filled from Joe’s CV (Joe Cunnell · jcunnell@hotmail.co.uk)
- **Case studies:** titles and blurbs match real campaigns; CV metrics labelled “(from CV)”. No invented Instagram/X post view counts. Social post examples to be added in a later pass.
- **Photo / headshot:** none included yet; add an `<img>` in the hero if desired
- **Social links:** optional — LinkedIn, X, Discord, etc. in the contact or footer section

## Deploy on GitHub Pages (free)

1. Create a new GitHub repository (e.g. `joe-portfolio` or `username.github.io`).
2. Push this folder’s contents to the repo (root or `/docs`).
3. In the repo: **Settings → Pages → Build and deployment**.
4. Source: **Deploy from a branch** → branch `main` (or `master`) → folder `/` (root) or `/docs`.
5. Save. After a minute or two, the site is live at  
   `https://<username>.github.io/<repo>/` (or `https://<username>.github.io/` for a user site).

## Deploy on Netlify (free)

1. Go to [netlify.com](https://www.netlify.com/) and sign in (GitHub login works well).
2. **Add new site → Import an existing project** and pick the repo, **or** drag-and-drop this folder onto Netlify Drop.
3. Build settings: leave build command empty; publish directory = site root (`.`).
4. Deploy. You’ll get a `*.netlify.app` URL; you can add a custom domain later.

No Node/npm build is required for either host.

## Licence

Content and code for Joe’s personal use. Keep brand/campaign claims aligned with approved CV details before sharing publicly.
