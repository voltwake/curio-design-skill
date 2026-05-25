---
kind: reference
format: card-social
about: "Reference patterns for composing social-media cards / carousels from a Curio DESIGN.md. NOT a required template."
---

> **⚠ This is a REFERENCE, not a template.** The canonical rules for
> using any Curio design live in the top-level `SKILL.md`. Read those
> first. Use this file only when you want inspiration for carousel
> *structure* (cover → idea → closing flow, platform dimensions,
> card-cardinality heuristics). The user's actual ask trumps anything
> here — card count comes from content volume, not from a template;
> platform choice comes from the user, not from a default.

# Reference · Social Cards

A series of N visually-tight cards designed to be screenshotted, posted
in carousel form (XHS / IG / LinkedIn), or as a single image (Twitter).
Each card carries one idea. Done well, every card in a Bauhaus carousel
should be recognizably Bauhaus even cropped out of context.

## Output format

- **One HTML file** with N `<div class="card platform-X">` blocks
- Cards stacked vertically in browser (for review); per-card screenshot
  ready
- Optional: a small "screenshot all cards" button at top that uses
  html2canvas (or instructs user to manually screenshot)
- Fonts via `typography.families.googleFontsImport`

## Platform dimensions and rules

| Platform | Dimensions | Aspect | Typical card count | Notes |
|---|---|---|---|---|
| **xhs (小红书)** | 1080 × 1440 | 3:4 | 3–9 (max 18 native) | Mobile-first, big type, generous padding, save-worthy content |
| **twitter / x** | 1200 × 675 | 16:9 | 1 (single image) or 2–4 (thread) | Wide format, headline + 1–2 lines body |
| **instagram-feed** | 1080 × 1080 | 1:1 | 1–10 (carousel) | Square, balanced composition |
| **instagram-portrait** | 1080 × 1350 | 4:5 | 1–10 (carousel) | Best engagement, taller than square |
| **linkedin** | 1200 × 627 | ~16:8.4 | 1–10 (document post) | Cleaner / more corporate tone usually |

**XHS-specific rules** (since it's the most popular case):
- Mobile-first viewing → minimum 32px (24px font-size) for body text
- Add small watermark bottom-right (author handle + date) per XHS norms
- Cover card determines whether anyone clicks — make it scroll-stopping

## Card-type structure

| Card # | Type | Purpose | Required? |
|---|---|---|---|
| 1 | **Cover** | Hook + promise. Big title + 1 line subtitle + visual badge ("干货" / "建议收藏" / etc.) | yes |
| 2 to N-1 | **Idea cards** | One core idea per card. Heading + 2–4 supporting sentences. Optional inline visual / number / icon. | yes |
| N | **Closing CTA** | Summary one-liner + CTA (关注 / 收藏 / 评论 / Visit URL) | yes |

A common structure for a 5-card XHS post:
1. Cover: "3 things nobody tells you about X"
2. Idea 1
3. Idea 2
4. Idea 3
5. Closing: "Save this + follow for more"

A 9-card post:
- 1 cover
- 1 "what we'll cover" agenda (optional)
- 6 idea cards
- 1 closing CTA

**Card cardinality is driven by content, not template.** If the user has
3 key points, make 5 cards (1 cover + 3 idea + 1 closing). If they have
8 key points, make 10 cards. Don't pad.

## Universal card rules

- **One idea per card.** Two ideas = two cards.
- **Body text ≤ 60 words per card.** XHS readers swipe fast.
- **Padding ≥ 80px on all sides** (cards are seen on phones; mobile
  thumb obscures edges).
- **Title ≥ 60px font-size on XHS** (titles need to read at small
  preview thumbnail size).
- **Page indicator in corner** ("1/5", "2/5", etc.) — small, muted.
- **Watermark bottom corner** — author handle / date — `colors.text.muted`.

## Mapping DESIGN.md → card

### Card canvas

| Element | Token |
|---|---|
| Card background | `colors.background.page` |
| Card border (if `composition.framing: bordered`) | `borders.width.default` solid `borders.color.default` |
| Card padding | `spacing.scale[9]` (≈64px) minimum, `scale[10]` (≈96px) preferred |
| Card border-radius | `borders.radius.lg` for friendly designs, `0` for modernist |

If `meta.isDark = true`, the entire carousel goes dark — coherent set,
not mixed light/dark cards.

### Cover card typography

| Element | Token | Notes |
|---|---|---|
| Hook badge ("干货" / "MUST READ" / etc.) | `typography.families.heading`, `scale.sm`, `weights.bold`, uppercase, `colors.accent.500` text on `colors.text.primary` pill background | Small badge top of card |
| Main title | `typography.families.heading`, `scale.6xl` or `7xl`, `weights.bold` or `extrabold`, `lineHeights.tight` | Dominates the card |
| Subtitle | `typography.families.body`, `scale.xl`, `weights.normal`, `colors.text.secondary` | Single line under title |
| Page indicator | `typography.families.body` or `mono`, `scale.xs`, `colors.text.muted` | Bottom-right corner |
| Watermark | `typography.families.body`, `scale.xs`, `colors.text.muted` | Bottom-left or bottom-right |

### Idea card typography

| Element | Token | Notes |
|---|---|---|
| Card number ("01" / "02") | `typography.families.heading`, `scale.7xl`, `weights.bold`, `colors.primary.500` at low opacity, or accent color | Decorative background number |
| Idea heading | `typography.families.heading`, `scale.4xl` or `5xl`, `weights.semibold` | Top of card |
| Idea body | `typography.families.body`, `scale.lg` or `xl`, `weights.normal`, `lineHeights.relaxed` | 2–4 lines |
| Inline highlight (key phrase) | same as body but `weights.bold` and `colors.primary.500` | Sparingly |
| Page indicator + watermark | same as cover | |

### Closing card typography

| Element | Token | Notes |
|---|---|---|
| Closing line | `typography.families.heading`, `scale.5xl`, `weights.bold` | Centered |
| CTA button / link | `components.button.primary` or styled `<a>` in `colors.primary.500` underlined | Large, tappable |
| URL / handle | `typography.families.body` or `mono`, `scale.lg`, `colors.text.primary` | Below CTA |

### Color usage (per card)

- **Cover** — full bg in `colors.background.page` OR full bg in
  `colors.primary.500` with inverse text (more scroll-stopping)
- **Idea cards** — same bg as cover (consistent set); accent color used
  for the big card number and inline highlights
- **Closing** — can switch to accent or primary bg for emphasis, or
  stay consistent with body

### Decorative elements

Carousel cards are short on space but high on density — use the design's
`## Techniques` for visual punctuation:
- A "geometric badge" or "shape stamp" in a card corner
- A "marquee tape" / "sticker strip" at top or bottom of card
- A "pattern fill" as background of the cover card only
- A "underline accent" under the card heading

Carousels feel cohesive when the **same decorative element appears
across all cards** (in different positions or sizes). E.g., the same
yellow Bauhaus triangle in different corners across 5 cards.

## Cover card composition options

A. **Big-title centered** — title fills 60% of card vertically,
   subtitle directly below, badge above. Works for editorial /
   bold designs.

B. **Block-color hero** — full-bleed primary-color background, title
   in inverse text large, subtitle small below. Works for Bauhaus /
   Swiss / bold designs.

C. **Decorative-frame** — title in moderate size, framed top-and-bottom
   by decorative element (squiggle / line / shape pattern). Works for
   Memphis / art nouveau / playful designs.

D. **Asymmetric photo** — image placeholder fills right 40% of card,
   title in left 60% — for product or lifestyle content. Works with
   any design.

## DO

- Make the cover card scroll-stopping — that's 80% of the engagement battle
- Repeat ONE decorative element across all cards for set coherence
- Use the design's actual heading font at huge sizes — XHS rewards
  typographic confidence
- Number idea cards visibly ("01", "02"…) — gives the reader a sense of
  progress and a reason to swipe
- Include watermark with author/handle + designbycurio.com microcredit
  (small, in muted color)

## DON'T

- Don't reuse the same layout across all cards exactly — mix in a "big
  number" card, a "quote" card, a "comparison" card etc. to keep
  visual rhythm
- Don't add Curio branding so large it dominates — credit is muted, not
  promotional
- Don't make body text smaller than `scale.lg` — XHS phones make
  smaller text unreadable
- Don't put a CTA on every card — save it for closing card

## Skeleton (paste this and fill)

```html
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<title>{{topic}} — {{platform}}</title>
<style>
  @import url('{{design.typography.families.googleFontsImport}}');
  :root {
    --bg:      {{design.colors.background.page}};
    --ink:     {{design.colors.text.primary}};
    --ink-2:   {{design.colors.text.secondary}};
    --ink-3:   {{design.colors.text.muted}};
    --primary: {{design.colors.primary.500}};
    --accent:  {{design.colors.accent.500}};
    --font-h:  {{design.typography.families.heading}};
    --font-b:  {{design.typography.families.body}};
  }
  body { background: #222; margin: 0; padding: 24px;
         display: flex; flex-direction: column; align-items: center; gap: 24px; }
  .card {
    background: var(--bg);
    color: var(--ink);
    font-family: var(--font-b);
    position: relative;
    overflow: hidden;
    padding: 80px;
    /* XHS dimensions; swap to platform value */
    width: 1080px; height: 1440px;
  }
  .card.cover { /* cover-specific styles */ }
  .card.idea  { /* idea-specific styles */ }
  .card.closing { /* closing-specific styles */ }
  .page-num { position: absolute; bottom: 32px; right: 32px;
              color: var(--ink-3); font-size: 20px; }
  .watermark { position: absolute; bottom: 32px; left: 32px;
               color: var(--ink-3); font-size: 18px; }
</style>
</head>
<body>

<div class="card cover">...</div>
<div class="card idea">...</div>
<div class="card idea">...</div>
<div class="card idea">...</div>
<div class="card closing">...</div>

</body>
</html>
```

## Example invocation

User: "Make a 小红书 carousel about 5 lessons from running my first
startup, in Memphis style."

You should:
1. Read `designs/memphis-sottsass-1981.md`
2. Read this method
3. Determine cardinality: 5 lessons → 1 cover + 5 idea + 1 closing = 7 cards
4. Cover: composition option **C (decorative-frame)** — Memphis squiggle
   border, title in big Memphis sans, "5 LESSONS · 1 YEAR · 1 STARTUP"
   hook badge, mint/pink/yellow color palette confetti pattern
5. Idea cards: each has a big card number ("01", "02"…) in Memphis
   accent color, heading + 2-line body, recurring squiggle in different
   corner each card
6. Closing card: "Save this · follow for more weekly" + handle, on
   primary-pink background with inverse text
7. All cards on XHS 1080×1440 canvas
8. Save to `xhs-startup-lessons-memphis.html`

Same brief with `designs/aesop-bottles.md` should be unrecognizable —
muted beige / black / cream palette, restrained serif heading,
no decoration except a single thin rule, ample whitespace, calm
authority instead of playful punch.
