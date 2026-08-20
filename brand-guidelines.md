# New Vision Fellowship — Brand Guidelines

Human- and agent-readable guidelines. For structured data (hex values, font weights, asset
paths), read [`brand-kit.json`](brand-kit.json) — it is the source of truth.

---

## The one-paragraph version

New Vision Fellowship exists **to multiply God's glory on the earth.** Our visual identity is
warm, grounded, and editorial — closer to a well-made print piece than a typical church website.
Deep charcoal for drama, warm off-white paper for reading, and a green palette drawn from the leaf
in our logo. Strong sans-serif headlines, a readable serif for body copy, and one hand-script
flourish per piece. Never pure black, never pure white, never cold gray.

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

| Role | Name | Hex | Notes |
| --- | --- | --- | --- |
| Primary | Brand Leaf Green | `#5f9a32` | On light backgrounds |
| Primary, deep | Green Deep | `#42701f` | Small text and links on light |
| Primary, bright | Green Bright | `#74ca33` | **Dark backgrounds only** |
| Secondary | Olive | `#4a5d2f` | Muted supporting green |
| Secondary, deep | Olive Deep | `#37461f` | Dark green panels, white text |
| Dark surface | Charcoal | `#24201d` | Never pure black |
| Dark surface, lifted | Charcoal Lift | `#2d2823` | Raised elements on dark |
| Light surface | Paper | `#faf7f1` | Never pure white |
| Light surface, card | Paper Card | `#f1ece2` | Cards and wells |
| Light surface, deep | Paper Deep | `#e9e2d5` | Third layer |
| Text | Ink | `#221f1b` | Body and headings on light |
| Text, soft | Ink Soft | `#4a443d` | Secondary copy |
| Line | Hairline | `#e1dacc` | Dividers on light |
| Line, dark | Hairline Dark | `#433d36` | Dividers on dark |

### The four On-Ramp accents

Earthy, green-anchored category colors. They color-code our four on-ramps — and **never grow to a
fifth.**

| On-Ramp | Name | Hex |
| --- | --- | --- |
| Gather | Gather Green | `#5d8a3e` |
| Give | Give Ochre | `#b3852b` |
| Group | Group Muted Teal | `#347b6f` |
| Go | Go Terracotta | `#ae5230` |

### Rules

1. Never pure black or pure white as a background.
2. Greens lead. Accents differentiate categories. Warm neutrals carry everything else.
3. On dark backgrounds, swap Brand Leaf Green for Green Bright.
4. One or two background colors per composition. No more.

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

### Minimum sizes

- **Print:** body copy no smaller than 12pt.
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
- **Match the variant to the background.** The `color` variant has a **charcoal** wordmark and is for
  light backgrounds. The `color_on_dark` variant has a **white** wordmark and is for charcoal and
  photographic backgrounds. Placing either on the wrong background makes the wordmark disappear.
- Single-colour options: `white` (all white, for dark) and `black` (all charcoal, for one-ink print).
- Maintain clearspace equal to the height of the leaf mark on all sides.
- Never stretch, recolor, rotate, or add effects.
- Never place the logo on a busy photo without a darkening veil beneath it.
- The **leaf mark** alone works as a favicon, avatar, or small decorative accent — never as a
  substitute for the full logo in a primary placement.
- The horizontal wordmark is roughly **22:1**. Size it by width, not height — at 26px tall it runs
  well over 500px wide and will crowd anything beside it.

### Stacked lockup variants

| File | Colors | Use on |
| --- | --- | --- |
| `nvf-stacked-color.svg` | Charcoal + green | Light backgrounds &mdash; **the default** |
| `nvf-stacked-color-dark.svg` | White + green | Dark and photographic backgrounds |
| `nvf-stacked-white.svg` | All white | Dark, where green cannot reproduce |
| `nvf-stacked-black.svg` | All charcoal | Single-colour print |

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

## Print specifications

| Setting | Value |
| --- | --- |
| Trim | 8.5 × 11 in |
| With bleed | 8.625 × 11.125 in |
| Bleed | 0.125 in |
| Resolution | 350 DPI |
| Color mode | CMYK |

**Measure DPI at placed size, not native size.** A 1500px photo is plenty at 1 inch wide and
badly short at 8 inches wide. Keep important content — faces, text, logos — at least 0.25in inside
the trim line so nothing critical is lost to the cut.

---

## Avoid

Aggressive gradient backgrounds · glassmorphism · emoji · drop shadows on text · pure black or
white · cold grays · a fifth accent color · Inter, Roboto, or Arial · cramped layouts · stock
photography of people who are not our people.
