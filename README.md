# 🤝🏽 Inventure x Dakota F. - Technical Assessment

## 📑 Design Notes

I kept the surface area tiny and legible: semantic HTML, a single SCSS file for global rhythm, and restrained typography. The visual language leans on white space, a muted gray scale, and a single blue accent—aiming for “calm utility.” IA comes first: a hero with your copy, three scannable pillars (Broker Network, Marketing Engine, AI Learning), and a short “Next Iterations” note to signal product thinking.

Navigation is predictable and responsive. Cards and tiles are modular so future blocks—feeds, profile rows, permissioned spaces—slot in without layout churn. Accessibility basics are included (skip link, sensible landmarks, readable contrast).

- Accessibility touches: skip link, semantic landmarks, readable contrast.
- Minimal surface area to make iteration cheap.
- Components are intentionally simple so production features can drop in without layout churn.

**Next steps in a live product:**

- **Community:** public broker profiles, topic channels, and a permissioned “deal room.”
- **AI Lab:** guided sourcing prompts and interview rubrics backed by embeddings + retrieval over briefs, wins, and calibration docs.
- **Telemetry:** privacy-first analytics to steer iteration and measure improvements in time-to-signal across the funnel.

---

# 💻 Recruiting Without Limits — Next.js + SCSS Shell

A tiny, fast Next.js (App Router) site demonstrating clean IA, navigation, and responsiveness. No backend; just enough to show my thinking and future directions for the app.

## Run locally

```bash
npm i
npm run dev
# open http://localhost:3000
```

## 🚏 Pages / Routes

- `/` — Landing with provided copy + roadmap tiles
- `/community` — Broker directory, channels, and a “deal room” concept
- `/ai-lab` — Guided sourcing mock and rubric teasers

## 🛠️ Stack

- Next.js 14 (App Router)
- React 18
- SCSS (single global file + module styles for header/footer)
