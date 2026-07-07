# weStream — landing page

Marketing/landing page for **[weStream](https://github.com/vukasin-djuricic/weStream)**, a peer-to-peer
video streamer that plays a file the moment it starts downloading — directly from other people, no server.

**Live:** https://vukasin-djuricic.github.io/weStream-landing/

This repo is a **static site** (single `index.html` + `assets/`). No build step, no dependencies.

## Structure

```
index.html            # the whole page (inline CSS + JS)
assets/
  film/               # f_0001…f_0241.webp — scroll-scrubbed hero animation
  shots/              # app screenshots used in the page
```

## Run locally

Any static server, e.g.:

```
python3 -m http.server 8000    # then open http://localhost:8000
```

## Deploy

Hosted via **GitHub Pages** from the `master` branch (root). Push to `master` → Pages redeploys.
