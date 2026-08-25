# New Vision Fellowship — Brand Guidelines

Human- and agent-readable guidelines. For structured data (hex values, font weights, asset
paths), read [`brand-kit.json`](brand-kit.json) — it is the source of truth. Its structure is
defined in [`brand-kit.schema.json`](brand-kit.schema.json) (JSON Schema, Draft 2020-12). Ready-
to-use CSS custom properties matching the JSON's canonical values live in
[`brand-tokens.css`](brand-tokens.css). A versioned ZIP of the complete kit — JSON, schema,
this file, the CSS tokens, a README, and every distributable NVF logo, ministry, and initiative
asset — is available from the brand kit site's Downloads section.

---

## The one-paragraph version

New Vision Fellowship exists **to multiply God's glory on the earth.** Our visual identity is
warm, grounded, and editorial — closer to a well-made print piece than a typical church website.
Deep charcoal for drama, warm off-white paper for reading, and a green palette drawn from the leaf
in our logo. Strong sans-serif headlines, a readable serif for body copy, and one hand-script
flourish per piece. Charcoal and Paper carry every background — never pure black or pure white
outside of untouched logo artwork, and never a cold gray.

---

## Voice

**Write like a trusted friend who is a little further down the road:** warm, direct, unhurried.

We are inviting people into something bigger than themselves, so we open doors rather than push.
Grace and truth are not rivals — we say hard things kindly and clearly, and we never hedge them
into vagueness. Plain language carries profound ideas. Concrete detail earns trust where
superlatives do not.

Before publishing, ask: *Would a first-time guest understand this, and would a longtime member
recognize us in it?*

### Do

- Write to "you" in active voice — "you can take your next step," not "individuals are encouraged to"
- Choose the shorter, plainer word; explain any church term a guest would not know
- Be specific — real names, real numbers, real streets earn trust
- Invite warmly: "There's a seat for you here"
- Say hard truths kindly and plainly
- End with one concrete next step: verb + what happens + where to go
- Keep sentences mostly short; read aloud and cut anything breathless
- Title Case for titles, ALL CAPS for short labels, sentence case elsewhere
- Exactly one warm, human flourish per piece
- Paragraphs of one idea, three or four sentences maximum

### Don't

- No urgency or FOMO — "don't miss out," "limited time," "last chance"
- No hype words — amazing, incredible, life-changing, unlock
- No corporate speak — leverage, utilize, engagement, onboarding, stakeholders
- No insider shorthand used cold — unpacking, doing life, pouring into, seasons
- No hedging — just, kind of, sort of, maybe
- Never imply anyone is behind, failing, or missing out
- Never write about "people" in third person when you mean the reader
- Never substitute superlatives for evidence — show the number
- No more than one script flourish or exclamation point per piece
- Never straight quotes or apostrophes; always curly

### Phrases that sound like us

> "There's a seat for you here."
> "Let's get moving for the Master."
> "A doorway, not a gate."
> "Serving isn't the finish line, it's the starting line."
> "Grace and truth are not rivals."
> "If you can find us, you can worship with us." *(from our church-plant years)*

---

## Color

**The governing principle: dark, dramatic moments plus light, readable content.** Use deep
charcoal for covers, hero bands, and dividers. Keep the bulk of reading on warm off-white paper.

**Application palette vs. logo colors.** The greens below are the canonical
**application-palette** colors — used for layouts, backgrounds, accents, CSS tokens, website
styling, and newly created branded materials. Official logo artwork carries its own,
separately-set green(s) baked into each file (see each asset's `colors` field in
`brand-kit.json`). The two are deliberately allowed to differ slightly — logo colors are
immutable, asset-specific values read from the artwork itself, and must **never** be edited to
match this palette. Always use logo files exactly as supplied.

| Role | Name | Hex | Notes |
| --- | --- | --- | --- |
| Primary | Brand Leaf Green | `#5f9a32` | On light backgrounds. Canonical application-palette green |
| Primary, deep | Green Deep | `#42701f` | Small text and links on light |
| Primary, bright | Green Bright | `#74ca33` | **Dark backgrounds only.** Canonical application-palette green |
| Secondary | Olive | `#4a5d2f` | Muted supporting green |
| Secondary, deep | Olive Deep | `#37461f` | Dark green panels, white text |
| Dark surface | Charcoal | `#24201d` | Never pure black as a general background — see Rules below |
| Dark surface, lifted | Charcoal Lift | `#2d2823` | Raised elements on dark |
| Light surface | Paper | `#faf7f1` | Never pure white as a general background — see Rules below |
| Light surface, card | Paper Card | `#f1ece2` | Cards and wells |
| Light surface, deep | Paper Deep | `#e9e2d5` | Third layer |
| Text | Ink | `#221f1b` | Body and headings on light |
| Text, soft | Ink Soft | `#4a443d` | Secondary copy |
| Text, metadata | Metadata | `#6d675b` | Small uppercase labels and swatch metadata on light backgrounds — passes WCAG AA where Ink Soft reads too heavy |
| Text, metadata on dark | Metadata Dark | `#9a8f81` | Small labels and metadata on Charcoal |
| Line | Hairline | `#e1dacc` | Dividers on light — decorative only, never text |
| Line, dark | Hairline Dark | `#433d36` | Dividers on dark |

### The four accent colors

Earthy, green-anchored category colors, used to differentiate sections wherever four categories
need distinct colors — and **never grow to a fifth.** They happen to also color-code the four
on-ramps (Gather, Give, Group, Go), but outside that specific framework refer to them by color
name.

| Name | Hex | As a background, pair with |
| --- | --- | --- |
| Moss Green | `#5d8a3e` | Neither white nor Ink passes WCAG AA for normal text — large text, or border/rule/icon use only |
| Ochre | `#b3852b` | Ink (`#221f1b`) — white fails normal-text contrast on Ochre |
| Muted Teal | `#347b6f` | White |
| Terracotta | `#ae5230` | White |

**Text-safe variants.** Moss and Ochre themselves fail WCAG AA as small text on Paper — use these
darker tones instead, the same relationship Green Deep has to Brand Leaf Green:

| Name | Hex | Use |
| --- | --- | --- |
| Moss Deep | `#4a6e31` | Small text, labels, and links on light backgrounds |
| Ochre Deep | `#7d5d1e` | Small text, labels, and links on light backgrounds |

### Digital / interactive colors

**For on-screen product UI only** — app-like screens, buttons, links, hover states, and small
badges on very dark backgrounds, as used on my.nvf.life. Print, booklets, and announcement
graphics keep using the palette and accents above, not these. Tiny interactive elements need more
lightness and chroma than a printed page does to stay legible and tappable against a near-black
screen.

| Role | Name | Hex | Notes |
| --- | --- | --- | --- |
| Dark surface | UI Charcoal | `#1b1815` | A touch darker than Charcoal, for contrast against the greens below |
| Link | Interactive Green | `#93d86a` | Links and secondary interactive text |
| Button | Interactive Green, Bold | `#7fd142` | Primary buttons and other high-emphasis controls |
| Alert | Alert Red | `#a94442` | Errors, destructive actions, required-field warnings — the only red in the system |
| Badge | Badge Teal | `#45a394` | Small tags and badges, where Muted Teal needs more lift |
| Badge | Badge Ochre | `#cf9f3f` | Small tags and badges, where Ochre needs more lift |

### Rules

1. Never use pure black or pure white as general background colors. Use Charcoal and Paper
   instead. Pure black or white may remain where it is part of approved, unmodified logo artwork
   or required one-color reproduction.
2. Greens lead. Accents differentiate categories. Warm neutrals carry everything else.
3. On dark backgrounds, swap Brand Leaf Green for Green Bright.
4. One or two background colors per composition. No more.
5. Never use the digital/interactive colors above in print or static compositions.
6. Before pairing any text color with any background color, check the accessibility table below.
   Never place normal-size text in a pairing that isn't marked safe for normal text.

### Accessibility

Every meaningful text/background pairing in this system has been checked against WCAG 2.1 AA
(4.5:1 for normal text, 3:1 for large text — 18pt/24px+ regular or 14pt/18.66px+ bold). Small
uppercase tracked labels count as normal text, not large text. The full, current table — with
exact ratios — lives in `color_system.accessibility.pairings` in `brand-kit.json`; a few of the
non-obvious ones:

- **Brand Leaf Green as a background** passes with Ink (`#221f1b`) text, not white — white only
  clears the large-text minimum.
- **Ochre as a background** passes with Ink text, not white — the same white-text instinct that
  works on Terracotta and Muted Teal does not work on Ochre.
- **Moss as a background** doesn't clear normal-text contrast with *either* white or Ink text —
  reserve it for large text, borders, rules, icons, or other decorative use, or set small text in
  a light chip instead of directly on the fill.
- **Green Bright never goes on Paper** — it fails even the large-text minimum there.

If a pairing you need isn't in the table, calculate the WCAG contrast ratio — don't guess from how
a color looks.

---

## Typography

Three families, each with one job.

- **Archivo** (400–900) — every heading, title, label, kicker, number, and UI element. Tight
  letter-spacing on large sizes; wide tracking on small uppercase labels.
- **Source Serif 4** (Georgia fallback) — all body and long-form copy. Line-height 1.4–1.6. Always
  apply `text-wrap: pretty`.
- **Kaushan Script** — one warm accent per composition. A greeting, a value name, a caption
  lead-in like *"We are…"*. **Never** body copy or critical information.

> The On-Ramp cover lockup also uses **Tan St. Canard**, **Breathing**, and **DM Sans**, set in
> Canva. Those are specific to that lockup and are not needed for general brand work.

### Font sources

- **Archivo** — [fonts.google.com/specimen/Archivo](https://fonts.google.com/specimen/Archivo)
- **Source Serif 4** — [fonts.google.com/specimen/Source+Serif+4](https://fonts.google.com/specimen/Source+Serif+4)
- **Kaushan Script** — [fonts.google.com/specimen/Kaushan+Script](https://fonts.google.com/specimen/Kaushan+Script)

Fonts are provided by their respective sources. Follow the source's current terms when
downloading or distributing them. This kit does not host font files.

### Minimum sizes

- **Print:** body copy between 12pt and 15pt.
- **Projected:** minimum text height is `viewing distance ÷ 200`. At 40 feet that is 2.4 inches —
  on a 1920px canvas across a 130in screen, roughly 36px. Comfortable is `÷ 150`.
- **QR codes on screen:** a code must be roughly 12–15× its width away to scan. At 40 feet that
  means 30–38 inches on screen. A QR code tucked beside body copy will not scan from the seats —
  give it a dedicated slide.

---

## Logo usage

The **stacked lockup** (NEW VISION over FELLOWSHIP with the leaf mark) is our primary logo. Use the
**horizontal wordmark** only when vertical space is constrained.

- Prefer SVG everywhere.
- **Match the variant to the background.** The `black_text` variant has a **charcoal** wordmark and
  is for light backgrounds. The `white_text` variant has a **white** wordmark and is for charcoal
  and photographic backgrounds. Placing either on the wrong background makes the wordmark disappear.
- Single-color options: `all_white` (for dark) and `all_black` (for one-ink print).
- Maintain clearspace equal to the height of the leaf mark on all sides.
- Never stretch, recolor, rotate, or add effects. The green(s) baked into each logo file are
  immutable, asset-specific colors — they do not need to match, and must never be edited to
  match, the application palette in the Color section above. Always use logo files exactly as
  supplied.
- Never place the logo on a busy photo without a darkening veil beneath it.
- The **leaf mark** and **cross mark** alone work as a favicon, avatar, or small decorative accent
  — never as a substitute for the full logo in a primary placement.
- The horizontal wordmark is roughly **22:1**. Size it by width, not height — at 26px tall it runs
  well over 500px wide and will crowd anything beside it.

### Stacked lockup variants

| File | Colors | Use on |
| --- | --- | --- |
| `nvf-stacked-color.svg` | Charcoal + green | Light backgrounds &mdash; **the default** |
| `nvf-stacked-color-dark.svg` | White + green | Dark and photographic backgrounds |
| `nvf-stacked-white.svg` | All white | Dark, where green cannot reproduce |
| `nvf-stacked-black.svg` | All charcoal | Single-color print |

### Horizontal wordmark variants

All flat, no cross. They vary by whether the wordmark is single-color or keeps the green leaf
accent.

| File | Colors | Use on |
| --- | --- | --- |
| `nvf-horizontal-black.svg` | All black | Light backgrounds &mdash; single-color, no green |
| `nvf-horizontal-color.png` | Black + green | Light backgrounds &mdash; keeps the green leaf |
| `nvf-horizontal-white.svg` | White + green | Dark backgrounds &mdash; keeps the green leaf |
| `nvf-horizontal-all-white.svg` | All white | Dark backgrounds &mdash; single-color, no green |

> `nvf-horizontal-white-text.png` is the same design as `nvf-horizontal-white.svg`, kept as a PNG
> for raster-only contexts. Prefer the SVG.

**Cross mark.** `nvf-cross-mark.svg` is the cross alone, in the same two-green pinwheel treatment
as the rest of the mark. Use it sparingly, the same way as the leaf mark.

---

## Signature design patterns

**Kicker → Title → Rule.** Nearly every section opens the same way: a small uppercase green
kicker, a large Archivo title, then a short rounded green rule bar.

**Cards.** Paper Card background, 10–20px radius, generous padding, and often a left or top accent
border in the category color.

**Contrast columns.** Two columns side by side — one light Paper Card, one Olive Deep with white
text and inline Green Bright highlights. We use this to contrast ideas (religion vs. the gospel).

**Image veil.** To place white text over photography, lay a bottom-weighted charcoal gradient over
the image, then set the caption in white Archivo with a Kaushan Script lead-in above it.

> ⚠️ **Never use blurred `text-shadow` for legibility.** Print and PDF engines rasterize
> large-blur shadows into visible translucent rectangles behind each line of text. Use the
> gradient veil instead.

**Timeline.** A vertical spine gradient from green to olive, years on the left in Archivo 900
green, alternating filled and outlined dots sitting on top of the spine.

**Road motif.** A winding road on dark asphalt — our On-Ramp metaphor made visual. Always veiled
before type goes on top.

---

## Photography & imagery

Direction for any photograph, video still, or AI-generated image — a booklet cover, an
announcement slide, a web hero, a social graphic, anything. Not scoped to one project.

**Mood.** Warm, cinematic, editorial — grounded, hopeful, and premium, like a well-made print
piece. Never garish, clip-arty, or corporate-stock.

**Lighting.** Golden-hour warmth and soft natural light, with a gentle film grain. Slightly
desaturated, warm-leaning color grade. Charcoal shadows, never crushed to pure black. Cinematic
but understated — no HDR, no harsh contrast.

**Motifs.**

- **Road.** A winding or open road — the journey of faith. Same idea as the road motif above,
  carried into photography.
- **Leaf and new growth.** A single leaf or a fresh sprout, echoing the leaf mark — visual
  shorthand for growth.
- **Pottery and clay.** Earthen vessels, hands shaping or holding clay, kiln-fired pottery — our
  picture of formation. The vessel and the material carry the meaning; a literal potter's wheel in
  motion is not required.
- **Hands.** Open, giving, or raised in worship.
- **Community.** People gathered, walking together, going out into neighborhoods and nations
  (Acts 2:41-47).

> Clay in the Potter's Hands is where our growth framework comes from (`frameworks.clay_stages`
> in brand-kit.json), rooted in Isaiah 64:8 — "We are the clay, and You our potter." It's literal
> too: the ground around our campus sits on some of the richest natural clay in the state.

**Composition.** Clean and minimal, with generous negative space and a strong focal subject at
shallow depth of field. When a shot will carry a text overlay, keep roughly a third of the frame
open and darker for it — see the image veil above for the treatment that finishes the job.

**Subject tone.** Real, candid, diverse, and intergenerational people — never stocky, staged, or
generic stock photography of people who are not our people. Authentic worship, service, and
hospitality. Reverent and joyful, never cheesy.

> Warm, cinematic, editorial photography in a charcoal-and-green palette — golden light, open
> roads, growing and shaped things, and authentic community — with minimalist composition and room
> for clean modern type.

### AI-generated imagery

Everything above applies to AI-generated images too — they follow the same mood, lighting,
motifs, composition, and subject tone. On top of that:

- Keep an internal record whenever final, published imagery is AI-generated or materially
  AI-altered.
- **Disclose AI use publicly** whenever a reasonable viewer might mistake the image for a real
  New Vision person, event, facility, ministry activity, mission trip, testimony, or historical
  moment.
- Never portray a generated person as an actual member, guest, employee, missionary, ministry
  recipient, or community resident.
- Never create an identifiable depiction of a real person without that person's permission.
- Never generate an image of a minor that implies it documents an actual New Vision activity.
- Never use AI to recreate, repair, extend, or redesign a logo — see Logo modification, below.
- Clearly label conceptual or illustrative AI imagery wherever the surrounding context could
  otherwise mislead a viewer into thinking it's documentary.

---

## Digital signage & motion

A high-impact, read-from-a-distance visual language — bold type, dark charcoal backgrounds, a
photo, minimal clutter. Born on the roadside digital sign, but the same mood, typography, motifs,
and motion also carry to Sunday-morning presentation slides (1920x1080) and, for some
announcements, Facebook/Instagram posts. It is not the definitive design for slides or social —
just one strong, on-brand option for them. Shares the mood, palette, and subject tone above, but
has its own typography and motion rules specific to this family of formats. Not for print or
general web.

**Extended dark shades.** Two additional near-black tones for high-contrast, distance-legible
signage only — `#171411` and `#0f0e0c`. Use alongside Charcoal, not as a replacement for it
elsewhere.

**Typography.** Archivo at 900 weight is the default — mostly uppercase, tight line spacing,
strong left alignment, never a thin weight for main text. When a design calls for an even more
condensed, distance-legible headline than Archivo provides, approved alternates are Anton, Bebas
Neue, League Spartan, Montserrat ExtraBold, Oswald Heavy, or a Druk-style condensed face, used
sparingly — not a replacement for Archivo elsewhere in the brand. Off-white text on dark; green
reserved for emphasis words only.

**Layout.** The composition principles are shared across formats; the exact split below is
specific to the roadside sign's wide canvas. On other canvases, keep the same feel — dominant
text, one supporting photo, a dark gradient for legibility, generous negative space — but adapt
the split to the aspect ratio rather than forcing 2:1.

- *Roadside sign* — a wide, roughly 2:1 billboard composition. Left 55–65% carries the headline;
  right 35–45% carries the photographic subject. A dark gradient overlay runs left to right so
  text stays readable.
- *Sunday slides* — 1920x1080 (16:9). The same dark, bold, text-forward feel, composed for a
  widescreen frame rather than the sign's 2:1 split — e.g. text over a full-bleed photo with a
  gradient veil, or a top/bottom split instead of left/right.
- *Social posts* — for select Facebook/Instagram announcements only, not every post. Adapt the
  same mood and typography to the platform's own canvas (square or vertical) rather than the
  sign's proportions.
- *Shared* — no more than one photo, no icon clutter, generous negative space. The logo, if used,
  sits small-to-medium in a corner as an exact flat asset only — never redrawn, distorted, or
  rearranged.

**Background motifs.** A large, very faint two-leaf shape in dark green or olive; a soft green
gradient glow; thin green accent lines; subtle dust or grain texture; an occasional very faint
hexagon or geometric pattern; a warm vignette at the edges; charcoal paper texture.

**Motion (for animated slides).** Text enters word-by-word with a quick scale-up-and-settle
"stomp" — slight overshoot, then lock into place, each word landing over 0.4–0.8 seconds total.
The background leaf motif slides or fades in from the left; the photo layer slides in from the
right, beneath the text; light parallax between the three layers; a single green accent line or
glow sweeps across once. Gentle film grain stays constant throughout. **Never** animate the people
themselves, and no bouncing, spinning, or excessive effects. Hold the finished slide long enough to
read; transitions between slides are smooth, dark, and understated.

> A bold, high-impact ministry-values look using authentic church photography, large readable
> typography, dark charcoal backgrounds, green brand accents, subtle leaf motifs, and cinematic
> editorial motion — born on the roadside sign, at home on Sunday slides and select social posts
> too — communicating clarity, warmth, conviction, mission, and community.

---

## Print specifications

There is no single fixed trim size, bleed, resolution, or color mode for New Vision print work —
those depend on the specific piece and the specific printer. An earlier version of this file
listed one project's numbers (Letter trim, 350 DPI, CMYK) as if they were universal; they were
not.

**Before sending a file to print, ask the printer for that job's trim size, bleed, minimum
resolution, color mode, and accepted file format**, and design to those numbers. Body copy runs
12–15pt regardless of the specific job.

Whatever the resolution turns out to be, measure it at the image's *placed* size, not its native
size — a 1500px photo is plenty at 1 inch wide and badly short at 8 inches wide. Keep important
content — faces, text, logos — safely inside the trim line so nothing critical is lost to the cut.

---

## Brand governance

**Brand steward:** Pastor Jeremy Parker and/or the church's Ministry Leadership Team.
**Contact:** 336.427.6264. **Last reviewed:** 2026-08-24.

**Permitted use.** New Vision Fellowship staff, volunteers, contractors, vendors, and ministry
partners may use these assets for authorized New Vision Fellowship communications and ministry
work. Permission is limited to the assigned NVF purpose and does not permit resale,
redistribution as a standalone asset collection, unrelated commercial use, political endorsement,
or an implication that NVF endorses an outside organization.

**Logo modification.** Use official logo files exactly as supplied. Proportional resizing and
normal placement (with clearspace, per Logo usage above) is fine. Never redraw, trace, regenerate,
approximate, rearrange, distort, rotate, recolor, crop, add effects to, or AI-recreate a logo, and
never type the church name in a font to imitate a missing logo. If a format you need doesn't exist
in this kit, request it from the brand steward rather than recreating it.

**No approval needed** for routine communications that use approved assets, verified facts, and
established formats.

**Approval required** from Pastor Jeremy Parker and/or the Ministry Leadership Team for:

- Any proposed logo or lockup modification
- Permanent signage
- Merchandise made for sale
- Paid advertising
- New co-branded lockups or prominent partner-logo arrangements
- Sensitive doctrinal, political, crisis, legal, or pastoral communications
- AI imagery that could be mistaken for a real NVF person, service, event, facility, or
  historical moment

**Copyright.** Unless otherwise identified, original New Vision Fellowship brand assets are
© 2026 New Vision Fellowship and are provided for authorized NVF ministry use. Third-party names,
logos, fonts, and partner marks remain the property of their respective owners and are governed
by their owners' terms.

---

## AI content rules

On top of the Voice section above, an AI agent drafting New Vision copy should never invent:
service times · event dates, times, prices, registration details, or locations · staff names or
titles · contact information · statistics or attendance figures · testimonies or quotations ·
ministry claims · facts about actual members, photographs, or events.

**When information is missing,** ask a concise clarifying question rather than guessing. If the
author explicitly asks for an incomplete draft anyway, use a visible placeholder such as
`[NEEDS EVENT DATE]`, list every unresolved placeholder at the end, and never represent the draft
as publication-ready.

**Scripture.** Preferred translation is the **NASB 2020**, unless the author specifies otherwise
— NASB95, CSB, and ESV are also acceptable in some cases when the author requests them. Never
blend translations or invent wording: use the exact text supplied by the author, or text verified
from an authorized source. If the wording can't be verified, ask for the passage text or cite the
reference only, without quoting it. Always name the translation (usually NASB 2020) when quoting
Scripture.

**Human review is required before publishing:** doctrinal claims · crisis communication ·
political or culturally sensitive subjects · allegations or legal matters · pastoral-care or
safety communication · children's materials · claims about real people or events · potentially
misleading AI imagery.

---

## Avoid

Aggressive gradient backgrounds · glassmorphism · emoji · drop shadows on text · pure black or
white as a general background (untouched logo artwork excepted) · cold grays · a fifth accent
color · Inter, Roboto, or Arial · cramped layouts · stock
photography of people who are not our people.
