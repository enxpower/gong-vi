# Gong Tiejing — Personal Visual Identity

A private, modern steel-seal identity system. Engineer + founder. Graphite frame, copper light.

## View

Open **`index.html`** in any browser (double-click). No build step, no dependencies — every mark is inlined SVG.

## Contents

```
gong-vi/
├── index.html                         # full VI spec manual (self-contained)
├── README.md
└── assets/
    ├── mark-primary-seal.svg          # circular seal — formal / favicon source
    ├── mark-primary-seal-graphite.svg # same, graphite on light
    ├── mark-primary-seal-copper.svg   # copper on graphite (foil/press)
    ├── mark-secondary-chop.svg        # square chop — technical documents
    └── favicon.svg                    # reduced mark, legible to 16px
```

## The mark

A single letter **G**, compass-built with humanist terminals. Inside: a steel-beam
cross locked by a central **rivet** — the load-bearing point. 铁 (iron) · 靖 (steady).
No year is engraved; the seal is meant to outlast any single date.

| Mark | Use |
|------|-----|
| Primary seal (circular) | Signatures, official documents, favicon source |
| Secondary chop (square) | Engineering and technical documents |
| Favicon | App icons and anything below ~48px |

## Core tokens

| Token | Hex | Role |
|-------|-----|------|
| Graphite | `#1C2024` | Primary — marks, text, dark grounds |
| Cool Silver | `#9AA3AB` | Standard secondary |
| Copper | `#A8602F` | Warm accent — press/foil only |
| Gold | `#B08D3E` | Reserved — highest ceremony, physical |
| Paper | `#FDFCFA` | Light ground |

Type: Spectral (display) · Inter (body) · IBM Plex Mono (data). Latin only.

## Favicon usage

```html
<link rel="icon" type="image/svg+xml" href="/assets/favicon.svg">
```

---
Private identity system · not for public distribution.
