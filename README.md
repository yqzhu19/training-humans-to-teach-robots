# Robot Learning from Novice Teachers — project page

A single page hosting two related papers, by Yuqing Zhu, (Endong Sun,) and Matthew Howard:

1. **ICML 2026** — *Making Learner Weakness Actionable for Learning from Demonstration with Novice Teachers* (CLASP) — shown first.
2. **ICRA 2026** — *Training Humans to Teach Robots: Large and Lasting Skill Gains* — with project video.

## 🔗 Live site (published)

**https://yqzhu19.github.io/training-humans-to-teach-robots/**

- 📄 ICML paper (PDF): [in repo](static/pdf/icml.pdf) · [live](https://yqzhu19.github.io/training-humans-to-teach-robots/static/pdf/icml.pdf)
- 📄 ICRA paper (PDF): [in repo](static/pdf/paper.pdf) · [live](https://yqzhu19.github.io/training-humans-to-teach-robots/static/pdf/paper.pdf)
- 💻 Repo: https://github.com/yqzhu19/training-humans-to-teach-robots

## What's here

```
index.html              # the page (ICML paper first, then ICRA project + video)
static/css/style.css    # styling (change colors in the :root block at the top)
static/pdf/icml.pdf     # ICML 2026 paper
static/pdf/paper.pdf    # ICRA 2026 paper
ICRA26_1579_VI_fi.mp4   # ICRA project video (repo root)
static/images/          # teaser, method, and result figures (unused by the slim page)
```

## How to edit

Open `index.html` and search for `[[` — every spot still needing your input
(affiliation, links, video id, figure captions) is marked with `[[...]]`.
Replace the placeholder images in `static/images/` with your real figures,
keeping the same filenames (`teaser.png`, `method.png`, `result1.png`, …).

Preview locally: open `index.html` in a browser, or run `python3 -m http.server`
and visit http://localhost:8000.

## Publishing (one-time GitHub Pages setup)

1. Go to **Settings → Pages**: https://github.com/yqzhu19/training-humans-to-teach-robots/settings/pages
2. Under **Build and deployment → Source**, choose **"Deploy from a branch"**.
3. Branch **`main`**, folder **`/ (root)`**, then **Save**.
4. Wait ~1 minute, refresh — your page is live at the link at the top of this file.

After that, every push to `main` updates the live site automatically.
