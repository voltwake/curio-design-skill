---
version: 1

meta:
  id: etsy-handmade
  name: Etsy Handmade
  description: "Warm, homespun craft-fair marketplace with orange accents and serif warmth"
  isDark: false
  tags: [hand-drawn, friendly, organic, warm, handmade]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2005 founded; current visual ~2018–2024"
  region: "Brooklyn, New York"
  regionZh: "美国纽约布鲁克林"
  keyFigures: [Rob Kalin, Chris Maguire, Haim Schoppik, Etsy Brand team]
  movements: [Handmade marketplace, indie-craft economy, anti-mass-production retail]

introduction: |
  Etsy is the digital craft fair — a marketplace that celebrates the handmade, the personal, and the imperfect. Founded in Brooklyn in 2005, its visual identity wraps warm orange and cream tones around serif typography and product photography that feels like browsing a maker's stall.

  The design system deliberately resists corporate polish. Hand-drawn illustration accents, warm cream backgrounds, and a signature orange (#F1641E) signal that every item was made by a real person. It's friendly, organic, and unapologetically homespun.
introductionZh: |
  Etsy 是一个数字手工艺集市——一个赞颂手工制作、个性化与不完美之美的市场平台。2005年诞生于纽约布鲁克林，其视觉风格以温暖的橙色与奶油色调为底，搭配衬线字体和产品摄影，营造出如同漫步手作人摊位般的亲切感。

  这套设计体系有意回避企业化的光滑质感。手绘插画点缀、暖奶油色背景以及标志性的 Etsy 橙（#F1641E）无不在诉说：这里的每件物品都出自真实的双手。温暖、有机、毫不掩饰的手工质朴气息，是 Etsy 品牌最动人的视觉语言。

colors:
  primary:
    "50": "#FEF3ED"
    "100": "#FDE3D4"
    "200": "#FBC7A9"
    "300": "#F9A87D"
    "400": "#F78652"
    "500": "#F1641E"
    "600": "#D85518"
    "700": "#B44513"
    "800": "#8F370F"
    "900": "#6B290B"
    "950": "#471B07"
  secondary:
    "50": "#F0F6F0"
    "100": "#D9E9DA"
    "200": "#B3D3B5"
    "300": "#8CBD90"
    "400": "#5DA362"
    "500": "#2D5731"
    "600": "#274C2B"
    "700": "#1F3D22"
    "800": "#182F1A"
    "900": "#112213"
    "950": "#0A140B"
  accent:
    "50": "#F5F5F5"
    "100": "#E5E5E5"
    "200": "#CCCCCC"
    "300": "#B0B0B0"
    "400": "#8A8A8A"
    "500": "#595959"
    "600": "#3D3D3D"
    "700": "#2B2B2B"
    "800": "#1A1A1A"
    "900": "#0A0A0A"
    "950": "#050505"
  neutral:
    "50": "#FAFAF8"
    "100": "#F5F3EF"
    "200": "#EBE8E1"
    "300": "#D9D4CA"
    "400": "#B5AFA3"
    "500": "#8A8478"
    "600": "#6B655A"
    "700": "#524D44"
    "800": "#3A362F"
    "900": "#222222"
    "950": "#111111"
  semantic:
    success: { bg: "#2D5731", text: "#FFFFFF", light: "#E8F5E9", border: "#2D5731" }
    warning: { bg: "#F5A623", text: "#222222", light: "#FFF3E0", border: "#F5A623" }
    error: { bg: "#D32F2F", text: "#FFFFFF", light: "#FFEBEE", border: "#D32F2F" }
    info: { bg: "#1976D2", text: "#FFFFFF", light: "#E3F2FD", border: "#1976D2" }
  background:
    page: "#FFF8E8"
    surface: "#FFFFFF"
    subtle: "#FFFCF2"
  text:
    primary: "#222222"
    secondary: "#595959"
    muted: "#757575"
    inverse: "#FFFFFF"

typography:
  families:
    heading: "'Source Serif 4', 'Georgia', serif"
    body: "'Inter', 'Helvetica Neue', sans-serif"
    mono: "'JetBrains Mono', 'Fira Code', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Source+Serif+4:ital,opsz,wght@0,8..60,300;0,8..60,400;0,8..60,600;0,8..60,700;1,8..60,400&family=Inter:wght@300;400;500;600;700&family=JetBrains+Mono:wght@400;500&display=swap"
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
  weights:
    light: 300
    normal: 400
    medium: 500
    semibold: 600
    bold: 700
    extrabold: 800
  lineHeights:
    tight: 1.2
    snug: 1.375
    normal: 1.55
    relaxed: 1.625
    loose: 1.8
  letterSpacing:
    tighter: "-0.04em"
    tight: "-0.01em"
    normal: "0"
    wide: "0.05em"

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:
    sm: "640px"
    md: "768px"
    lg: "1024px"
    xl: "1280px"
    full: "100%"
  gridGap:
    sm: "8px"
    md: "16px"
    lg: "24px"
    xl: "48px"
  sectionPadding:
    sm: "32px"
    md: "64px"
    lg: "96px"
    xl: "128px"

borders:
  radius:
    none: "0"
    sm: "2px"
    md: "4px"
    lg: "8px"
    xl: "16px"
    full: "9999px"
  color:
    default: "#E5E0D5"
    subtle: "#EBE8E1"
    strong: "#222222"
    focus: "#F1641E"
  width:
    thin: "1px"
    default: "1px"
    thick: "2px"
  style: "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(0,0,0,0.04)"
  sm: "0 1px 4px rgba(0,0,0,0.06)"
  md: "0 4px 12px rgba(0,0,0,0.08)"
  lg: "0 8px 24px rgba(0,0,0,0.10)"
  xl: "0 12px 40px rgba(0,0,0,0.12)"
  "2xl": "0 20px 60px rgba(0,0,0,0.14)"
  inner: "inset 0 1px 2px rgba(0,0,0,0.04)"
  focus: "0 0 0 3px rgba(241,100,30,0.25)"

motion:
  level: "restrained"
  durations:
    instant: "0ms"
    fast: "120ms"
    normal: "250ms"
    slow: "400ms"
    slower: "600ms"
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in: "cubic-bezier(0.4, 0, 1, 1)"
    out: "cubic-bezier(0, 0, 0.2, 1)"
    spring: "cubic-bezier(0.34, 1.56, 0.64, 1)"
  hoverPatterns: [lift, opacity, tint]
  reducedMotion: true

composition:
  layout: "grid"
  contentWidth: "container"
  framing: "solid"
  gridIntensity: "strong"
  rhythm: "8px"

surfaceStyle: "solid"
blur: "none"

iconography:
  treatment: "outline"
  set: "lucide"
  size:
    sm: "16px"
    md: "20px"
    lg: "24px"
  stroke: "1.5px"

components:
  button:
    primary:
      background: "#0A0A0A"
      color: "#FFFFFF"
      border: "none"
      shadow: "none"
      hoverBackground: "#222222"
      hoverShadow: "0 1px 4px rgba(0,0,0,0.06)"
      hoverColor: "#FFFFFF"
    secondary:
      background: "transparent"
      color: "#F1641E"
      border: "2px solid #F1641E"
      shadow: "none"
      hoverBackground: "#FEF3ED"
      hoverShadow: "none"
      hoverColor: "#D85518"
    ghost:
      background: "transparent"
      color: "#222222"
      border: "none"
      shadow: "none"
      hoverBackground: "#FFFCF2"
      hoverShadow: "none"
      hoverColor: "#0A0A0A"
    danger:
      background: "#D32F2F"
      color: "#FFFFFF"
      border: "none"
      shadow: "none"
      hoverBackground: "#B71C1C"
      hoverShadow: "none"
      hoverColor: "#FFFFFF"
    sizes:
      sm: { height: "32px", padding: "0 12px", fontSize: "0.875rem" }
      md: { height: "40px", padding: "0 20px", fontSize: "1rem" }
      lg: { height: "48px", padding: "0 28px", fontSize: "1.125rem" }
    borderRadius: "4px"
    fontWeight: 600
    letterSpacing: "0"
    textTransform: "none"
  input:
    background: "#FFFCF2"
    color: "#222222"
    border: "1px solid #E5E0D5"
    borderRadius: "4px"
    padding: "10px 14px"
    focusBorder: "1px solid #F1641E"
    placeholderColor: "#999999"
  card:
    base:
      background: "#FFFFFF"
      border: "1px solid #EBE8E1"
      borderRadius: "8px"
      padding: "0"
      shadow: "0 1px 4px rgba(0,0,0,0.06)"
    hover:
      shadow: "0 4px 12px rgba(0,0,0,0.08)"
      transform: "translateY(-2px)"
---

# Etsy Handmade

> The digital craft fair — warm, personal, and proudly handmade.

## Origin

Etsy launched in 2005 from a Brooklyn apartment, founded by Rob Kalin, Chris Maguire, and Haim Schoppik as a marketplace where independent makers could sell handcrafted goods directly to buyers. It emerged as a counterpoint to mass-produced e-commerce, championing the idea that every product has a human story behind it. By 2024, Etsy hosts millions of sellers across ceramics, textiles, jewelry, and vintage goods.

The visual identity has evolved through several refreshes, with the current direction (circa 2018–2024) leaning into warm cream backgrounds, a signature orange, and serif typography that evokes a hand-lettered shop sign. The design intentionally avoids the sterile polish of big-tech marketplaces — photography shows craft-fair tables, maker's hands, and the beautiful imperfections of handmade objects. It's a brand that wears its warmth on its sleeve.

## Overview

Composition cues:
- **Layout**: Product-grid layouts, typically 4-up at desktop, showcasing photography of handmade goods
- **Content width**: Container (max ~1280px), centered with generous margin
- **Framing**: Solid card frames that act as photo-first product tiles with seller info below
- **Grid intensity**: Strong — the grid is the core browsing experience, dense but breathable

## Colors

Etsy's palette draws from the craft fair: warm cream backgrounds like unbleached canvas, a signature orange (#F1641E) that feels more amber and handmade than any tech-startup orange, deep brown-black text for readability, and forest green accents that nod to sustainability and natural materials. The overall impression is warmth — like afternoon sunlight on a wooden market stall.

**Role usage**:
- Page background → `colors.background.page` (#FFF8E8)
- Card and surface background → `colors.background.surface` (#FFFFFF)
- Subtle background for inputs → `colors.background.subtle` (#FFFCF2)
- Primary actions and links → `colors.primary.500` (#F1641E)
- Primary button fills → `colors.accent.900` (#0A0A0A)
- Body text → `colors.text.primary` (#222222)
- Secondary text and seller info → `colors.text.secondary` (#595959)
- Sustainability and eco badges → `colors.secondary.500` (#2D5731)

## Typography

The type voice splits between a warm serif for headlines and a clean sans-serif for body text, mirroring the Etsy experience itself — artisanal character up front, practical readability for browsing. Source Serif 4 stands in for Etsy's proprietary display serif, lending headlines a hand-set quality. Inter handles body text with quiet professionalism, staying out of the way while product photography and maker stories take center stage.

**Text styles**:
- `display-xl` — Source Serif 4, 96px, weight 700, line-height 1.0, letter-spacing -0.01em
- `display-lg` — Source Serif 4, 64px, weight 700, line-height 1.1, letter-spacing -0.01em
- `heading-1` — Source Serif 4, 40px, weight 600, line-height 1.2, letter-spacing -0.01em
- `heading-2` — Source Serif 4, 32px, weight 600, line-height 1.25, letter-spacing -0.01em
- `body-lg` — Inter, 18px, weight 400, line-height 1.55, letter-spacing 0
- `body-md` — Inter, 16px, weight 400, line-height 1.55, letter-spacing 0
- `caption` — Inter, 13px, weight 400, line-height 1.4, letter-spacing 0
- `mono-md` — JetBrains Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout

- Base unit: 8px rhythm for all spatial decisions
- Scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128px
- Container max-width: 1280px centered
- Product grid gap: 24px at desktop, 16px at tablet, 8px at mobile
- Section padding: 64px vertical at desktop, 32px at mobile
- Card internal padding: 0 for product image area, 12–16px for text area below

## Elevation & Depth

Etsy's surfaces are deliberately flat and tangible — like paper, wood, and fabric rather than floating glass. Shadows are minimal and warm-toned, suggesting objects resting on a craft table rather than hovering in space. Elevation is used sparingly: product cards get a whisper of shadow to separate them from the cream background, and hover states lift cards just enough to signal interactivity.

- Surface style: solid, opaque — no transparency or glass effects
- Blur: none
- Shadow ladder: xs (barely perceptible) → sm (card resting state, `0 1px 4px rgba(0,0,0,0.06)`) → md (hover / focus) → lg (modals)
- Hover lift: `translateY(-2px)` with shadow transition

## Shapes

- Button border-radius: 4px (slightly rounded, friendly but not bubbly)
- Card border-radius: 8px (soft-cornered product frames)
- Input border-radius: 4px
- Badge / pill border-radius: 9999px (full round for tags and filters)
- Avatar border-radius: 9999px (circular seller photos)

## Motion

Etsy's motion is restrained and warm — transitions should feel like a hand gently nudging something into place, not snapping or bouncing. Nothing should feel mechanical or aggressive. Hover lifts are subtle, page transitions are soft fades, and loading states use gentle opacity pulses rather than sharp spinners.

- Level: restrained
- Default transition: 250ms ease
- Hover card lift: 250ms with `cubic-bezier(0.4, 0, 0.2, 1)`
- Fade-in for lazy-loaded images: 400ms ease-out
- Hover patterns: lift, opacity, tint
- Reduced motion: respected — all transitions become instant

## Techniques

### Craft-paper card frame
Product cards that feel like items pinned to a craft-fair board — photo-dominant with a thin warm border and gentle shadow, text tucked below.
```css
.craft-card {
  background: #FFFFFF;
  border: 1px solid #EBE8E1;
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 1px 4px rgba(0,0,0,0.06);
  transition: box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1),
              transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.craft-card:hover {
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  transform: translateY(-2px);
}
.craft-card__image {
  width: 100%;
  aspect-ratio: 1;
  object-fit: cover;
}
.craft-card__info {
  padding: 12px 16px;
  background: #FFFCF2;
}
```

### Warm cream input field
Input fields that sit naturally on the cream background, with an Etsy-orange focus ring that feels like a hand underlining something important.
```css
.warm-input {
  background: #FFFCF2;
  border: 1px solid #E5E0D5;
  border-radius: 4px;
  padding: 10px 14px;
  font-family: 'Inter', sans-serif;
  font-size: 1rem;
  color: #222222;
  transition: border-color 200ms ease, box-shadow 200ms ease;
}
.warm-input::placeholder {
  color: #999999;
}
.warm-input:focus {
  outline: none;
  border-color: #F1641E;
  box-shadow: 0 0 0 3px rgba(241,100,30,0.25);
}
```

### Hand-drawn accent divider
A subtle wavy SVG divider used between sections, evoking the hand-drawn illustration style found in Etsy's marketing materials.
```css
.handmade-divider {
  width: 100%;
  height: 24px;
  background: url("data:image/svg+xml,%3Csvg width='200' height='12' viewBox='0 0 200 12' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath d='M0 6 Q25 0 50 6 T100 6 T150 6 T200 6' stroke='%23E5E0D5' stroke-width='1.5' fill='none' stroke-linecap='round'/%3E%3C/svg%3E") repeat-x center;
  opacity: 0.8;
  margin: 32px 0;
}
```

## Iconography

Etsy uses outline-style icons that feel approachable and slightly soft — never heavy or filled. The stroke weight sits at 1.5px, thin enough to feel crafted but thick enough for legibility at small sizes. Icons complement the serif/sans split: they're modern in construction but warm in character.

- Treatment: outline (linear)
- Set: Lucide (closest to Etsy's custom icon style)
- Stroke: 1.5px, round caps and joins

## Do's & Don'ts

### ✓ Do
- Use Source Serif 4 for all headlines to maintain the handmade, editorial warmth
- Keep the cream (#FFF8E8) page background as the default canvas
- Use Etsy orange (#F1641E) for interactive highlights, links, and secondary CTAs
- Let product photography be the hero — large, well-lit craft images dominate
- Use filled-black (#0A0A0A) buttons for primary actions to ground the warm palette

### ✗ Don't
- Don't use sleek minimalism — resist the urge to strip away warmth and texture
- Don't apply cool corporate palettes (blues, grays) that feel like enterprise software
- Don't use brutalist or sharp anti-design — Etsy is friendly, never confrontational
- Don't add heavy decorative gradients — the palette is flat, warm, and honest
- Don't substitute modern sans-serif headings — the serif is essential to Etsy's character

## Applications

Etsy Handmade is ideal for marketplace interfaces, artisan storefronts, and craft-focused e-commerce platforms. It suits any product where the maker's story matters — from small-batch food to handmade jewelry to vintage finds. The warm, photography-forward design also adapts well to editorial layouts, gift guides, and curated collection pages where browsing should feel like discovering treasures at a weekend market.
