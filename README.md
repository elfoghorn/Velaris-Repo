# Velaris Empire Compendium

A static 3-page site: the Nephilim bloodline record, Marasa'n's full character profile, and an index page linking the two.

## Files

- `index.html` — landing page
- `nephilim.html` — Nephilim race lore
- `marasan.html` — Marasa'n's full profile
- `portrait.png`, `formal.png`, `armor.png`, `blade.png` — Marasa'n reference images
- `adonai-prime.png`, `adonai-ruins.png` — Adonai-Vel before and after the Hollowing

All links between pages are relative, so this works from a repo root or a project subpath without any changes.

## Hosting on GitHub Pages

1. Create a new GitHub repository (public, unless you're on a plan that supports private Pages).
2. Upload all the files in this folder to the repository root (or to a `/docs` folder — your choice).
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to "Deploy from a branch".
5. Pick the branch (usually `main`) and the folder you uploaded to (`/root` or `/docs`).
6. Save. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

No build step, no dependencies — it's plain HTML/CSS/JS plus the images, so this is all you need.
