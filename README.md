# Personal Blog — Pillar 1

> **Personal OS**: Blog → Automation → Projects → Research

A Jekyll-based static blog deployed via GitHub Pages. This is the **single source of truth** for all long-form content — four distinct collections, each with its own purpose and permalink structure.

## Content Collections

| Collection | Folder | Permalink | AI Assisted | Purpose |
|---|---|---|---|---|
| Stories | `_stories/` | `/stories/:title` | No (human-only) | Personal narrative, raw experiences |
| Essays | `_essays/` | `/essays/:title` | Yes | Opinion, policy, automotive analysis |
| Work Articles | `_work/` | `/work/:title` | Yes | MSIL/Vahan/CAFE data-driven pieces |
| Complexity Lab | `_lab/` | `/lab/:title` | Yes | Network science notes, research ideas |

## Front Matter Schema

Each post uses this front matter:

```yaml
---
title: "Post Title"
date: YYYY-MM-DD
category: stories | essays | work | lab
ai_assisted: true | false
human_only: true | false   # only for _stories/
tags: []
reading_time: N
doi:                       # optional, once research is published
---
```

## Tech Stack

- **Theme**: Minima (upgrade to al-folio for research focus)
- **Plugins**: jekyll-feed, jekyll-seo-tag, jekyll-sitemap
- **Deploy**: GitHub Actions → GitHub Pages
- **Domain**: kapil433.github.io/personal-blog (custom domain: kapilgupta.in)

## LinkedIn Distribution Strategy

Do NOT use LinkedIn share button. Instead:
1. Write a 2–3 sentence hook (human-written — your voice)
2. Paste direct URL to the blog post
3. Add 3–5 specific tags: `#VehicleRegistration #CafeNorms #ComplexityScience`

## Part of the Four-Pillar System

```
Pillar 1: Blog (this repo)
Pillar 2: social-automation
Pillar 3: msil-work-tool | commercialize-analytics | complexity-lab
Pillar 4: research-platform
```
