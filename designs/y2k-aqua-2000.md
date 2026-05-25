---
version: 1

meta:
  id: y2k-aqua-2000
  name: "Y2K Aqua 2000"
  description: "Glossy candy-blue pill buttons and translucent pinstripe surfaces channeling Mac OS X's lickable Aqua interface"
  isDark: false
  tags: [decorative, friendly, historical, y2k, playful]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "1999–2007; Mac OS X 10.0 launched March 2001"
  region: "Cupertino, California"
  regionZh: "美国加州库比蒂诺"
  keyFigures: ["Steve Jobs", "Cordell Ratzlaff", "Bas Ording"]
  movements: ["Y2K design language", "Frutiger Aero"]

introduction: |
  Aqua was Apple's audacious answer to the millennium: a user interface so glossy, so candy-bright, that Steve Jobs declared users would want to lick it. Launched with Mac OS X in March 2001, Aqua wrapped every pixel in translucent blue gradients, pill-shaped buttons, and water-droplet highlights that made screens feel like sunlit swimming pools.

  This system distills that era's unapologetic optimism — pinstripe textures, jellybean window controls, genie-effect theatrics — into a modern token set. It is Y2K nostalgia at its most joyful: bright, bubbly, and gloriously skeuomorphic.
introductionZh: |
  Aqua 是苹果公司在千禧年之交对数字界面的一次大胆宣言。2001 年 3 月随 Mac OS X 一同亮相的 Aqua 界面，以晶莹剔透的糖果蓝渐变、药丸形按钮和水滴般的高光效果，让每一个像素都仿佛浸泡在阳光下的泳池里。乔布斯曾说"我希望它好看到让人想舔一口"。

  本设计系统提炼了那个时代毫不掩饰的乐观精神——细条纹纹理、果冻色窗口控件、精灵特效般的动画——将其转化为现代可用的设计令牌。这是 Y2K 怀旧美学最欢快的化身：明亮、圆润、充满拟物主义的光泽。

colors:
  primary:
    "50": "#eef6fe"
    "100": "#d9ecfd"
    "200": "#b8dbfb"
    "300": "#8dc5f8"
    "400": "#6db3f2"
    "500": "#3d8de6"
    "600": "#1e6dd0"
    "700": "#1a5bb0"
    "800": "#1a4d90"
    "900": "#1c4174"
    "950": "#132a4c"
  secondary:
    "50": "#f0f4f8"
    "100": "#dce4ed"
    "200": "#bdccde"
    "300": "#93acc7"
    "400": "#6b8aad"
    "500": "#4d6e93"
    "600": "#3d587b"
    "700": "#354a65"
    "800": "#2f3f55"
    "900": "#2b3749"
    "950": "#1c2430"
  accent:
    "50": "#fef5f5"
    "100": "#fee2e2"
    "200": "#fecaca"
    "300": "#fca5a5"
    "400": "#f87171"
    "500": "#ef4444"
    "600": "#dc2626"
    "700": "#b91c1c"
    "800": "#991b1b"
    "900": "#7f1d1d"
    "950": "#450a0a"
  neutral:
    "50": "#f8fafc"
    "100": "#f1f5f9"
    "200": "#e2e8f0"
    "300": "#cbd5e1"
    "400": "#94a3b8"
    "500": "#64748b"
    "600": "#475569"
    "700": "#334155"
    "800": "#1e293b"
    "900": "#0f172a"
    "950": "#020617"
  semantic:
    success: { bg: "#22c55e", text: "#ffffff", light: "#dcfce7", border: "#86efac" }
    warning: { bg: "#f59e0b", text: "#ffffff", light: "#fef9c3", border: "#fde68a" }
    error:   { bg: "#ef4444", text: "#ffffff", light: "#fee2e2", border: "#fca5a5" }
    info:    { bg: "#3d8de6", text: "#ffffff", light: "#eef6fe", border: "#8dc5f8" }
  background:
    page:    "#fafdff"
    surface: "#ffffff"
    subtle:  "#eef3f9"
  text:
    primary:   "#1e293b"
    secondary: "#475569"
    muted:     "#94a3b8"
    inverse:   "#ffffff"

typography:
  families:
    heading: "'Nunito', 'Lato', system-ui, sans-serif"
    body:    "'Lato', 'Nunito', system-ui, sans-serif"
    mono:    "'SF Mono', 'Menlo', 'Monaco', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Lato:wght@300;400;700;900&family=Nunito:wght@400;600;700;800&display=swap"
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
  gridGap:        { sm: "8px", md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "8px", md: "12px", lg: "16px", xl: "24px", full: "9999px" }
  color:  { default: "#cbd5e1", subtle: "#e2e8f0", strong: "#94a3b8", focus: "#6db3f2" }
  width:  { thin: "1px", default: "1px", thick: "2px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(30,109,208,0.06)"
  sm: "0 2px 4px rgba(30,109,208,0.08)"
  md: "0 4px 8px rgba(30,109,208,0.10), inset 0 1px 0 rgba(255,255,255,0.6)"
  lg: "0 8px 16px rgba(30,109,208,0.12), inset 0 1px 0 rgba(255,255,255,0.5)"
  xl: "0 12px 24px rgba(30,109,208,0.14), inset 0 2px 0 rgba(255,255,255,0.4)"
  "2xl": "0 20px 40px rgba(30,109,208,0.16)"
  inner: "inset 0 2px 4px rgba(30,109,208,0.12)"
  focus: "0 0 0 3px rgba(109,179,242,0.45)"

motion:
  level: "lively"
  durations: { instant: "0ms", fast: "120ms", normal: "250ms", slow: "400ms", slower: "600ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.4, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.2, 1)"
    spring:  "cubic-bezier(0.34, 1.56, 0.64, 1)"
  hoverPatterns: ["lift", "glow", "scale"]
  reducedMotion: true

composition:
  layout:        "flex"
  contentWidth:  "container"
  framing:       "glassy"
  gridIntensity: "soft"
  rhythm:        "4px"

surfaceStyle: "glass"
blur:         "12px"

iconography:
  treatment: "filled"
  set:       "lucide"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "1.5px"

components:
  button:
    primary:
      background: "linear-gradient(180deg, #6db3f2 0%, #1e6dd0 100%)"
      color: "#ffffff"
      border: "1px solid #1a5bb0"
      shadow: "0 2px 6px rgba(30,109,208,0.3), inset 0 1px 0 rgba(255,255,255,0.4)"
      hoverBackground: "linear-gradient(180deg, #85c1f5 0%, #2578da 100%)"
      hoverShadow: "0 4px 10px rgba(30,109,208,0.4), inset 0 1px 0 rgba(255,255,255,0.5)"
      hoverColor: "#ffffff"
    secondary:
      background: "linear-gradient(180deg, #f8fafc 0%, #e2e8f0 100%)"
      color: "#334155"
      border: "1px solid #cbd5e1"
      shadow: "0 1px 3px rgba(0,0,0,0.08), inset 0 1px 0 rgba(255,255,255,0.8)"
      hoverBackground: "linear-gradient(180deg, #ffffff 0%, #eef3f9 100%)"
      hoverShadow: "0 2px 6px rgba(0,0,0,0.10), inset 0 1px 0 rgba(255,255,255,0.9)"
      hoverColor: "#1e293b"
    ghost:
      background: "transparent"
      color: "#3d8de6"
      border: "1px solid transparent"
      shadow: "none"
      hoverBackground: "rgba(109,179,242,0.10)"
      hoverShadow: "none"
      hoverColor: "#1e6dd0"
    danger:
      background: "linear-gradient(180deg, #f87171 0%, #dc2626 100%)"
      color: "#ffffff"
      border: "1px solid #b91c1c"
      shadow: "0 2px 6px rgba(220,38,38,0.3), inset 0 1px 0 rgba(255,255,255,0.3)"
      hoverBackground: "linear-gradient(180deg, #fca5a5 0%, #ef4444 100%)"
      hoverShadow: "0 4px 10px rgba(220,38,38,0.4), inset 0 1px 0 rgba(255,255,255,0.4)"
      hoverColor: "#ffffff"
    sizes:
      sm: { height: "32px", padding: "0 16px", fontSize: "0.875rem" }
      md: { height: "40px", padding: "0 24px", fontSize: "1rem" }
      lg: { height: "48px", padding: "0 32px", fontSize: "1.125rem" }
    borderRadius: "9999px"
    fontWeight: 700
    letterSpacing: "0"
    textTransform: "none"
  input:
    background: "#ffffff"
    color: "#1e293b"
    border: "1px solid #cbd5e1"
    borderRadius: "12px"
    padding: "8px 14px"
    focusBorder: "#6db3f2"
    placeholderColor: "#94a3b8"
  card:
    base:
      background: "rgba(255,255,255,0.85)"
      border: "1px solid rgba(203,213,225,0.5)"
      borderRadius: "16px"
      padding: "24px"
      shadow: "0 4px 12px rgba(30,109,208,0.08), inset 0 1px 0 rgba(255,255,255,0.7)"
    hover:
      shadow: "0 8px 20px rgba(30,109,208,0.14), inset 0 1px 0 rgba(255,255,255,0.8)"
      transform: "translateY(-2px)"
---

# Y2K Aqua 2000

> Glossy candy-blue pills and translucent pinstripe surfaces — the lickable interface that defined a millennium.

## Origin

Aqua was Apple's user interface revolution, unveiled with Mac OS X 10.0 Cheetah in March 2001. Born from late-1999 prototypes at Apple's Cupertino campus, it was the brainchild of UI lead Cordell Ratzlaff and interaction designer Bas Ording, with Steve Jobs famously demanding the interface look "so good you'll want to lick it." Aqua replaced the platinum grays of Classic Mac OS with candy-colored translucency that made every button feel like a liquid gemstone.

The aesthetic dominated personal computing for nearly a decade, from the original iMac G4's sunflower design through iTunes' brushed-metal era and the iPod silhouette campaign. Aqua's glossy pill buttons, pinstripe window backgrounds, and water-droplet icons became the visual vocabulary of early-2000s digital optimism. Its influence faded with Leopard's matte shift in 2007 and died with iOS 7's flat purge in 2013 — but today it lives on as beloved Y2K nostalgia, closely related to the Frutiger Aero movement.

## Overview

Composition cues:
- **Layout**: Flex-based with centered content containers, mirroring Mac OS X's window-centric paradigm
- **Content width**: Container (1024–1280px), generous side margins like a desktop window floating on a pinstripe background
- **Framing**: Glassy — every surface hints at translucency with subtle white inner-top highlights and blue-tinted shadows
- **Grid intensity**: Soft — structure is present but disguised by rounded corners and glossy gradients

## Colors

Aqua's palette is a swimming pool on a California summer day. The signature candy-blue gradient — #6db3f2 at its highlight to #1e6dd0 at depth — appears on every primary interactive element. Supporting colors are drawn from the Mac OS X window chrome: the red/yellow/green jellybean stoplight buttons, graphite neutrals for secondary surfaces, and a pristine near-white (#fafdff) page background with the faintest blue tint, evoking the original pinstripe desktop.

**Role usage**:
- Page background → `colors.background.page` (#fafdff with blue tint)
- Card/panel surfaces → `colors.background.surface` (white at 85% opacity for translucency)
- Primary actions (buttons, links) → `colors.primary.400`–`colors.primary.600` gradient
- Body text → `colors.text.primary` (dark slate, never pure black)
- Secondary text → `colors.text.secondary` (muted slate-gray)
- Focus rings → `shadows.focus` (aqua-blue glow)
- Danger/destructive → `colors.accent.500` (jellybean red from window chrome)
- Subtle backgrounds/stripes → `colors.background.subtle` (pale blue-gray)

## Typography

Aqua's type voice is friendly, round, and readable — the humanist sans-serif tradition that Apple championed with Lucida Grande. This system uses **Nunito** for headings (its rounded terminals echo Aqua's pill-shaped geometry) and **Lato** for body text (its warm neutrality mirrors Lucida Grande's role). Text often carries a subtle embossed quality via light text-shadow, reinforcing the skeuomorphic depth that defines the era.

**Text styles**:
- `display-xl` — Nunito, 96px, weight 800, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Nunito, 64px, weight 700, line-height 1.1, letter-spacing -0.02em
- `heading-1` — Nunito, 48px, weight 700, line-height 1.2, letter-spacing -0.02em
- `body-lg` — Lato, 18px, weight 400, line-height 1.625, letter-spacing 0
- `body-md` — Lato, 16px, weight 400, line-height 1.5, letter-spacing 0
- `caption` — Lato, 12px, weight 400, line-height 1.5, letter-spacing 0.05em
- `mono-md` — SF Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout

- Base unit: 4px
- Scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128
- Container max-widths: 640 / 768 / 1024 / 1280px
- Section padding: 32px (sm) → 128px (xl) — generous vertical breathing room
- Grid gap: 8–48px, scaling with container size
- Rhythm: 4px grid for all spacing decisions

## Elevation & Depth

Aqua is defined by its illusion of physical depth. Every surface exists in a layered space: backgrounds sit behind translucent panels, which sit behind glossy interactive elements. This depth is achieved through a combination of techniques — outer drop shadows tinted blue (not black), inner white highlight borders simulating light catching a glassy edge, and subtle backdrop-blur for translucent surfaces. The result feels like peering through layers of tinted glass.

- Surface style: Glass — semi-transparent white backgrounds with backdrop-blur
- Blur: 12px backdrop-blur on card and panel surfaces
- Shadow ladder: xs → 2xl, all tinted with primary blue (rgba of #1e6dd0) rather than neutral black
- Inner highlights: inset 0 1px 0 rgba(255,255,255,0.4–0.8) on elevated elements
- Focus state: 3px aqua-blue glow ring (rgba(109,179,242,0.45))

## Shapes

- Buttons: full pill radius (9999px) — the defining Aqua shape
- Cards: 16px radius — generously rounded but not capsular
- Inputs: 12px radius — softer than modern defaults
- Small elements (badges, chips): 8px radius
- Modals/dialogs: 16–24px radius
- No sharp 90° corners anywhere in the system

## Motion

Aqua was theatrical in its motion — the Genie effect, the pulsing default button, the bouncing dock icons. This system channels that lively personality with spring-based easings and playful hover responses, while remaining usable. Motion exists to delight, not distract: every animation reinforces the illusion that interface elements are physical, glossy objects responding to touch.

- Level: Lively
- Durations: instant 0ms / fast 120ms / normal 250ms / slow 400ms / slower 600ms
- Default easing: cubic-bezier(0.4, 0, 0.2, 1) — smooth deceleration
- Spring easing: cubic-bezier(0.34, 1.56, 0.64, 1) — slight overshoot for bouncy feel
- Hover patterns: lift (translateY -2px), glow (blue shadow expansion), scale (1.02–1.05)
- Reduced motion: respected, falls back to opacity-only transitions

## Techniques

### Aqua Glossy Pill Button

The signature Aqua button: a vertical gradient from highlight to depth with an inner white shine line, creating the illusion of a liquid-filled capsule catching light from above.

```css
.aqua-button {
  background: linear-gradient(180deg, #6db3f2 0%, #1e6dd0 100%);
  border: 1px solid #1a5bb0;
  border-radius: 9999px;
  box-shadow:
    0 2px 6px rgba(30, 109, 208, 0.3),
    inset 0 1px 0 rgba(255, 255, 255, 0.4);
  color: #ffffff;
  font-weight: 700;
  padding: 8px 24px;
  text-shadow: 0 -1px 0 rgba(0, 0, 0, 0.15);
  transition: all 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.aqua-button:hover {
  background: linear-gradient(180deg, #85c1f5 0%, #2578da 100%);
  box-shadow:
    0 4px 10px rgba(30, 109, 208, 0.4),
    inset 0 1px 0 rgba(255, 255, 255, 0.5);
  transform: translateY(-1px);
}
```

### Pinstripe Background

The subtle vertical-striped texture that appeared behind every Mac OS X Aqua window, recreated with a 1px repeating gradient.

```css
.pinstripe-bg {
  background-color: #fafdff;
  background-image: repeating-linear-gradient(
    90deg,
    transparent,
    transparent 1px,
    rgba(109, 179, 242, 0.04) 1px,
    rgba(109, 179, 242, 0.04) 2px
  );
}
```

### Glassy Translucent Card

A semi-transparent surface with backdrop-blur and inner highlight that simulates the layered glass panels of Aqua window chrome.

```css
.glass-card {
  background: rgba(255, 255, 255, 0.85);
  backdrop-filter: blur(12px);
  -webkit-backdrop-filter: blur(12px);
  border: 1px solid rgba(203, 213, 225, 0.5);
  border-radius: 16px;
  box-shadow:
    0 4px 12px rgba(30, 109, 208, 0.08),
    inset 0 1px 0 rgba(255, 255, 255, 0.7);
  padding: 24px;
  transition: all 250ms cubic-bezier(0.4, 0, 0.2, 1);
}
.glass-card:hover {
  box-shadow:
    0 8px 20px rgba(30, 109, 208, 0.14),
    inset 0 1px 0 rgba(255, 255, 255, 0.8);
  transform: translateY(-2px);
}
```

## Iconography

Icons in Aqua are filled and rounded, reflecting the system's emphasis on friendly, tangible objects. The original Mac OS X icons were richly detailed 3D renderings — photo-realistic mail stamps, glossy folder icons, shimmering CD discs. This system uses Lucide icons with filled treatment and 1.5px stroke for a modern interpretation that retains the warmth and approachability of the original icon language.

- Treatment: Filled
- Set: Lucide
- Stroke: 1.5px

## Do's & Don'ts

### ✓ Do
- Use pill-shaped buttons with vertical candy-blue gradients for all primary actions
- Add inner white highlight (inset 0 1px 0 rgba(255,255,255,0.4)) to every elevated surface
- Keep backgrounds bright — near-white with the faintest blue tint
- Use generous border-radius everywhere (12–24px cards, full pill buttons)
- Apply blue-tinted shadows instead of neutral gray/black shadows

### ✗ Don't
- Use flat design — Aqua is defined by its glossy gradients and depth
- Apply brutalist or raw aesthetics — Aqua is polished and friendly
- Use muted earth tones — the palette is candy-bright and cool-blue
- Use sharp 90° corners anywhere — every edge should be rounded
- Use serif fonts — Apple's Aqua era was exclusively humanist sans-serif
- Apply dark mode treatments — Aqua is sun-bright and daylit

## Applications

Y2K Aqua 2000 is ideal for nostalgic landing pages, personal portfolio sites that celebrate early-2000s web culture, and playful product interfaces that want to evoke warmth and approachability. It works beautifully for music players, media browsers, and creative tool interfaces — anywhere the glossy, tactile quality of physical objects enhances the user experience. It is also a natural fit for retro-themed marketing campaigns and Y2K revival projects.
