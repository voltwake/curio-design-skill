---
version: 1

meta:
  id: edo-ukiyo-e-hokusai
  name: "Edo Ukiyo-e (Hokusai)"
  description: "Prussian blue woodblock prints on warm washi paper — flat color planes, bold diagonals, and refined serif typography"
  isDark: false
  tags: [organic, decorative, historical]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "1603–1868 Edo period; Hokusai active 1779–1849"
  region: "Edo (now Tokyo), Japan"
  regionZh: "日本江户（今东京）"
  keyFigures: [Katsushika Hokusai, Utagawa Hiroshige, Kitagawa Utamaro, Tōshūsai Sharaku]
  movements: [ukiyo-e woodblock tradition, fūkeiga (landscape), bijinga (beauty pictures)]

introduction: |
  Ukiyo-e — "pictures of the floating world" — is the Japanese woodblock printing tradition that defined Edo-period visual culture. This design system distills Hokusai's iconic palette of Prussian blue and vermillion on warm washi paper into a modern interface language.

  Flat color planes replace gradients. Delicate brush-line outlines replace heavy borders. Asymmetric compositions with strong diagonal energy echo the compositional boldness of "The Great Wave off Kanagawa."
introductionZh: |
  浮世绘是江户时代（1603–1868）日本最具代表性的视觉艺术传统。葛饰北斋以《神奈川冲浪里》闻名世界，其普鲁士蓝与朱红的经典配色成为日本版画的标志。

  本设计系统将浮世绘的平涂色块、精致墨线轮廓与和纸质感融入现代界面设计，用有限的色彩与大胆的对角构图，唤起江户浮世的风雅与力量。

colors:
  primary:
    "50": "#e6f0f7"
    "100": "#b3d1e6"
    "200": "#80b2d5"
    "300": "#4d93c4"
    "400": "#2674b0"
    "500": "#003c66"
    "600": "#00335a"
    "700": "#002a4d"
    "800": "#002040"
    "900": "#001733"
    "950": "#000e22"
  secondary:
    "50": "#fdf0ed"
    "100": "#f6cec4"
    "200": "#f0ac9b"
    "300": "#e98a72"
    "400": "#d96750"
    "500": "#c8442d"
    "600": "#b03b27"
    "700": "#983221"
    "800": "#80291b"
    "900": "#681f14"
    "950": "#44140d"
  accent:
    "50": "#faf5e8"
    "100": "#f0e4bf"
    "200": "#e6d396"
    "300": "#dcc26d"
    "400": "#d2b15e"
    "500": "#c8a050"
    "600": "#b08c44"
    "700": "#987838"
    "800": "#80642c"
    "900": "#685020"
    "950": "#443514"
  neutral:
    "50": "#f7f4ef"
    "100": "#f0e8d6"
    "200": "#e4dac4"
    "300": "#d3c9b0"
    "400": "#b8aa92"
    "500": "#9d8c74"
    "600": "#837460"
    "700": "#695c4c"
    "800": "#4f4538"
    "900": "#352e24"
    "950": "#1a1712"
  semantic:
    success:
      bg: "#2a6642"
      text: "#ffffff"
      light: "#e6f0eb"
      border: "#2a6642"
    warning:
      bg: "#c8a050"
      text: "#352e24"
      light: "#faf5e8"
      border: "#c8a050"
    error:
      bg: "#c8442d"
      text: "#ffffff"
      light: "#fdf0ed"
      border: "#c8442d"
    info:
      bg: "#003c66"
      text: "#ffffff"
      light: "#e6f0f7"
      border: "#003c66"
  background:
    page: "#f0e8d6"
    surface: "#f7f4ef"
    subtle: "#e4dac4"
  text:
    primary: "#1a1712"
    secondary: "#4f4538"
    muted: "#837460"
    inverse: "#f0e8d6"

typography:
  families:
    heading: "'Cormorant Garamond', 'Noto Serif JP', Georgia, serif"
    body: "'Lora', 'Noto Serif JP', Georgia, serif"
    mono: "'IBM Plex Mono', 'Courier New', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;0,700;1,400&family=Lora:ital,wght@0,400;0,500;0,600;0,700;1,400&family=IBM+Plex+Mono:wght@400;500&family=Noto+Serif+JP:wght@400;500;700&display=swap"
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
    normal: 1.5
    relaxed: 1.625
    loose: 1.8
  letterSpacing:
    tighter: "-0.04em"
    tight: "-0.02em"
    normal: "0"
    wide: "0.05em"

spacing:
  base: "4px"
  scale: ["2px", "4px", "6px", "8px", "12px", "16px", "24px", "32px", "48px", "64px", "96px", "128px"]
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
    lg: "6px"
    xl: "8px"
    full: "9999px"
  color:
    default: "#1a1712"
    subtle: "#d3c9b0"
    strong: "#1a1712"
    focus: "#003c66"
  width:
    thin: "1px"
    default: "1px"
    thick: "2px"
  style: "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(26,23,18,0.05)"
  sm: "0 1px 3px rgba(26,23,18,0.08)"
  md: "0 4px 6px rgba(26,23,18,0.07)"
  lg: "0 10px 15px rgba(26,23,18,0.06)"
  xl: "0 20px 25px rgba(26,23,18,0.08)"
  "2xl": "0 25px 50px rgba(26,23,18,0.12)"
  inner: "inset 0 1px 2px rgba(26,23,18,0.04)"
  focus: "0 0 0 3px rgba(0,60,102,0.25)"

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
  hoverPatterns: [opacity, tint, underline]
  reducedMotion: true

composition:
  layout: "stack"
  contentWidth: "container"
  framing: "bordered"
  gridIntensity: "subtle"
  rhythm: "8px"

surfaceStyle: "flat"
blur: "none"

iconography:
  treatment: "linear"
  set: "lucide"
  size:
    sm: "16px"
    md: "20px"
    lg: "24px"
  stroke: "1.5px"

components:
  button:
    primary:
      background: "#003c66"
      color: "#f0e8d6"
      border: "1px solid #003c66"
      shadow: "none"
      hoverBackground: "#002a4d"
      hoverShadow: "none"
      hoverColor: "#f0e8d6"
    secondary:
      background: "#c8442d"
      color: "#f0e8d6"
      border: "1px solid #c8442d"
      shadow: "none"
      hoverBackground: "#983221"
      hoverShadow: "none"
      hoverColor: "#f0e8d6"
    ghost:
      background: "transparent"
      color: "#003c66"
      border: "1px solid transparent"
      shadow: "none"
      hoverBackground: "rgba(0,60,102,0.06)"
      hoverShadow: "none"
      hoverColor: "#002a4d"
    danger:
      background: "#c8442d"
      color: "#ffffff"
      border: "1px solid #c8442d"
      shadow: "none"
      hoverBackground: "#983221"
      hoverShadow: "none"
      hoverColor: "#ffffff"
    sizes:
      sm:
        height: "32px"
        padding: "0 12px"
        fontSize: "0.875rem"
      md:
        height: "40px"
        padding: "0 16px"
        fontSize: "1rem"
      lg:
        height: "48px"
        padding: "0 24px"
        fontSize: "1.125rem"
    borderRadius: "2px"
    fontWeight: 600
    letterSpacing: "0.05em"
    textTransform: "none"
  input:
    background: "transparent"
    color: "#1a1712"
    border: "1px solid #d3c9b0"
    borderRadius: "2px"
    padding: "8px 12px"
    focusBorder: "#003c66"
    placeholderColor: "#837460"
  card:
    base:
      background: "#f7f4ef"
      border: "1px solid #1a1712"
      borderRadius: "2px"
      padding: "24px"
      shadow: "none"
    hover:
      shadow: "0 4px 6px rgba(26,23,18,0.07)"
      transform: "translateY(-1px)"
---

# Edo Ukiyo-e (Hokusai)

> Prussian blue and vermillion on warm washi — flat woodblock planes brought to the browser.

## Origin

Ukiyo-e (浮世絵, "pictures of the floating world") is the Japanese woodblock printing tradition that flourished during the Edo period (1603–1868). Published in Edo (modern Tokyo), these prints depicted landscapes, kabuki actors, courtesans, and the pleasures of the merchant class. Multi-block color printing on handmade washi paper used water-based pigments, producing flat, saturated color fields bound by delicate sumi ink outlines.

Katsushika Hokusai (1760–1849) elevated the landscape genre with his monumental series "Thirty-Six Views of Mount Fuji" (1830–1832). The arrival of imported Prussian blue pigment around 1820 enabled the deep, luminous blues that became Hokusai's signature — most famously in "The Great Wave off Kanagawa." His contemporary Utagawa Hiroshige further refined the landscape tradition, and both artists profoundly influenced the European Impressionists, with Van Gogh famously copying Hiroshige's compositions in 1887.

## Overview

Composition cues:
- **Layout**: Stacked vertical compositions with layered foreground/middle/sky planes
- **Content width**: Container-bound, echoing the rectangular print format
- **Framing**: Thin black-outline borders evoking the woodblock panel edge
- **Grid intensity**: Subtle — asymmetric placement with strong diagonal energy preferred over rigid grids

## Colors

The palette is deliberately constrained to 5–7 colors, mirroring the practical limits of multi-block woodcut printing. Prussian blue (#003c66) anchors the system as the signature hue — deep, luminous, and historically specific. Vermillion (#c8442d) provides warmth and energy as the secondary. Ochre (#c8a050) acts as an accent bridging the warm paper ground and the cooler blues. All colors sit on the warm off-white of washi paper (#f0e8d6), never on pure white.

**Role usage**:
- Page background → `colors.background.page` (washi #f0e8d6)
- Card / surface fill → `colors.background.surface`
- Primary actions & links → `colors.primary.500` (Prussian blue)
- Destructive / emphasis accents → `colors.secondary.500` (vermillion)
- Decorative highlights → `colors.accent.500` (ochre)
- Body text → `colors.text.primary`
- Supporting text → `colors.text.secondary`
- Borders & outlines → `colors.neutral.900` (sumi ink black)

## Typography

The type voice is refined, calligraphic, and unhurried — echoing the elegant hand of Edo-period brush lettering. Cormorant Garamond provides high-contrast serif letterforms for display and headings, with its fine hairlines recalling the delicate lines of woodblock outlines. Lora serves body text with a slightly sturdier, more readable character. Noto Serif JP is included as a fallback for any Japanese text, preserving cultural authenticity.

**Text styles**:
- `display-xl` — Cormorant Garamond, 96px, weight 700, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Cormorant Garamond, 64px, weight 700, line-height 1.1, letter-spacing -0.02em
- `heading-1` — Cormorant Garamond, 48px, weight 600, line-height 1.2, letter-spacing -0.02em
- `body-lg` — Lora, 18px, weight 400, line-height 1.625, letter-spacing 0
- `body-md` — Lora, 16px, weight 400, line-height 1.5, letter-spacing 0
- `caption` — Lora, 12px, weight 500, line-height 1.5, letter-spacing 0.05em
- `mono-md` — IBM Plex Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout

- Base unit: 4px; primary rhythm at 8px
- Scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128 px
- Container max-widths: sm 640 / md 768 / lg 1024 / xl 1280 px
- Section padding: sm 32 / md 64 / lg 96 / xl 128 px — generous vertical breathing room echoing the unprinted margins of woodblock prints

## Elevation & Depth

Ukiyo-e is fundamentally flat — prints have no cast shadows, no atmospheric perspective, only layered planes of color. This system honors that philosophy. Surfaces are flat with no default shadows. Elevation is communicated through thin ink-black outlines and color-plane layering rather than drop shadows. On hover, a minimal shadow may appear to indicate interactivity, but it should feel like a page lifting slightly off the desk — never a floating UI card.

- Surface style: flat, solid color fills
- Blur: none — no glass or frosted effects
- Shadow ladder: none by default; xs–md reserved for interactive hover states only

## Shapes

- Corner radii are minimal: sm 2px / md 4px / lg 6px / xl 8px
- Sharp, rectilinear shapes echo the carved woodblock edge
- Full radius (9999px) for pills and badges only

## Motion

Restrained and deliberate — movements should feel like the careful placement of a woodblock on paper, not a digital bounce. Transitions are smooth but unhurried.

- Level: restrained
- Durations: fast 120ms / normal 250ms / slow 400ms
- Default easing: cubic-bezier(0.4, 0, 0.2, 1) — ease-in-out
- Hover patterns: opacity fade, color tint shift, underline reveal
- No scale transforms, no bouncy springs — flatness is the point

## Techniques

### Washi Paper Texture

A subtle noise overlay that gives surfaces the warm, fibrous feel of handmade Japanese paper.

```css
.washi-surface {
  background-color: #f0e8d6;
  position: relative;
}
.washi-surface::after {
  content: "";
  position: absolute;
  inset: 0;
  background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 200 200' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.05'/%3E%3C/svg%3E");
  pointer-events: none;
  mix-blend-mode: multiply;
}
```

### Sumi Ink Outline Card

Cards framed with a thin, hand-drawn-feeling black border — the digital equivalent of a woodblock panel edge.

```css
.ukiyo-card {
  background: #f7f4ef;
  border: 1px solid #1a1712;
  border-radius: 2px;
  padding: 24px;
  position: relative;
  transition: box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.ukiyo-card:hover {
  box-shadow: 0 4px 6px rgba(26, 23, 18, 0.07);
}
```

### Vermillion Seal Stamp Accent

A square accent mark inspired by the red hanko (personal seal) that artists stamped on their prints. Used for badges, tags, or emphasis markers.

```css
.hanko-stamp {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  background: #c8442d;
  color: #f0e8d6;
  font-family: 'Cormorant Garamond', serif;
  font-weight: 700;
  font-size: 0.75rem;
  letter-spacing: 0.05em;
  padding: 4px 8px;
  border-radius: 2px;
  line-height: 1;
}
```

## Iconography

Icons should feel linear and refined, as if drawn with a fine-tipped brush. Thin strokes echo the sumi ink outlines of woodblock prints. Avoid filled or heavy icon styles that would overpower the delicate palette.

- Treatment: linear (outline only)
- Set: Lucide — its clean, thin strokes complement the serif typography
- Stroke: 1.5px

## Do's & Don'ts

### ✓ Do
- Use Prussian blue (#003c66) for primary actions, links, and navigational elements
- Keep the palette to 5–7 colors maximum — constraint is the tradition
- Frame content with thin sumi-ink outlines rather than shadows
- Let the warm washi paper background breathe — generous whitespace honors the print margin
- Use asymmetric, diagonal compositions for hero sections and feature layouts

### ✗ Don't
- Use saturated neon palettes — they destroy the woodblock register
- Fall back on modern sans-serif minimalism — it's anti-Edo in spirit
- Add photorealistic drop shadows — ukiyo-e is fundamentally flat
- Impose Western perspective grids on layouts — use layered planes instead
- Substitute Christmas-red cinnabar for true vermillion (#c8442d)

## Applications

This system is ideal for editorial and storytelling interfaces — digital magazines, cultural institution websites, long-form reading experiences, and portfolio sites where refined typography and restrained color create a contemplative atmosphere. It pairs well with photography and illustration-heavy content, and is especially suited for projects that bridge Japanese and Western audiences.
