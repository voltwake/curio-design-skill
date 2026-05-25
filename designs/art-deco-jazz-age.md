---
version: 1

meta:
  id: art-deco-jazz-age
  name: Art Deco Jazz Age
  description: "1920s machine-age glamour — geometric gold on deep black, sunburst motifs, and the luxurious shimmer of Gatsby's Manhattan"
  isDark: true
  tags: [decorative, luxurious, historical, bold, editorial]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "~1920–1939; named after the 1925 Paris Exposition Internationale des Arts Décoratifs et Industriels Modernes"
  region: "Paris, France; then New York City and Miami, United States"
  regionZh: "法国巴黎；后传至美国纽约与迈阿密"
  keyFigures: [Erté, Cassandre, Tamara de Lempicka, William Van Alen]
  movements: [Post-Cubism, Egyptian Revival, Fauvism color heritage]

introduction: |
  Art Deco is the visual language of the Jazz Age — an exuberant fusion of machine-age streamlining and ancient geometric ornament that dominated architecture, fashion, and graphic design from the mid-1920s through the late 1930s. Its vocabulary of sunburst rays, stepped ziggurats, and chevron patterns adorned everything from the Chrysler Building's lobby to Cassandre's ocean liner posters.

  This design system distills that vocabulary into digital tokens: warm gold accents against deep black grounds, high-contrast geometric serifs, bilateral symmetry, and the polished metallic sheen of a Manhattan elevator door rendered in CSS.
introductionZh: |
  装饰艺术是爵士时代的视觉语言——将机械时代的流线造型与古老几何纹饰融于一体，在 1920 年代中期至 1930 年代末主宰了建筑、时装与平面设计。太阳光芒、阶梯金字塔、人字纹等图案装点了从克莱斯勒大厦门厅到卡桑德尔远洋邮轮海报的一切表面。

  这套设计系统将上述语汇提炼为数字令牌：暖金色点缀深黑底色、高对比度几何衬线体、左右对称构图，以及曼哈顿电梯门般的金属光泽——全部以 CSS 实现。

colors:
  primary:
    "50": "#FDF8EC"
    "100": "#FAF0D4"
    "200": "#F2DDAA"
    "300": "#E5C87A"
    "400": "#D7B462"
    "500": "#c9a84c"
    "600": "#A98A3A"
    "700": "#876D2C"
    "800": "#655120"
    "900": "#443716"
    "950": "#2A220D"
  secondary:
    "50": "#EFF8F4"
    "100": "#D5EDDF"
    "200": "#A8D9BC"
    "300": "#6FBE92"
    "400": "#3E9A6A"
    "500": "#1B6B45"
    "600": "#165A3A"
    "700": "#12482F"
    "800": "#0D3623"
    "900": "#092518"
    "950": "#05150D"
  accent:
    "50": "#F8F0EE"
    "100": "#EFDDDA"
    "200": "#DFB8B0"
    "300": "#C98E82"
    "400": "#A8645A"
    "500": "#7A3B33"
    "600": "#66302A"
    "700": "#522622"
    "800": "#3E1C19"
    "900": "#2B1311"
    "950": "#1A0B0A"
  neutral:
    "50": "#F5F3EE"
    "100": "#E8E4DB"
    "200": "#CEC8BA"
    "300": "#B0A898"
    "400": "#8A8272"
    "500": "#6B6456"
    "600": "#524C40"
    "700": "#3A362E"
    "800": "#24211C"
    "900": "#171510"
    "950": "#0D0C09"
  semantic:
    success: { bg: "#1A2E1D", text: "#6BBF72", light: "#0F1F12", border: "#2A4F30" }
    warning: { bg: "#2E2A16", text: "#BFA85A", light: "#1F1C0F", border: "#4F4520" }
    error: { bg: "#2E1A18", text: "#BF6B65", light: "#1F0F0E", border: "#4F2A27" }
    info: { bg: "#1A1F2E", text: "#6B8ABF", light: "#0F1420", border: "#2A3A4F" }
  background:
    page: "#0d0908"
    surface: "#16120e"
    subtle: "#1e1912"
  text:
    primary: "#F5F0E0"
    secondary: "#c9a84c"
    muted: "#8A8272"
    inverse: "#0d0908"

typography:
  families:
    heading: "'Cinzel', 'Georgia', serif"
    body: "'Cormorant Garamond', 'Georgia', serif"
    mono: "'JetBrains Mono', 'Fira Code', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Cinzel:wght@400;500;600;700;800;900&family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,500;1,600;1,700&family=Poiret+One&family=JetBrains+Mono:wght@400;500;700&display=swap"
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
    tight: 1.1
    snug: 1.3
    normal: 1.5
    relaxed: 1.625
    loose: 1.8
  letterSpacing:
    tighter: "-0.04em"
    tight: "-0.02em"
    normal: "0"
    wide: "0.1em"

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
    lg: "6px"
    xl: "8px"
    full: "9999px"
  color:
    default: "#3A362E"
    subtle: "#24211C"
    strong: "#c9a84c"
    focus: "#c9a84c"
  width:
    thin: "1px"
    default: "1px"
    thick: "2px"
  style: "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(0,0,0,0.3)"
  sm: "0 2px 4px rgba(0,0,0,0.4)"
  md: "0 4px 16px rgba(0,0,0,0.5)"
  lg: "0 8px 32px rgba(0,0,0,0.6)"
  xl: "0 16px 48px rgba(0,0,0,0.7)"
  "2xl": "0 24px 64px rgba(0,0,0,0.8)"
  inner: "inset 0 1px 4px rgba(0,0,0,0.5)"
  focus: "0 0 0 3px rgba(201,168,76,0.35)"

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
    spring: "cubic-bezier(0.22, 1, 0.36, 1)"
  hoverPatterns: [glow, opacity, tint]
  reducedMotion: true

composition:
  layout: "grid"
  contentWidth: "container"
  framing: "bordered"
  gridIntensity: "strong"
  rhythm: "8px"

surfaceStyle: "layered"
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
      background: "#c9a84c"
      color: "#0d0908"
      border: "1px solid #c9a84c"
      shadow: "0 2px 4px rgba(0,0,0,0.4)"
      hoverBackground: "#D7B462"
      hoverShadow: "0 4px 16px rgba(201,168,76,0.3)"
      hoverColor: "#0d0908"
    secondary:
      background: "transparent"
      color: "#c9a84c"
      border: "1px solid #c9a84c"
      shadow: "none"
      hoverBackground: "rgba(201,168,76,0.1)"
      hoverShadow: "0 0 8px rgba(201,168,76,0.2)"
      hoverColor: "#D7B462"
    ghost:
      background: "transparent"
      color: "#F5F0E0"
      border: "1px solid transparent"
      shadow: "none"
      hoverBackground: "rgba(201,168,76,0.06)"
      hoverShadow: "none"
      hoverColor: "#c9a84c"
    danger:
      background: "#7A3B33"
      color: "#F5F0E0"
      border: "1px solid #7A3B33"
      shadow: "none"
      hoverBackground: "#A8645A"
      hoverShadow: "0 0 12px rgba(122,59,51,0.4)"
      hoverColor: "#F5F0E0"
    sizes:
      sm: { height: "32px", padding: "0 14px", fontSize: "0.875rem" }
      md: { height: "40px", padding: "0 24px", fontSize: "1rem" }
      lg: { height: "48px", padding: "0 32px", fontSize: "1.125rem" }
    borderRadius: "2px"
    fontWeight: 600
    letterSpacing: "0.1em"
    textTransform: "uppercase"
  input:
    background: "#0d0908"
    color: "#F5F0E0"
    border: "1px solid #3A362E"
    borderRadius: "2px"
    padding: "10px 14px"
    focusBorder: "1px solid #c9a84c"
    placeholderColor: "#8A8272"
  card:
    base:
      background: "#16120e"
      border: "1px solid rgba(201,168,76,0.25)"
      borderRadius: "4px"
      padding: "24px"
      shadow: "0 8px 32px rgba(0,0,0,0.6)"
    hover:
      shadow: "0 12px 40px rgba(0,0,0,0.7), 0 0 20px rgba(201,168,76,0.08)"
      transform: "translateY(-2px)"
---

# Art Deco Jazz Age

> Machine-age geometry gilded in warm gold — sunburst motifs, stepped ziggurats, and the polished glamour of 1920s Manhattan rendered as a digital design system.

## Origin

Art Deco emerged from the 1925 *Exposition Internationale des Arts Décoratifs et Industriels Modernes* in Paris, christening a style that had been brewing since the early 1920s. It absorbed the fractured planes of Cubism, the bold palettes of Fauvism, and the exotic geometry of Egyptian Revival — the latter ignited by Howard Carter's 1922 opening of Tutankhamun's tomb. Poster artist Cassandre, painter Tamara de Lempicka, fashion illustrator Erté, and architect William Van Alen each channeled the movement into different media, but all shared the same DNA: streamlined geometry, metallic opulence, and bilateral symmetry.

By 1930 the style had crossed the Atlantic and was reaching skyward. Van Alen's Chrysler Building — its stainless-steel crown a stack of radiating arches — became the movement's definitive monument. Ocean liners, radio consoles, movie palaces, and cocktail shakers all wore the same visual uniform: stepped pyramids, chevron borders, sunburst fans, and surfaces lacquered in gold, silver, and onyx. Deco was unabashedly modern, unabashedly luxurious, and unabashedly optimistic — a style that believed the machine would deliver beauty, not destroy it.

## Overview
Composition cues:
- **Layout**: Grid-based with strong bilateral symmetry; vertical emphasis echoing skyscraper silhouettes
- **Content width**: Container-bound (max 1024–1280px), centered with generous horizontal margins
- **Framing**: Bordered — gold hairline rules, chevron corner accents, stepped geometric ornaments as dividers
- **Grid intensity**: Strong — visible grid lines and repeating geometric patterns reinforce the Deco vocabulary

## Colors
The palette is a midnight gala at the Chrysler Building. A deep, warm black ground (#0d0908) — not blue-black, not grey-black, but the near-black of lacquered ebony — absorbs the eye. Warm gold (#c9a84c) is the commanding accent: the color of gilded elevator doors, engraved cocktail cases, and sunburst plaster ceilings. It is the only primary hue and carries all interactive states. Deep emerald and oxblood appear as secondary and tertiary accents — the green of jade cufflinks, the red of a lacquered cigarette case — used sparingly for variety without competing with the gold. Ivory-white text (#F5F0E0) reads cleanly against the dark ground.

**Role usage**:
- Page background → `colors.background.page` (#0d0908 lacquered black)
- Card / surface panels → `colors.background.surface` (#16120e warm charcoal)
- Subtle inset backgrounds → `colors.background.subtle` (#1e1912)
- Primary body text → `colors.text.primary` (#F5F0E0 ivory)
- Gold accent text (labels, links, highlights) → `colors.text.secondary` (#c9a84c warm gold)
- Muted captions and meta text → `colors.text.muted` (#8A8272)
- Primary interactive accent (buttons, focus rings, active states) → `colors.primary.500` (#c9a84c gold)
- Secondary accent for depth → `colors.secondary.500` (deep emerald)

## Typography
The typographic voice is a 1930s movie-palace marquee carved in stone. Display headlines use Cinzel — a geometric serif whose wide capitals and fine hairlines evoke inscriptional Roman lettering filtered through Deco's love of clean geometry. Body text is set in Cormorant Garamond, a high-contrast serif with Didone proportions that supplies elegance without fussiness. For decorative display moments (hero taglines, section labels), Poiret One is available — a slender geometric display face that channels Erté and the thin-line glamour of 1920s fashion illustration. All type is set with wide letter-spacing; uppercase transforms are encouraged for buttons and labels to reinforce the monumental quality.

**Text styles**:
- `display-xl` — Cinzel, 96px, weight 700, line-height 1.0, letter-spacing 0.1em, uppercase
- `display-lg` — Cinzel, 64px, weight 700, line-height 1.1, letter-spacing 0.08em, uppercase
- `heading-1` — Cinzel, 48px, weight 600, line-height 1.1, letter-spacing 0.06em
- `body-lg` — Cormorant Garamond, 18px, weight 400, line-height 1.5, letter-spacing 0
- `body-md` — Cormorant Garamond, 16px, weight 400, line-height 1.5, letter-spacing 0
- `caption` — Cinzel, 12px, weight 500, line-height 1.3, letter-spacing 0.1em, uppercase
- `mono-md` — JetBrains Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout
- Base unit: 4px; primary rhythm on an 8px grid
- Spacing scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128px
- Container max-width: 1024px (lg) to 1280px (xl), centered
- Section padding: 64–96px vertical, mirroring the soaring vertical proportions of Deco architecture
- Cards and panels use 24px internal padding with gold-tinted hairline borders

## Elevation & Depth
Depth is achieved through stacked opaque surfaces of increasing warmth against a pure-dark ground — the layering of lacquer, not the blur of frosted glass. The material metaphor is polished obsidian and brushed gold leaf: hard, reflective, precisely delineated. Shadows are deep and diffuse, suggesting recesses carved into stone rather than floating paper.

- Surface style: Layered opaque panels (#16120e on #0d0908)
- Blur: None — glass effects would undermine the hard-edge material language
- Shadow ladder: xs (subtle vignette) → sm → md → lg (card default: `0 8px 32px rgba(0,0,0,0.6)`) → xl → 2xl
- Focus ring: `0 0 0 3px rgba(201,168,76,0.35)` — a warm gold halo

## Shapes
- Button border-radius: 2px (nearly square — Deco demands precision, not softness)
- Card border-radius: 4px
- Input border-radius: 2px
- General: radii never exceed 8px; rounded-full reserved only for avatar masks
- Chevron and stepped-pyramid decorative shapes can cap or crown sections

## Motion
Motion is restrained and deliberate — the slow, mechanical sweep of an elevator dial, not a playful bounce. Transitions favor opacity fades and subtle gold glows that recall neon signage warming up. Speed feels calibrated, like Art Deco machinery: precise, purposeful, never frantic.

- Level: Restrained
- Durations: fast 120ms (micro-interactions), normal 250ms (state changes), slow 400ms (reveals), slower 600ms (page transitions)
- Easings: default `cubic-bezier(0.4, 0, 0.2, 1)`, spring `cubic-bezier(0.22, 1, 0.36, 1)` for card lifts
- Hover patterns: warm gold glow, opacity fade, gold tint shift
- Reduced-motion: fully supported — all animation respects `prefers-reduced-motion`

## Techniques

### Gold Sunburst Divider
A CSS-only sunburst section divider — radiating gold lines from a central point, evoking the Chrysler Building's crown and Deco ceiling rosettes.
```css
.sunburst-divider {
  position: relative;
  height: 80px;
  display: flex;
  align-items: center;
  justify-content: center;
  overflow: hidden;
}
.sunburst-divider::before {
  content: "";
  position: absolute;
  width: 200px;
  height: 200px;
  background: repeating-conic-gradient(
    #c9a84c 0deg 2deg,
    transparent 2deg 15deg
  );
  opacity: 0.2;
  mask-image: radial-gradient(circle, black 30%, transparent 70%);
  -webkit-mask-image: radial-gradient(circle, black 30%, transparent 70%);
}
.sunburst-divider::after {
  content: "◆";
  position: relative;
  color: #c9a84c;
  font-size: 14px;
  z-index: 1;
}
```

### Stepped Chevron Border
Deco's signature stepped-pyramid silhouette as a repeating top-border pattern for hero sections and cards.
```css
.chevron-header {
  position: relative;
  padding-top: 24px;
}
.chevron-header::before {
  content: "";
  position: absolute;
  top: 0;
  left: 50%;
  transform: translateX(-50%);
  width: 120px;
  height: 12px;
  background:
    linear-gradient(135deg, transparent 33.33%, #c9a84c 33.33%, #c9a84c 66.66%, transparent 66.66%) 0 0 / 12px 12px repeat-x;
  opacity: 0.6;
}
```

### Gilded Focus Ring
An animated gold-glow focus state that simulates the warm luminescence of gold leaf catching light — used on interactive elements to maintain the luxurious atmosphere.
```css
.deco-focus:focus-visible {
  outline: none;
  box-shadow:
    0 0 0 2px #0d0908,
    0 0 0 4px #c9a84c,
    0 0 16px rgba(201, 168, 76, 0.25);
  transition: box-shadow 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
```

## Iconography
Icons use a thin linear treatment — the precision of an engraver's burin on a gold cigarette case. They appear in gold (#c9a84c) for navigation and interactive elements, in ivory (#F5F0E0) for content-area informational icons, and maintain a consistent 1.5px stroke weight that harmonizes with Cinzel's fine hairlines.

- Treatment: Linear (outline only)
- Set: Lucide
- Stroke: 1.5px

## Do's & Don'ts

### ✓ Do
- Use warm gold (#c9a84c) as the sole primary accent — it anchors the entire Deco identity
- Set display headlines in Cinzel with wide letter-spacing and uppercase transforms for monumental impact
- Employ bilateral symmetry and strong vertical axis alignment in layouts
- Use stepped, chevron, and sunburst geometric ornaments as section dividers and decorative accents
- Maintain deep, warm black grounds to showcase metallic accents at maximum contrast

### ✗ Don't
- Use pastels — they belong to the 1950s, not the 1920s
- Set headings in sans-serif faces — the geometric serif is essential to Deco's elegance
- Introduce earth tones or browns — Deco's palette is metallic and jewel-toned, not organic
- Allow asymmetric chaos — Deco is composed, balanced, and deliberately symmetrical
- Apply cool minimalism — Deco is maximalist ornament with geometric discipline, not reduction

## Applications
Art Deco Jazz Age is ideal for luxury brand sites, cocktail bar and speakeasy digital experiences, upscale event invitations and gala landing pages, editorial magazines with a vintage-glamour bent, and portfolio sites for architects, jewelers, or fashion designers who want to channel the era's gilded confidence. It excels wherever the audience expects opulence, craft, and a sense of occasion — and where a gold-on-black palette will read as deliberate luxury rather than mere darkness.
