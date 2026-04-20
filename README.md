# Learn While Live — Hugo Site

Personal website of Alexandre Hefren. Built with [Hugo](https://gohugo.io/) using a fully custom layout and vanilla CSS. No theme registry, no npm.

## Run locally

```bash
cd hugo-site
hugo server
```

Open http://localhost:1313 in your browser. Changes to content, layouts, and CSS reload automatically.

## Add a new post

1. Create a file in `content/posts/my-post-title.md`
2. Use this frontmatter template:

```yaml
---
title: "My Post Title"
date: 2026-03-17
excerpt: "One sentence summary shown in post cards."
teaser: "/images/posts/my-image.jpg"   # optional header image
tags:
  - science
  - writing
toc: true      # set to false to hide table of contents
math: false    # set to true to enable KaTeX math rendering
draft: false
---

Post content in Markdown here.
```

3. Push to `main` — the site deploys automatically.

## Add a photo to the gallery

1. Copy the image file to `static/images/photos/street/` or `static/images/photos/landscape/`
2. Open `content/photography/street.md` (or `landscape.md`)
3. Add an entry to the `gallery:` list in the frontmatter:

```yaml
  - url: /images/photos/street/my-photo.jpg
    image_path: /images/photos/street/my-photo.jpg
    alt: "Manchester, 2026"
    title: "Manchester, 2026"
```

## Deploy via GitHub Pages (default, automatic)

**One-time setup:**
1. In your GitHub repo → Settings → Pages → Source: select **GitHub Actions**
2. Move (or symlink) `.github/workflows/deploy.yml` to the **repo root** `.github/workflows/deploy.yml`
   (GitHub Actions must be at the repo root, not inside `hugo-site/`)
3. Set your custom domain in Settings → Pages → Custom domain: `www.alexandrehefren.com`

**After that:** every push to `main` triggers a build and deploy automatically. No manual steps needed.

## Switch to Cloudflare Pages

See `cloudflare-pages-setup.txt` for the three settings to paste into the Cloudflare Pages dashboard. No code changes required — just a dashboard connection and a DNS record update.

## Notice shortcode (in posts)

To add a highlighted notice block:

```
{{</* notice "primary" */>}}
Your notice text here. **Markdown** is supported.
{{</* /notice */>}}
```

Types: `primary` (slate blue border), `info` (blue border).

## Math in posts

Set `math: true` in frontmatter. Use `$$...$$` for inline math and `\[...\]` for display math.

Example: `$$E = mc^2$$` renders inline. `\[E = mc^2\]` renders as a centred block.
