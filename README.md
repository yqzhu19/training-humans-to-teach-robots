# Training Humans to Teach Robots: Large and Lasting Skill Gains

Project page for our **ICRA 2026** paper, by Yuqing Zhu, Endong Sun, and Matthew Howard.

## 🔗 Live site

**https://yqzhu19.github.io/training-humans-to-teach-robots/**

- 📄 Paper (PDF): https://yqzhu19.github.io/training-humans-to-teach-robots/static/pdf/paper.pdf
- 💻 Repo: https://github.com/yqzhu19/training-humans-to-teach-robots

> If the live link doesn't load yet, GitHub Pages just needs to be turned on once —
> see "Publishing" below.

## What's here

```
index.html              # the page
static/css/style.css    # styling (change colors in the :root block at the top)
static/images/          # teaser, method, and result figures (replace the placeholders)
static/pdf/paper.pdf    # the paper
static/videos/          # drop a local demo.mp4 here if not using YouTube
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
