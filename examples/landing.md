---
kind: reference
format: landing
about: "Reference patterns for composing marketing landing pages from a Curio DESIGN.md. NOT a required template."
---

> **⚠ This is a REFERENCE, not a template.** The canonical rules for
> using any Curio design live in the top-level `SKILL.md`. Read those
> first. Use this file only when you want inspiration for landing-page
> *structure* (which sections to include, common token-mapping per
> section, responsive breakpoints). The user's actual ask trumps
> anything here — don't include a "social proof" section if the user
> has no testimonials, don't force a 6-section flow if a 3-section
> page fits better.

# Reference · Landing Page

A single-scroll marketing page composed from a Curio design. Should
feel like a real product site in the design's aesthetic — not like a
template with the brand name in the corner.

## Output format

- **One HTML file** with inline `<style>`, fully self-contained
- Width: responsive (mobile-first), max content width follows the
  design's `spacing.container.xl`
- Fonts loaded via `typography.families.googleFontsImport`
- Smooth scroll, anchor links between sections
- No JS framework — vanilla HTML + CSS + minimal inline JS for menu
  toggle on mobile

## Section structure (in scroll order)

| Section | Required? | Purpose |
|---|---|---|
| **nav** | yes | Logo / brand + 3–5 links + login / CTA |
| **hero** | yes | Headline + subheadline + primary CTA + visual (image / abstract shape / mockup) |
| **features** | yes | 3 (or 6) feature blocks: icon + heading + 1-line description |
| **social-proof** | optional but high-value | Logos row, testimonial quote, or stats strip |
| **detail / use-case** | optional | One long block per use-case with text + image |
| **secondary-CTA** | yes | Mid-scroll re-engagement — different phrasing from hero |
| **pricing-teaser** | optional | 2–3 tier cards, link to full pricing |
| **FAQ** | optional | 5–8 accordion items |
| **footer-CTA** | yes | Final push, big and bold |
| **footer** | yes | 3–4 column links + copyright + small print |

A minimal landing = nav + hero + features + secondary-CTA + footer.
A complete one = all 10 sections.

## Universal page rules

- **Hero loads in <1 viewport.** Headline + sub + CTA must be visible
  without scroll on a 1440×900 desktop and a 390×844 mobile.
- **One primary CTA color** throughout — never two buttons fighting for
  attention in the same fold.
- **Vertical rhythm.** Use `spacing.sectionPadding.lg` between every
  major section. Don't squeeze.
- **Headline ≤ 12 words.** Subhead ≤ 25 words. If you can't fit, the
  product needs a better tagline, not a longer hero.
- **Generous horizontal margin on mobile** (`spacing.scale[6]` minimum).

## Mapping DESIGN.md → landing

### Page chrome

| Element | Token |
|---|---|
| Page background | `colors.background.page` |
| Section alt background (for visual rhythm) | `colors.background.subtle` |
| Section dividers (if used) | `borders.width.thin` solid `borders.color.subtle` |
| Container max-width | `spacing.container.xl` (or `lg` for narrower designs) |
| Container side padding | `spacing.scale[6]` mobile, `spacing.scale[8]` desktop |
| Section vertical padding | `spacing.sectionPadding.lg` |

### Nav

| Element | Token |
|---|---|
| Nav background | usually `colors.background.page` (transparent until scroll) |
| Logo / wordmark | `typography.families.heading`, `scale.xl`, `weights.bold`, `colors.text.primary` |
| Nav links | `typography.families.body`, `scale.sm`, `colors.text.secondary` |
| Active / hover state | `colors.text.primary` or `colors.primary.500` |
| Login button (secondary) | `components.button.ghost` or `secondary` |
| Primary CTA button | `components.button.primary` |

### Hero

| Element | Token |
|---|---|
| Hero background | `colors.background.page`, OR a primary-color block (if design uses `composition.framing` boldly), OR a subtle gradient if `surfaceStyle` allows |
| Headline | `typography.families.heading`, `scale.6xl` desktop / `scale.4xl` mobile, `weights.bold` |
| Subheadline | `typography.families.body`, `scale.xl` desktop / `scale.lg` mobile, `colors.text.secondary` |
| Primary CTA | `components.button.primary` at size `lg` |
| Secondary CTA (text link) | `colors.text.primary` underlined or with arrow |
| Hero visual placeholder | bordered or shadowed block using `borders.radius.lg` and `shadows.lg` (or whatever the design specifies) |

### Features

3-up grid by default (6 = 2 rows of 3). Each feature block:

| Element | Token |
|---|---|
| Block background | `components.card.base.background` or page bg |
| Block padding | from `components.card.base.padding` |
| Block border / radius / shadow | from `components.card.base` |
| Icon | `iconography.set` (Lucide by default), color `colors.primary.500`, size `iconography.size.lg` |
| Block heading | `typography.families.heading`, `scale.xl`, `weights.semibold` |
| Block description | `typography.families.body`, `scale.base`, `colors.text.secondary` |

### Social proof (logos / stats / testimonial)

| Element | Token |
|---|---|
| Section background | `colors.background.subtle` |
| Logos row | grayscaled at low opacity, single line, 5–8 logos |
| Stats big number | `typography.families.heading`, `scale.5xl`, `colors.primary.500` |
| Stats label | `typography.families.body`, `scale.sm`, `colors.text.muted`, uppercased |
| Testimonial quote | `typography.families.heading`, `scale.2xl`, `weights.normal` |
| Testimonial attribution | `typography.families.body`, `scale.base`, `colors.text.secondary` |

### Footer

| Element | Token |
|---|---|
| Footer background | `colors.background.subtle` or inverse (`text.primary` if dramatic) |
| Footer headings | `typography.families.heading`, `scale.sm`, uppercased, `colors.text.muted` |
| Footer links | `typography.families.body`, `scale.sm`, `colors.text.secondary` |
| Footer divider | `borders.width.thin` solid `borders.color.subtle` |
| Copyright line | `scale.xs`, `colors.text.muted` |

## Composition cues to honor

Read the design's `composition` block:

- `layout: grid` → use a 12-column CSS grid for the hero and features
- `layout: stack` → vertical stack with generous spacing, less reliance on grids
- `framing: bordered` → wrap hero and feature cards in visible borders
- `framing: full-bleed` → hero extends edge-to-edge, features may also
- `gridIntensity: strong` → expose alignment marks, vertical lines, geometric overlays (sparingly)
- `gridIntensity: subtle` → no visible grid, whitespace does the work
- `rhythm: 4px` (or 8px) → all margins and paddings snap to that baseline

## Techniques to apply

If the design has `## Techniques` with CSS snippets, use them:

- A "primary-color block accent" → use it for the secondary-CTA section
  (full-bleed colored block, inverse text, big CTA button)
- A "hard-offset shadow press" → use it for hover state on the primary CTA
- A "geometric shape badge" → use it for feature icons or section markers
- A "marquee scroll" / "sticker pattern" / "underline accent" → use where
  it fits the section

## Responsive rules

- Breakpoints: 1024px (desktop), 768px (tablet), 640px (mobile)
- Hero: 2-column desktop (text left, visual right) → 1-column mobile
- Features: 3-column desktop → 2-column tablet → 1-column mobile
- Nav: full horizontal desktop → hamburger toggle mobile
- All `typography.scale.*` values shift one step down on mobile
  (e.g., hero headline `6xl` → `4xl`)

## DO

- Make the hero CTA visually dominate — biggest single element above fold
- Use `components.card.base` exactly as specified for feature blocks
- Use the design's actual logo placement preferences (left for most;
  centered for ceremonial / luxury designs)
- Add subtle hover states on every clickable thing
- Add `prefers-reduced-motion` guard on any transition / animation
- Include a Curio attribution in the page footer:
  `<small>Design system: <a href="https://designbycurio.com/{{design.id}}">{{design.name}}</a> · powered by Curio</small>`

## DON'T

- Don't use stock landing-page tropes when the design rejects them
  (gradient hero on a flat design, glassmorphism on Bauhaus, rounded
  corners on brutalism, sans-serif headings on art deco)
- Don't add testimonials with fake names — use placeholder text like
  "[Testimonial from [Customer Name], [Title] at [Company]]" so the
  user knows to fill them in
- Don't auto-add a "Made with Curio" badge bigger than `text.muted` —
  it's a footer credit, not a watermark
- Don't ship without a real footer — links can be `#` placeholders, but
  the structure must be there

## Skeleton (paste this and fill)

```html
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>{{product.name}} — {{product.tagline}}</title>
<style>
  @import url('{{design.typography.families.googleFontsImport}}');
  :root {
    --bg:      {{design.colors.background.page}};
    --bg-sub:  {{design.colors.background.subtle}};
    --surface: {{design.colors.background.surface}};
    --ink:     {{design.colors.text.primary}};
    --ink-2:   {{design.colors.text.secondary}};
    --ink-3:   {{design.colors.text.muted}};
    --primary: {{design.colors.primary.500}};
    --accent:  {{design.colors.accent.500}};
    --font-h:  {{design.typography.families.heading}};
    --font-b:  {{design.typography.families.body}};
    --radius:  {{design.borders.radius.md}};
    --shadow:  {{design.shadows.md}};
    --container: {{design.spacing.container.xl}};
    --section-pad: {{design.spacing.sectionPadding.lg}};
  }
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { background: var(--bg); color: var(--ink); font-family: var(--font-b);
         line-height: 1.5; }
  .container { max-width: var(--container); margin: 0 auto; padding: 0 24px; }
  /* nav, hero, features, social-proof, secondary-cta, footer sections... */
</style>
</head>
<body>

<nav>...</nav>
<section class="hero">...</section>
<section class="features">...</section>
<section class="social-proof">...</section>
<section class="secondary-cta">...</section>
<footer>...</footer>

</body>
</html>
```

## Example invocation

User: "Make a landing page for our project management SaaS, in
Stripe-2024 style."

You should:
1. Read `designs/stripe-2024.md`
2. Read this method
3. Build a landing with:
   - Nav with Stripe-style gradient under-bar on hover
   - Hero with two-column layout, big serif-ish modernist headline, soft
     blue accent CTA
   - 3 feature cards using Stripe's card spec (subtle border, slight
     shadow, generous padding)
   - Stats strip in muted background
   - Secondary CTA block in primary blue with inverse text
   - 4-column footer with subtle muted links
4. Apply Stripe's "underline-on-hover" or "gradient accent" technique
   if present
5. Save to `landing-stripe.html`

Same prompt with `designs/etsy-handmade.md` should produce a totally
different feel — warm red palette, hand-drawn icon set, organic card
shapes, friendly serif heading, illustration-led hero — same structural
skeleton.
