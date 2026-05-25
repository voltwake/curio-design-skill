---
version: 1

meta:
  id: notion-modern
  name: Notion Modern
  description: Warm-cream, serif-display productivity aesthetic that codified the writing-software feel of the 2020s
  isDark: false
  tags: [friendly, editorial, modernist, minimal, professional]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2016 founded; current visual language ~2021–2024"
  region: "San Francisco, California"
  regionZh: "美国旧金山"
  keyFigures: [Ivan Zhao, Akshay Kothari, Notion Brand Team]
  movements: [Markdown culture, Classic book design, Warm-neutral SaaS aesthetic]

introduction: |
  Notion is the productivity-and-knowledge-management app whose design language popularized warm-neutral backgrounds, serif display headings, and the "well-formatted Markdown document" aesthetic across modern SaaS. Founded by Ivan Zhao in San Francisco, its visual identity pairs deep navy accents with a warm off-white canvas that feels more like paper than screen.

  The result is an interface that reads like a beautifully typeset book — generous line-heights, restrained color, and hand-drawn illustrations as decorative flourishes. Notion's design codified what "writing software" looks like in the 2020s, spawning an entire genre of warm-cream productivity tools from Coda to Reflect to Tana.
introductionZh: |
  Notion 是一款生产力与知识管理应用，其设计语言将温暖的米白色背景、衬线展示字体以及"排版精美的 Markdown 文档"美学推广到了整个现代 SaaS 领域。由华裔创始人赵伊（Ivan Zhao）在美国旧金山创立，其视觉风格以深海军蓝点缀搭配温润的米白色画布，给人纸质书页般的阅读感受。

  最终呈现的界面如同一本精心排版的书籍——宽松的行高、克制的配色，以及手绘插画作为装饰点缀。Notion 的设计定义了 2020 年代"书写软件"的视觉标准，催生了从 Coda 到 Reflect、Tana 在内的一整个暖色调生产力工具流派。

colors:
  primary:
    "50": "#e8ecf3"
    "100": "#c5cfe0"
    "200": "#9bafc9"
    "300": "#6e8fb3"
    "400": "#4d749e"
    "500": "#0e2a4d"
    "600": "#0c2341"
    "700": "#091c34"
    "800": "#071527"
    "900": "#040e1a"
    "950": "#020710"
  secondary:
    "50": "#f8ede8"
    "100": "#edd3c8"
    "200": "#dfb4a3"
    "300": "#d1947d"
    "400": "#c47a60"
    "500": "#b85c3c"
    "600": "#994c32"
    "700": "#7a3d28"
    "800": "#5c2e1e"
    "900": "#3d1f14"
    "950": "#27130c"
  accent:
    "50": "#f8ede8"
    "100": "#edd3c8"
    "200": "#dfb4a3"
    "300": "#d1947d"
    "400": "#c47a60"
    "500": "#b85c3c"
    "600": "#994c32"
    "700": "#7a3d28"
    "800": "#5c2e1e"
    "900": "#3d1f14"
    "950": "#27130c"
  neutral:
    "50": "#fbfaf9"
    "100": "#f5f3f0"
    "200": "#eeebe7"
    "300": "#ddd9d3"
    "400": "#b8b4ae"
    "500": "#91908c"
    "600": "#6b6a67"
    "700": "#4b4a47"
    "800": "#37352f"
    "900": "#25231e"
    "950": "#141310"
  semantic:
    success: { bg: "#2da44e", text: "#ffffff", light: "#e6f4ea", border: "#238c3f" }
    warning: { bg: "#d29922", text: "#ffffff", light: "#fef8e7", border: "#b58318" }
    error:   { bg: "#cf222e", text: "#ffffff", light: "#fde8e8", border: "#b01c25" }
    info:    { bg: "#0e2a4d", text: "#ffffff", light: "#e8ecf3", border: "#091c34" }
  background:
    page:    "#fbfaf9"
    surface: "#ffffff"
    subtle:  "#f5f3f0"
  text:
    primary:   "#37352f"
    secondary: "#6b6a67"
    muted:     "#91908c"
    inverse:   "#ffffff"

typography:
  families:
    heading: "'Source Serif 4', 'Lora', 'Georgia', serif"
    body:    "'Inter', -apple-system, BlinkMacSystemFont, sans-serif"
    mono:    "'SFMono-Regular', 'IBM Plex Mono', 'Consolas', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Source+Serif+4:ital,opsz,wght@0,8..60,300;400;500;600;700;800;1,8..60,400&family=Inter:wght@300;400;500;600;700&display=swap"
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
  lineHeights: { tight: 1.2, snug: 1.4, normal: 1.6, relaxed: 1.7, loose: 1.8 }
  letterSpacing: { tighter: "-0.04em", tight: "-0.02em", normal: "0", wide: "0.05em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      { sm: "640px", md: "768px", lg: "900px", xl: "1080px", full: "100%" }
  gridGap:        { sm: "8px",  md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "4px", md: "6px", lg: "8px", xl: "12px", full: "9999px" }
  color:  { default: "#eeebe7", subtle: "#f5f3f0", strong: "#ddd9d3", focus: "#0e2a4d" }
  width:  { thin: "1px", default: "1px", thick: "2px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(55,53,47,0.04)"
  sm: "0 2px 4px rgba(55,53,47,0.06)"
  md: "0 4px 8px rgba(55,53,47,0.08)"
  lg: "0 8px 16px rgba(55,53,47,0.10)"
  xl: "0 12px 24px rgba(55,53,47,0.12)"
  2xl: "0 24px 48px rgba(55,53,47,0.16)"
  inner: "inset 0 1px 2px rgba(55,53,47,0.04)"
  focus: "0 0 0 3px rgba(14,42,77,0.2)"

motion:
  level: "restrained"
  durations: { instant: "0ms", fast: "120ms", normal: "200ms", slow: "350ms", slower: "500ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.42, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.58, 1)"
    spring:  "cubic-bezier(0.34, 1.2, 0.64, 1)"
  hoverPatterns: [tint, opacity, underline]
  reducedMotion: true

composition:
  layout:        "stack"
  contentWidth:  "narrow"
  framing:       "bordered"
  gridIntensity: "subtle"
  rhythm:        "8px"

surfaceStyle: "solid"
blur:         "none"

iconography:
  treatment: "outline"
  set:       "lucide"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "1.5px"

components:
  button:
    primary:   { background: "#0e2a4d", color: "#ffffff", border: "none", shadow: "none", hoverBackground: "#091c34", hoverShadow: "none", hoverColor: "#ffffff" }
    secondary: { background: "transparent", color: "#37352f", border: "1px solid #ddd9d3", shadow: "none", hoverBackground: "#f5f3f0", hoverShadow: "none", hoverColor: "#37352f" }
    ghost:     { background: "transparent", color: "#6b6a67", border: "none", shadow: "none", hoverBackground: "#f5f3f0", hoverShadow: "none", hoverColor: "#37352f" }
    danger:    { background: "#cf222e", color: "#ffffff", border: "none", shadow: "none", hoverBackground: "#b01c25", hoverShadow: "none", hoverColor: "#ffffff" }
    sizes:
      sm: { height: "28px", padding: "0 12px", fontSize: "0.8125rem" }
      md: { height: "36px", padding: "0 16px", fontSize: "0.875rem" }
      lg: { height: "44px", padding: "0 24px", fontSize: "1rem" }
    borderRadius: "6px"
    fontWeight: 500
    letterSpacing: "0"
    textTransform: "none"
  input:
    background: "#f5f3f0"
    color: "#37352f"
    border: "1px solid #eeebe7"
    borderRadius: "6px"
    padding: "8px 12px"
    focusBorder: "1px solid #0e2a4d"
    placeholderColor: "#91908c"
  card:
    base:  { background: "#ffffff", border: "1px solid #eeebe7", borderRadius: "8px", padding: "20px", shadow: "none" }
    hover: { shadow: "0 2px 4px rgba(55,53,47,0.06)", transform: "none" }
---

# Notion Modern

> Warm-cream paper, deep navy ink, and serif display headings — the writing-software aesthetic that defined productivity SaaS in the 2020s.

## Origin

Notion was founded in 2016 by Ivan Zhao and Simon Last in San Francisco, with Akshay Kothari joining early as COO. Zhao, a designer-CEO, drew inspiration from Bret Victor's Dynamicland, Ted Nelson's hypertext visions, and the tradition of well-typeset books. The product began as a tool for teams to write, plan, and organize knowledge — and its visual identity evolved to match that bookish sensibility, arriving by 2021 at the warm-cream, serif-heavy aesthetic that now defines the brand.

By 2023–2024, "Notion-like" had become its own genre in SaaS design. The combination of off-white #fbfaf9 backgrounds, deep navy or warm rust accents, serif display headings, and hand-drawn decorative illustrations proved so compelling that competitors from Coda to Reflect to Tana adopted unmistakably similar visual languages. Notion didn't just build a product — it established the visual vocabulary for what "writing software" looks and feels like.

## Overview

Composition cues:
- **Layout**: Vertical stack layout — content flows in a single, well-paced column like a printed page
- **Content width**: Narrow — text containers max out around 900–1080px, optimized for comfortable reading
- **Framing**: Bordered — subtle 1px warm-grey borders separate surfaces; shadows are virtually absent
- **Grid intensity**: Subtle — generous whitespace and reading-first rhythm; structure is implied, not enforced

## Colors

Notion's color philosophy is warmth through restraint. The background is never pure white — it's #fbfaf9, a warm cream that evokes quality paper and reduces the clinical feel of a digital interface. Text sits at #37352f, a dark warm slate that softens the harshness of pure black while maintaining excellent readability. The primary accent is deep navy #0e2a4d, used sparingly for links, active states, and primary buttons. A warm rust #b85c3c serves as a secondary accent for callouts and decorative moments. Everything else lives in a warm grey scale derived from the same undertone. The palette is deliberately muted so that user content — text, images, embeds — always feels like the protagonist.

**Role usage**:
- Page background → `colors.background.page` (#fbfaf9)
- Card / block surfaces → `colors.background.surface` (#ffffff)
- Sidebar / input fills → `colors.background.subtle` (#f5f3f0)
- Primary actions & links → `colors.primary.500` (#0e2a4d)
- Accent highlights & callouts → `colors.accent.500` (#b85c3c)
- Body text → `colors.text.primary` (#37352f)
- Secondary labels → `colors.text.secondary` (#6b6a67)
- Borders & dividers → `colors.neutral.200` (#eeebe7)

## Typography

Notion's type voice is literary yet approachable. Headings use Source Serif 4, a workhorse serif that echoes the proprietary Lyon Display Notion uses in-product — warm, slightly condensed letterforms that feel authoritative without being stuffy. Body text is set in Inter at regular weight with generous line-height (1.6–1.7), creating the comfortable reading cadence of a well-typeset article. The contrast between serif headings and sans-serif body is the core of Notion's typographic identity: it signals "this is a document worth reading" while keeping UI text clean and functional. Monospaced text for code blocks and inline code maintains a quiet, technical presence without dominating.

**Text styles**:
- `display-xl` — Source Serif 4, 72px, weight 700, line-height 1.1, letter-spacing -0.04em
- `display-lg` — Source Serif 4, 56px, weight 700, line-height 1.15, letter-spacing -0.02em
- `heading-1` — Source Serif 4, 36px, weight 600, line-height 1.25, letter-spacing -0.02em
- `body-lg` — Inter, 18px, weight 400, line-height 1.7, letter-spacing 0
- `body-md` — Inter, 16px, weight 400, line-height 1.6, letter-spacing 0
- `caption` — Inter, 12px, weight 500, line-height 1.4, letter-spacing 0
- `mono-md` — SFMono-Regular, 14px, weight 400, line-height 1.6, letter-spacing 0

## Spacing & Layout

- Base unit: 4px; primary rhythm at 8px multiples for generous, reading-first spacing
- Spacing scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128
- Container max-widths: 640 / 768 / 900 / 1080px (narrower than typical SaaS — optimized for reading)
- Section padding: 32px (mobile) → 64px (tablet) → 96px (desktop) → 128px (hero)
- Grid gaps: 8px (tight lists) / 16px (standard) / 24px (cards) / 48px (section grids)
- Page margin: generous horizontal margins create a centered, book-like column

## Elevation & Depth

Notion achieves depth through border and background stepping, not shadows. The page canvas sits at warm cream #fbfaf9, content blocks float on white #ffffff, and subtle backgrounds like sidebar or input fills drop to #f5f3f0. Borders at #eeebe7 — warm and barely-there — delineate cards, inputs, and section dividers. Shadows are essentially absent from the product UI; the only elevation comes from dropdown menus and popovers, which use a very soft warm shadow. The effect is papery and flat, like content laid on a desk rather than floating in space.

- Surface style: solid — no glass, no blur, no transparency
- Primary depth cue: background-color stepping (cream → white → warm grey)
- Borders preferred over shadows for all surface separation
- Shadow usage: reserved for dropdowns, popovers, and floating menus
- Shadow intensity: minimal — warm-toned rgba(55,53,47,0.06) at most

## Shapes

- Button border-radius: 6px (softly rounded rectangle)
- Card / block border-radius: 8px
- Input border-radius: 6px
- Tag / badge border-radius: 9999px (full pill)
- Avatar border-radius: 9999px (full circle)
- Large containers (modals, dialogs): 12px

## Motion

Notion's motion is restrained and utilitarian — transitions exist to orient the user, never to entertain. Page transitions are near-instant, dropdown menus appear with a quick 120ms fade, and hover states shift with subtle opacity changes. There is no bounce, no overshoot, no playful spring. The motion vocabulary prioritizes responsiveness over personality, matching the tool's identity as a quiet workspace that stays out of the writer's way. The exception is Notion's signature block-drag animation, which uses a gentle easing to make content rearrangement feel physical and intentional.

- Level: restrained
- Fast interactions (hover, focus): 120ms
- Standard transitions (dropdown, tooltip): 200ms
- Emphasized animations (page transition, modal): 350ms
- Easing: smooth ease-out default; no bounce or spring
- Hover patterns: tint (warm-grey background wash), opacity (text brightens/dims), underline (links reveal underline on hover)

## Techniques

### Warm Paper Canvas

Notion's signature warm-cream background creates a paper-like reading surface that distinguishes it from the cold whites and greys of typical SaaS interfaces. The warmth comes from a carefully chosen off-white with yellow-brown undertones.

```css
.page {
  background-color: #fbfaf9;
  color: #37352f;
  font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
  -webkit-font-smoothing: antialiased;
}

.page-content {
  max-width: 900px;
  margin: 0 auto;
  padding: 48px 96px;
  line-height: 1.6;
}
```

### Serif-Sans Heading Pair

The core typographic move of Notion's identity: serif display headings that signal editorial authority, paired with clean sans-serif body text for readability. The contrast creates a "well-typeset document" feel.

```css
.heading {
  font-family: 'Source Serif 4', 'Georgia', serif;
  font-weight: 700;
  color: #37352f;
  letter-spacing: -0.02em;
  line-height: 1.2;
  margin-bottom: 0.5em;
}

.heading-1 { font-size: 2.25rem; }
.heading-2 { font-size: 1.75rem; font-weight: 600; }
.heading-3 { font-size: 1.375rem; font-weight: 600; }

.body-text {
  font-family: 'Inter', sans-serif;
  font-size: 1rem;
  font-weight: 400;
  line-height: 1.6;
  color: #37352f;
}
```

### Outlined Button with Warm Border

Notion's secondary buttons use a warm-grey outline style — no fill, no shadow — that feels light and unobtrusive. The warm border color keeps the button consistent with the paper-toned canvas.

```css
.button-secondary {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  height: 36px;
  padding: 0 16px;
  background: transparent;
  border: 1px solid #ddd9d3;
  border-radius: 6px;
  color: #37352f;
  font-family: 'Inter', sans-serif;
  font-size: 0.875rem;
  font-weight: 500;
  cursor: pointer;
  transition: background-color 120ms ease;
}

.button-secondary:hover {
  background-color: #f5f3f0;
}

.button-secondary:focus-visible {
  outline: none;
  box-shadow: 0 0 0 3px rgba(14, 42, 77, 0.2);
}
```

## Iconography

Notion uses clean, outline-style icons with a 1.5px stroke weight — simple and geometric, designed to complement the serif-sans typographic pairing without competing for attention. Icons serve a strictly functional role: navigation, actions, block types. Decorative illustration is handled separately through Notion's signature hand-drawn blob illustrations, which are full-color, organic, and playful — a deliberate contrast to the utilitarian icon system.

- Treatment: outline, 1.5px stroke
- Set: Lucide (closest match to Notion's custom icon vocabulary)
- Sizes: 16px (inline/block-type indicators), 20px (toolbar/sidebar), 24px (navigation)

## Do's & Don'ts

### ✓ Do
- Use warm cream #fbfaf9 as the page background — it is the foundation of the entire aesthetic
- Pair serif headings (Source Serif 4) with Inter body text for the signature editorial contrast
- Use generous line-height (1.6–1.7) on body text to prioritize reading comfort
- Keep content width narrow (~900px) to create a book-like reading column
- Use deep navy #0e2a4d sparingly — only for primary actions, links, and key interactive elements

### ✗ Don't
- Use pure white #ffffff as the page background (Notion specifically uses warm cream)
- Use pure black #000000 for text (Notion uses warm dark slate #37352f)
- Apply loud decorative colors that compete with content
- Use heavy drop shadows for cards or surfaces (borders only)
- Apply brutalist sharp corners or hard geometric edges
- Design dark-mode-first — this system is paper-toned by nature

## Applications

Notion Modern is the ideal design language for productivity tools, knowledge bases, documentation sites, personal wikis, and any interface where long-form reading is the primary activity. The warm-cream palette and serif-sans pairing create an environment that feels inviting for extended writing sessions, while the restrained component system keeps the UI from competing with user content. It also works beautifully for editorial sites, blog platforms, and content-management tools that want to signal "your words matter here."
