# Nikitha Padmanabha — Academic Homepage

Built using the [luost26/academic-homepage](https://github.com/luost26/academic-homepage) Jekyll template, deployed on Netlify.

## Setup

### Prerequisites
- Ruby 3.x
- Bundler (`gem install bundler`)

### Run locally
```bash
bundle install
bundle exec jekyll serve
```
Then open `http://localhost:4000`.

## Deploying to Netlify

1. Push this repo to GitHub.
2. In Netlify → **Add new site** → **Import from Git** → select your repo.
3. Build command: `bundle exec jekyll build`
4. Publish directory: `_site`
5. Done — Netlify handles it via `netlify.toml`.

## Adding your photo

Replace `assets/images/photos/portrait.jpg` with your own photo (keep the same filename, or update `_data/profile.yml`).

## Adding blog posts

Create files in `_posts/` named `YYYY-MM-DD-title.md` with front matter:

```markdown
---
layout: default
title: "Your Post Title"
date: 2026-01-01
---

Your content here.
```

## Updating content

All content lives in:
- `_data/profile.yml` — name, bio, social links
- `_data/cv.yml` — experience, education, skills
- `_showcase/` — project cards (one `.md` file per project)
- `_posts/` — blog posts
