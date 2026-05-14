# AI Use Case Prioritiser

A simple, sector-aware tool for scoring AI use cases on three dimensions: **Value**, **Risk** and **Readiness**.

Branded as a concept piece for **Simpson Associates** and built as a presales discovery aid — a simplified alternative to more complex agentic-AI scoring frameworks.

---

## What it does

- Walks a user through **15 questions** (5 per dimension) to score any AI use case
- Produces a clear verdict, a 2x2 prioritisation matrix, and a recommended next step
- **Exports a fully branded 4-slide PowerPoint** of the result
- Comes with a **pre-loaded worked example** — North Yorkshire Council's award-winning AI-powered insight engine for Children's Social Care — so you can see the framework in action with real numbers

---

## Why three dimensions, not eighteen

Most AI scoring frameworks (including the excellent Zygens DDAD that inspired this) use 15–20 dimensions across complexity, risk, value and beyond. That's perfect for a workshop with 50+ candidate use cases and a team of domain experts.

But in **presales discovery**, you have 30–60 minutes with a customer who hasn't yet defined their use cases. You need a tool that:

1. Surfaces what matters in a single conversation
2. Doesn't lose a CIO or CDO by dimension three
3. Adds a readiness layer that protects against over-promising

So the framework collapses to:

| Dimension | What it asks |
|---|---|
| **Value** | How much real impact will this create — reach, time, outcomes, financial, visibility |
| **Risk** | What could go wrong — data, autonomy, regulation, failure impact, workforce |
| **Readiness** | Can we actually do it — data, platform, sponsorship, governance, time-to-start |

---

## Running locally

This is a single `index.html` file with no build step:

```bash
# Open the file directly in a browser
open index.html
# OR serve it with any static server
python3 -m http.server 8000
```

## Deploying to GitHub Pages

1. Push to your repo
2. Settings → Pages → Source: `main` branch / `/` (root)
3. Site is live in ~2 minutes

---

## Credits

- Concept and build: **Luke Craven** ([Pathed Consulting](https://pathed-hub.netlify.app))
- Framework inspiration: [Zygens DDAD](https://ddad.zygens.com/)
- Built for the Presales AI Specialist conversation with Simpson Associates
- Pre-loaded example data sourced from Simpson's [North Yorkshire Council case study](https://www.simpson-associates.co.uk/clients/north-yorkshire-council/)

---

## Tech notes

- Single-file React (CDN — no build step)
- PptxGenJS for the PowerPoint export
- Google Fonts: Manrope (body) + Source Serif 4 (display)
- Tested with Chrome, Edge, Safari, Firefox
