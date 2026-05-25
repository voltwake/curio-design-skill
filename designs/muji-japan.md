---
version: 1

meta:
  id: muji-japan
  name: MUJI
  description: The no-brand brand — warm cream, kraft brown, and black text stripped to the necessary
  isDark: false
  tags: [minimal, organic, friendly, professional, editorial]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "1980 founded as Mujirushi Ryōhin; current visual heritage continuous since Kenya Hara's art direction from 2002"
  region: "Tokyo, Japan"
  regionZh: "日本东京"
  keyFigures: [Kenya Hara, Naoto Fukasawa, Ikko Tanaka]
  movements: [Anti-brand minimalism, Japanese craft heritage, Sustainable mass-market design]

introduction: |
  MUJI — Mujirushi Ryōhin, literally "no-brand quality goods" — was born in 1980 as a deliberate rejection of consumer-brand decoration. Products are unbadged, packaging reveals the thing itself rather than selling a lifestyle, and every visual decision serves the philosophy that removing the unnecessary reveals the essential.

  Under Kenya Hara's art direction since 2002, MUJI's visual language crystallized into warm cream backgrounds, kraft-brown paper tones, and black type set with Japanese density and editorial restraint. The result is a design system that feels like unbleached paper and pale wood — quiet, honest, and deliberately anti-decorative.
introductionZh: |
  無印良品（MUJI）于 1980 年在日本创立，其名称字面意思为"没有品牌的优质商品"。它的诞生是对消费品牌过度装饰的一次自觉反叛——产品不打标签，包装只展示物品本身，而非营造某种生活方式的幻象。

  自 2002 年原研哉出任艺术总监以来，無印良品的视觉语言凝结为温润的米白底色、牛皮纸色调与黑色排版，以日式的紧凑与编辑式的克制构成独特的设计气质。最终呈现的视觉效果如同未漂白的纸张与浅色木材——安静、诚实、刻意地拒绝一切装饰。

colors:
  primary:
    "50": "#f0f0f0"
    "100": "#d6d6d6"
    "200": "#b8b8b8"
    "300": "#999999"
    "400": "#7a7a7a"
    "500": "#1A1A1A"
    "600": "#151515"
    "700": "#111111"
    "800": "#0d0d0d"
    "900": "#080808"
    "950": "#040404"
  secondary:
    "50": "#f7f2ed"
    "100": "#ecddd0"
    "200": "#ddc5ae"
    "300": "#cdac8c"
    "400": "#b99a7d"
    "500": "#A78B6E"
    "600": "#8e755c"
    "700": "#745f4b"
    "800": "#5b4a3a"
    "900": "#41352a"
    "950": "#2a2119"
  accent:
    "50": "#f7f2ed"
    "100": "#ecddd0"
    "200": "#ddc5ae"
    "300": "#cdac8c"
    "400": "#b99a7d"
    "500": "#A78B6E"
    "600": "#8e755c"
    "700": "#745f4b"
    "800": "#5b4a3a"
    "900": "#41352a"
    "950": "#2a2119"
  neutral:
    "50": "#FBF8F0"
    "100": "#F8F4ED"
    "200": "#f0ebe2"
    "300": "#e0d8cc"
    "400": "#b8b0a4"
    "500": "#737373"
    "600": "#5c5c5c"
    "700": "#474747"
    "800": "#333333"
    "900": "#1A1A1A"
    "950": "#0d0d0d"
  semantic:
    success: { bg: "#3c763d", text: "#ffffff", light: "#eef5ee", border: "#2d5e2e" }
    warning: { bg: "#8a6d3b", text: "#ffffff", light: "#f5f0e6", border: "#6e572f" }
    error:   { bg: "#a94442", text: "#ffffff", light: "#f5eaea", border: "#873635" }
    info:    { bg: "#1A1A1A", text: "#ffffff", light: "#f0f0f0", border: "#111111" }
  background:
    page:    "#F8F4ED"
    surface: "#FFFFFF"
    subtle:  "#FBF8F0"
  text:
    primary:   "#1A1A1A"
    secondary: "#737373"
    muted:     "#999999"
    inverse:   "#FFFFFF"

typography:
  families:
    heading: "'Inter', 'Hiragino Sans', -apple-system, sans-serif"
    body:    "'Inter', 'Hiragino Sans', -apple-system, sans-serif"
    mono:    "'SF Mono', 'Consolas', 'Liberation Mono', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap"
  scale:
    2xs: "0.625rem"
    xs: "0.75rem"
    sm: "0.875rem"
    base: "1rem"
    lg: "1.125rem"
    xl: "1.25rem"
    2xl: "1.5rem"
    3xl: "1.875rem"
    4xl: "2.25rem"
    5xl: "3rem"
    6xl: "4rem"
    7xl: "6rem"
  weights: { light: 300, normal: 400, medium: 500, semibold: 600, bold: 700, extrabold: 800 }
  lineHeights: { tight: 1.2, snug: 1.375, normal: 1.6, relaxed: 1.7, loose: 1.8 }
  letterSpacing: { tighter: "-0.04em", tight: "-0.02em", normal: "0", wide: "0.05em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      { sm: "640px", md: "768px", lg: "1024px", xl: "1200px", full: "100%" }
  gridGap:        { sm: "8px",  md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "1px", md: "2px", lg: "2px", xl: "4px", full: "9999px" }
  color:  { default: "#e0d8cc", subtle: "#f0ebe2", strong: "#b8b0a4", focus: "#1A1A1A" }
  width:  { thin: "1px", default: "1px", thick: "2px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "none"
  sm: "none"
  md: "none"
  lg: "none"
  xl: "none"
  2xl: "none"
  inner: "none"
  focus: "0 0 0 2px rgba(26,26,26,0.15)"

motion:
  level: "minimal"
  durations: { instant: "0ms", fast: "100ms", normal: "200ms", slow: "350ms", slower: "500ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.42, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.58, 1)"
    spring:  "cubic-bezier(0.25, 1, 0.5, 1)"
  hoverPatterns: [opacity, tint]
  reducedMotion: true

composition:
  layout:        "grid"
  contentWidth:  "container"
  framing:       "minimal"
  gridIntensity: "soft"
  rhythm:        "8px"

surfaceStyle: "flat"
blur:         "none"

iconography:
  treatment: "linear"
  set:       "lucide"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "1.5px"

components:
  button:
    primary:   { background: "#1A1A1A", color: "#FFFFFF", border: "none", shadow: "none", hoverBackground: "#333333", hoverShadow: "none", hoverColor: "#FFFFFF" }
    secondary: { background: "#A78B6E", color: "#FFFFFF", border: "none", shadow: "none", hoverBackground: "#8e755c", hoverShadow: "none", hoverColor: "#FFFFFF" }
    ghost:     { background: "transparent", color: "#1A1A1A", border: "1px solid #e0d8cc", shadow: "none", hoverBackground: "#FBF8F0", hoverShadow: "none", hoverColor: "#1A1A1A" }
    danger:    { background: "#a94442", color: "#FFFFFF", border: "none", shadow: "none", hoverBackground: "#873635", hoverShadow: "none", hoverColor: "#FFFFFF" }
    sizes:
      sm: { height: "28px", padding: "0 12px", fontSize: "0.8125rem" }
      md: { height: "36px", padding: "0 16px", fontSize: "0.875rem" }
      lg: { height: "44px", padding: "0 24px", fontSize: "0.9375rem" }
    borderRadius: "2px"
    fontWeight: 400
    letterSpacing: "0"
    textTransform: "none"
  input:
    background: "transparent"
    color: "#1A1A1A"
    border: "none"
    borderRadius: "0"
    padding: "8px 0"
    focusBorder: "none"
    placeholderColor: "#999999"
  card:
    base:  { background: "#FFFFFF", border: "1px solid #e0d8cc", borderRadius: "2px", padding: "24px", shadow: "none" }
    hover: { shadow: "none", transform: "none" }
---

# MUJI

> The no-brand brand — warm cream, kraft brown, and black text stripped to the necessary.

## Origin

MUJI — Mujirushi Ryōhin, meaning "no-brand quality goods" — was founded in 1980 by Ryohin Keikaku Co. Ltd. in Tokyo as a deliberate rebellion against the consumer-brand excess of 1980s Japan. Originally offering 40 products (9 household goods, 31 food items), MUJI stripped away packaging decoration, logos, and aspirational branding. Under early creative director Ikko Tanaka, the visual identity adopted the unbleached recycled-paper aesthetic and minimal typographic language that persists today. The philosophy: remove everything decorative, and what remains is the necessary.

In 2002, graphic designer Kenya Hara became art director and crystallized MUJI's modern visual language — the warm cream palette, the editorial use of negative space, and the signature product photography where objects sit alone on pale wood or linen in soft daylight. Product designer Naoto Fukasawa contributed the "Super Normal" design philosophy, creating objects so intuitive they disappear into daily life. Together, they built a design system that spans muji.com, 1000+ stores worldwide, MUJI Hotel, MUJI Books, and the iconic unbleached recycled-paper packaging system.

## Overview

Composition cues:
- **Layout**: Grid layout — products and content arranged in clean, rectilinear grids with editorial rhythm
- **Content width**: Container — standard widths for product grids and editorial content, never cramped
- **Framing**: Minimal — surfaces are flat with thin borders or no borders at all; no glass, no glow
- **Grid intensity**: Soft — structure is present but quietly implied through whitespace and alignment

## Colors

MUJI's color philosophy is the absence of brand color. The palette is drawn entirely from natural materials: the warm cream `#F8F4ED` of unbleached paper, the kraft brown `#A78B6E` of recycled packaging, the black `#1A1A1A` of printed text, and the warm grey `#737373` of aged wood. There are no chromatic brand accents — no red, no blue, no green stamped onto the identity. When color appears on muji.com, it comes exclusively from product photography: a red kettle, a blue shirt, an orange cushion. The brand itself stays silent, a neutral ground that lets the products speak. This restraint is the design system's most radical statement.

**Role usage**:
- Page background → `colors.background.page` (#F8F4ED)
- Product cards / content panels → `colors.background.surface` (#FFFFFF)
- Subtle section fills → `colors.background.subtle` (#FBF8F0)
- Primary CTAs & body text → `colors.primary.500` (#1A1A1A)
- Kraft-tone secondary buttons → `colors.secondary.500` (#A78B6E)
- Secondary labels & metadata → `colors.text.secondary` (#737373)
- Borders & dividers → `colors.neutral.300` (#e0d8cc)

## Typography

MUJI's typographic voice is quiet and regular-weight. On muji.com and MUJI communications in Japan, headings use Hiragino Sans (the standard Japanese system font), paired with Helvetica for Latin text. In this system, Inter serves as the Google Fonts substitute — its neutral, slightly humanist letterforms align with MUJI's philosophy of objects that are "just right." Critically, headings are set at regular weight, not bold — MUJI does not shout. Body text runs at 14–15px with a line-height of 1.6, slightly denser than typical Western SaaS, reflecting Japanese typographic density and MUJI's editorial restraint.

**Text styles**:
- `display-xl` — Inter, 72px, weight 400, line-height 1.1, letter-spacing 0
- `display-lg` — Inter, 48px, weight 400, line-height 1.15, letter-spacing 0
- `heading-1` — Inter, 32px, weight 400, line-height 1.25, letter-spacing 0
- `body-lg` — Inter, 16px, weight 400, line-height 1.6, letter-spacing 0
- `body-md` — Inter, 14px, weight 400, line-height 1.6, letter-spacing 0
- `caption` — Inter, 12px, weight 400, line-height 1.4, letter-spacing 0
- `mono-md` — SF Mono, 13px, weight 400, line-height 1.6, letter-spacing 0

## Spacing & Layout

- Base unit: 4px; primary rhythm at 8px multiples for clean, editorial spacing
- Spacing scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128
- Container max-widths: 640 / 768 / 1024 / 1200px (standard container for product grids)
- Section padding: 32px (mobile) → 64px (tablet) → 96px (desktop) → 128px (hero sections)
- Grid gaps: 8px (tight) / 16px (standard) / 24px (product cards) / 48px (section grids)
- Page margins create generous negative space — emptiness is MUJI's primary compositional tool

## Elevation & Depth

MUJI's surfaces are deliberately flat. There are no drop shadows, no layered transparency, no material elevation — the design philosophy treats the screen as a sheet of paper, and paper does not float. Depth is communicated exclusively through background-color stepping: the warm cream page (#F8F4ED) sits behind white product cards (#FFFFFF), which sit above subtle fills (#FBF8F0). Thin borders in warm grey (#e0d8cc) separate surfaces when needed, but many elements simply float in whitespace with no border at all.

- Surface style: flat — no glass, no blur, no translucency
- Shadows: none across the entire system
- Primary depth cue: background-color stepping (cream → white → subtle)
- Borders: thin 1px warm grey, used sparingly
- Whitespace is the primary separation mechanism

## Shapes

- Button border-radius: 2px (rectilinear, Japanese print sensibility)
- Card border-radius: 2px
- Input border-radius: 0 (borderless underline fields)
- Small elements (tags, badges): 2px
- No pill-radius elements — MUJI is rectilinear throughout
- Large containers (modals, overlays): 4px maximum

## Motion

MUJI's motion temperament is minimal — transitions exist only when their absence would create confusion. Page loads are instant, hover states shift with a quiet opacity change, and menus appear without fanfare. There is no spring, no bounce, no overshoot. Movement in MUJI's world is like the sliding of a shoji screen: smooth, purposeful, and so understated you barely notice it happened. Reduced motion is the default state of mind.

- Level: minimal
- Fast interactions (hover, focus): 100ms
- Standard transitions (dropdown, reveal): 200ms
- Emphasized animations (page, modal): 350ms
- Easing: standard ease-out; no spring physics
- Hover patterns: opacity (gentle dim/brighten), tint (warm cream background wash)

## Techniques

### Kraft-Paper Background Grain

MUJI's signature material quality comes from a subtle kraft-paper texture overlaid on the warm cream background. This creates the tactile impression of recycled paper packaging — the brand's most recognizable material.

```css
.muji-surface {
  background-color: #F8F4ED;
  position: relative;
}

.muji-surface::after {
  content: '';
  position: absolute;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg width='200' height='200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.65' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.03'/%3E%3C/svg%3E");
  pointer-events: none;
  mix-blend-mode: multiply;
}
```

### Underline-Only Input Field

MUJI's form inputs strip away the conventional bordered rectangle, leaving only a bottom border — an editorial, Japanese-print-inspired approach that treats the input as a line on a page rather than a box.

```css
.muji-input {
  width: 100%;
  padding: 8px 0;
  border: none;
  border-bottom: 1px solid #e0d8cc;
  background: transparent;
  color: #1A1A1A;
  font-family: 'Inter', 'Hiragino Sans', sans-serif;
  font-size: 0.875rem;
  line-height: 1.6;
  outline: none;
  transition: border-color 200ms ease;
  border-radius: 0;
  -webkit-appearance: none;
}

.muji-input:focus {
  border-bottom-color: #1A1A1A;
}

.muji-input::placeholder {
  color: #999999;
}
```

### Regular-Weight Heading

MUJI's anti-display typography technique: headings at regular weight (400) rather than bold, creating a quiet, editorial hierarchy that refuses to shout. The heading distinguishes itself through size and spacing alone, not weight.

```css
.muji-heading {
  font-family: 'Inter', 'Hiragino Sans', sans-serif;
  font-weight: 400;
  color: #1A1A1A;
  letter-spacing: 0;
  line-height: 1.25;
  margin-bottom: 1em;
}

.muji-heading--xl { font-size: 3rem; line-height: 1.1; }
.muji-heading--lg { font-size: 2rem; line-height: 1.15; }
.muji-heading--md { font-size: 1.5rem; }
.muji-heading--sm { font-size: 1.125rem; }
```

## Iconography

MUJI's iconography follows the same philosophy as its products: simple, functional, and stripped of personality. Icons use thin linear strokes at 1.5px weight — enough to be legible but never heavy enough to assert themselves visually. They serve purely navigational and functional roles (cart, search, menu, arrows) and never appear as decorative illustration. The Lucide set, with its clean geometric construction and consistent stroke weight, best approximates MUJI's utilitarian icon language.

- Treatment: linear, 1.5px stroke
- Set: Lucide
- Sizes: 16px (inline metadata), 20px (navigation), 24px (primary actions)

## Do's & Don'ts

### Do
- Use warm cream #F8F4ED as the page background — it is the unbleached-paper foundation
- Set headings at regular weight (400) — MUJI typography does not shout
- Let product photography be the only source of chromatic color
- Use generous negative space as a compositional tool — emptiness is intentional
- Keep border-radius at 2px or less for all interactive elements

### Don'ts
- Use chromatic brand accents (MUJI has none — color is product-only)
- Apply decorative gradients or shadows
- Use bold display typography
- Add friendly playful illustration
- Use pill-radius buttons (anti-MUJI rectilinear)

## Applications

MUJI's design system is ideal for e-commerce platforms, product catalogs, lifestyle brands, and editorial sites where the merchandise or content should be the visual protagonist — not the interface. The warm, material palette and flat surfaces create a gallery-like neutrality that elevates whatever is placed upon it. It also suits sustainability-focused brands, Japanese-market products, and any interface that wants to communicate honesty, restraint, and craft without decoration.
