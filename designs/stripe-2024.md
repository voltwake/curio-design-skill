---
version: 1

meta:
  id: stripe-2024
  name: Stripe 2024
  description: Trustworthy fintech elegance — indigo gradients, breathable whitespace, and quietly confident typography
  isDark: false
  tags: [modernist, minimal, professional, friendly, tech]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2010 founded; current visual language ~2020–2024"
  region: "San Francisco, California"
  regionZh: "美国旧金山，加利福尼亚"
  keyFigures: ["Patrick Collison", "John Collison", "Ludwig van der Pol"]
  movements: ["Gradient Mesh Renaissance", "Modern B2B SaaS Minimalism"]

introduction: |
  Stripe's design language is the visual shorthand for "trustworthy fintech." Built on a near-white canvas, a signature indigo purple, and generous whitespace, it communicates competence without coldness. Gradient mesh heroes — swirling blends of indigo, violet, and teal — add warmth and dimensionality to an otherwise restrained palette.

  The system pairs Inter's neutral precision with soft shadows, rounded cards, and breathable layouts. Every element earns its place through clarity, not decoration. Stripe proves that a payments company can feel as considered as a design studio.
introductionZh: |
  Stripe 的设计语言是"值得信赖的金融科技"的视觉代名词。以近乎纯白的画布、标志性的靛蓝紫色和充裕的留白为基础，传递出专业却不冰冷的品牌气质。英雄区域的渐变网格——靛蓝、紫罗兰与青色交融流动——为克制的配色增添了温度与纵深感。

  整套系统将 Inter 字体的中性精确感与柔和阴影、圆角卡片和呼吸感布局相结合。每个元素都通过清晰性而非装饰来证明自身的存在价值。Stripe 证明了一家支付公司可以像设计工作室一样考究。

colors:
  primary:
    "50": "#f5f4ff"
    "100": "#eceaff"
    "200": "#d9d6ff"
    "300": "#b9b3ff"
    "400": "#9b93ff"
    "500": "#635bff"
    "600": "#5147e0"
    "700": "#4338c2"
    "800": "#352da3"
    "900": "#272185"
    "950": "#181466"
  secondary:
    "50": "#f0f7ff"
    "100": "#dfeeff"
    "200": "#b8dcff"
    "300": "#7ac1ff"
    "400": "#3aa3ff"
    "500": "#0a84ff"
    "600": "#0068d6"
    "700": "#0050ad"
    "800": "#003d85"
    "900": "#002b5c"
    "950": "#001c3d"
  accent:
    "50": "#effcf6"
    "100": "#d9f8ea"
    "200": "#b3f0d5"
    "300": "#7ce4b8"
    "400": "#47d49a"
    "500": "#1db87e"
    "600": "#179a69"
    "700": "#127b55"
    "800": "#0e6244"
    "900": "#0b4e37"
    "950": "#073324"
  neutral:
    "50": "#f6f9fc"
    "100": "#edf1f7"
    "200": "#d8e0eb"
    "300": "#b7c2d2"
    "400": "#8e9db4"
    "500": "#6b7c96"
    "600": "#556178"
    "700": "#42505f"
    "800": "#2d3a49"
    "900": "#1a2332"
    "950": "#0a2540"
  semantic:
    success: { bg: "#1db87e", text: "#ffffff", light: "#effcf6", border: "#b3f0d5" }
    warning: { bg: "#f5a623", text: "#ffffff", light: "#fef7e8", border: "#fde0a1" }
    error:   { bg: "#df1b41", text: "#ffffff", light: "#fef0f2", border: "#f9c4cd" }
    info:    { bg: "#635bff", text: "#ffffff", light: "#f5f4ff", border: "#d9d6ff" }
  background:
    page:    "#f6f9fc"
    surface: "#ffffff"
    subtle:  "#edf1f7"
  text:
    primary:   "#0a2540"
    secondary: "#425466"
    muted:     "#6b7c96"
    inverse:   "#ffffff"

typography:
  families:
    heading: "'Inter', 'Inter Display', -apple-system, BlinkMacSystemFont, sans-serif"
    body:    "'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
    mono:    "'JetBrains Mono', 'SF Mono', 'Fira Code', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500&display=swap"
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
  container:      { sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:        { sm: "8px",  md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "4px", md: "8px", lg: "12px", xl: "16px", full: "9999px" }
  color:  { default: "#d8e0eb", subtle: "#edf1f7", strong: "#b7c2d2", focus: "#635bff" }
  width:  { thin: "1px", default: "1px", thick: "2px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(10,37,64,0.04)"
  sm: "0 1px 3px rgba(10,37,64,0.06)"
  md: "0 4px 8px rgba(10,37,64,0.08)"
  lg: "0 8px 16px rgba(10,37,64,0.08)"
  xl: "0 12px 24px rgba(10,37,64,0.1)"
  "2xl": "0 20px 40px rgba(10,37,64,0.12)"
  inner: "inset 0 1px 2px rgba(10,37,64,0.04)"
  focus: "0 0 0 3px rgba(99,91,255,0.25)"

motion:
  level: "restrained"
  durations: { instant: "0ms", fast: "120ms", normal: "250ms", slow: "400ms", slower: "600ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.4, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.2, 1)"
    spring:  "cubic-bezier(0.34, 1.56, 0.64, 1)"
  hoverPatterns: ["lift", "tint", "opacity"]
  reducedMotion: true

composition:
  layout:        "flex"
  contentWidth:  "container"
  framing:       "solid"
  gridIntensity: "subtle"
  rhythm:        "8px"

surfaceStyle: "layered"
blur:         "none"

iconography:
  treatment: "linear"
  set:       "lucide"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "1.5px"

components:
  button:
    primary:
      background: "linear-gradient(180deg, #7a73ff 0%, #635bff 100%)"
      color: "#ffffff"
      border: "none"
      shadow: "0 1px 3px rgba(99,91,255,0.3), 0 1px 2px rgba(0,0,0,0.08)"
      hoverBackground: "linear-gradient(180deg, #8b85ff 0%, #7a73ff 100%)"
      hoverShadow: "0 4px 8px rgba(99,91,255,0.35), 0 2px 4px rgba(0,0,0,0.1)"
      hoverColor: "#ffffff"
    secondary:
      background: "#ffffff"
      color: "#0a2540"
      border: "1px solid #d8e0eb"
      shadow: "0 1px 2px rgba(10,37,64,0.04)"
      hoverBackground: "#f6f9fc"
      hoverShadow: "0 2px 4px rgba(10,37,64,0.06)"
      hoverColor: "#0a2540"
    ghost:
      background: "transparent"
      color: "#635bff"
      border: "none"
      shadow: "none"
      hoverBackground: "rgba(99,91,255,0.06)"
      hoverShadow: "none"
      hoverColor: "#5147e0"
    danger:
      background: "#df1b41"
      color: "#ffffff"
      border: "none"
      shadow: "0 1px 3px rgba(223,27,65,0.3)"
      hoverBackground: "#c4163a"
      hoverShadow: "0 4px 8px rgba(223,27,65,0.35)"
      hoverColor: "#ffffff"
    sizes:
      sm: { height: "32px", padding: "4px 12px", fontSize: "0.875rem" }
      md: { height: "40px", padding: "8px 16px", fontSize: "1rem" }
      lg: { height: "48px", padding: "12px 24px", fontSize: "1.125rem" }
    borderRadius: "8px"
    fontWeight: 600
    letterSpacing: "0"
    textTransform: "none"
  input:
    background: "#ffffff"
    color: "#0a2540"
    border: "1px solid #d8e0eb"
    borderRadius: "8px"
    padding: "8px 12px"
    focusBorder: "#635bff"
    placeholderColor: "#8e9db4"
  card:
    base:
      background: "#ffffff"
      border: "1px solid #edf1f7"
      borderRadius: "12px"
      padding: "24px"
      shadow: "0 1px 3px rgba(10,37,64,0.06)"
    hover:
      shadow: "0 8px 16px rgba(10,37,64,0.08)"
      transform: "translateY(-2px)"
---

# Stripe 2024

> Trustworthy fintech elegance — indigo gradients, breathable whitespace, and quietly confident typography.

## Origin

Stripe was founded in 2010 by Patrick and John Collison in San Francisco as a developer-first payments platform. From the start, Stripe invested heavily in design as a competitive advantage, treating its marketing site as a product in its own right. By 2020, the company had established a visual language — anchored by indigo purple, near-white backgrounds, and gradient mesh hero sections — that became the gold standard for B2B SaaS design.

The current 2022–2024 iteration refines this foundation with even more generous whitespace, layered card compositions, and subtle animated gradients that blend indigo, violet, and teal. Ludwig van der Pol's design leadership and the Stripe Press publishing imprint (with its Penguin-style serif book covers) both contributed to a system that balances Silicon Valley engineering rigor with old-world editorial taste. "Stripe-like" has become a common shorthand on design briefs across the industry.

## Overview
Composition cues:
- **Layout**: Flex-based, generous vertical rhythm, card-centric content blocks
- **Content width**: Container (max ~1280px) with ample side margins
- **Framing**: Solid white cards with ultra-subtle borders and soft shadows
- **Grid intensity**: Subtle — content floats in whitespace, grid is felt but invisible

## Colors
Stripe's palette radiates quiet authority. The signature indigo `#635bff` is the gravitational center — a purple that reads as serious without being corporate. It sits on `#f6f9fc`, a near-white that is warmer than pure white but cooler than cream. Deep slate `#0a2540` grounds all text. Gradient mesh accents — blending indigo through violet into teal — add dimensionality to hero sections without competing with content. The supporting palette is intentionally narrow: no loud colors beyond the indigo-violet-teal family.

**Role usage**:
- Page background → `colors.background.page`
- Card / surface background → `colors.background.surface`
- Primary actions and focus states → `colors.primary.500`
- Body text → `colors.text.primary`
- Secondary text → `colors.text.secondary`
- Muted labels and placeholders → `colors.text.muted`
- Success states → `colors.semantic.success`
- Gradient mesh heroes → radial gradients blending `primary.500` + `secondary.500` + `accent.500`

## Typography
Stripe uses Söhne (closed-license), so this system substitutes Inter — a typeface with similar neutral geometry and excellent legibility at all sizes. Inter's even spacing and open apertures echo Söhne's clarity. Headings use Inter at semibold to bold weights with tight letter-spacing, creating a confident but approachable voice. Body text at regular weight reads effortlessly at 16px on the near-white background. The overall typographic stance is: precision without sterility.

**Text styles**:
- `display-xl` — Inter, 96px, weight 800, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Inter, 64px, weight 700, line-height 1.1, letter-spacing -0.02em
- `heading-1` — Inter, 48px, weight 700, line-height 1.2, letter-spacing -0.02em
- `heading-2` — Inter, 36px, weight 600, line-height 1.25, letter-spacing -0.02em
- `body-lg` — Inter, 18px, weight 400, line-height 1.625, letter-spacing 0
- `body-md` — Inter, 16px, weight 400, line-height 1.5, letter-spacing 0
- `caption` — Inter, 14px, weight 500, line-height 1.375, letter-spacing 0
- `mono-md` — JetBrains Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout
- Base unit: 8px rhythm throughout
- Spacing scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128px
- Container max-widths: 640 / 768 / 1024 / 1280px
- Section vertical padding: 64–128px depending on viewport
- Card internal padding: 24px (md) to 32px (lg)
- Grid gap: 16–24px between cards

## Elevation & Depth
Stripe's surfaces are layered but whisper-quiet. Cards float just above the page with shadows so subtle they're almost subliminal — 1–3px blur at 4–8% opacity. There is no heavy shadow ladder; depth is communicated through background color shifts (page → surface → subtle) and the faintest edge borders. On hover, cards lift gently with increased shadow spread. The overall impression is of clean paper sheets arranged on a light table.

- Surface style: layered white cards on near-white page
- Blur: none (no glass/blur effects on standard surfaces)
- Shadow ladder: xs (1px) → sm (3px) → md (8px) → lg (16px), all using `rgba(10,37,64)` at low opacity
- Hover lift: `translateY(-2px)` + shadow promotion

## Shapes
- Card border-radius: 12px
- Button border-radius: 8px
- Input border-radius: 8px
- Tag / badge radius: 6px
- Avatar / icon containers: 9999px (full circle)
- No sharp corners anywhere in the system

## Motion
Stripe's motion is restrained and purposeful — nothing bounces, nothing spins. Transitions exist to confirm interactions, not to entertain. Hover states lift or tint over 120–250ms with standard easing. Page transitions are instant. The gradient mesh heroes are the sole exception: they animate slowly and continuously, giving the otherwise static page a sense of living energy.

- Level: restrained
- Fast interactions (hover, focus): 120ms
- Standard transitions (expand, slide): 250ms
- Slow decorative (gradient mesh drift): 600ms+
- Default easing: `cubic-bezier(0.4, 0, 0.2, 1)`
- Hover patterns: lift (`translateY(-2px)`), tint (background shift), opacity fade
- `prefers-reduced-motion`: all transitions collapse to instant

## Techniques

### Gradient Mesh Hero
A multi-stop radial gradient background that simulates colored light, characteristic of Stripe's hero sections since ~2020.
```css
.gradient-mesh-hero {
  background:
    radial-gradient(ellipse 80% 50% at 40% 20%, rgba(99,91,255,0.3) 0%, transparent 70%),
    radial-gradient(ellipse 60% 40% at 80% 60%, rgba(168,85,247,0.2) 0%, transparent 70%),
    radial-gradient(ellipse 50% 60% at 20% 80%, rgba(29,184,126,0.15) 0%, transparent 70%),
    #f6f9fc;
  min-height: 600px;
}
```

### Indigo Glow Button
Stripe's primary button uses a vertical gradient and a colored shadow to create a soft "glow" beneath the button, making it feel elevated without heavy shadows.
```css
.btn-primary {
  background: linear-gradient(180deg, #7a73ff 0%, #635bff 100%);
  color: #ffffff;
  border: none;
  border-radius: 8px;
  padding: 8px 16px;
  font-weight: 600;
  box-shadow: 0 1px 3px rgba(99,91,255,0.3), 0 1px 2px rgba(0,0,0,0.08);
  transition: all 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.btn-primary:hover {
  background: linear-gradient(180deg, #8b85ff 0%, #7a73ff 100%);
  box-shadow: 0 4px 8px rgba(99,91,255,0.35), 0 2px 4px rgba(0,0,0,0.1);
  transform: translateY(-1px);
}
```

### Whisper Card
Stripe's signature card style — barely-there border, near-invisible shadow, generous padding. The card communicates structure through whitespace rather than decoration.
```css
.whisper-card {
  background: #ffffff;
  border: 1px solid #edf1f7;
  border-radius: 12px;
  padding: 24px;
  box-shadow: 0 1px 3px rgba(10,37,64,0.06);
  transition: box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1),
              transform 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.whisper-card:hover {
  box-shadow: 0 8px 16px rgba(10,37,64,0.08);
  transform: translateY(-2px);
}
```

## Iconography
Stripe uses thin, linear icons that match the system's overall restraint. Icons are functional signifiers, never decorative — they label actions, not embellish surfaces. The stroke weight is light enough to blend with body text without competing with headings.

- Treatment: linear (outline only)
- Set: Lucide (closest open-source match to Stripe's custom set)
- Stroke: 1.5px
- Sizes: 16px (inline), 20px (default), 24px (feature)

## Do's & Don'ts

### Do
- Use Stripe indigo `#635bff` for all primary actions and interactive focus states
- Maintain generous whitespace — let content breathe in at least 64px of section padding
- Keep shadows ultra-subtle (max ~8% opacity) on cards and surfaces
- Use gradient mesh accents only on hero sections and decorative backgrounds
- Pair Inter headings at semibold/bold with regular-weight body text for clear hierarchy

### Don't
- Apply heavy decorative patterns or textures to surfaces
- Use loud colors outside the indigo-violet-teal gradient family
- Design with brutalist hard edges or sharp corners
- Default to dark mode — Stripe's identity is daylit
- Set body text in a serif typeface (serif is reserved for accent headings only)

## Applications
Stripe 2024 is ideal for fintech platforms, developer tools, SaaS dashboards, and any product that needs to communicate trustworthiness and technical sophistication simultaneously. Its restrained palette and generous whitespace work especially well for content-heavy marketing sites, documentation portals, and API reference pages where clarity is paramount.
