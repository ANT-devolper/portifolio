# Portfolio

Personal portfolio landing page for Antonio Borges, showcasing experience and
projects. Built with plain **HTML, CSS and JavaScript** — no build step and no
dependencies.

## Design

Dark minimalist theme: deep background, large typography, generous whitespace
and a single vibrant accent color. The whole palette is driven by CSS custom
properties in `styles.css` (`:root`), so the theme can be re-skinned by editing
a few variables (start with `--accent`).

## Structure

```
index.html    Markup and page sections (hero, about, projects, contact)
styles.css    Theme variables and all styling
script.js     Light interactions (mobile menu, scroll reveal, footer year)
assets/       Images and icons
```

## Sections

- **Hero** — name, role and primary calls to action.
- **About** — short intro plus a compact experience timeline.
- **Projects** — responsive grid of project cards with tags and links.
- **Skills & Contact** — tech stack and contact links (email, LinkedIn, GitHub).

## Running locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server
# then open http://localhost:8000
```

## Deploy

The site is fully static and works with no configuration on GitHub Pages,
Netlify or Vercel — just point the host at the repository root.

## Customizing

- **Accent / colors:** edit the variables in `:root` (`styles.css`).
- **Content:** update the placeholder text, experience timeline, project cards
  and contact links in `index.html`.
