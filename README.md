# My website

A Jekyll site for GitHub Pages: research, writing, creative work and CV.

## Put it online (one time, ~10 minutes)

1. On github.com, create a new **public** repository named **`<your-username>.github.io`**
   (exactly that, with your username). This makes your site live at `https://<your-username>.github.io`.
2. Open the repo, click **Add file → Upload files**, and drag in *everything inside* this folder
   (not the folder itself — `_config.yml` should sit at the top level). Commit.
3. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**,
   branch **main**, folder **/ (root)**. Save.
4. Wait 1–2 minutes, then visit `https://<your-username>.github.io`.

> Using a different repo name (e.g. `website`)? Set `baseurl: "/website"` in `_config.yml`.

## Where to edit things

| What | File |
|---|---|
| Name, tagline, email, social links | `_config.yml` |
| Homepage intro paragraph | `index.html` |
| Research intro | `research.html` |
| Interests (home + research) | `_data/interests.yml` |
| Publications, posters, talks | `_data/publications.yml` |
| Gallery pieces | `_data/gallery.yml` + images in `assets/img/` |
| About text + CV | `about.md` (and drop your PDF at `assets/files/cv.pdf`) |
| Projects | `_data/projects.yml` |
| Colours, spacing, frame width | top of `assets/css/style.css` |

You can edit any of these directly on github.com (click the file → pencil icon); the site rebuilds itself.

## Writing a blog post

Add a file to `_posts/` named `YYYY-MM-DD-short-title.md`, starting with:

```
---
layout: post
title: "Your title"
summary: "One line shown on the blog list."
tags: [notes]
---

Write in Markdown here.
```

On github.com: open `_posts` → **Add file → Create new file**, name it, paste, commit. Done.

## Preview on your Mac (optional)

```
brew install ruby
gem install bundler
bundle install
bundle exec jekyll serve
```
Then open http://localhost:4000.
