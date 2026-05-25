---
version: 1

meta:
  id: slack-2019
  name: Slack 2019
  description: Friendly aubergine-anchored SaaS brand that balances professionalism with warmth
  isDark: false
  tags: [friendly, tech, modernist, professional, playful]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2013 founded; canonical visual identity from 2019 Pentagram refresh"
  region: "San Francisco / Vancouver"
  regionZh: "美国旧金山 / 加拿大温哥华"
  keyFigures: [Stewart Butterfield, Michael Bierut, Pentagram]
  movements: [SaaS messaging, productivity tooling, post-email work]

introduction: |
  Slack's 2019 identity, crafted by Pentagram under Michael Bierut, distilled a chaotic rainbow into a disciplined four-color lozenge mark anchored by aubergine purple. The result is a brand that reads as both approachable and enterprise-ready — a serious collaboration tool that never feels cold.

  The design system leans on rounded geometry, generous whitespace, and restrained use of its quadrant accents (yellow, green, blue, pink) to create interfaces that feel conversational rather than corporate.
introductionZh: |
  2019年，Pentagram 团队在 Michael Bierut 的带领下为 Slack 打造了全新品牌形象，将原本混乱的彩虹色系精炼为以茄紫色为灵魂、四色菱形标志为核心的视觉语言。这套设计既有企业级工具的专业感，又保留了 Slack 一贯的亲和力。

  整个设计系统以圆润的几何形态、充裕的留白以及克制使用的四色点缀（黄、绿、蓝、粉）为特征，让界面如同一场轻松的对话，而非冰冷的办公软件。

colors:
  primary:
    "50": "#F8F0F8"
    "100": "#EEDCEE"
    "200": "#D9B3D9"
    "300": "#B87AB9"
    "400": "#7E2D7F"
    "500": "#4A154B"
    "600": "#411246"
    "700": "#370F3C"
    "800": "#2D0C31"
    "900": "#230926"
    "950": "#16051A"
  secondary:
    "50": "#EBF9FE"
    "100": "#D4F2FC"
    "200": "#A8E5F9"
    "300": "#6FD4F5"
    "400": "#36C5F0"
    "500": "#1BA8D4"
    "600": "#158BAF"
    "700": "#116F8C"
    "800": "#0D5369"
    "900": "#093A4A"
    "950": "#052530"
  accent:
    "50": "#E9F8F1"
    "100": "#D0F0E2"
    "200": "#A1E1C5"
    "300": "#63CFA2"
    "400": "#2EB67D"
    "500": "#249A69"
    "600": "#1D7E56"
    "700": "#176344"
    "800": "#114A33"
    "900": "#0B3123"
    "950": "#071F16"
  neutral:
    "50": "#F8F8F8"
    "100": "#F0F0F0"
    "200": "#E0E0E0"
    "300": "#C8C8C8"
    "400": "#A0A0A0"
    "500": "#808080"
    "600": "#616061"
    "700": "#4A494A"
    "800": "#333233"
    "900": "#1D1C1D"
    "950": "#121112"
  semantic:
    success: { bg: "#2EB67D", text: "#FFFFFF", light: "#E9F8F1", border: "#2EB67D" }
    warning: { bg: "#ECB22E", text: "#1D1C1D", light: "#FDF5E3", border: "#ECB22E" }
    error:   { bg: "#E01E5A", text: "#FFFFFF", light: "#FDE8EF", border: "#E01E5A" }
    info:    { bg: "#36C5F0", text: "#1D1C1D", light: "#EBF9FE", border: "#36C5F0" }
  background:
    page:    "#FFFFFF"
    surface: "#F8F8F8"
    subtle:  "#F0F0F0"
  text:
    primary:   "#1D1C1D"
    secondary: "#616061"
    muted:     "#868686"
    inverse:   "#FFFFFF"

typography:
  families:
    heading: "'Manrope', system-ui, -apple-system, sans-serif"
    body:    "'Manrope', system-ui, -apple-system, sans-serif"
    mono:    "'JetBrains Mono', 'Fira Code', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500;700&display=swap"
  scale: {"2xs": "0.625rem", xs: "0.75rem", sm: "0.875rem", base: "1rem", lg: "1.125rem", xl: "1.25rem", "2xl": "1.5rem", "3xl": "1.875rem", "4xl": "2.25rem", "5xl": "3rem", "6xl": "4rem", "7xl": "6rem"}
  weights: {light: 300, normal: 400, medium: 500, semibold: 600, bold: 700, extrabold: 800}
  lineHeights: {tight: 1.2, snug: 1.375, normal: 1.5, relaxed: 1.625, loose: 1.8}
  letterSpacing: {tighter: "-0.04em", tight: "-0.01em", normal: "0", wide: "0.05em"}

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      {sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%"}
  gridGap:        {sm: "8px",  md: "16px", lg: "24px", xl: "48px"}
  sectionPadding: {sm: "32px", md: "64px", lg: "96px", xl: "128px"}

borders:
  radius: {none: "0", sm: "4px", md: "6px", lg: "8px", xl: "12px", full: "9999px"}
  color:  {default: "#E0E0E0", subtle: "#F0F0F0", strong: "#1D1C1D", focus: "#4A154B"}
  width:  {thin: "1px", default: "1px", thick: "2px"}
  style:  "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(0,0,0,0.05)"
  sm: "0 1px 3px rgba(0,0,0,0.08)"
  md: "0 4px 8px rgba(0,0,0,0.08)"
  lg: "0 8px 16px rgba(0,0,0,0.10)"
  xl: "0 12px 24px rgba(0,0,0,0.12)"
  "2xl": "0 20px 40px rgba(0,0,0,0.15)"
  inner: "inset 0 1px 2px rgba(0,0,0,0.04)"
  focus: "0 0 0 3px rgba(74,21,75,0.25)"

motion:
  level: "restrained"
  durations: {instant: "0ms", fast: "100ms", normal: "200ms", slow: "350ms", slower: "500ms"}
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.4, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.2, 1)"
    spring:  "cubic-bezier(0.34, 1.56, 0.64, 1)"
  hoverPatterns: [tint, opacity, scale]
  reducedMotion: true

composition:
  layout:        "flex"
  contentWidth:  "container"
  framing:       "solid"
  gridIntensity: "subtle"
  rhythm:        "4px"

surfaceStyle: "flat"
blur:         "none"

iconography:
  treatment: "outline"
  set:       "heroicons"
  size:      {sm: "16px", md: "20px", lg: "24px"}
  stroke:    "1.5px"

components:
  button:
    primary:   {background: "#4A154B", color: "#FFFFFF", border: "none", shadow: "none", hoverBackground: "#370F3C", hoverShadow: "0 1px 3px rgba(0,0,0,0.08)", hoverColor: "#FFFFFF"}
    secondary: {background: "#FFFFFF", color: "#4A154B", border: "1px solid #4A154B", shadow: "none", hoverBackground: "#F8F0F8", hoverShadow: "none", hoverColor: "#4A154B"}
    ghost:     {background: "transparent", color: "#4A154B", border: "none", shadow: "none", hoverBackground: "#F8F0F8", hoverShadow: "none", hoverColor: "#370F3C"}
    danger:    {background: "#E01E5A", color: "#FFFFFF", border: "none", shadow: "none", hoverBackground: "#C4184E", hoverShadow: "none", hoverColor: "#FFFFFF"}
    sizes:     {sm: {height: "28px", padding: "0 12px", fontSize: "0.8125rem"}, md: {height: "36px", padding: "0 16px", fontSize: "0.9375rem"}, lg: {height: "44px", padding: "0 24px", fontSize: "1.0625rem"}}
    borderRadius: "6px"
    fontWeight: 600
    letterSpacing: "-0.01em"
    textTransform: "none"
  input:
    background: "#FFFFFF"
    color: "#1D1C1D"
    border: "1px solid #E0E0E0"
    borderRadius: "6px"
    padding: "8px 12px"
    focusBorder: "#4A154B"
    placeholderColor: "#868686"
  card:
    base:  {background: "#FFFFFF", border: "1px solid #E0E0E0", borderRadius: "8px", padding: "16px", shadow: "0 1px 3px rgba(0,0,0,0.08)"}
    hover: {shadow: "0 4px 8px rgba(0,0,0,0.08)", transform: "translateY(-1px)"}
---

# Slack 2019

> Business chat with a heartbeat — aubergine soul, quadrant accents, friendly geometry.

## Origin

Slack launched in 2013 as a pivot from a failed game studio, quickly becoming the default chat tool for tech teams. Its original identity — a rainbow octothorpe mark with eleven colors — was joyful but chaotic, impossible to render consistently at small sizes and across co-brand contexts. By 2019, Slack had outgrown startup quirkiness and needed a mark that worked at enterprise scale.

Pentagram's Michael Bierut led the 2019 refresh, distilling the rainbow into four pencil-color quadrants (blue, green, yellow, pink) locked into a rotated lozenge shape, all anchored by Slack's signature aubergine purple `#4A154B`. The new identity kept the brand's warmth while establishing the visual discipline needed for a platform serving millions of workspaces — and ultimately for Salesforce's $27.7 billion acquisition in 2021.

## Overview
Composition cues:
- **Layout**: Flex-based left-rail + content area, echoing Slack's own sidebar/channel architecture
- **Content width**: Container (max 1280px), generous horizontal padding
- **Framing**: Solid cards and surfaces with clear boundaries, no glass effects
- **Grid intensity**: Subtle — structure through whitespace rather than visible grid lines

## Colors
Slack's color philosophy centers on restraint around a bold anchor. Aubergine `#4A154B` dominates navigation and primary actions, while the four quadrant accents — yellow `#ECB22E`, green `#2EB67D`, blue `#36C5F0`, and pink `#E01E5A` — appear individually for semantic roles (success, warning, info, error) rather than together. The post-2019 brand explicitly avoids using all four accents simultaneously; each earns its moment.

**Role usage**:
- Page background → `colors.background.page` (`#FFFFFF`)
- Sidebar / nav background → `colors.primary.500` (`#4A154B`)
- Primary actions → `colors.primary.500`
- Success states → `colors.accent.400` / `#2EB67D`
- Warning states → `#ECB22E`
- Error / destructive → `#E01E5A`
- Info / links → `#36C5F0`
- Body text → `colors.text.primary` (`#1D1C1D`)

## Typography
Slack's type voice is friendly, direct, and unpretentious. The proprietary Slack Sans (approximated here by Manrope) is a geometric sans-serif with open apertures and slightly rounded terminals that softens the corporate edge. Headings use semibold-to-bold weights with subtle negative tracking (`-0.01em`), giving them presence without shouting. Body text sits at regular weight with generous line-height for readability in dense conversational contexts.

**Text styles**:
- `display-xl` — Manrope, 96px, weight 800, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Manrope, 64px, weight 700, line-height 1.1, letter-spacing -0.02em
- `heading-1` — Manrope, 36px, weight 700, line-height 1.2, letter-spacing -0.01em
- `heading-2` — Manrope, 28px, weight 600, line-height 1.3, letter-spacing -0.01em
- `body-lg` — Manrope, 18px, weight 400, line-height 1.5, letter-spacing 0
- `body-md` — Manrope, 15px, weight 400, line-height 1.5, letter-spacing 0
- `caption` — Manrope, 13px, weight 500, line-height 1.4, letter-spacing 0
- `mono-md` — JetBrains Mono, 14px, weight 400, line-height 1.6, letter-spacing 0

## Spacing & Layout
- Base unit: 4px
- Scale follows a progression: 4 → 8 → 12 → 16 → 24 → 32 → 48 → 64 → 96 → 128
- Container max-width: 1280px with 24px horizontal gutters at desktop
- Section padding: 64px vertical (md) to 96px (lg) for marketing layouts
- Component internal padding: 12–16px, matching the conversational density of a chat UI

## Elevation & Depth
Slack's surfaces are flat and honest — no glass, no blur, no heavy drop shadows. Depth is communicated through border separation and subtle box-shadows on interactive elements. The sidebar's solid aubergine fill creates the primary depth layer; everything else lives on white or near-white surfaces with 1px borders.

- Surface style: flat, opaque fills only
- Blur: none — no backdrop-filter effects
- Shadow ladder: xs (1px ambient) for resting states, sm (3px) for cards, md (8px) for dropdowns and popovers
- Elevation is binary: sidebar (aubergine) vs. content (white)

## Shapes
- Button radius: 6px — rounded but not pill-shaped, approachable without being childish
- Message bubble / card radius: 8px — slightly softer for content containers
- Avatar radius: 4px (rounded square, matching Slack's actual avatar style)
- Pill / tag radius: 9999px (full pill for status badges and channel pills)
- Input radius: 6px — matches buttons for visual consistency

## Motion
Slack's motion is restrained and functional — animations exist to confirm actions and guide attention, never to entertain. Transitions are fast (100–200ms) with ease-out curves, making the interface feel snappy and responsive like a real-time chat tool should.

- Level: restrained
- Fast interactions (hover, toggle): 100ms
- Standard transitions (panel open, modal appear): 200ms
- Slow transitions (page-level): 350ms
- Easing: ease-out for entrances, ease-in-out for state changes
- Hover patterns: subtle aubergine tint fill, slight opacity shift, micro-scale (1.01×)
- Respects `prefers-reduced-motion`

## Techniques

### Aubergine Sidebar Gradient
A subtle vertical gradient on navigation surfaces, darkening toward the bottom to add depth without breaking the flat aesthetic.
```css
.sidebar {
  background: linear-gradient(180deg, #4A154B 0%, #370F3C 100%);
  color: #FFFFFF;
  width: 260px;
  padding: 16px 0;
}
.sidebar-item {
  padding: 6px 24px;
  border-radius: 6px;
  margin: 0 8px;
  color: rgba(255, 255, 255, 0.7);
  transition: background 100ms ease-out;
}
.sidebar-item:hover,
.sidebar-item--active {
  background: rgba(255, 255, 255, 0.1);
  color: #FFFFFF;
}
```

### Quadrant Accent Badge
Status badges using a single quadrant accent color as a filled pill — the Slack way to use brand colors without deploying the full four-color palette.
```css
.badge {
  display: inline-flex;
  align-items: center;
  gap: 6px;
  padding: 2px 10px;
  border-radius: 9999px;
  font-size: 0.8125rem;
  font-weight: 600;
  letter-spacing: -0.01em;
}
.badge--green {
  background: #E9F8F1;
  color: #2EB67D;
}
.badge--blue {
  background: #EBF9FE;
  color: #1BA8D4;
}
.badge--yellow {
  background: #FDF5E3;
  color: #9E7500;
}
.badge--pink {
  background: #FDE8EF;
  color: #E01E5A;
}
```

### Message Compose Bar
The signature bottom-anchored input with rounded corners, inline action icons, and a subtle border that intensifies on focus — the most-used component in Slack's UI.
```css
.compose-bar {
  display: flex;
  align-items: flex-end;
  gap: 8px;
  border: 1px solid #E0E0E0;
  border-radius: 8px;
  padding: 8px 12px;
  background: #FFFFFF;
  transition: border-color 200ms ease-out;
}
.compose-bar:focus-within {
  border-color: #4A154B;
  box-shadow: 0 0 0 3px rgba(74, 21, 75, 0.15);
}
.compose-bar textarea {
  flex: 1;
  border: none;
  outline: none;
  font-family: 'Manrope', sans-serif;
  font-size: 0.9375rem;
  line-height: 1.5;
  resize: none;
  color: #1D1C1D;
}
.compose-bar textarea::placeholder {
  color: #868686;
}
```

## Iconography
Slack uses clean outline icons with 1.5px strokes, matching the friendly-but-not-cute personality of the brand. Icons are sized at 20px for inline use and 24px for navigation, always rendered in the current text color or muted gray — never in the quadrant accent colors unless conveying a specific semantic state.

- Treatment: outline
- Set: Heroicons (closest to Slack's custom set)
- Stroke: 1.5px, round caps and joins

## Do's & Don'ts

### Do
- Use aubergine `#4A154B` as the dominant brand color for navigation and primary actions
- Apply quadrant accents one at a time for semantic meaning (green = success, pink = error)
- Keep border-radius consistent: 6px for interactive elements, 8px for containers
- Maintain generous whitespace between content blocks — let the layout breathe like a conversation
- Use Manrope at semibold (600) for headings with -0.01em tracking

### Don't
- Resurrect the old rainbow octothorpe or use all four accent colors simultaneously
- Apply cold blue corporate palettes — warmth is core to the brand
- Use heavy gradients across whole pages — the aubergine gradient is sidebar-only
- Introduce serif typography of any kind
- Use brutalist sharp edges or 0px border-radius on interactive elements

## Applications
Slack 2019's design system is ideal for SaaS dashboards, collaboration tools, internal communication platforms, and productivity apps that need to feel both professional and human. The aubergine-anchored palette with restrained accent use works especially well for products that have dense, text-heavy interfaces — chat, project management, documentation — where warmth and readability must coexist with information density.
