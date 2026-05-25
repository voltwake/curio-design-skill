---
kind: reference
format: poster
about: "Reference patterns for composing single-page posters from a Curio DESIGN.md. NOT a required template."
---

> **⚠ This is a REFERENCE, not a template.** The canonical rules for
> using any Curio design live in the top-level `SKILL.md`. Read those
> first. Use this file only when you want inspiration for poster
> *composition* (5 layout presets, common dimensions, focal-point
> ideas). The user's actual ask trumps anything here — pick a preset
> that fits the design's character, or invent your own composition
> entirely.

# Reference · Poster

A single visual canvas. Posters are where a design system shows off
hardest — typography is loud, color is committed, composition is the
whole point. Get this right and a Bauhaus poster vs an Art Deco poster
will look like they come from entirely different planets.

## Output format

- **One HTML file** with an absolutely-positioned canvas of fixed
  dimensions, ready to screenshot
- Default size: **1080 × 1350** (4:5, optimal for Instagram / 小红书
  cover / general social)
- Other supported sizes (specify in inputs):
  - `1080 × 1080` — square (Instagram feed)
  - `1080 × 1920` — vertical (Stories / Reels cover)
  - `1200 × 1500` — 4:5 print-ready at 150dpi
  - `2480 × 3508` — A4 at 300dpi (print)
- Single `<div class="poster">` with all elements absolutely positioned
  inside, so screenshot output is pixel-exact
- Fonts via `typography.families.googleFontsImport`

## Anatomy of a poster

| Zone | Purpose | Required? |
|---|---|---|
| **focal area** (top 1/2 or center) | The one thing the eye lands on first — title, hero number, icon, image, or shape | yes |
| **title block** | Main message in the design's heading font, very large | yes |
| **subtitle / body** | 1–3 lines of supporting copy | usually yes |
| **footer info strip** | Date / location / URL / hashtag / pricing | for events / promos |
| **decorative elements** | Shapes, lines, marks, motifs from the design's vocabulary | depends on design |

There is **no single layout** for posters. A good poster method gives
you composition options, not a fixed grid.

## Composition presets

Pick one based on the design's `composition` block and the subject:

### A. Centered classical
- Title center-aligned, centered in upper half
- Subtitle directly below
- Decorative element top + bottom (or none)
- Footer info bottom-center
- **Fits**: art deco, classical serif designs, ceremonial / luxury

### B. Asymmetric grid (Swiss / Bauhaus / brutalism)
- Title aligned to a strict left or right grid line, often spanning
  multiple "columns" of an implied 6 or 12-col grid
- Subtitle offset deliberately to break/extend the grid
- One large decorative shape (circle / square / triangle / line) in
  primary color, sized to anchor the composition
- Footer in mono or condensed type at bottom-left or bottom-right
- **Fits**: Bauhaus, Swiss international, brutalist, modernist

### C. Editorial magazine
- Big serif title with body text wrapping or layered
- Pull-quote treatment for subtitle
- Footer info treated like a masthead (small caps, divided by pipes)
- **Fits**: editorial, parchment, NYT-style, Substack-ish

### D. Decorative envelope (Memphis / Art Nouveau / Vaporwave)
- Title smaller relative to canvas — let the design's decorations dominate
- Multiple decorative elements (squiggles, shapes, patterns) frame and
  invade the text area
- Subtitle layered or rotated
- **Fits**: Memphis, art nouveau, vaporwave, Y2K, afrofuturism

### E. Hero photo / illustration
- Full-bleed image (or AI-gen placeholder block) covering 60–70% of canvas
- Title overlaid in primary color or inverse text on a darker region
- Body text in a flat-color band at bottom
- **Fits**: photo-led campaigns, product promo, event posters

**Rule of thumb**: read the design's `## Overview` `composition cues` and
`## Applications` sections. They usually point at one of these.

## Mapping DESIGN.md → poster

### Canvas

| Element | Token |
|---|---|
| Poster background | `colors.background.page` (or a primary-color block if dramatic) |
| Canvas border (rare, design-dependent) | `borders.width.thick` solid `borders.color.default` |
| Inner padding | `spacing.scale[9]` (≈64px) for social, `scale[10]` (≈96px) for A4 |

If `meta.isDark = true`, dark background, light type. If the design's
character is "saturated primary as background" (Bauhaus often does
this for posters), use `colors.primary.500` as bg with `text.inverse`.

### Typography (this is where posters earn their identity)

| Element | Font | Size | Weight |
|---|---|---|---|
| Main title | `typography.families.heading` | **massive** — `typography.scale.7xl` or larger (use raw `clamp(6rem, 15vw, 14rem)` for hero impact) | `weights.bold` or `extrabold` |
| Subtitle | `typography.families.heading` or `body` (depends on design) | `typography.scale.2xl` or `3xl` | `weights.medium` or `normal` |
| Body | `typography.families.body` | `typography.scale.lg` | `weights.normal` |
| Footer info | `typography.families.body` or `mono` | `typography.scale.sm` | `weights.medium` |
| Decorative caps / labels | per design's letter-spacing rules | varies | per design |

**Apply the design's specific typography rules**:
- Bauhaus uses lowercase + wide letter-spacing on caps blocks
- Art Deco uses uppercase + medium tracking + condensed serifs
- Vaporwave uses gradient or chrome-effect on display type
- Hand-drawn designs use the design's `display` or `script` font
- Editorial uses serif headings with tight tracking

### Color

- Use **2–3 colors max** on a poster (the design's bg, primary, and one
  accent). Posters that use the full palette look noisy.
- The dominant color depends on composition preset:
  - Centered classical → mostly background + ink, one accent on title
  - Asymmetric grid → big block of primary color, with text in inverse
  - Editorial → mostly background + ink, accent in a single decorative element
  - Decorative envelope → 2–3 colors actively used as compositional elements
  - Hero photo → photo carries color, type is monochrome

### Decorative elements (this is what makes a poster "look like the design")

Read the design's `## Techniques` block. If there's anything like:
- "Geometric shape badge" → use shapes as compositional anchors
- "Squiggle / sticker / patch motif" → use them as background or framing
- "Hard-offset shadow" → apply to the title block (offset duplicate in
  accent color) for a screenprint effect
- "Pattern fill" / "tile fill" / "grain" → use as background texture
- "Marquee" / "ticker" / "scroll text" → use as edge decoration

If the design lists `iconography.set: lucide` (or similar), you can use
2–3 icons as decoration, sized large, in `colors.primary.500`.

### Shapes / borders / shadows

- `composition.framing: bordered` → poster has a visible inner or outer
  border (use `borders.width.thick` for poster scale)
- `borders.radius` → all decorative rectangular elements use this radius
  (0 for Bauhaus, large for friendly designs)
- `shadows.lg` or `xl` → apply to the title block or decorative shape
  for depth (skip if `surfaceStyle: flat`)

## Subject-specific guidance

### Event poster
- Title = event name
- Subtitle = tagline or speaker / artist names
- Footer = **date · time · venue · URL or QR placeholder**
- Use composition preset **B (asymmetric grid)** or **A (centered classical)**

### Product / announcement poster
- Title = product name
- Subtitle = one-line value prop
- Footer = launch date / where to buy / hashtag
- Use composition preset **E (hero photo)** with mockup placeholder, or
  **B (asymmetric)** with the product shape as the anchor

### Promo / sale poster
- Title = the deal (50% OFF / FREE SHIPPING / etc.)
- Big number treatment
- Use composition preset **D (decorative envelope)** for playful, or
  **B (asymmetric)** for bold

### Quote / motivational poster
- Title = the quote (in quote marks per design)
- Subtitle = attribution
- Use composition preset **C (editorial magazine)** with pull-quote
  treatment

### Movie / show / album poster
- Title = the work's name, very large
- Subtitle = release date / starring / cast list
- Use composition preset **E (hero photo)** with image placeholder

## DO

- Make ONE element absolutely dominate. A poster with no clear focal
  point reads as "design school exercise"
- Use the design's actual fonts at huge sizes — that's where they shine
- Apply the design's `## Techniques` aggressively — posters are where
  these get to show off
- Snap all elements to a baseline grid (`composition.rhythm`)
- If `composition.gridIntensity: strong`, expose alignment guides as
  faint visible lines in `colors.text.muted` at low opacity

## DON'T

- Don't fill every corner — posters need negative space
- Don't add stock "design" decorations (drop shadows, gradients,
  bevels) that the design doesn't have
- Don't use more than 2–3 colors
- Don't use Lorem Ipsum for the title — the title IS the design;
  if user didn't provide one, ask for it
- Don't include a Curio watermark on the visible canvas — credit goes
  in a `<small>` below the poster div, not on the design itself

## Skeleton (paste this and fill)

```html
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>Poster — {{subject}}</title>
<style>
  @import url('{{design.typography.families.googleFontsImport}}');
  :root {
    --bg:       {{design.colors.background.page}};
    --ink:      {{design.colors.text.primary}};
    --ink-2:    {{design.colors.text.secondary}};
    --primary:  {{design.colors.primary.500}};
    --accent:   {{design.colors.accent.500}};
    --font-h:   {{design.typography.families.heading}};
    --font-b:   {{design.typography.families.body}};
  }
  body { background: #222; margin: 0; padding: 24px; display: grid; place-items: center; }
  .poster {
    width: 1080px; height: 1350px;
    background: var(--bg);
    color: var(--ink);
    font-family: var(--font-b);
    position: relative;
    overflow: hidden;
  }
  /* Compose absolute-positioned title, subtitle, footer, decoration here */
</style>
</head>
<body>

<div class="poster">
  <h1 style="font-family: var(--font-h);
             font-size: clamp(6rem, 15vw, 14rem);
             line-height: 0.9;
             position: absolute;
             top: 96px; left: 96px;">{{title}}</h1>
  <p style="position: absolute; top: ...; left: ...;">{{subtitle}}</p>
  <!-- decorative shapes -->
  <div class="footer-info" style="position: absolute; bottom: 96px; left: 96px;">
    {{date}} · {{venue}} · {{url}}
  </div>
</div>

<small>Design: <a href="https://designbycurio.com/{{design.id}}">{{design.name}}</a></small>

</body>
</html>
```

## Example invocation

User: "Make a poster for my design talk on Friday, in Bauhaus style.
Title: 'Form Follows Function: A Century of Bauhaus'. Venue: SCMP,
Hong Kong. Date: 2026-06-13."

You should:
1. Read `designs/bauhaus-weimar.md`
2. Read this method
3. Use composition preset **B (asymmetric grid)** — matches Bauhaus's
   `gridIntensity: strong` and historic poster lineage
4. Layout: title spans 8 of 12 implied columns, set in lowercase Josefin
   Sans, wraps to 3 lines, in `colors.text.primary` (near-black)
5. One large yellow circle (Kandinsky's accent.500) anchors the
   composition in the upper-right
6. Subtitle below title in Work Sans, modest size
7. Date · venue · URL strip at the bottom in uppercase Work Sans with
   wide letter-spacing, divided by pipe characters in red
8. Background = cream `#f4ecd8` (Bauhaus paper)
9. Hard-offset shadow on the title for screenprint feel
10. Save to `poster-bauhaus-talk.html`

Same brief in `designs/art-deco-jazz-age.md` should yield a completely
different result — centered classical composition, gold-on-black,
chevron decorations, uppercase Didone-style serif title, sunburst motif
behind the title, date set in geometric monogram style.
