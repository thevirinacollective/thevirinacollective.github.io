# The Virina Collective website

This folder is the website of The Virina Collective, published for free with GitHub Pages.
Any change you save ("Commit changes") appears on the live site after about a minute.

## Where things are

| To change... | Edit this file |
| --- | --- |
| Site name, description, contact email, Google Form link | `_config.yml` |
| Menu and footer (every page) | `_layouts/default.html` |
| Home page | `index.html` |
| Our focus page (conditions, figures, working groups) | `our-focus.html` |
| Board members | `_data/board.yml` (photos go in `images/board/`) |
| Projects page | `projects.html` |
| Blog posts | one file per post in `_posts/` |
| Join the network page | `join.html` |
| Privacy policy | `privacy.md` |
| Colours, fonts, spacing | `assets/css/style.css` |

## Writing a blog post

1. Open the `_posts` folder and click **Add file → Create new file**.
2. Name it `YYYY-MM-DD-short-title.md`, for example `2026-11-15-conference-announced.md`.
3. Start the file with this header, then write the post below it:

```
---
layout: post
title: "Your post title"
category: "News"
excerpt: "One sentence shown on the Blog page."
---
```

4. Click **Commit changes**. The post appears on the Blog page about a minute later.

Formatting: `## Heading`, `**bold**`, `*italic*`, `- list item`, `[link text](https://address)`,
and `![image description](/images/photo.jpg)` for an image uploaded to the `images` folder.

## If the site stops updating

Open the **Actions** tab. A red cross means the last change has a mistake (often a missing quotation mark
or wrong indentation in a `.yml` file). Click it to see which file, fix it, and commit again.
