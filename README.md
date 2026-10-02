# AI App & Website Builder Explorer

An interactive single-file explorer that helps you compare and choose AI-powered app & website builders. Browse a curated list of tools, compare platforms side-by-side, explore pricing, and use the decision helper to pick the right builder for your needs.

## Features

- Interactive tool explorer with filters (search by category, pricing model, features)
- Platform comparison view — stack builders against each other
- Pricing overview with charts
- Decision helper — guided flow to narrow down the right tool
- Future outlook section on where AI builders are heading
- Single `index.html` — fully client-side, no build step

## Tech Stack

- Single HTML file (HTML + Tailwind CSS + vanilla JS)
- Tailwind CSS (CDN)
- Chart rendering in-page (no heavy deps)

## Quick Start

Just open `index.html` in a browser — or serve it:

```bash
npx serve .
```

## Project Structure

```
├── index.html   # The entire app — explorer, comparisons, pricing, decision helper
└── README.md
```

## Deploy

Fully static — host `index.html` on any static host (GitHub Pages, Cloudflare Pages, Netlify).

---

Built by Girish Lade — https://ladestack.in
