# LeTiffany.github.io

Personal homepage, served via [GitHub Pages](https://pages.github.com/).

Live at: https://LeTiffany.github.io (once Pages is enabled — see below).

## Structure

- `index.html` — page content
- `style.css` — styling (light/dark aware)
- `assets/` — put `CV.pdf`, a headshot, etc. here

## Editing

Everything is plain HTML/CSS, no build step. Edit `index.html` directly, then
commit and push — the live site updates automatically within a minute or two.

Look for `<!-- TODO -->` comments in `index.html` for placeholder content to
fill in (bio, project descriptions, CV link, real contact links).

## First-time setup

1. Create a new **public** repo on GitHub named exactly `LeTiffany.github.io`.
2. `git remote add origin https://github.com/LeTiffany/LeTiffany.github.io.git`
3. `git push -u origin main`
4. On GitHub: Settings → Pages → Source → deploy from branch `main` / root
   (this step is often automatic for a `<username>.github.io` repo).
5. Visit https://LeTiffany.github.io after the first deploy finishes (~1 min).
