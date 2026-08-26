# UA Fraud Carousel — Designer Brief

Wireframe brief for the Go Mobile Indonesia LinkedIn carousel on the mobile UA
attribution fraud case study. Nine slides, 1080 × 1350 px.

**Live:** `https://<your-username>.github.io/ua-fraud-carousel-brief/`

## What this is

A layout and device reference for the graphic designer — not final art. Brand
styling (sparkle texture, wordmark, gradients, display face) stays as per the
existing Go Mobile carousel system. What's fixed here is:

- the visual device on each slide
- the exact copy, with word counts
- the colour language

## Colour is information, not decoration

| Colour | Hex | Means |
|---|---|---|
| Grey | `#C7C1BC` | Normal / unproven supply |
| Red | `#D93B21` | Contaminated |
| Green | `#2FA24A` | Proven / genuine |
| Orange | `#F58220` | Go Mobile intervention |

Nothing else gets a colour. Orange does not appear until slide 5 — the slide
where we act.

## Slides

| # | Device |
|---|---|
| 01 | Dot grid — 22 of 100 red (feed thumbnail) |
| 02 | One bar splitting into sixty |
| 03 | Fake-attribution explainer |
| 04 | Day 1 → Day 2 spikes + rotation loop |
| 05 | The gate: proven vs capped lanes |
| 06 | Real daily fraud-rate chart |
| 07 | 525 → 588 as the hero |
| 08 | Audit status checklist |
| 09 | Bookend — same grid, one red dot |

## Notes for the designer

- Bar heights, chart line and dot positions are **sketches**. Slide 6 must use
  the real daily values from the source deck.
- Slides 01 and 09 are one asset with different red indices. Grid position and
  dot size must match exactly.
- All disclaimers (anonymisation, client measurement platform, proprietary
  method, the 1.7% organic band) live in the post caption, not on the slides.
- Deliver 1080 × 1350 PNG × 9, plus slide 1 at 1200 × 627 for the link preview.

## Running locally

No build step. Open `index.html` in a browser. The only external request is the
Google Fonts stylesheet; offline it falls back to system fonts and the layout
still holds.

## Deploying

Static site, served from the repository root.

1. Push to `main`.
2. Settings → Pages → Source: **Deploy from a branch** → Branch `main`, folder `/ (root)`.
3. Wait ~1 minute for the first build.

`.nojekyll` is included so GitHub Pages serves the files as-is.
