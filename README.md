# NURA

A family health-intelligence platform — turning a family's scattered medical reports into understanding, foresight, and preparation for the person coordinating a loved one's recovery.

**Live site:** `https://stoicurious09.github.io/nura/` *(once GitHub Pages is enabled — see below)*

## Why this exists

When someone comes home from a hospital bed after a serious event, the medicine doesn't stop — the understanding does. A family with no clinical training inherits the job of tracking biomarkers, reconciling prescriptions across specialists, and knowing which trend is normal and which is a warning. NURA closes that gap: not a records drawer, not a chatbot — a curated, cited, evidence-graded intelligence layer built for the caregiver, not the hospital.

## What's in this repo

| Page | What it covers |
|---|---|
| [`index.html`](index.html) | The landing page — the story, the principles, links to everything below |
| [`team-brief.html`](team-brief.html) | Everything the team has learned, on one page — the fastest way in |
| [`strategy-report.html`](strategy-report.html) | Market sizing, competitive landscape, pricing benchmark, viability verdict |
| [`entry-strategy.html`](entry-strategy.html) | Porter's Five Forces, SWOT, and Blue Ocean analysis of the go-to-market entry point |
| [`biomarker-compendium.html`](biomarker-compendium.html) | The evidence base — biomarkers and lifestyle levers linked to risk and recovery, every claim graded and sourced |
| [`execution-playbook.html`](execution-playbook.html) | The offering, feature roadmap, team plan, pricing, and budget |
| [`dashboard-concept.html`](dashboard-concept.html) | A working concept demo of the product's family health dashboard |
| [`evidence-index.json`](evidence-index.json) | Machine-readable registry of every clinical claim, its evidence grade, and its sources |

Every page is a single self-contained HTML file — no build step, no dependencies. Open any of them directly in a browser, locally or on GitHub Pages. All pages support light and dark mode automatically (`prefers-color-scheme`).

## Principles this project holds to

- **Evidence, not opinion.** No clinical claim ships on a single paper — every insight is corroborated across guidelines, meta-analyses, and cohort studies, with citations shown.
- **The doctor stays the hero.** NURA explains, organizes, and prepares — it never diagnoses, prescribes, or advises changing treatment.
- **Trends over values.** A single test result rarely tells the story; the direction it's moving usually does.

## Publishing to GitHub Pages

This folder is the repo root. To serve it:

1. Push this repo to `stoicurious09/nura` (or any repo name) on GitHub.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — the site publishes at `https://stoicurious09.github.io/<repo-name>/` within a minute or two.

## Status

Early-stage strategy and product research, ahead of a 10-week concierge pilot with real families. This repo is the working archive for the team — update it as the pilot generates real data and the documents evolve.
