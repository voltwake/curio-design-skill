---
kind: reference
format: deck
about: "Reference patterns for composing slide decks from a Curio DESIGN.md. NOT a required template."
---

> **⚠ This is a REFERENCE, not a template.** The canonical rules for
> using any Curio design live in the top-level `SKILL.md`. Read those
> first. Use this file only when you want inspiration for slide-deck
> *structure* (typical slide types, common 10-slide pitch ordering,
> token-mapping ideas). The user's actual ask trumps anything here —
> don't pad to 10 slides if 6 fits, don't force a "data slide" if
> there's no data, don't use this slide-type table as a checklist.

# Reference · Slide Deck

Build a presentation deck out of a Curio design. **You** provide the
structure and content rules; the **DESIGN.md** provides every visual
token. The output should look unmistakably like the chosen design —
a Bauhaus deck and a wabi-sabi deck of the same content should be
visually unrecognizable as siblings.

## Output format

- **One HTML file**, one `<section class="slide">` per slide
- Slide dimensions: `width: 1280px; height: 720px;` (16:9), centered in
  viewport, one slide visible at a time
- Navigation: arrow keys + click-to-advance (small inline JS)
- Print-friendly: each slide is a CSS `@page` boundary so the user can
  Cmd+P → "Save as PDF" → ready for upload to Google Slides / Keynote
- All fonts loaded via `typography.families.googleFontsImport`

## Slide types (compose these — not every deck uses all)

| Type | When to use | Required elements |
|---|---|---|
| **cover** | Always slide 1 | Title, optional subtitle, optional author/date, optional logo placeholder |
| **section divider** | Between major sections (every 3–5 slides) | Large numbered marker (01, 02…), section name |
| **content** | Body of the deck | 1 heading + 3–5 bullets OR 1 heading + 2-column layout |
| **data** | Numbers, charts, comparisons | Big number (one), label, optional chart |
| **quote** | Pull quote, testimonial, principle | Large quote text + attribution |
| **closing** | Always last slide | "Thanks" / CTA / contact info |

A 10-slide deck typically goes: cover · 2 content · section · 2 content
· data · quote · content · closing. A 14-slide pitch deck typically goes:
cover · problem · solution · why-now · product · market · traction · biz
model · GTM · team · ask · thanks.

## Universal slide rules (apply to all types)

- **Maximum ~30 words per slide.** If you have more, split into multiple
  slides. If you can't split, this is a doc, not a deck — switch method.
- **One idea per slide.** Don't pack two thoughts into one.
- **Title goes top-left or top-center.** Pick one and stay consistent.
- **Page number bottom-right** in `colors.text.muted` at `typography.scale.xs`.
- **Generous padding.** Use `spacing.scale[8]` (≈48px) minimum on slide edges.

## Mapping DESIGN.md → deck

This is the bridge. Every visual decision points back at a token.

### Slide canvas

| Element | Token |
|---|---|
| Slide background | `colors.background.page` |
| Slide border (if design uses `composition.framing: bordered`) | `borders.width.default` solid `borders.color.default` |
| Inner padding | `spacing.scale[8]` to `spacing.scale[9]` |

If `meta.isDark = true`, swap to dark tones — page bg gets darker,
text gets `colors.text.inverse` if defined, else light neutral.

### Typography

| Slide element | Token (family) | Token (size) | Token (weight) |
|---|---|---|---|
| Cover title | `typography.families.heading` | `typography.scale.6xl` or `7xl` | `weights.bold` or `extrabold` |
| Section divider number | `typography.families.heading` | `typography.scale.7xl` | `weights.bold` |
| Section divider name | `typography.families.heading` | `typography.scale.3xl` | `weights.semibold` |
| Content slide heading | `typography.families.heading` | `typography.scale.4xl` or `5xl` | `weights.semibold` |
| Content bullets | `typography.families.body` | `typography.scale.xl` or `2xl` | `weights.normal` |
| Data big number | `typography.families.heading` | `typography.scale.7xl` | `weights.bold` |
| Data label | `typography.families.body` | `typography.scale.lg` | `weights.medium` |
| Quote text | `typography.families.heading` | `typography.scale.4xl` | `weights.normal` |
| Quote attribution | `typography.families.body` | `typography.scale.base` | `weights.medium` |
| Page number / footer | `typography.families.body` | `typography.scale.xs` | `weights.normal` |

Line height: `typography.lineHeights.tight` for big headings, `normal`
for body. Letter spacing: respect any `typography.letterSpacing` rules
in the design (e.g., Bauhaus uses wide tracking for caps).

### Color usage

- **Accent / numbers / dividers / underlines** — `colors.primary.500`
- **Section-divider full background block** (optional dramatic choice) —
  `colors.primary.500` or `colors.secondary.500` (whichever fits mood),
  with text in `colors.text.inverse`
- **Data callouts** — number in `colors.primary.500`, label in `text.primary`
- **Quote marks** — `colors.accent.500` or `colors.primary.500`
- **Page number** — `colors.text.muted`
- **Bullets / list markers** — small geometric mark in `colors.primary.500`
  (use the design's `iconography.set` if specified; otherwise a simple
  filled circle or square)

### Components

If the deck has a CTA button on the closing slide, use
`components.button.primary` exactly as specified (background, color,
border, shadow, hover state, font weight, letter-spacing, text-transform).

If the deck has cards (e.g., 3-up feature cards on a content slide),
use `components.card.base` exactly (background, border, radius, padding,
shadow).

### Shadows / borders / radii

- Cards / images use `shadows.md` and `borders.radius.md`
- Don't add shadows the design doesn't have. If `surfaceStyle: flat` and
  shadow ladder is all `none`, your slides are flat — no shadows anywhere.

### Motion

- If `motion.level: minimal` or the design lists no `hoverPatterns`,
  slide transitions are instant or simple fade
- If `motion.level: lively` or design uses spring easings, you can add
  a small slide-in transition
- Respect `motion.reducedMotion: true` → wrap transitions in
  `@media (prefers-reduced-motion: no-preference)`

## Reading the design's `## Techniques` section

The markdown body of a DESIGN.md often includes named techniques with
CSS snippets — e.g. Bauhaus's "Primary-color block accent" or "Hard-offset
shadow press." **Use them.** A section divider in Bauhaus should literally
use the block-accent technique; a hover state on the closing-slide button
should use the shadow-press technique.

If the design names a technique, the design's identity often *depends*
on that technique. A Memphis deck without squiggle accents isn't Memphis.

## DO

- Use the design's actual font families — load via `googleFontsImport`
- Apply `composition.framing` (bordered? card-bound? full-bleed?) to
  every slide consistently
- Match `composition.gridIntensity` — `strong` means visible alignment
  grid hints; `subtle` means whitespace-led
- Re-use the design's preferred shapes (Bauhaus = squares/circles;
  art deco = chevrons/sunbursts; vaporwave = grids/triangles)
- Read the design's `## Applications` section — it often says "best for
  X / Y / Z" which helps you decide deck tone (formal? playful?)

## DON'T

- Don't invent any color, font, or radius value not in the design tokens
- Don't add stock-presentation patterns (gradient hero, generic icons,
  rounded cards) when the design rejects them (Bauhaus = 0 radius;
  brutalism = no shadows; etc.)
- Don't force every slide to look the same — mix slide types
- Don't put more than one big idea on one slide
- Don't ignore `meta.isDark` — a dark design wants dark slides, not
  white ones with the dark accent color
- Don't use English typography defaults (`font-family: Helvetica`) when
  the design specifies Chinese / Arabic / display fonts — trust the
  design's font stack

## Skeleton (paste this and fill)

```html
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>{{topic}} — {{design.name}}</title>
<style>
  @import url('{{design.typography.families.googleFontsImport}}');
  :root {
    /* Pull every token you'll use into CSS vars */
    --bg:       {{design.colors.background.page}};
    --surface:  {{design.colors.background.surface}};
    --ink:      {{design.colors.text.primary}};
    --ink-2:    {{design.colors.text.secondary}};
    --ink-3:    {{design.colors.text.muted}};
    --primary:  {{design.colors.primary.500}};
    --accent:   {{design.colors.accent.500}};
    --font-h:   {{design.typography.families.heading}};
    --font-b:   {{design.typography.families.body}};
    --radius:   {{design.borders.radius.md}};
    --shadow:   {{design.shadows.md}};
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { background: #222; color: var(--ink); font-family: var(--font-b); }
  .slide {
    width: 1280px; height: 720px;
    background: var(--bg);
    padding: 64px;
    margin: 24px auto;
    position: relative;
    display: flex; flex-direction: column;
    /* apply design's composition.framing here */
  }
  .slide-num { position: absolute; bottom: 32px; right: 48px;
               color: var(--ink-3); font-size: 12px; }
  /* Per-slide-type styles here, all using vars above */
</style>
</head>
<body>

<section class="slide cover">
  <h1 style="font-family: var(--font-h); font-size: 96px;">{{title}}</h1>
  <p style="font-size: 22px; color: var(--ink-2); margin-top: 24px;">{{subtitle}}</p>
  <span class="slide-num">01 / {{total}}</span>
</section>

<!-- repeat for each slide type… -->

<script>
  // Optional: arrow-key nav, full-screen mode, etc.
</script>
</body>
</html>
```

## Example invocation

User: "Make a 10-slide pitch deck for our climate-tech startup, in
Bauhaus style."

You should:
1. Read `designs/bauhaus-weimar.md` (frontmatter + body)
2. Read this method file
3. Generate a 10-slide HTML deck following the pitch sequence
   (cover · problem · solution · why-now · product · market · traction ·
    biz model · team · ask)
4. Apply Bauhaus tokens throughout — red/blue/yellow primaries, Josefin
   Sans headings in lowercase, hard-offset shadows on cards, 0-radius
   corners, cream `#f4ecd8` background, 4px baseline grid alignment
5. Use the design's "primary-color block accent" technique for section
   dividers (full-bleed red slide with cream text)
6. Apply the design's "hard-offset shadow press" to the closing CTA button
7. Save to `pitch-bauhaus.html` and tell user where it is

Same prompt with `designs/wabi-sabi-tea.md` (if Pro) should produce
something **completely visually different** — muted ink-on-paper,
generous whitespace, irregular shapes, restrained type — but the same
10 conceptual slides.
