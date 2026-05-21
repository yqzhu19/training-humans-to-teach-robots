# ICRA 2026 Project Page

Static project page for our ICRA 2026 paper, built to be hosted for free on **GitHub Pages**.

## What's here

```
index.html              # the page — edit the [[PLACEHOLDERS]] in here
static/css/style.css    # styling (change colors in the :root block at the top)
static/images/          # teaser, method, and result figures (replace the placeholders)
static/videos/          # drop a local demo.mp4 here if not using YouTube
```

## How to edit

1. Open `index.html` and search for `[[` — every editable spot (title, authors,
   affiliations, links, abstract, captions, BibTeX) is marked with `[[...]]`.
2. Replace the placeholder images in `static/images/` with your real figures,
   keeping the same filenames (`teaser.png`, `method.png`, `result1.png`, …).
3. For the video, either put your YouTube video id in the `iframe` `src`, or
   uncomment the `<video>` block and drop a `demo.mp4` into `static/videos/`.
4. Preview locally by opening `index.html` in a browser, or run a quick server:
   `python3 -m http.server` then visit http://localhost:8000

## How to publish on GitHub Pages

Account: **yqzhu19**

Two common URL options:
- **Project site** (recommended): `https://yqzhu19.github.io/<repo-name>/`
- **User site**: `https://yqzhu19.github.io/` — only if the repo is named exactly `yqzhu19.github.io`

Steps (project site):

1. Create a new public repo on GitHub, e.g. `icra2026-project`.
2. From this folder, push the files:
   ```bash
   git init
   git add .
   git commit -m "Initial project page"
   git branch -M main
   git remote add origin https://github.com/yqzhu19/icra2026-project.git
   git push -u origin main
   ```
3. On GitHub: repo **Settings → Pages → Build and deployment → Source = "Deploy from a branch"**,
   pick branch `main` and folder `/ (root)`, then **Save**.
4. Wait ~1 minute; your page goes live at `https://yqzhu19.github.io/icra2026-project/`.

That's it — no build step, no dependencies.
