# nikolasgkou-site

Zone01 Athens specialization-branch site, styled with [Tailwind CSS](https://tailwindcss.com)
(Play CDN — no build step) and ready to deploy on **GitHub Pages**.

## Files

| File           | Purpose                                                                 |
| -------------- | ----------------------------------------------------------------------- |
| `index.html`   | Landing page: key dates + a card grid of the seven branches, all generated from one data array so every card is structurally identical. |
| `pitch.html`   | Single viewer that renders any branch — `pitch.html?b=<slug>` fetches `pitches/<slug>.md` and renders it with `marked` + Tailwind Typography. Slugs are whitelisted. |
| `pitches/*.md` | The content. Edit these markdown files to change a branch; no code changes needed. |
| `404.html`     | Custom not-found page served automatically by GH Pages.                 |
| `.nojekyll`    | Tells GitHub Pages to skip Jekyll and serve files as-is.                |

To add a branch: drop a `pitches/<slug>.md` file, add the slug to the `DOCS` set in
`pitch.html`, and add an entry to the `BRANCHES` array in `index.html`.

## Local preview

The pages `fetch()` the markdown, so they must be served over HTTP (opening
`index.html` via `file://` will fail CORS). Serve the folder:

```bash
python3 -m http.server 8000
# → http://localhost:8000
```

## Deploy to GitHub Pages

### Option A — user/org site (`nikolasgkou.github.io`)

Serves at `https://nikolasgkou.github.io/`.

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin git@github.com:nikolasgkou/nikolasgkou.github.io.git
git push -u origin main
```

Then in the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `/ (root)`**.

### Option B — project site (any repo name)

Serves at `https://nikolasgkou.github.io/<repo>/`.

```bash
git init
git add .
git commit -m "Initial site"
git branch -M main
git remote add origin git@github.com:nikolasgkou/<repo>.git
git push -u origin main
```

Then enable Pages the same way (Settings → Pages → branch `main`, root).

> **Note:** For a project site the root path is `/<repo>/`, so use relative links
> (e.g. `href="#about"`, `href="page.html"`) rather than absolute paths starting
> with `/`. The boilerplate already does this.

## Going to production

The Play CDN is great for a quick artifact but isn't optimized (no purge, larger
payload, a console warning). If this grows, switch to the Tailwind CLI build and
commit the compiled CSS — ask and I'll set that up.
