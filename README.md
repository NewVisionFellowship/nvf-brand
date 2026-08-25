# New Vision Fellowship — Brand

This repository is the single source of truth for New Vision Fellowship's brand assets, colors,
typography, and voice. It is designed to be consumed by **AI agents and automation tools** to
produce consistently branded work.

**Live at:** https://branding.nvf.life

## Agent instructions

Start with **`brand-kit.json`** — it contains all structured brand data in a single
machine-readable file. For tone, logo usage, and writing rules, read **`brand-guidelines.md`**.

All asset paths in the JSON are relative to the repository root; resolve them against `base_url`.

Never redraw, recolor, or AI-recreate a logo — see `governance.logo_modification_policy`. Never
invent service times, event details, staff names, contact info, or statistics — see
`ai_content_rules`. For AI-generated imagery, see `ai_imagery`.

When producing branded output, use **Brand Leaf Green (`#569c33`)** as the primary color on light
backgrounds and **Green Bright (`#74c933`)** on dark ones — both canonical values taken directly
from the official logo artwork — set headings in **Archivo** and body copy in **Source Serif 4**,
and follow the voice object. Before pairing any color with text, check
`color_system.accessibility.pairings`. Logos are SVGs in `logos/` — prefer the stacked lockup in
most contexts.

## Repository structure

| Path | Description |
| --- | --- |
| `brand-kit.json` | Machine-readable brand data — colors, typography, logos, frameworks, voice, governance, AI rules. **Start here.** |
| `brand-kit.schema.json` | JSON Schema (Draft 2020-12) describing the structure of `brand-kit.json` |
| `brand-guidelines.md` | Human- and agent-readable guidelines — voice, color, accessibility, logo usage, design patterns, governance |
| `brand-tokens.css` | CSS custom properties matching the JSON's canonical color, type, and radius values |
| `index.html` | Visual reference page for all brand assets, with copy and download controls |
| `downloads/nvf-brand-kit.zip` | The complete kit — JSON, schema, guidelines, CSS tokens, this README, and every distributable asset below |
| `logos/` | Primary logo lockups — stacked, horizontal wordmark, leaf mark, and cross mark |
| `sub-brands/` | Population-focused ministry logos — the Wheel, the Kiln, the Mill, Titus 2 Women, Men of Vision, Vintage Visions, Melding Moms |
| `initiatives/` | Initiative logos — Life Groups and Love My Neighbor Day |

## Asset conventions

**Variants.** Every asset entry includes a `variant` field — `color`, `white`, `black`, or
`white_text`.

**Backgrounds.** White variants are for dark backgrounds; color and black variants are for light
backgrounds. On a dark photographic background, always use the white variant.

**Formats.** Prefer SVG for all vector and programmatic use. PNGs are provided where no vector
original exists.

**Paths.** All paths are relative to the repository root and match the physical directory
structure.

## How to publish this

This repo is designed to be served as a static site so that both humans and agents can reach it
by URL.

1. Push this folder to a public GitHub repository.
2. In **Settings → Pages**, set the source to the `main` branch, root directory.
3. Add a `CNAME` file containing your subdomain (for example `branding.nvf.life`), then point a
   `CNAME` DNS record at `<your-org>.github.io`.

GitHub Pages then serves every file in the repo at a stable public URL:

- `https://branding.nvf.life/` → `index.html` (the human-readable page)
- `https://branding.nvf.life/brand-kit.json` → the machine-readable file agents fetch
- `https://branding.nvf.life/logos/nvf-stacked-white.svg` → any individual asset

Point an agent at the JSON URL and it can read the whole brand and pull exactly the asset it
needs.

## Quick reference

**Mission** — To multiply God's glory on the earth.
**Vision** — Multitudes shaped and sent for Christ.

**Core values**
1. Jesus takes center stage
2. God's Word grounds us
3. Grace and truth are not rivals
4. The gospel transforms how we live
5. People matter to God and to us

**The four On-Ramps** — Gather · Give · Group · Go

New Vision Fellowship · 1135 West Academy Street, Madison, NC · info@nvf.life · 336.427.6264
