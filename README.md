# Noted

A private app for couples. Each partner keeps notes on the other (sizes, favorite things, things they mentioned wanting, important dates), and Noted suggests gifts with shop links around those dates. One subscription covers both partners.

This repo holds the clickable high-fidelity prototype, designed at iOS 390 × 844.

## What's here

| File | What it is |
| --- | --- |
| `Main.dc.html` | The whole prototype: every screen, sheet and interaction lives here |
| `Partner.dc.html`, `Moment.dc.html`, `QuickAdd.dc.html`, `Family.dc.html` | Frames that open `Main` straight into a given screen |
| `HomeDark.dc.html`, `PartnerDark.dc.html`, `MomentDark.dc.html` | The same, in dark mode |
| `Repair.dc.html`, `RepairResult.dc.html`, `RepairSafety.dc.html`, `RepairPaywall.dc.html` | The Make it right feature: input, response, safety state, free-limit paywall |
| `canvas.json` | Canvas layout: frame positions, titles and order |

## Screens

- **Home**: moments row (upcoming dates, nearest one emphasized) and a gift feed tied to the nearest moment
- **Partner profile**: Instagram-style profile with stats, highlights (Sizes, Food, Style, Flowers, Don't buy) and a 3-column grid of notes
- **Quick add**: photo, link, note or date, tagged in a few taps
- **Moment detail**: countdown, three picks drawn from notes, gifts given before
- **Family**: mini profiles for her family, with dates, notes and gift ideas
- **You**: shared subscription, privacy, dark mode toggle
- **Make it right**: a private repair assistant for after a fight, with a safety state and a soft paywall after 3 free uses

## Design system

- Ground: warm cream `#F5EFE6` (dark `#16120F`)
- Ink: `#221C18` (dark `#F2EAE0`)
- Accent: wine `#8A2E3B`
- Type: Newsreader for names and headings, Hanken Grotesk for UI

## Note on running it

These are Design Component (`.dc.html`) files from a Claude Design canvas. They load a `support.js` runtime that the canvas provides, so opening them directly in a browser won't render them. Treat this repo as the design source and reference for building the real app.

Placeholder content: couple Arjun and Meera. Prices marked `[PRICE]` are still to be decided.
