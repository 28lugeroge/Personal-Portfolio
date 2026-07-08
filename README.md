# Portfolio

My personal developer portfolio, built with plain HTML, CSS, and JavaScript — no build step, no framework, deploys straight to GitHub Pages.

## Structure

- `index.html` — page content
- `style.css` — all styling and design tokens (see `:root` for colors/fonts)
- `script.js` — mobile nav toggle, scroll-reveal animations, footer year

## Editing

Open `index.html` and search for `<!-- EDIT` comments — those mark the placeholder content (name, role, bio, projects, links, email) to swap for your own. Colors and fonts live as CSS variables at the top of `style.css`.

## Running locally

Just open `index.html` in a browser — or, for live-reload while editing, use the VS Code "Live Server" extension or run:

```
python3 -m http.server 8000
```

and visit `http://localhost:8000`.

## Deployment

This site is deployed via GitHub Pages from the `main` branch. See the repo settings under **Settings → Pages**.
