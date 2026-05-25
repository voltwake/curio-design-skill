---
version: 1

meta:
  id: klarna-shopping
  name: Klarna
  description: Dusty bubblegum pink meets bold black sans — buy-now-pay-later reimagined as a fashion brand
  isDark: false
  tags: [playful, friendly, bold, minimal, modern]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2005 founded; current pink rebrand ~2018; visual stable through 2024"
  region: "Stockholm, Sweden"
  regionZh: "瑞典斯德哥尔摩"
  keyFigures: [Sebastian Siemiatkowski, Niklas Adalberth, DesignStudio London]
  movements: [Buy-now-pay-later fintech, Embedded checkout, Fashion-aligned consumer finance]

introduction: |
  Klarna turned consumer credit into a fashion statement. Its 2018 rebrand by DesignStudio London introduced the signature dusty bubblegum pink — not hot, not pastel, but a very specific #FFA8CD that became the most recognizable color in fintech.

  The system pairs that pink exclusively with bold black typography and white space. No secondary chromatic accents, no gradients, no decorative shadows — just three colors doing the heavy lifting. The result feels more like a fashion magazine than a payment provider.
introductionZh: |
  Klarna 将消费信贷变成了一种时尚宣言。2018 年伦敦 DesignStudio 主导的品牌重塑引入了标志性的"Klarna 粉" —— 一种介于泡泡糖与灰粉之间、独一无二的 #FFA8CD，迅速成为金融科技领域辨识度最高的色彩。

  整套视觉体系只用三种颜色：粉、黑、白。没有多余的彩色点缀，没有渐变，没有装饰性阴影。粗黑的无衬线字体搭配大面积粉色色块，让一家支付公司看起来更像时尚杂志，传达出"消费可以轻松甜蜜"的品牌态度。

colors:
  primary:
    "50": "#FFF5F9"
    "100": "#FFEBF3"
    "200": "#FFD6E7"
    "300": "#FFC1DB"
    "400": "#FFB4D4"
    "500": "#FFA8CD"
    "600": "#F08CB5"
    "700": "#E8709A"
    "800": "#C9537D"
    "900": "#A33A62"
    "950": "#7D2549"
  secondary:
    "50": "#F5F5F5"
    "100": "#EBEBEB"
    "200": "#D6D6D6"
    "300": "#B8B8B8"
    "400": "#999999"
    "500": "#5C5C5C"
    "600": "#4A4A4A"
    "700": "#383838"
    "800": "#262626"
    "900": "#171717"
    "950": "#0A0A0A"
  accent:
    "50": "#F5F5F5"
    "100": "#EBEBEB"
    "200": "#D6D6D6"
    "300": "#B8B8B8"
    "400": "#999999"
    "500": "#0A0A0A"
    "600": "#090909"
    "700": "#080808"
    "800": "#060606"
    "900": "#040404"
    "950": "#020202"
  neutral:
    "50": "#FAFAFA"
    "100": "#F5F5F5"
    "200": "#E5E5E5"
    "300": "#D4D4D4"
    "400": "#A3A3A3"
    "500": "#737373"
    "600": "#525252"
    "700": "#404040"
    "800": "#262626"
    "900": "#171717"
    "950": "#0A0A0A"
  semantic:
    success: { bg: "#ECFDF5", text: "#065F46", light: "#D1FAE5", border: "#6EE7B7" }
    warning: { bg: "#FFFBEB", text: "#92400E", light: "#FEF3C7", border: "#FCD34D" }
    error:   { bg: "#FEF2F2", text: "#991B1B", light: "#FEE2E2", border: "#FCA5A5" }
    info:    { bg: "#FFF5F9", text: "#7D2549", light: "#FFEBF3", border: "#FFA8CD" }
  background:
    page:    "#FFFFFF"
    surface: "#FFFFFF"
    subtle:  "#FFA8CD"
  text:
    primary:   "#0A0A0A"
    secondary: "#5C5C5C"
    muted:     "#999999"
    inverse:   "#FFFFFF"

typography:
  families:
    heading: "'Inter', -apple-system, BlinkMacSystemFont, sans-serif"
    body:    "'Inter', -apple-system, BlinkMacSystemFont, sans-serif"
    mono:    "'JetBrains Mono', 'Fira Code', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&family=JetBrains+Mono:wght@400;500&display=swap"
  scale:
    "2xs": "0.625rem"
    xs: "0.75rem"
    sm: "0.875rem"
    base: "1rem"
    lg: "1.125rem"
    xl: "1.25rem"
    "2xl": "1.5rem"
    "3xl": "1.875rem"
    "4xl": "2.25rem"
    "5xl": "3rem"
    "6xl": "4rem"
    "7xl": "6rem"
  weights: {light: 300, normal: 400, medium: 500, semibold: 600, bold: 700, extrabold: 800}
  lineHeights: {tight: 1.2, snug: 1.375, normal: 1.5, relaxed: 1.625, loose: 1.8}
  letterSpacing: {tighter: "-0.04em", tight: "-0.025em", normal: "0", wide: "0.05em"}

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      {sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%"}
  gridGap:        {sm: "8px",  md: "16px", lg: "24px", xl: "48px"}
  sectionPadding: {sm: "32px", md: "64px", lg: "96px", xl: "128px"}

borders:
  radius: {none: "0", sm: "4px", md: "6px", lg: "8px", xl: "12px", full: "9999px"}
  color:  {default: "#E5E5E5", subtle: "#F5F5F5", strong: "#0A0A0A", focus: "#FFA8CD"}
  width:  {thin: "1px", default: "1px", thick: "2px"}
  style:  "solid"

shadows:
  none: "none"
  xs: "none"
  sm: "none"
  md: "none"
  lg: "none"
  xl: "none"
  "2xl": "none"
  inner: "none"
  focus: "0 0 0 3px rgba(255, 168, 205, 0.4)"

motion:
  level: "restrained"
  durations: {instant: "0ms", fast: "120ms", normal: "200ms", slow: "350ms", slower: "500ms"}
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.4, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.2, 1)"
    spring:  "cubic-bezier(0.34, 1.56, 0.64, 1)"
  hoverPatterns: [opacity, tint, scale]
  reducedMotion: true

composition:
  layout:        "flex"
  contentWidth:  "container"
  framing:       "solid"
  gridIntensity: "subtle"
  rhythm:        "8px"

surfaceStyle: "flat"
blur:         "none"

iconography:
  treatment: "linear"
  set:       "lucide"
  size:      {sm: "16px", md: "20px", lg: "24px"}
  stroke:    "1.5px"

components:
  button:
    primary:
      background: "#FFA8CD"
      color: "#0A0A0A"
      border: "none"
      shadow: "none"
      hoverBackground: "#E8709A"
      hoverShadow: "none"
      hoverColor: "#FFFFFF"
    secondary:
      background: "transparent"
      color: "#0A0A0A"
      border: "2px solid #0A0A0A"
      shadow: "none"
      hoverBackground: "#0A0A0A"
      hoverShadow: "none"
      hoverColor: "#FFFFFF"
    ghost:
      background: "transparent"
      color: "#0A0A0A"
      border: "none"
      shadow: "none"
      hoverBackground: "rgba(255, 168, 205, 0.15)"
      hoverShadow: "none"
      hoverColor: "#0A0A0A"
    danger:
      background: "#991B1B"
      color: "#FFFFFF"
      border: "none"
      shadow: "none"
      hoverBackground: "#7F1D1D"
      hoverShadow: "none"
      hoverColor: "#FFFFFF"
    sizes:
      sm: {height: "36px", padding: "0 16px", fontSize: "0.875rem"}
      md: {height: "44px", padding: "0 24px", fontSize: "1rem"}
      lg: {height: "52px", padding: "0 32px", fontSize: "1.125rem"}
    borderRadius: "6px"
    fontWeight: 600
    letterSpacing: "-0.01em"
    textTransform: "none"
  input:
    background: "#FFFFFF"
    color: "#0A0A0A"
    border: "1px solid #E5E5E5"
    borderRadius: "6px"
    padding: "12px 16px"
    focusBorder: "#FFA8CD"
    placeholderColor: "#999999"
  card:
    base:
      background: "#FFFFFF"
      border: "none"
      borderRadius: "8px"
      padding: "24px"
      shadow: "none"
    hover:
      shadow: "none"
      transform: "translateY(-1px)"
---

# Klarna

> Buy-now-pay-later that thinks it's a fashion brand — dusty bubblegum pink, bold black type, and nothing else.

## Origin

Klarna was founded in 2005 in Stockholm by Sebastian Siemiatkowski and Niklas Adalberth as a simpler way to pay online. For its first decade the brand looked like any other payment company — blue, trustworthy, forgettable. Everything changed with the 2018 rebrand led by DesignStudio London, which introduced the now-iconic "Klarna pink" (#FFA8CD) alongside a stripped-back black-and-white palette and the "Smoooth" campaign starring Snoop Dogg.

The rebrand deliberately positioned Klarna not as a fintech utility but as a fashion-adjacent lifestyle brand. The singular pink hue — a very specific dusty bubblegum, neither hot nor pastel — became one of the most distinctive colors in consumer technology. By refusing to add secondary accent colors and relying on bold sans-serif typography against generous pink panels, Klarna carved out a visual identity that feels more like a fashion magazine editorial than a checkout widget.

## Overview

Composition cues:
- **Layout**: Flex-based with editorial fashion-magazine proportions — large hero panels, generous whitespace
- **Content width**: Container (max ~1280px) with full-bleed pink hero sections
- **Framing**: Solid flat panels — no glass, no blur, no gradients
- **Grid intensity**: Subtle — content breathes with generous spacing rather than visible grid lines

## Colors

Klarna's color world is radically simple: one pink, one black, one white. The signature #FFA8CD is not a generic pink — it's a dusty bubblegum that sits in a specific space between warm and cool. This restraint is the point. Where other brands add accent after accent, Klarna lets the pink do all the emotional work while black grounds the typography and white gives everything room to breathe.

**Role usage**:
- Page background → `colors.background.page` (#FFFFFF)
- Brand hero panels → `colors.background.subtle` (#FFA8CD)
- Surface/cards → `colors.background.surface` (#FFFFFF)
- Primary actions (CTA buttons) → `colors.primary.500` (#FFA8CD)
- Body text → `colors.text.primary` (#0A0A0A)
- Secondary text → `colors.text.secondary` (#5C5C5C)
- Hover/active state → `colors.primary.700` (#E8709A)
- Focus rings → `shadows.focus` (pink alpha ring)

## Typography

Inter at bold and black weights channels Klarna Sans's confident, rounded sans-serif energy. Headlines hit hard — large sizes, tight negative tracking (-2.5%), heavy weight. The type is conversational and direct, never formal or precious. Body copy at 16px/1.5 stays comfortable and readable, letting the bold headlines and pink panels carry the personality.

**Text styles**:
- `display-xl` — Inter, 96px, weight 800, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Inter, 64px, weight 800, line-height 1.05, letter-spacing -0.03em
- `heading-1` — Inter, 48px, weight 700, line-height 1.1, letter-spacing -0.025em
- `heading-2` — Inter, 36px, weight 700, line-height 1.15, letter-spacing -0.025em
- `body-lg` — Inter, 18px, weight 400, line-height 1.6, letter-spacing 0
- `body-md` — Inter, 16px, weight 400, line-height 1.5, letter-spacing 0
- `caption` — Inter, 13px, weight 500, line-height 1.4, letter-spacing 0.01em
- `mono-md` — JetBrains Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout

- Base unit: 8px rhythm
- Scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128px
- Container: 1280px max, centered with auto margins
- Section padding: 64–128px vertical for generous editorial breathing room
- Grid gap: 16–24px between cards and content blocks

## Elevation & Depth

Klarna is intentionally flat. There are no box shadows anywhere in the system — not on cards, not on buttons, not on dropdowns. Depth is communicated through color contrast alone: pink panels sit on white backgrounds, white cards sit on pink panels. The only shadow in the system is the focus ring, which uses a translucent pink glow for accessibility.

- Surface style: flat — zero elevation, zero blur
- Shadows: none across the board (xs through 2xl all resolve to `none`)
- Focus indicator: `0 0 0 3px rgba(255, 168, 205, 0.4)` — the only "shadow" in the system
- Depth hierarchy: color-driven (white on pink, pink on white) rather than shadow-driven

## Shapes

- Button border-radius: 6px — slightly rounded, friendly without being bubbly
- Card border-radius: 8px — a touch softer than buttons
- Input border-radius: 6px — matches buttons for visual consistency
- Pill/tag: 9999px full-round for badges and status indicators
- No sharp corners (0px radius) used in UI elements

## Motion

Klarna's motion is restrained and purposeful. Transitions are quick and smooth — the brand name "Smoooth" hints at the feel but the actual UI avoids flashy animations. Interactions respond instantly, hover states shift color or opacity without dramatic movement. The system respects reduced-motion preferences fully.

- Level: restrained — motion supports, never entertains
- Durations: fast 120ms for micro-interactions, normal 200ms for state changes, slow 350ms for panel reveals
- Default easing: `cubic-bezier(0.4, 0, 0.2, 1)` — standard Material-style ease
- Hover patterns: opacity fade, pink tint wash, subtle scale (1.02 max)
- No bounce, no spring, no parallax — the pink does the talking, not the motion

## Techniques

### Full-bleed pink hero panel

Klarna's signature layout move: a full-width solid pink panel that anchors the page and contains the primary headline and CTA. No gradient, no texture, no image overlay — just #FFA8CD edge to edge.

```css
.hero-panel {
  background-color: #FFA8CD;
  width: 100%;
  padding: 96px 0;
  display: flex;
  align-items: center;
  justify-content: center;
}
.hero-panel h1 {
  color: #0A0A0A;
  font-family: 'Inter', sans-serif;
  font-weight: 800;
  font-size: clamp(2.5rem, 6vw, 6rem);
  letter-spacing: -0.03em;
  text-align: center;
  max-width: 900px;
}
```

### Black ghost button with pink fill hover

The secondary CTA pattern — a bold black-bordered button that floods with pink on hover, creating a satisfying two-step visual hierarchy alongside the primary pink-filled button.

```css
.btn-ghost {
  background: transparent;
  color: #0A0A0A;
  border: 2px solid #0A0A0A;
  border-radius: 6px;
  padding: 12px 24px;
  font-family: 'Inter', sans-serif;
  font-weight: 600;
  font-size: 1rem;
  cursor: pointer;
  transition: all 200ms cubic-bezier(0.4, 0, 0.2, 1);
}
.btn-ghost:hover {
  background: #FFA8CD;
  border-color: #FFA8CD;
  color: #0A0A0A;
}
```

### Pink-on-white card grid

Product or feature cards on a pink background — white cards with no shadow, using the pink surround as the only depth cue. The editorial fashion-magazine layout feel comes from generous padding and minimal content density.

```css
.card-grid {
  background: #FFA8CD;
  padding: 96px 24px;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 24px;
  max-width: 1280px;
  margin: 0 auto;
}
.card-grid .card {
  background: #FFFFFF;
  border-radius: 8px;
  padding: 32px;
  border: none;
  box-shadow: none;
  transition: transform 200ms cubic-bezier(0.4, 0, 0.2, 1);
}
.card-grid .card:hover {
  transform: translateY(-2px);
}
```

## Iconography

Klarna uses thin, linear icons that stay out of the way of the bold pink-and-black visual hierarchy. Icons are functional, not decorative — they label actions and navigation without competing with the typography or color for attention.

- Treatment: linear stroke, no fills
- Set: Lucide (clean, geometric, matches Inter's character)
- Stroke: 1.5px at all sizes

## Do's & Don'ts

### Do
- Use Klarna pink #FFA8CD for primary CTAs and hero panels — it is the brand
- Keep the palette to exactly three colors: pink, black, white
- Set headlines in Inter bold/extrabold with tight negative tracking
- Use full-bleed pink panels as section dividers and hero backgrounds
- Let generous whitespace carry the editorial fashion-magazine feel

### Don't
- Use hot saturated pink — Klarna pink is dusty and specific, not neon
- Add secondary chromatic accents (no teal, no yellow, no blue — just black/white/pink)
- Apply dark mode — Klarna is canonically a light-mode brand
- Use serif typefaces — the brand is entirely sans-serif
- Add decorative box shadows — depth comes from color contrast, not elevation

## Applications

Klarna's system is purpose-built for consumer-facing fintech and e-commerce checkout experiences where trust needs to feel effortless rather than institutional. The bold pink panels and fashion-editorial layouts work equally well for shopping apps, product landing pages, and marketing campaigns. The radical color simplicity (three colors only) makes it especially effective for embedded checkout widgets and payment UIs where clarity and brand recognition must coexist in tight spaces.
