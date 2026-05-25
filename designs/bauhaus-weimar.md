---
version: 1

meta:
  id: bauhaus-weimar
  name: Bauhaus Weimar
  description: "Functional clarity through geometric primitives and primary colors, rooted in the 1919–1933 Bauhaus school"
  isDark: false
  tags: [modernist, decorative, historical, experimental, bold]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "1919–1933"
  region: "Weimar, Dessau, Berlin — Germany"
  regionZh: "德国魏玛、德绍、柏林"
  keyFigures: [Walter Gropius, László Moholy-Nagy, Wassily Kandinsky, Herbert Bayer]
  movements: [Modernism, Functionalism, De Stijl-adjacent]

introduction: |
  The Bauhaus school, founded by Walter Gropius in 1919 Weimar, fused fine art, craft, and industrial production into a single discipline. Its visual language — geometric primitives, primary colors, and unadorned sans-serif type — rejected ornament in favor of functional clarity.

  This design system distills that philosophy into digital tokens: bold red, blue, and yellow on cream paper; Josefin Sans headings stripped of capitals; hard-edged shadows without blur; and asymmetric grids governed by the circle, square, and triangle.
introductionZh: |
  包豪斯学校由沃尔特·格罗皮乌斯于 1919 年在德国魏玛创立，将纯艺术、手工艺与工业生产融为一体。它以几何基本形——圆形、正方形、三角形——和三原色构建视觉语言，摒弃一切多余装饰，追求功能至上的清晰表达。

  本设计系统将包豪斯精神转化为数字设计令牌：奶油纸底上的纯正红蓝黄、去掉大写的几何无衬线字体、无模糊的硬偏移投影，以及由不对称网格驱动的版面节奏，致敬这一改变了现代设计走向的运动。

colors:
  primary:
    "50": "#fde8e8"
    "100": "#fac5c5"
    "200": "#f59090"
    "300": "#ef5b5b"
    "400": "#e82d2d"
    "500": "#d50000"
    "600": "#b30000"
    "700": "#900000"
    "800": "#6e0000"
    "900": "#4d0000"
    "950": "#2e0000"
  secondary:
    "50": "#e8ecf5"
    "100": "#c5cfe8"
    "200": "#8fa0d1"
    "300": "#5a72ba"
    "400": "#2e50b0"
    "500": "#1a3da6"
    "600": "#15328a"
    "700": "#10276e"
    "800": "#0c1c52"
    "900": "#081237"
    "950": "#040920"
  accent:
    "50": "#fff9e0"
    "100": "#fff2b3"
    "200": "#ffe866"
    "300": "#ffdf1a"
    "400": "#ffd500"
    "500": "#ffd500"
    "600": "#d4b200"
    "700": "#aa8e00"
    "800": "#806b00"
    "900": "#554700"
    "950": "#332b00"
  neutral:
    "50": "#f8f6f0"
    "100": "#f4ecd8"
    "200": "#e8dcc0"
    "300": "#d4c8a8"
    "400": "#b0a080"
    "500": "#8c7a5c"
    "600": "#6e6048"
    "700": "#504636"
    "800": "#332c22"
    "900": "#1a1610"
    "950": "#0d0b08"
  semantic:
    success: { bg: "#1a8a1a", text: "#ffffff", light: "#e6f5e6", border: "#1a8a1a" }
    warning: { bg: "#ffd500", text: "#1a1610", light: "#fff9e0", border: "#d4b200" }
    error:   { bg: "#d50000", text: "#ffffff", light: "#fde8e8", border: "#b30000" }
    info:    { bg: "#1a3da6", text: "#ffffff", light: "#e8ecf5", border: "#15328a" }
  background:
    page:    "#f4ecd8"
    surface: "#ffffff"
    subtle:  "#f8f6f0"
  text:
    primary:   "#1a1610"
    secondary: "#504636"
    muted:     "#8c7a5c"
    inverse:   "#f4ecd8"

typography:
  families:
    heading: "'Josefin Sans', 'Work Sans', sans-serif"
    body:    "'Work Sans', 'Helvetica Neue', sans-serif"
    mono:    "'JetBrains Mono', 'Courier New', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@300;400;500;600;700&family=Work+Sans:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500;700&display=swap"
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
  lineHeights: { tight: 1.1, snug: 1.25, normal: 1.5, relaxed: 1.625, loose: 1.8 }
  letterSpacing: { tighter: "-0.04em", tight: "-0.02em", normal: "0", wide: "0.08em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container: { sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:   { sm: "8px", md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "0", md: "0", lg: "0", xl: "0", full: "9999px" }
  color:  { default: "#1a1610", subtle: "#d4c8a8", strong: "#000000", focus: "#1a3da6" }
  width:  { thin: "1px", default: "2px", thick: "4px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "2px 2px 0 #1a1610"
  sm: "3px 3px 0 #1a1610"
  md: "4px 4px 0 #1a1610"
  lg: "6px 6px 0 #1a1610"
  xl: "8px 8px 0 #1a1610"
  "2xl": "12px 12px 0 #1a1610"
  inner: "inset 2px 2px 0 rgba(0,0,0,0.08)"
  focus: "0 0 0 3px rgba(26,61,166,0.4)"

motion:
  level: "minimal"
  durations: { instant: "0ms", fast: "100ms", normal: "200ms", slow: "350ms", slower: "500ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.4, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.2, 1)"
    spring:  "cubic-bezier(0.175, 0.885, 0.32, 1.275)"
  hoverPatterns: [stroke, opacity, tint]
  reducedMotion: true

composition:
  layout:        "grid"
  contentWidth:  "container"
  framing:       "bordered"
  gridIntensity: "strong"
  rhythm:        "4px"

surfaceStyle: "flat"
blur:         "none"

iconography:
  treatment: "linear"
  set:       "lucide"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "2px"

components:
  button:
    primary:   { background: "#d50000", color: "#ffffff", border: "2px solid #1a1610", shadow: "3px 3px 0 #1a1610", hoverBackground: "#b30000", hoverShadow: "1px 1px 0 #1a1610", hoverColor: "#ffffff" }
    secondary: { background: "#1a3da6", color: "#ffffff", border: "2px solid #1a1610", shadow: "3px 3px 0 #1a1610", hoverBackground: "#15328a", hoverShadow: "1px 1px 0 #1a1610", hoverColor: "#ffffff" }
    ghost:     { background: "transparent", color: "#1a1610", border: "2px solid #1a1610", shadow: "none", hoverBackground: "#f4ecd8", hoverShadow: "none", hoverColor: "#1a1610" }
    danger:    { background: "#d50000", color: "#ffffff", border: "2px solid #6e0000", shadow: "3px 3px 0 #6e0000", hoverBackground: "#b30000", hoverShadow: "1px 1px 0 #6e0000", hoverColor: "#ffffff" }
    sizes:
      sm: { height: "32px", padding: "0 12px", fontSize: "0.75rem" }
      md: { height: "40px", padding: "0 20px", fontSize: "0.875rem" }
      lg: { height: "48px", padding: "0 28px", fontSize: "1rem" }
    borderRadius: "0"
    fontWeight: 700
    letterSpacing: "0.08em"
    textTransform: "uppercase"
  input:
    background: "#ffffff"
    color: "#1a1610"
    border: "2px solid #1a1610"
    borderRadius: "0"
    padding: "8px 12px"
    focusBorder: "2px solid #1a3da6"
    placeholderColor: "#8c7a5c"
  card:
    base:  { background: "#ffffff", border: "2px solid #1a1610", borderRadius: "0", padding: "24px", shadow: "4px 4px 0 #1a1610" }
    hover: { shadow: "2px 2px 0 #1a1610", transform: "translate(2px, 2px)" }
---

# Bauhaus Weimar

> Functional clarity through geometric primitives and the three primary colors — circle, square, triangle; red, blue, yellow.

## Origin

The Bauhaus was founded in 1919 by architect Walter Gropius in Weimar, Germany, as a radical experiment in uniting fine art, craft, and industrial production under one roof. Its faculty — Kandinsky, Klee, Moholy-Nagy, Bayer, Albers, Breuer — developed a visual curriculum built on geometric fundamentals and the rejection of bourgeois ornament. The school moved to Dessau in 1925 and Berlin in 1932 before the Nazi regime forced its closure in 1933.

Despite its short life, Bauhaus became the most influential design school in history. Herbert Bayer's "universal" lowercase alphabet, Kandinsky's color-shape theory (yellow=triangle, red=square, blue=circle), and Moholy-Nagy's experiments in photography and typography established a design grammar that remains legible a century later. This system translates that grammar into digital tokens: bold primary fills, hard geometry, no blur, no ornament — form follows function.

## Overview

Composition cues:
- **Layout**: Asymmetric grid with strong horizontal and diagonal axes
- **Content width**: Container-bound (1024–1280px), with occasional full-bleed primary-color blocks
- **Framing**: Thick black borders on cards and surfaces; no rounded corners
- **Grid intensity**: Strong — visible structure, deliberate alignment to a 4px baseline

## Colors

The Bauhaus color system descends directly from Kandinsky's 1923 questionnaire mapping primary colors to primary shapes. Red, blue, and yellow are used at full saturation as bold, flat fills — never muted, never gradient. Black provides structural weight (borders, type, rules), cream (#f4ecd8) provides the warm paper ground, and white serves as the clean surface.

**Role usage**:
- Page background → `colors.background.page` (cream #f4ecd8)
- Card/surface background → `colors.background.surface` (white)
- Primary actions, alerts → `colors.primary.500` (red #d50000)
- Secondary actions, links → `colors.secondary.500` (blue #1a3da6)
- Highlights, accents, tags → `colors.accent.500` (yellow #ffd500)
- Body text, borders → `colors.text.primary` (near-black #1a1610)
- Muted/caption text → `colors.text.muted`
- Inverse text on dark fills → `colors.text.inverse`

## Typography

Bauhaus typography is geometric, economical, and deliberately lowercase. Herbert Bayer argued that two alphabets (upper and lower case) were wasteful; his Universal typeface used only lowercase forms. This system uses Josefin Sans — a geometric sans-serif inspired by 1920s Scandinavian and German modernism — for headings, with Work Sans for body text. Uppercase is reserved for button labels and tags, rendered with wide letter-spacing.

**Text styles**:
- `display-xl` — Josefin Sans, 96px, weight 700, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Josefin Sans, 64px, weight 700, line-height 1.1, letter-spacing -0.02em
- `heading-1` — Josefin Sans, 48px, weight 600, line-height 1.1, letter-spacing -0.02em
- `body-lg` — Work Sans, 18px, weight 400, line-height 1.5, letter-spacing 0
- `body-md` — Work Sans, 16px, weight 400, line-height 1.5, letter-spacing 0
- `caption` — Work Sans, 12px, weight 500, line-height 1.25, letter-spacing 0.08em, uppercase
- `mono-md` — JetBrains Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout

- Base unit: 4px
- Scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128px
- Container max-widths: sm 640px, md 768px, lg 1024px, xl 1280px
- Grid gap: 16px default; 24px for larger layouts
- Section padding: 64px vertical (md), scaling to 96–128px on larger viewports
- Rhythm: strict 4px baseline grid

## Elevation & Depth

The Bauhaus rejected illusionistic depth. There are no soft shadows, no blur, no gradient overlays. When elevation is needed, it is expressed through hard-offset solid shadows — a flat colored rectangle displaced by a fixed number of pixels, recalling screenprint registration marks and constructivist poster layering.

- Surface style: flat — no glass, no layering
- Blur: none (0px throughout)
- Shadow ladder: hard-offset only — `2px 2px 0`, `4px 4px 0`, `6px 6px 0`, etc., in near-black
- Hover interaction: shadow compresses (offset decreases) and element translates toward its shadow

## Shapes

- All border radii: `0` (sharp right angles throughout)
- Exception: `full: 9999px` for pure circles (Kandinsky's blue-circle motif)
- No rounded rectangles — the only curved form allowed is the perfect circle

## Motion

Bauhaus design is static by nature — posters, architecture, furniture. Motion is minimal and mechanical: short durations, linear or ease-out timing, no bounce or spring. Transitions communicate state change, not personality.

- Level: minimal
- Durations: fast 100ms, normal 200ms, slow 350ms
- Easings: standard ease-out; no spring physics
- Hover patterns: stroke-weight change, opacity shift, background tint swap
- `prefers-reduced-motion`: fully respected

## Techniques

### Primary-color block accent

A full-width section break using a saturated primary color as background, inverting text to white or cream. Used to punctuate page rhythm with bold Bauhaus energy.

```css
.block-accent {
  background-color: #d50000;
  color: #f4ecd8;
  padding: 64px 0;
  text-transform: lowercase;
  letter-spacing: 0.08em;
  font-family: 'Josefin Sans', sans-serif;
  font-weight: 700;
}
```

### Hard-offset shadow press

Interactive elements use a hard shadow that compresses on hover/active, creating a tactile "press" without any blur or soft gradient. The element translates toward its shadow.

```css
.shadow-press {
  box-shadow: 4px 4px 0 #1a1610;
  transition: box-shadow 100ms ease-out, transform 100ms ease-out;
}
.shadow-press:hover {
  box-shadow: 2px 2px 0 #1a1610;
  transform: translate(2px, 2px);
}
.shadow-press:active {
  box-shadow: 0 0 0 #1a1610;
  transform: translate(4px, 4px);
}
```

### Geometric shape badge

A decorative element using Kandinsky's color-shape associations: yellow triangle, red square, blue circle — used as tags, status badges, or section markers.

```css
.badge-circle {
  width: 32px;
  height: 32px;
  border-radius: 9999px;
  background-color: #1a3da6;
  border: 2px solid #1a1610;
}
.badge-square {
  width: 32px;
  height: 32px;
  border-radius: 0;
  background-color: #d50000;
  border: 2px solid #1a1610;
}
.badge-triangle {
  width: 0;
  height: 0;
  border-left: 16px solid transparent;
  border-right: 16px solid transparent;
  border-bottom: 28px solid #ffd500;
}
```

## Iconography

Icons follow the Bauhaus principle of reduction to essentials. Line-based, geometric, with consistent 2px stroke weight — no fills, no decorative detail. Each icon should feel like it could have been drawn with a compass and straight edge.

- Treatment: linear (stroke only)
- Set: Lucide (closest to Bauhaus geometric clarity)
- Stroke: 2px, square caps, sharp joins

## Do's & Don'ts

### Do
- Use pure primary red, blue, and yellow at full saturation for key UI elements
- Prefer lowercase for headings and labels (following Bayer's Universal principle)
- Apply hard-offset solid shadows instead of soft/blurred ones
- Use sharp 0-radius corners on all rectangular elements
- Let negative space and the cream background breathe between elements

### Don't
- Use soft pastels — Bauhaus was bold and saturated, not gentle
- Use serif fonts of any kind — Bauhaus rejected calligraphic tradition
- Apply gradients, blur effects, or glassmorphism — these contradict material honesty
- Use brown, olive, or earthy palettes — those belong to Arts & Crafts, not Bauhaus
- Add decorative organic curves — all curves must be perfect circles or arcs

## Applications

This system is best suited for portfolio sites, design tool interfaces, editorial layouts, and landing pages that want to project confident modernist authority. It works well for creative studios, architecture firms, design education platforms, and cultural institutions. The strong geometric vocabulary and bold primary palette ensure high visual impact at any scale.
