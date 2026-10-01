# New Vision Fellowship — Brand Kit

Version 2026.09.7

This is the complete New Vision Fellowship brand kit: structured data, guidelines, CSS tokens,
and official logo, ministry, and initiative assets. It's meant to be handed to a designer, an
agency, a volunteer, or an AI agent so they can produce on-brand work without needing anything
else.

**Live source:** https://branding.nvf.life — always has the current version of everything in this
package, plus a visual reference page.

## Start here

1. **`brand-kit.json`** — the structured source of truth. Colors (with WCAG accessibility
   pairings), typography, logo and asset metadata, voice, governance, and AI-use rules, all in one
   machine-readable file. `brand-kit.schema.json` describes its structure (JSON Schema, Draft
   2020-12).
2. **`brand-guidelines.md`** — the same information in human-readable prose: voice and tone, color
   and accessibility rules, logo usage, design patterns, and governance.
3. **`brand-tokens.css`** — CSS custom properties for every color, using the same values as
   `brand-kit.json`.

## Package contents

```
brand-kit.json          Structured brand data — start here
brand-kit.schema.json   JSON Schema for brand-kit.json
brand-guidelines.md     Human-readable guidelines — read this for expanded guidance
brand-tokens.css        CSS custom properties matching brand-kit.json
README.md               This file
logos/                  Primary NVF lockups — stacked, horizontal wordmark, leaf mark, cross mark
sub-brands/             Population-focused ministry logos
initiatives/             Initiative logos (Life Groups, Love My Neighbor Day)
```

Logos are provided as SVG where an official vector source exists, alongside a transparent PNG
companion; a few official assets exist only as PNG and have no SVG. Check each asset's `format`
and `available_formats` fields in `brand-kit.json` rather than assuming a file type.

## Logo modification

Use official logo files exactly as supplied. Proportional resizing and normal placement (with
clearspace) is fine. Never redraw, trace, regenerate, approximate, rearrange, distort, rotate,
crop, add effects to, or AI-recreate a logo's shape. If a format you need isn't in this package,
**request it — don't recreate it.**

Default logo colors should be preferred where they don't clash with the surrounding design. When
the artwork calls for a different treatment, recoloring a logo's flat color fields is permitted
within reason, as long as its shape, proportions, and composition are left completely untouched.

## Fonts

This kit does not include font files.

- **Archivo** — https://fonts.google.com/specimen/Archivo
- **Source Serif 4** — https://fonts.google.com/specimen/Source+Serif+4
- **Kaushan Script** — https://fonts.google.com/specimen/Kaushan+Script

Fonts are provided by their respective sources. Follow the source's current terms when
downloading or distributing them.

## Brand steward

Pastor Jeremy Parker and/or the church's Ministry Leadership Team &middot; 336.427.6264

## Authorized use

New Vision Fellowship staff, volunteers, contractors, vendors, and ministry partners may use
these assets for authorized New Vision Fellowship communications and ministry work. Permission is
limited to the assigned NVF purpose and does not permit resale, redistribution as a standalone
asset collection, unrelated commercial use, political endorsement, or an implication that NVF
endorses an outside organization.

## Copyright

Unless otherwise identified, original New Vision Fellowship brand assets are © 2026 New Vision
Fellowship and are provided for authorized NVF ministry use. Third-party names, logos, fonts, and
partner marks remain the property of their respective owners and are governed by their owners'
terms.
