# Conquest Metagame — Brand Guide

Logo and identity system for *Conquest Metagame* by Nexxus Drako (Pyra Drake).

## Concept

The mark is an **invasion wheel**: an eight-slice wheel badge with a gold rim
and a pointer at 12 o'clock, echoing the game's core mechanic — spinning a
wheel to resolve an invasion. The hub carries a bold "C" monogram set in
gold, standing in for both **C**onquest and the token a player plants on a
captured **C**apital. Alternating crimson/charcoal slices double as a nod to
the "balkanized" map the game is played on.

The wordmark pairs a tall, condensed, tracked-out **CONQUEST** with a
narrow, wide-spaced **METAGAME** subtitle underneath, split by a two-tone
slanted bar (gold + crimson) for a sharp, graphic accent.

## Typeface

**[Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue)** — a free,
open-source, all-caps condensed display font licensed under the
[SIL Open Font License 1.1](https://scripts.sil.org/OFL). It's bold,
modern, and reads as "poster/military stencil," which fits a strategy
wargame without leaning on a licensed or closed font.

- Use it for the logotype, headlines, section titles, and UI callouts.
- All logo text has already been converted to vector outlines (see
  `svg/`), so **the font itself is not required to display the logo files**
  — only needed if you're setting new text (rules, UI, marketing copy) in
  the same style.
- Get it: `https://fonts.google.com/specimen/Bebas+Neue` or via
  `@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');`
- Pair it with a plain, highly-legible body font for rules text (e.g.
  **Inter** or **Source Sans 3**, both OFL/free) — Bebas Neue is display-only
  and should never be used for paragraphs.

## Color Palette

| Swatch | Name | Hex | Use |
|---|---|---|---|
| 🟥 | Conquest Crimson | `#B5121B` | Primary accent, aggression, invasion |
| ⬛ | Charcoal | `#1B1B1D` | Primary dark neutral, backgrounds, text on light |
| ▪️ | Gunmetal | `#2E2F33` | Secondary dark, wheel slices |
| 🟨 | Capital Gold | `#C9A227` | Rim, hub, tokens — the "prize" color |
| 🟡 | Gold Light | `#E4C25A` | Gold on dark backgrounds (better contrast) |
| ⬜ | Parchment | `#EDE6D6` | Light background (nods to the paint/dry-erase map) |
| ⬜ | Off-White | `#F7F4EC` | Text/logo on dark backgrounds |

Crimson + gold + charcoal is the core triad. Never introduce a fourth hue
into the logo itself; use the palette's neutrals to extend it in UI.

## Logo Files

```
branding/
├── svg/   vector masters — scale to any size, edit fills directly
└── png/   pre-rendered raster exports
```

| File | Purpose |
|---|---|
| `icon.svg` / `icon-*.png` | Full-color hero mark (wheel + hub). Use ≥64px. |
| `favicon.svg` / `favicon-*.png` | Simplified ring+hub+"C" badge for small sizes (browser tabs, app icons, 16–64px). |
| `icon-mono-black.svg`, `icon-mono-white.svg`, `icon-mono-gold.svg` | Single-color knockout badge (solid disc with the "C" cut out) for embroidery, stamps, watermarks, or any single-ink use. |
| `logo-horizontal-*.svg/png` | Icon + full wordmark side by side. `-light` for light backgrounds, `-dark` for dark, `-transparent` for placing over art/photos. |
| `logo-stacked-*.svg/png` | Icon above the wordmark — for square formats (social avatars, box art, title cards). |
| `wordmark-*-text.svg/png` | Wordmark alone, no icon — for tight horizontal spaces (headers, footers). |

All SVGs are pure vector paths (text has been converted to outlines), so
they render identically everywhere with zero font dependency.

## Usage Rules

**Do**
- Keep the gold rim and crimson/charcoal slices in that fixed ratio — don't recolor per-theme.
- Give the mark clear space on all sides equal to at least the width of one wheel slice.
- Use the `-transparent` lockup over photos or textured backgrounds.
- Use the simplified `favicon` mark, not the full wheel, below ~64px.

**Don't**
- Don't stretch or skew the icon (the wordmark's skew is baked into the vector — never re-skew it further).
- Don't recolor the wordmark to a color outside the palette.
- Don't place the dark-text wordmark on a dark background or vice versa — use the matching light/dark variant.
- Don't rotate the wheel icon; the pointer must stay at 12 o'clock.

## Attribution

Logo and brand assets © 2026 Pyra Drake, released under the same
**CC BY-SA 4.0** license as the game rules. Bebas Neue is © Ryoichi
Tsunekawa, licensed under the SIL Open Font License 1.1 — free for
commercial and non-commercial use with no attribution requirement, though
crediting the type designer is good practice.
