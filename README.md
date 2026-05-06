# GregorySuzan.github.io
<<<<<<< HEAD
A single-page bio site designed with a terminal/cyberpunk aesthetic. No frameworks, no build tools, no dependencies — just a static index.html that loads fast and looks sharp.
=======

Personal bio-link page hosted on GitHub Pages — a developer-focused alternative to Linktree built with plain HTML/CSS.

🔗 **Live site:** [gregorysuzan.github.io](https://gregorysuzan.github.io)

---

## Overview

A single-page bio site designed with a terminal/cyberpunk aesthetic. No frameworks, no build tools, no dependencies — just a static `index.html` that loads fast and looks sharp.

**Links featured:**
- 🌐 Portfolio — [gregorysuzan.com](https://www.gregorysuzan.com)
- 🐙 GitHub — [@GregorySuzan](https://github.com/GregorySuzan)
- 💼 LinkedIn — [gregory-suzan](https://www.linkedin.com/in/gregory-suzan/)
- 🐦 X — [@GregorySuzanOG](https://x.com/GregorySuzanOG)
- ⭐ Featured project — [multi-tier-vpc-architecture](https://github.com/GregorySuzan/multi-tier-vpc-architecture)
- ✉️ Email — hello@gregorysuzan.com

---

## Stack

| Layer | Choice |
|---|---|
| Hosting | GitHub Pages (free) |
| Framework | None — vanilla HTML/CSS |
| Fonts | JetBrains Mono + Space Grotesk (Google Fonts) |
| Icons | Inline SVG |
| Build step | None |

---

## Project Structure

```
GregorySuzan.github.io/
├── index.html        # Main page
├── images/
│   └── avatar.jpg    # Profile photo (400×400px recommended)
└── README.md
```

---

## Local Development

No install needed. Just open the file directly in your browser:

```bash
git clone https://github.com/GregorySuzan/GregorySuzan.github.io
cd GregorySuzan.github.io
open index.html
```

Or use the VS Code Live Server extension for hot reload while editing.

---

## Deployment

This repo is configured to deploy automatically via GitHub Pages.

Any push to the `main` branch goes live at `gregorysuzan.github.io` within ~60 seconds.

**To enable on a fresh fork:**
1. Go to **Settings → Pages**
2. Set source to `main` branch, `/ (root)` folder
3. Save — GitHub will publish it automatically

---

## Customisation

| What | Where |
|---|---|
| Links / URLs | `index.html` — update the `href` attributes in the `.links` section |
| Profile photo | Replace `images/avatar.jpg` (keep it square, under 200kb) |
| Accent colour | `index.html` — update `--green` / `--cyan` in `:root` CSS variables |
| Bio text | `index.html` — find the `.bio` div |
| Status badge | `index.html` — find the `.status` div |

---

## About

Built by someone who spent 6 years in design before pivoting to cloud computing. This page exists because `yourname.github.io` is always a better link than a Linktree URL.

---

*Inspired by [LittleLink](https://github.com/sethcottle/littlelink). Built from scratch.*
>>>>>>> 9b37d0c (Initial commit)
