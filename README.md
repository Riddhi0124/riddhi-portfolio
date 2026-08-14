# Riddhi Patel — Portfolio

A single-file portfolio website. Everything lives in `index.html` (HTML, CSS, and JS all in one file — no build step, no dependencies to install).

## How to open & edit

1. **Open the folder in VS Code:** File → Open Folder → select this `riddhi-portfolio` folder.
2. **Preview it:** double-click `index.html` to open it in your browser, or install the **Live Server** extension in VS Code (right-click `index.html` → "Open with Live Server") to see edits update instantly.
3. **Edit:** open `index.html` and change the text/links directly.

## Where to change things (search for these in index.html)

| What you want to change | Search for | Notes |
|---|---|---|
| A project's GitHub link | `href="https://github.com/Riddhi0124/` | Each project card has a `Code ↗` link |
| A project's live demo link | `Live demo ↗` | Add/remove these `<a>` lines per card |
| Your email | `riddhip0103@gmail.com` | Appears in the Contact section |
| LinkedIn / GitHub profile | `riddhi-patel-068428327` / `github.com/Riddhi0124` | Nav + Contact links |
| Add a new certification | `<!-- CERTIFICATIONS -->` | Copy a `<div class="cert">` block |
| Add a new experience/education entry | `<!-- EXPERIENCE -->` / `<!-- EDUCATION -->` | Copy an `.exp-item` block |
| Add a new skill chip | `<!-- SKILLS -->` | Add `<span class="chip">Name</span>` |

### Adding a new project card

Find the `<!-- PROJECTS (DARK BAND) -->` section and copy one full `<div class="proj reveal">…</div>` block. Then update:
- the `<h3>` title and `<p>` description
- the `href` on both the cover link and the `Code ↗` / `Live demo ↗` links
- the `.proj-tags` chips and the `.proj-tag-cat` / `.proj-year` labels

## Publishing to GitHub Pages (free hosting)

1. Create a new repo on GitHub (e.g. `riddhi-portfolio`).
2. Upload these files (or `git push`).
3. Repo → **Settings → Pages** → Source: `main` branch, `/root` → Save.
4. Your site goes live at `https://riddhi0124.github.io/riddhi-portfolio/`.

> Tip: to make it your main site at `https://riddhi0124.github.io`, name the repo exactly `Riddhi0124.github.io`.

## Files

- `index.html` — the entire site
- `README.md` — this file
- `.gitignore` — keeps OS/editor junk out of git
