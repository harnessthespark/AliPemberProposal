# Ali Pember Proposal

A small branded proposal page and four interactive coaching-tool sketches, built as a pitch to Ali Pember (goodenoughmama.co.uk).

**Live:** [harnessthespark.github.io/AliPemberProposal/proposal.html](https://harnessthespark.github.io/AliPemberProposal/proposal.html)

## What's here

| File | What it is |
|---|---|
| `proposal.html` | The branded three-route proposal (Essentials £197 / Connected £347 / Bespoke £497) |
| `index.html` | Hub landing page — three doors to the sketches below |
| `window.html` | **Your Window** — Window of Tolerance tracker with Polyvagal Ladder nested inside; barometer slider, body/thoughts/behaviour notes, saved-moments log with export + send-to-coach |
| `shifting-states.html` | **Shifting States** — strategy library for rough water and settled fog; favourites, "pick one for me" nudge |
| `conditions.html` | **Conditions to Thrive** — three-circle CFT model (bracing/reaching/settling) + day-in-life audit + reflection prompts |
| `htso-logo.png` | Harness the Spark wordmark |
| `hero-wave.mp4` / `hero-wave-poster.jpg` | Hero background for window.html |

## Tech

Single-file HTML per page. No framework, no build step. Vanilla JS + CSS, Playfair Display + DM Sans from Google Fonts. All client state saves to `localStorage` — nothing is uploaded.

## Deploy

GitHub Pages auto-deploys on push to `main`. Build takes ~30–60s. No CI, no manual step.

## Notes

- Sketches use placeholder copy and a calm sand/paper palette. Final tools would be in Ali's voice and branding throughout.
- The "Send to your coach" button uses `mailto:` with the log pre-filled in the body — client-controlled, no backend.
- The proposal CTA uses Gmail's web compose URL (works without a default mail handler).

---

Made by [Lisa Gills](https://harnessthespark.com) · Harness the Spark
