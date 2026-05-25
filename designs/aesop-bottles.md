---
version: 1

meta:
  id: aesop-bottles
  name: Aesop
  description: "Apothecary-meets-editorial skincare brand built on amber glass, deep walnut typography, and generous serif whitespace"
  isDark: false
  tags: [minimal, luxurious, editorial, organic, professional]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "1987 founded; visual heritage consistent through 2024"
  region: "Melbourne, Australia"
  regionZh: "澳大利亚墨尔本"
  keyFigures: [Dennis Paphitis, Suzanne Santos, Marsotto Edizioni]
  movements: [indie skincare, store-as-art-installation, apothecary aesthetics]

introduction: |
  Aesop's visual identity is the rare brand language that refuses urgency. Founded in Melbourne in 1987, every element — the amber-glass bottles, the walnut-brown Spectral serif, the cream-paper backgrounds — is calibrated to feel like walking into a 19th-century apothecary that happens to sell modern skincare.

  The design system prizes editorial whitespace, rectangular apothecary-label geometry, and a warm two-tone palette of deep brown and amber. There are no gradients, no pills, no sans-serif headlines. Every surface reads like a slow-fashion lookbook printed on fine paper.
introductionZh: |
  Aesop 的视觉语言是一种罕见的「反急迫」品牌设计。1987 年诞生于澳大利亚墨尔本，每一个元素——琥珀色玻璃瓶、胡桃棕色的衬线字体、奶油纸色的背景——都被精心调校，让人仿佛置身于一家 19 世纪的药剂房，却售卖着当代护肤品。

  整套设计系统崇尚编辑式留白、方正的药瓶标签几何，以及深棕与琥珀的暖色双调色板。没有渐变、没有药丸圆角、没有无衬线标题。每一个界面都像一本慢时尚画册，印在上好的纸张上。

colors:
  primary:
    "50": "#FDF5F2"
    "100": "#FAEAE4"
    "200": "#F3D0C4"
    "300": "#EAB09D"
    "400": "#D47A5E"
    "500": "#9F4A2E"
    "600": "#8A3F27"
    "700": "#703320"
    "800": "#572718"
    "900": "#3E1C11"
    "950": "#2A120B"
  secondary:
    "50": "#F7F3F0"
    "100": "#EDE6DF"
    "200": "#D9CCC0"
    "300": "#BEAB99"
    "400": "#8D7561"
    "500": "#3D2817"
    "600": "#352313"
    "700": "#2B1D10"
    "800": "#22170C"
    "900": "#181009"
    "950": "#0F0A06"
  accent:
    "50": "#FEF9F3"
    "100": "#FDF2E5"
    "200": "#FAE2C6"
    "300": "#F5CCA0"
    "400": "#D9A56E"
    "500": "#B87D3E"
    "600": "#9C6A34"
    "700": "#7E552A"
    "800": "#614120"
    "900": "#452F17"
    "950": "#2D1F0F"
  neutral:
    "50": "#FAF7F0"
    "100": "#F5F0E8"
    "200": "#EDE7DC"
    "300": "#DDD5C8"
    "400": "#C4B9A9"
    "500": "#A69889"
    "600": "#8A7D6F"
    "700": "#6E6358"
    "800": "#524A41"
    "900": "#38322B"
    "950": "#201C17"
  semantic:
    success: { bg: "#3D6B45", text: "#FFFFFF", light: "#E8F0E9", border: "#3D6B45" }
    warning: { bg: "#B87D3E", text: "#FFFFFF", light: "#FDF2E5", border: "#B87D3E" }
    error:   { bg: "#9F4A2E", text: "#FFFFFF", light: "#FDF5F2", border: "#9F4A2E" }
    info:    { bg: "#3D2817", text: "#FFFFFF", light: "#F7F3F0", border: "#3D2817" }
  background:
    page:    "#F5F0E8"
    surface: "#FFFFFF"
    subtle:  "#FAF7F0"
  text:
    primary:   "#3D2817"
    secondary: "#5E4A38"
    muted:     "#7A6B5C"
    inverse:   "#FAF7F0"

typography:
  families:
    heading: "'Spectral', Georgia, 'Times New Roman', serif"
    body:    "'Spectral', Georgia, 'Times New Roman', serif"
    mono:    "'IBM Plex Mono', 'Courier New', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=IBM+Plex+Mono:wght@400;500&family=Spectral:ital,wght@0,300;0,400;0,500;0,600;0,700;1,400;1,500&display=swap"
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
  weights: { light: 300, normal: 400, medium: 500, semibold: 600, bold: 700, extrabold: 800 }
  lineHeights: { tight: 1.2, snug: 1.4, normal: 1.5, relaxed: 1.75, loose: 1.9 }
  letterSpacing: { tighter: "-0.04em", tight: "-0.01em", normal: "0", wide: "0.01em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      { sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:        { sm: "8px",  md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "48px", md: "80px", lg: "120px", xl: "160px" }

borders:
  radius: { none: "0", sm: "2px", md: "4px", lg: "6px", xl: "8px", full: "9999px" }
  color:  { default: "#3D2817", subtle: "#DDD5C8", strong: "#3D2817", focus: "#9F4A2E" }
  width:  { thin: "1px", default: "1px", thick: "2px" }
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
  focus: "0 0 0 2px rgba(159, 74, 46, 0.25)"

motion:
  level: "minimal"
  durations: { instant: "0ms", fast: "120ms", normal: "280ms", slow: "450ms", slower: "700ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.4, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.2, 1)"
    spring:  "cubic-bezier(0.22, 1, 0.36, 1)"
  hoverPatterns: [opacity, underline]
  reducedMotion: true

composition:
  layout:        "stack"
  contentWidth:  "container"
  framing:       "minimal"
  gridIntensity: "subtle"
  rhythm:        "8px"

surfaceStyle: "flat"
blur:         "none"

iconography:
  treatment: "linear"
  set:       "lucide"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "1px"

components:
  button:
    primary:
      background: "#9F4A2E"
      color: "#FFFFFF"
      border: "none"
      shadow: "none"
      hoverBackground: "#8A3F27"
      hoverShadow: "none"
      hoverColor: "#FFFFFF"
    secondary:
      background: "transparent"
      color: "#3D2817"
      border: "1px solid #3D2817"
      shadow: "none"
      hoverBackground: "#3D2817"
      hoverShadow: "none"
      hoverColor: "#FAF7F0"
    ghost:
      background: "transparent"
      color: "#3D2817"
      border: "none"
      shadow: "none"
      hoverBackground: "transparent"
      hoverShadow: "none"
      hoverColor: "#9F4A2E"
    danger:
      background: "#9F4A2E"
      color: "#FFFFFF"
      border: "none"
      shadow: "none"
      hoverBackground: "#703320"
      hoverShadow: "none"
      hoverColor: "#FFFFFF"
    sizes:
      sm: { height: "36px", padding: "8px 16px", fontSize: "0.875rem" }
      md: { height: "44px", padding: "10px 24px", fontSize: "1rem" }
      lg: { height: "52px", padding: "14px 32px", fontSize: "1.125rem" }
    borderRadius: "4px"
    fontWeight: 500
    letterSpacing: "0.01em"
    textTransform: "none"
  input:
    background: "#FAF7F0"
    color: "#3D2817"
    border: "1px solid #DDD5C8"
    borderRadius: "4px"
    padding: "10px 14px"
    focusBorder: "1px solid #9F4A2E"
    placeholderColor: "#7A6B5C"
  card:
    base:
      background: "#FFFFFF"
      border: "1px solid #DDD5C8"
      borderRadius: "4px"
      padding: "24px"
      shadow: "none"
    hover:
      shadow: "none"
      transform: "none"
---

# Aesop

> Australian skincare dressed as a 19th-century apothecary — amber glass, walnut serif, editorial calm.

## Origin

Aesop was founded in 1987 by Dennis Paphitis in Melbourne, Australia, with a philosophy that skincare should be intelligent, considered, and timeless. Alongside co-founder Suzanne Santos, Paphitis built a brand that rejects the glossy theatrics of luxury cosmetics in favor of amber-glass bottles, brown-and-white printed labels, and stores designed by different architects around the world — each one a site-specific art installation.

The visual language has remained remarkably consistent through four decades: deep walnut brown on warm cream paper, generous serif typography set in a rhythm closer to literary publishing than retail. Collaborations with Italian brand partners like Marsotto Edizioni and the Aesop Reading Room print quarterly reinforce the brand's commitment to slow culture. Every touchpoint — from the aesop.com editorial homepage to the individually-designed store interiors in Hong Kong, Tokyo, and beyond — communicates the same quiet conviction: beauty is found in restraint.

## Overview

Composition cues:
- **Layout**: Vertical stack with generous section padding; editorial rhythm
- **Content width**: Container (max ~1024px), centered on the cream-paper page
- **Framing**: Minimal — thin brown borders on cards, no decorative chrome
- **Grid intensity**: Subtle — asymmetric two-column for product/text pairings, otherwise single-column

## Colors

Aesop's palette is a two-tone study in warmth: deep walnut brown `#3D2817` for all text, amber `#9F4A2E` for calls-to-action and interactive accents. Backgrounds move between warm cream paper `#F5F0E8`, off-white `#FAF7F0`, and pristine editorial white `#FFFFFF`. There are no bright accents, no blues, no gradients — the color story is entirely warm and analog, evoking aged paper and amber-glass bottles.

**Role usage**:
- Page background → `colors.background.page` (warm cream `#F5F0E8`)
- Surface / cards → `colors.background.surface` (white `#FFFFFF`)
- Subtle panels → `colors.background.subtle` (off-white `#FAF7F0`)
- Body and heading text → `colors.text.primary` (walnut `#3D2817`)
- Muted captions → `colors.text.muted` (warm grey `#7A6B5C`)
- Primary CTA fills → `colors.primary.500` (amber `#9F4A2E`)
- Borders and secondary actions → `colors.secondary.500` (walnut `#3D2817`)

## Typography

The entire typographic system uses a single family — Spectral — for both headings and body, reflecting Aesop's commitment to editorial unity. Type is never bold-display or aggressive; the largest display sizes remain elegant and restrained. Body text is set at generous `1.75` line-height, giving every paragraph the breathing room of a literary quarterly. Letter-spacing is barely perceptible at `0.01em`, adding quiet refinement without calling attention to itself. Weight variation is subtle: headings at 600 or 500, body at 400, captions at 300.

**Text styles**:
- `display-xl` — Spectral, 64px, weight 600, line-height 1.2, letter-spacing 0.01em
- `display-lg` — Spectral, 48px, weight 600, line-height 1.2, letter-spacing 0.01em
- `heading-1` — Spectral, 36px, weight 600, line-height 1.3, letter-spacing 0.01em
- `body-lg` — Spectral, 18px, weight 400, line-height 1.75, letter-spacing 0
- `body-md` — Spectral, 16px, weight 400, line-height 1.75, letter-spacing 0
- `caption` — Spectral, 14px, weight 300, line-height 1.5, letter-spacing 0.01em
- `mono-md` — IBM Plex Mono, 14px, weight 400, line-height 1.6, letter-spacing 0

## Spacing & Layout

- Base unit: 8px rhythm
- Scale: 2 4 6 8 12 16 24 32 48 64 96 128 px
- Container widths: sm 640px, md 768px, lg 1024px, xl 1280px
- Section padding is deliberately oversized — 80px–160px vertical — creating the "slow lookbook" reading cadence
- Grid gaps are generous: 24px–48px between editorial columns

## Elevation & Depth

Aesop's surfaces are entirely flat. There are no shadows, no layering effects, no glass morphism. Depth is created exclusively through whitespace and the contrast between the warm cream page and pure white card surfaces. The visual hierarchy reads like printed paper overlaid on a desk — physical, not digital.

- Surface style: flat, no box-shadow on any element
- Blur: none
- Shadow ladder: all levels set to `none`
- Focus state: subtle 2px amber ring (`rgba(159, 74, 46, 0.25)`) for accessibility only

## Shapes

- Button border-radius: 4px (rectangular, apothecary-label feel)
- Card border-radius: 4px
- Input border-radius: 4px
- No pill-radius anywhere in the system
- Maximum radius in use: 8px (rare, for modal containers)

## Motion

Aesop's digital presence is deliberately still. Motion is minimal and functional — opacity fades and underline reveals on hover, nothing more. The brand communicates through stillness and considered pacing, not through animation. Transitions are slow enough to feel intentional (280ms default) without dragging.

- Level: minimal
- Default transition: 280ms ease-out
- Hover patterns: opacity fade to 0.7, text-decoration underline reveal
- No scale, lift, glow, or tint effects
- Reduced-motion: fully supported, all transitions collapse to instant

## Techniques

### Apothecary Label Card

A paper-framed card with a thin walnut border that evokes Aesop's printed product labels.

```css
.apothecary-card {
  background: #FFFFFF;
  border: 1px solid #3D2817;
  border-radius: 4px;
  padding: 32px;
  position: relative;
}
.apothecary-card::after {
  content: '';
  position: absolute;
  inset: 4px;
  border: 1px solid rgba(61, 40, 23, 0.15);
  border-radius: 2px;
  pointer-events: none;
}
```

### Amber CTA with Ink Transition

A filled amber button that darkens on hover like ink absorbing into paper, using no shadow or scale.

```css
.amber-cta {
  background: #9F4A2E;
  color: #FFFFFF;
  border: none;
  border-radius: 4px;
  padding: 10px 24px;
  font-family: 'Spectral', Georgia, serif;
  font-weight: 500;
  letter-spacing: 0.01em;
  transition: background 280ms cubic-bezier(0, 0, 0.2, 1);
  cursor: pointer;
}
.amber-cta:hover {
  background: #703320;
}
```

### Editorial Whitespace Section

A full-width section using exaggerated vertical padding and a single centered text block, replicating the pacing of Aesop's reading-room editorials.

```css
.editorial-section {
  background: #FFFFFF;
  padding: 120px 24px;
  max-width: 640px;
  margin: 0 auto;
}
.editorial-section h2 {
  font-family: 'Spectral', Georgia, serif;
  font-size: 2.25rem;
  font-weight: 600;
  line-height: 1.3;
  color: #3D2817;
  letter-spacing: 0.01em;
  margin-bottom: 32px;
}
.editorial-section p {
  font-family: 'Spectral', Georgia, serif;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.75;
  color: #3D2817;
}
```

## Iconography

Icons are used sparingly — Aesop's visual system prefers text and whitespace over pictographic shorthand. When icons appear, they are thin linear strokes that complement rather than compete with the serif typography.

- Treatment: linear, 1px stroke weight
- Set: Lucide
- Sizes: 16px (inline), 20px (UI), 24px (navigation)

## Do's & Don'ts

### ✓ Do
- Use Spectral for every text element — headings, body, captions, buttons
- Let whitespace do the compositional work; sections should breathe
- Keep the color palette strictly within the walnut-amber-cream range
- Use rectangular 4px-radius shapes for all interactive elements
- Treat every page as an editorial spread, not a dashboard

### ✗ Don't
- Use sans-serif typefaces anywhere (Aesop is rigorously serif)
- Introduce bright accent colors outside the amber and brown family
- Apply modern SaaS gradient backgrounds
- Use Brutalist anti-design or raw, unpolished aesthetics
- Use pill-radius buttons or large rounded corners

## Applications

Aesop's design system is best suited for editorial product pages, brand storytelling sites, and luxury e-commerce experiences that prioritize reading comfort over conversion density. It excels in long-form content, lookbook-style product showcases, and any interface where the user should slow down and absorb rather than scan and click. The warm, bookish palette also works beautifully for cultural publications, literary journals, and curated marketplace storefronts.
