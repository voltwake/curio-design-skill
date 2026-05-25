---
version: 1

meta:
  id: substack-2023
  name: Substack 2023
  description: "The newsletter platform that looks like a bookstore — warm cream paper, signature orange-red, and serif-driven editorial layouts for independent writers"
  isDark: false
  tags: [editorial, friendly, modernist, professional]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2017 founded; current visual ~2022–2024"
  region: "San Francisco, United States"
  regionZh: "美国旧金山"
  keyFigures: ["Chris Best", "Hamish McKenzie", "Jairaj Sethi", "Substack Brand team"]
  movements: ["Independent writer economy", "post-Twitter media", "paid newsletters"]

introduction: |
  Substack is the platform that gave independent writers a dignified home on the internet. Its visual identity — warm cream backgrounds, signature orange-red, and editorial serif typography — says "literary tradition" while feeling approachably modern, more like browsing a curated bookstore than navigating SaaS software.

  The design system centers on reading comfort. Generous line-heights, narrow content columns, and a restrained palette of cream, charcoal, and a single accent orange let the writing itself be the hero. Every element, from newsletter-card grids to filled-orange CTAs, serves a publishing platform that takes its writers seriously.
introductionZh: |
  Substack 是让独立写作者在互联网上拥有体面家园的平台。它的视觉身份——温暖的奶油色背景、标志性的橙红色和编辑风格的衬线字体——传递着"文学传统"的气质，同时保持着平易近人的现代感，更像是在逛一家精心策展的书店，而非操作一款SaaS软件。

  整套设计体系以阅读舒适度为核心。宽裕的行高、克制的内容栏宽、以及仅由奶油色、炭灰色和一抹橙色构成的极简色板，让文字本身成为绝对主角。从通讯卡片网格到醒目的橙色行动按钮，每一个元素都在为这个认真对待写作者的出版平台服务。

colors:
  primary:
    "50": "#FFF5EE"
    "100": "#FFE4D1"
    "200": "#FFC9A3"
    "300": "#FFA96E"
    "400": "#FF8843"
    "500": "#FF6719"
    "600": "#E55A14"
    "700": "#BF4A10"
    "800": "#993B0D"
    "900": "#732C09"
    "950": "#4D1D06"
  secondary:
    "50": "#F8F8F8"
    "100": "#F0F0F0"
    "200": "#E0E0E0"
    "300": "#C8C8C8"
    "400": "#A0A0A0"
    "500": "#6B6B6B"
    "600": "#585858"
    "700": "#454545"
    "800": "#333333"
    "900": "#1F1F1F"
    "950": "#0F0F0F"
  accent:
    "50": "#FFF5EE"
    "100": "#FFE4D1"
    "200": "#FFC9A3"
    "300": "#FFA96E"
    "400": "#FF8843"
    "500": "#FF6719"
    "600": "#E55A14"
    "700": "#BF4A10"
    "800": "#993B0D"
    "900": "#732C09"
    "950": "#4D1D06"
  neutral:
    "50": "#FAF9F7"
    "100": "#F5F2EC"
    "200": "#EBE7DF"
    "300": "#DDD9D0"
    "400": "#B8B3AA"
    "500": "#8E8981"
    "600": "#6B6B6B"
    "700": "#525252"
    "800": "#3A3A3A"
    "900": "#1F1F1F"
    "950": "#0F0F0F"
  semantic:
    success: { bg: "#2D7D46", text: "#FFFFFF", light: "#E6F4EA", border: "#4CAF50" }
    warning: { bg: "#E6A817", text: "#1F1F1F", light: "#FFF8E1", border: "#FFB300" }
    error:   { bg: "#D32F2F", text: "#FFFFFF", light: "#FDECEA", border: "#EF5350" }
    info:    { bg: "#1976D2", text: "#FFFFFF", light: "#E3F2FD", border: "#42A5F5" }
  background:
    page:    "#F5F2EC"
    surface: "#FFFFFF"
    subtle:  "#EBE7DF"
  text:
    primary:   "#1F1F1F"
    secondary: "#525252"
    muted:     "#6B6B6B"
    inverse:   "#FFFFFF"

typography:
  families:
    heading: "'Newsreader', 'Georgia', serif"
    body:    "'Source Serif 4', 'Georgia', serif"
    mono:    "'JetBrains Mono', 'Courier New', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Newsreader:ital,opsz,wght@0,6..72,400;0,6..72,500;0,6..72,600;0,6..72,700;1,6..72,400;1,6..72,500&family=Source+Serif+4:ital,opsz,wght@0,8..60,400;0,8..60,500;0,8..60,600;0,8..60,700;1,8..60,400;1,8..60,500&family=JetBrains+Mono:wght@400;500&display=swap"
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
  lineHeights: { tight: 1.2, snug: 1.375, normal: 1.5, relaxed: 1.625, loose: 1.8 }
  letterSpacing: { tighter: "-0.04em", tight: "-0.02em", normal: "0", wide: "0.05em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      { sm: "640px", md: "720px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:        { sm: "8px", md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "4px", md: "6px", lg: "8px", xl: "12px", full: "9999px" }
  color:  { default: "#DDD9D0", subtle: "#EBE7DF", strong: "#1F1F1F", focus: "#FF6719" }
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
  focus: "0 0 0 3px rgba(255, 103, 25, 0.25)"

motion:
  level: "restrained"
  durations: { instant: "0ms", fast: "120ms", normal: "250ms", slow: "400ms", slower: "600ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.4, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.2, 1)"
    spring:  "cubic-bezier(0.22, 1, 0.36, 1)"
  hoverPatterns: [tint, opacity, underline]
  reducedMotion: true

composition:
  layout:        "grid"
  contentWidth:  "narrow"
  framing:       "solid"
  gridIntensity: "soft"
  rhythm:        "4px"

surfaceStyle: "solid"
blur:         "none"

iconography:
  treatment: "linear"
  set:       "lucide"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "1.5px"

components:
  button:
    primary:   { background: "#FF6719", color: "#FFFFFF", border: "none", shadow: "none", hoverBackground: "#E55A14", hoverShadow: "none", hoverColor: "#FFFFFF" }
    secondary: { background: "transparent", color: "#1F1F1F", border: "1px solid #1F1F1F", shadow: "none", hoverBackground: "#1F1F1F", hoverShadow: "none", hoverColor: "#FFFFFF" }
    ghost:     { background: "transparent", color: "#1F1F1F", border: "none", shadow: "none", hoverBackground: "rgba(31,31,31,0.06)", hoverShadow: "none", hoverColor: "#1F1F1F" }
    danger:    { background: "#D32F2F", color: "#FFFFFF", border: "none", shadow: "none", hoverBackground: "#B71C1C", hoverShadow: "none", hoverColor: "#FFFFFF" }
    sizes:
      sm: { height: "36px", padding: "0 16px", fontSize: "0.875rem" }
      md: { height: "44px", padding: "0 24px", fontSize: "1rem" }
      lg: { height: "52px", padding: "0 32px", fontSize: "1.125rem" }
    borderRadius: "6px"
    fontWeight: 600
    letterSpacing: "0"
    textTransform: "none"
  input:
    background: "#F5F2EC"
    color: "#1F1F1F"
    border: "1px solid #DDD9D0"
    borderRadius: "6px"
    padding: "10px 14px"
    focusBorder: "2px solid #FF6719"
    placeholderColor: "#8E8981"
  card:
    base:  { background: "#FFFFFF", border: "1px solid #EBE7DF", borderRadius: "8px", padding: "24px", shadow: "none" }
    hover: { shadow: "none", transform: "none" }
---

# Substack 2023

> The newsletter platform that looks like a bookstore — warm cream, signature orange-red, and serif-driven editorial layouts for independent writers.

## Origin

Substack was founded in 2017 by Chris Best, Hamish McKenzie, and Jairaj Sethi in San Francisco with a simple bet: that independent writers could build sustainable businesses through paid newsletters. What began as a minimal publishing tool grew into the defining platform of the independent writer economy, attracting journalists fleeing legacy media and essayists seeking direct connection with readers. The visual identity matured significantly around 2022–2024, moving from generic SaaS to a deliberately literary aesthetic that positions Substack as an heir to the small-press tradition.

The current design language draws on editorial magazine heritage and the warm materiality of printed books. The signature orange-red (#FF6719), warmer and redder than typical tech-brand oranges, acts as the single chromatic voice across a restrained palette of cream and charcoal. Serif typography — Tiempos Headline in the real product, approximated here by Newsreader and Source Serif 4 — signals that Substack is a publishing platform first and a technology product second. The April 2023 launch of Substack Notes extended this identity into a social layer, proving the visual system could flex beyond long-form reading into shorter-form discourse.

## Overview
Composition cues:
- **Layout**: Newsletter-card grid for discovery; single-column reading layout for articles
- **Content width**: Narrow — reading column max-width ~720px for comfortable long-form measure
- **Framing**: Solid — cream-paper cards and white reading surfaces, no glass or transparency
- **Grid intensity**: Soft — card grid for browsing, clean single-column for reading

## Colors
Substack's palette is deliberately bookish. The warm cream (#F5F2EC) evokes uncoated paper stock, creating a ground that feels physical rather than digital. The signature orange-red (#FF6719) is the single chromatic accent — warmer than Mailchimp's yellow, redder than Patagonia's rust — used for primary CTAs, subscribe buttons, and the occasional editorial highlight. Body text sits in deep charcoal (#1F1F1F) rather than pure black, softened just enough for comfortable long-form reading. The reading interface switches to pure white (#FFFFFF) to maximize contrast and reduce fatigue during extended sessions.

**Role usage**:
- Marketing & discovery backgrounds → `colors.background.page` (`#F5F2EC`)
- Reading interface & cards → `colors.background.surface` (`#FFFFFF`)
- Subtle section breaks → `colors.background.subtle` (`#EBE7DF`)
- Subscribe buttons & primary CTAs → `colors.primary.500` (`#FF6719`)
- Headlines & body text → `colors.text.primary` (`#1F1F1F`)
- Author bylines & secondary info → `colors.text.secondary` (`#525252`)
- Timestamps & metadata → `colors.text.muted` (`#6B6B6B`)
- Card borders & dividers → `colors.neutral.300` (`#DDD9D0`)

## Typography
Substack's typographic voice is literary but approachable — editorial serif that says "independent press" rather than "academic journal." Headlines are set in Newsreader at semibold with slight negative tracking (-0.01em), giving them the gravity of magazine cover lines. Body text runs in Source Serif 4 at generous 1.7 line-height, optimized for the long-form essays and newsletters that define the platform. The serif typography IS the brand texture — every curve and serif reinforces that this is a place for serious writing.

**Text styles**:
- `display-xl` — Newsreader, 96px, weight 700, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Newsreader, 64px, weight 700, line-height 1.05, letter-spacing -0.02em
- `heading-1` — Newsreader, 40px, weight 600, line-height 1.2, letter-spacing -0.01em
- `body-lg` — Source Serif 4, 20px, weight 400, line-height 1.7, letter-spacing 0
- `body-md` — Source Serif 4, 18px, weight 400, line-height 1.7, letter-spacing 0
- `caption` — Source Serif 4, 14px, weight 500, line-height 1.5, letter-spacing 0
- `mono-md` — JetBrains Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout
- Base unit: 4px rhythm
- Scale: 2 · 4 · 6 · 8 · 12 · 16 · 24 · 32 · 48 · 64 · 96 · 128 px
- Container max-width: 1280px for grid layouts; reading column max ~720px
- Section vertical padding: 64–128px — unhurried editorial pacing
- Grid gap: 16–24px between newsletter cards

## Elevation & Depth
Substack is a paper-first medium. There are no drop shadows, no frosted glass, no floating layers. Surfaces are differentiated through background color alone — cream for the marketing shell, white for reading and card interiors. The only "depth" is the warm-cool contrast between the cream page and white card surface, evoking a newsletter laid flat on a wooden desk. Focus states use a soft orange glow ring rather than a shadow lift.

- Surface style: solid — flat paper and ink
- Shadow ladder: all `none`
- Blur: none
- Focus ring: soft orange outline (`0 0 0 3px rgba(255, 103, 25, 0.25)`)

## Shapes
- Button border-radius: 6px — softly rounded, approachable but not bubbly
- Card border-radius: 8px — gentle rounding for newsletter preview cards
- Input border-radius: 6px — matching button radius for consistency
- General border-radius: 4–8px range — modern editorial, not hard-edged

## Motion
Substack moves with restrained confidence. The platform is built for reading, and nothing should compete with the writer's words for the reader's attention. Interactions are acknowledged with quick tint shifts and subtle opacity changes. Subscribe buttons respond with a color darken on hover. Link underlines appear smoothly. There are no bounces, lifts, or playful animations — the motion temperament is that of a well-designed magazine app, not a consumer social product.

- Level: restrained
- Hover transition: 250ms ease-out tint or opacity shift
- Page transitions: 400ms cross-fade
- Easing: `cubic-bezier(0.4, 0, 0.2, 1)` default
- Hover patterns: tint darken, opacity fade, underline reveal
- Reduced motion: always respected

## Techniques

### Cream Paper Newsletter Card
The signature Substack content card — a white card on cream background with subtle border, resembling a newsletter laid on a table.
```css
.newsletter-card {
  background: #FFFFFF;
  border: 1px solid #EBE7DF;
  border-radius: 8px;
  padding: 24px;
  max-width: 720px;
  transition: border-color 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.newsletter-card:hover {
  border-color: #DDD9D0;
}
.newsletter-card__title {
  font-family: 'Newsreader', serif;
  font-size: 1.5rem;
  font-weight: 600;
  color: #1F1F1F;
  letter-spacing: -0.01em;
  line-height: 1.3;
  margin-bottom: 8px;
}
.newsletter-card__excerpt {
  font-family: 'Source Serif 4', serif;
  font-size: 1rem;
  color: #525252;
  line-height: 1.6;
}
```

### Orange Subscribe CTA
The filled-orange primary action button — Substack's most recognizable UI element, used for subscribe and upgrade actions.
```css
.subscribe-btn {
  background: #FF6719;
  color: #FFFFFF;
  border: none;
  border-radius: 6px;
  padding: 10px 24px;
  font-family: 'Source Serif 4', serif;
  font-size: 1rem;
  font-weight: 600;
  cursor: pointer;
  transition: background 200ms cubic-bezier(0.4, 0, 0.2, 1);
}
.subscribe-btn:hover {
  background: #E55A14;
}
.subscribe-btn:focus-visible {
  outline: none;
  box-shadow: 0 0 0 3px rgba(255, 103, 25, 0.25);
}
```

### Editorial Reading Column
The long-form reading layout — a narrow centered column with generous line-height and serif body text, optimized for sustained reading.
```css
.reading-column {
  max-width: 720px;
  margin: 0 auto;
  padding: 64px 24px;
  background: #FFFFFF;
}
.reading-column h1 {
  font-family: 'Newsreader', serif;
  font-size: 2.5rem;
  font-weight: 700;
  color: #1F1F1F;
  letter-spacing: -0.01em;
  line-height: 1.15;
  margin-bottom: 16px;
}
.reading-column p {
  font-family: 'Source Serif 4', serif;
  font-size: 1.125rem;
  color: #1F1F1F;
  line-height: 1.7;
  margin-bottom: 1.5em;
}
.reading-column a {
  color: #1F1F1F;
  text-decoration: underline;
  text-decoration-color: #FF6719;
  text-underline-offset: 3px;
}
```

## Iconography
Icons are drawn from the Lucide set in linear style at 1.5px stroke weight, slightly heavier than a pure-editorial system to maintain warmth and approachability. They serve navigation, social sharing, and utility roles — the visual personality comes from typography and the orange accent, not from iconographic expression.

- Treatment: linear / outline
- Set: Lucide
- Stroke: 1.5px — warm and readable at small sizes

## Do's & Don'ts

### ✓ Do
- Use Substack orange (#FF6719) for primary actions — subscribe buttons, upgrade CTAs, link underlines
- Set body text in Source Serif 4 at 1.7+ line-height for long-form reading comfort
- Use warm cream (#F5F2EC) as the default background for marketing and discovery surfaces
- Switch to pure white (#FFFFFF) for the reading interface to maximize text contrast
- Keep newsletter cards simple — white on cream with subtle borders, no shadow theatrics

### ✗ Don't
- Use sans-serif body text — the serif IS the brand identity
- Use pure white backgrounds in marketing contexts — warm cream differentiates Substack from generic SaaS
- Introduce multiple chromatic accents — Substack orange is the one and only color voice
- Apply modern brutalist edges or sharp geometric treatments
- Add friendly playful illustrations — Substack is literary-serious, not whimsical

## Applications
The Substack 2023 system is ideal for newsletter platforms, independent publishing tools, long-form reading interfaces, and writer-focused content management systems. Its editorial serif typography, warm paper-like backgrounds, and narrow reading columns create an environment that treats written content with the respect of a print publication. The system also works well for literary magazines, essay collections, book review sites, and any product that wants to signal "we take writing seriously" without the austerity of academic design.
