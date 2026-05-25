---
version: 1

meta:
  id: apple-liquid-glass-2024
  name: "Apple Liquid Glass 2024"
  description: "Translucent layered glass surfaces with backdrop blur, specular highlights, and pastel tints on cosmic dark grounds"
  isDark: true
  tags: [tech, friendly, decorative, futuristic, luxurious]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2023 (Vision Pro announcement) — current; visionOS 1.0 shipped Feb 2024"
  region: "Cupertino, California"
  regionZh: "美国加利福尼亚州库比蒂诺"
  keyFigures: ["Alan Dye", "Apple Human Interface Team"]
  movements: ["Post-flat skeuomorphism", "Spatial computing UI", "Glassmorphism"]

introduction: |
  Apple's Liquid Glass is the visual language born from visionOS and the Apple Vision Pro — a spatial operating system where translucent, layered surfaces float in three-dimensional space. After a decade of flat design following iOS 7, Liquid Glass marks Apple's return to depth: panels of frosted glass with backdrop blur, specular highlights that shift with perspective, and muted pastel tints drawn from the user's environment. It is skeuomorphism reimagined for the spatial era.

  The design vocabulary builds on Apple's deep heritage — from the candy-gloss Aqua interface of Mac OS X to the refined translucency of iOS widgets — but pushes into territory inspired by cinematic sci-fi HUDs and architectural glass. Every surface breathes: light passes through, backgrounds shimmer beneath, and depth becomes a first-class design material.
introductionZh: |
  液态玻璃（Liquid Glass）是苹果为 visionOS 和 Apple Vision Pro 打造的全新视觉语言——在空间计算的世界里，半透明的毛玻璃面板悬浮于三维空间之中。经历了 iOS 7 以来长达十年的扁平化设计之后，苹果重新拥抱了深度与层次：磨砂玻璃质感的面板搭配背景模糊、随视角变化的高光反射，以及从用户环境中提取的柔和粉彩色调。这是为空间时代重新诠释的拟物设计。

  这套设计体系根植于苹果深厚的设计传统——从 Mac OS X 时代晶莹剔透的 Aqua 界面，到 iOS 控件的精致半透明效果——但同时也从科幻电影的全息界面和建筑玻璃幕墙中汲取灵感。每一个界面元素都在呼吸：光线穿透表面，背景在下方微微闪烁，深度本身成为了设计的核心材质。

colors:
  primary:
    "50": "#eafaff"
    "100": "#cff3ff"
    "200": "#a5ebff"
    "300": "#7ae2ff"
    "400": "#5cd9ff"
    "500": "#5cd9ff"
    "600": "#42b8e0"
    "700": "#2e97bd"
    "800": "#1f7699"
    "900": "#145876"
    "950": "#0a3a52"
  secondary:
    "50": "#fff7eb"
    "100": "#ffedd1"
    "200": "#ffdda8"
    "300": "#ffcb7e"
    "400": "#ffb959"
    "500": "#ffb959"
    "600": "#e09a3a"
    "700": "#bd7c22"
    "800": "#995f15"
    "900": "#76450d"
    "950": "#522e06"
  accent:
    "50": "#eefcf4"
    "100": "#d4f7e3"
    "200": "#b6f0cf"
    "300": "#a0e0c0"
    "400": "#a0e0c0"
    "500": "#a0e0c0"
    "600": "#6ec09a"
    "700": "#4a9e78"
    "800": "#327c5a"
    "900": "#215c41"
    "950": "#133d2b"
  neutral:
    "50": "#f0f2f5"
    "100": "#dde1e8"
    "200": "#bcc3d0"
    "300": "#99a3b5"
    "400": "#78849a"
    "500": "#5c6880"
    "600": "#495367"
    "700": "#38404f"
    "800": "#272d39"
    "900": "#181c25"
    "950": "#0c0f14"
  semantic:
    success: { bg: "#0d3b2a", text: "#a0e0c0", light: "#1a5c42", border: "#2e7a58" }
    warning: { bg: "#3b2e0d", text: "#ffb959", light: "#5c4a1a", border: "#7a6a2e" }
    error:   { bg: "#3b0d18", text: "#ff6b8a", light: "#5c1a2e", border: "#7a2e42" }
    info:    { bg: "#0d2a3b", text: "#5cd9ff", light: "#1a425c", border: "#2e5a7a" }
  background:
    page:    "#050a14"
    surface: "rgba(255,255,255,0.08)"
    subtle:  "rgba(255,255,255,0.04)"
  text:
    primary:   "#f0f2f5"
    secondary: "#99a3b5"
    muted:     "#5c6880"
    inverse:   "#050a14"

typography:
  families:
    heading: "'Inter Display', 'Inter', -apple-system, BlinkMacSystemFont, sans-serif"
    body:    "'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif"
    mono:    "'SF Mono', 'JetBrains Mono', 'Fira Code', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&display=swap"
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
  letterSpacing: { tighter: "-0.04em", tight: "-0.02em", normal: "0", wide: "0.05em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      { sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:        { sm: "8px",  md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "8px", md: "16px", lg: "24px", xl: "32px", full: "9999px" }
  color:  { default: "rgba(255,255,255,0.12)", subtle: "rgba(255,255,255,0.06)", strong: "rgba(255,255,255,0.20)", focus: "rgba(92,217,255,0.5)" }
  width:  { thin: "1px", default: "1px", thick: "2px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "0 1px 3px rgba(0,0,0,0.3)"
  sm: "0 2px 6px rgba(0,0,0,0.35)"
  md: "0 4px 16px rgba(0,0,0,0.4)"
  lg: "0 8px 32px rgba(0,0,0,0.45)"
  xl: "0 16px 48px rgba(0,0,0,0.5)"
  "2xl": "0 24px 64px rgba(0,0,0,0.6)"
  inner: "inset 0 1px 1px rgba(255,255,255,0.08)"
  focus: "0 0 0 3px rgba(92,217,255,0.4)"

motion:
  level: "restrained"
  durations: { instant: "0ms", fast: "120ms", normal: "250ms", slow: "400ms", slower: "600ms" }
  easings:
    default: "cubic-bezier(0.25, 0.1, 0.25, 1.0)"
    in:      "cubic-bezier(0.42, 0, 1.0, 1.0)"
    out:     "cubic-bezier(0, 0, 0.58, 1.0)"
    spring:  "cubic-bezier(0.34, 1.56, 0.64, 1.0)"
  hoverPatterns: ["lift", "glow", "scale"]
  reducedMotion: true

composition:
  layout:        "stack"
  contentWidth:  "container"
  framing:       "glassy"
  gridIntensity: "soft"
  rhythm:        "8px"

surfaceStyle: "glass"
blur:         "20px"

iconography:
  treatment: "linear"
  set:       "lucide"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "1.5px"

components:
  button:
    primary:
      background: "rgba(92,217,255,0.2)"
      color: "#5cd9ff"
      border: "1px solid rgba(92,217,255,0.3)"
      shadow: "0 2px 8px rgba(92,217,255,0.15)"
      hoverBackground: "rgba(92,217,255,0.3)"
      hoverShadow: "0 4px 16px rgba(92,217,255,0.25)"
      hoverColor: "#ffffff"
    secondary:
      background: "rgba(255,255,255,0.08)"
      color: "#f0f2f5"
      border: "1px solid rgba(255,255,255,0.12)"
      shadow: "none"
      hoverBackground: "rgba(255,255,255,0.14)"
      hoverShadow: "0 2px 8px rgba(255,255,255,0.08)"
      hoverColor: "#ffffff"
    ghost:
      background: "transparent"
      color: "#99a3b5"
      border: "1px solid transparent"
      shadow: "none"
      hoverBackground: "rgba(255,255,255,0.06)"
      hoverShadow: "none"
      hoverColor: "#f0f2f5"
    danger:
      background: "rgba(255,107,138,0.15)"
      color: "#ff6b8a"
      border: "1px solid rgba(255,107,138,0.25)"
      shadow: "none"
      hoverBackground: "rgba(255,107,138,0.25)"
      hoverShadow: "0 4px 16px rgba(255,107,138,0.2)"
      hoverColor: "#ffffff"
    sizes:
      sm: { height: "32px", padding: "0 14px", fontSize: "0.8125rem" }
      md: { height: "40px", padding: "0 20px", fontSize: "0.875rem" }
      lg: { height: "48px", padding: "0 28px", fontSize: "1rem" }
    borderRadius: "9999px"
    fontWeight: 500
    letterSpacing: "0.02em"
    textTransform: "none"
  input:
    background: "rgba(255,255,255,0.06)"
    color: "#f0f2f5"
    border: "1px solid rgba(255,255,255,0.10)"
    borderRadius: "16px"
    padding: "10px 16px"
    focusBorder: "rgba(92,217,255,0.5)"
    placeholderColor: "#5c6880"
  card:
    base:
      background: "rgba(255,255,255,0.08)"
      border: "1px solid rgba(255,255,255,0.12)"
      borderRadius: "24px"
      padding: "24px"
      shadow: "0 8px 32px rgba(0,0,0,0.4)"
    hover:
      shadow: "0 16px 48px rgba(0,0,0,0.5)"
      transform: "translateY(-2px)"
---

# Apple Liquid Glass 2024

> Translucent depth-layered glass surfaces floating on cosmic dark grounds — Apple's post-flat return to skeuomorphism for the spatial computing era.

## Origin

Apple's Liquid Glass visual language emerged with visionOS, the operating system powering Apple Vision Pro, announced at WWDC 2023 and shipped in February 2024. Led by Alan Dye and the Apple Human Interface Design team in Cupertino, it represents the most significant shift in Apple's design direction since Jony Ive's flat redesign of iOS 7 in 2013. The language draws from Apple's own skeuomorphic heritage — the glossy Aqua interface of Mac OS X (2001), the refined translucency of Apple Watch complications — as well as cinematic sci-fi HUD design and real architectural glass.

Liquid Glass turns depth into a first-class design material. Instead of flat cards on flat backgrounds, every panel is a translucent pane: content floats on layers of frosted glass, light bleeds through from behind, and specular highlights shift as though the interface itself were a physical object catching light. The approach evolved beyond Vision Pro into iOS 17's Control Center and widgets, signaling that spatial-era thinking now permeates Apple's entire design philosophy.

## Overview
Composition cues:
- **Layout**: Stacked layers with clear z-depth hierarchy — content floats on glass panes above a deep ambient ground.
- **Content width**: Container-bound (1024–1280px) with generous padding; panels never feel cramped.
- **Framing**: Glassy — every container is a translucent surface with backdrop blur, inner highlight, and soft drop shadow.
- **Grid intensity**: Soft — loose grid with generous gaps; spatial breathing room over density.

## Colors
Liquid Glass draws its palette from the interplay of light through translucent surfaces. The base ground is a near-black cosmic blue (#050a14), upon which soft pastel radial-gradient orbs — sky blue, amber, sage — create an ambient atmosphere. Surface colors are never opaque; they are white at 4–12% opacity, allowing the environment to bleed through. Text is cool neutral white, and accent colors are deliberately muted pastels: colors you might see refracted through architectural glass, never saturated or harsh.

**Role usage**:
- Page background → `colors.background.page` (#050a14 with ambient gradient orbs)
- Glass panel surface → `colors.background.surface` (rgba white at 0.08)
- Primary action / link → `colors.primary.500` (#5cd9ff sky blue)
- Secondary accent → `colors.secondary.500` (#ffb959 warm amber)
- Tertiary accent → `colors.accent.500` (#a0e0c0 sage green)
- Body text → `colors.text.primary` (#f0f2f5)
- Muted / caption text → `colors.text.muted` (#5c6880)
- Borders on glass → `borders.color.default` (rgba white at 0.12)

## Typography
The typographic voice is clean, modern, and spacious — the voice of an interface that never shouts. Inter Display serves as the heading face (standing in for Apple's proprietary SF Pro Display), with generous negative tracking at display sizes that gives headlines an airy, expansive quality. Inter Regular handles body copy with comfortable line heights. The overall impression is clinical precision softened by generous whitespace — text that breathes, never crowds.

**Text styles**:
- `display-xl` — Inter Display, 96px, weight 700, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Inter Display, 64px, weight 700, line-height 1.05, letter-spacing -0.03em
- `heading-1` — Inter Display, 48px, weight 600, line-height 1.1, letter-spacing -0.02em
- `heading-2` — Inter Display, 36px, weight 600, line-height 1.15, letter-spacing -0.02em
- `body-lg` — Inter, 18px, weight 400, line-height 1.625, letter-spacing 0
- `body-md` — Inter, 16px, weight 400, line-height 1.5, letter-spacing 0
- `caption` — Inter, 13px, weight 400, line-height 1.4, letter-spacing 0.02em
- `mono-md` — SF Mono / JetBrains Mono, 14px, weight 400, line-height 1.6, letter-spacing 0

## Spacing & Layout
- Base unit: 8px rhythm — all spacing snaps to multiples of 8.
- Scale: 4, 8, 12, 16, 24, 32, 48, 64, 96, 128px.
- Container max-width: 1280px centered with 24–48px side padding.
- Section vertical padding: 64–128px — generous breathing room between sections.
- Grid gap: 16–24px between glass panels.
- Card internal padding: 24–32px.

## Elevation & Depth
Liquid Glass treats depth as a tangible material. The cosmic ground plane sits deepest; ambient gradient orbs provide environmental color. Glass panels float above at varying z-levels — each distinguished by its blur intensity, shadow depth, and border luminance. Higher surfaces have stronger drop shadows (up to 32px blur at 0.45 opacity), brighter inner highlights, and slightly more opaque backgrounds. The result feels volumetric: you can sense the space between layers.

- Surface base: `background: rgba(255,255,255,0.08)` with `backdrop-filter: blur(20px)`.
- Inner highlight: `inset 0 1px 1px rgba(255,255,255,0.08)` along top edge.
- Shadow ladder: xs (3px blur) → sm (6px) → md (16px) → lg (32px) → xl (48px) → 2xl (64px).
- Elevated surface: increase background alpha to 0.12, shadow to lg, blur to 24px.
- Focus ring: 3px spread, primary blue at 40% opacity.

## Shapes
- Card corners: 24px (Apple continuous-corner aesthetic).
- Button corners: 9999px (full pill shape).
- Input corners: 16px.
- Small elements (badges, tags): 8px.
- Modal / dialog corners: 32px.

## Motion
Liquid Glass moves with quiet confidence — restrained, never flashy. Transitions are smooth and physics-aware, with a slight spring quality that makes elements feel like they have weight. Hover states lift subtly and glow; they never snap. Everything decelerates naturally, as though settling into place in a spatial environment. Reduced-motion is always respected.

- Level: restrained — motion supports spatial understanding without drawing attention.
- Durations: fast interactions 120ms, standard transitions 250ms, dramatic reveals 400–600ms.
- Default easing: `cubic-bezier(0.25, 0.1, 0.25, 1.0)` — smooth deceleration.
- Spring easing: `cubic-bezier(0.34, 1.56, 0.64, 1.0)` — for elements entering view.
- Hover: lift (translateY -2px) + glow (shadow intensification) + subtle scale (1.01–1.02).
- Glass panels on scroll: subtle parallax shift between layers.

## Techniques

### Liquid Glass Panel
The foundational surface treatment: a translucent panel with backdrop blur, specular top-edge highlight, and layered shadow — the building block of every card, modal, and container.
```css
.liquid-glass-panel {
  background: rgba(255, 255, 255, 0.08);
  backdrop-filter: blur(20px);
  -webkit-backdrop-filter: blur(20px);
  border: 1px solid rgba(255, 255, 255, 0.12);
  border-radius: 24px;
  box-shadow:
    0 8px 32px rgba(0, 0, 0, 0.4),
    inset 0 1px 1px rgba(255, 255, 255, 0.08);
}
```

### Cosmic Ambient Ground
The deep-space background with soft pastel orbs that provide environmental color bleeding through glass surfaces.
```css
.cosmic-ground {
  background: #050a14;
  position: relative;
  overflow: hidden;
}
.cosmic-ground::before {
  content: '';
  position: absolute;
  inset: 0;
  background:
    radial-gradient(ellipse 600px 400px at 20% 30%, rgba(92, 217, 255, 0.12), transparent),
    radial-gradient(ellipse 500px 500px at 70% 60%, rgba(255, 185, 89, 0.08), transparent),
    radial-gradient(ellipse 400px 300px at 50% 80%, rgba(160, 224, 192, 0.06), transparent);
  pointer-events: none;
}
```

### Specular Highlight Edge
A top-edge radial gradient simulating light catching the crown of a glass surface, adding dimensionality to flat panels.
```css
.specular-highlight {
  position: relative;
}
.specular-highlight::after {
  content: '';
  position: absolute;
  top: 0;
  left: 10%;
  right: 10%;
  height: 1px;
  background: radial-gradient(
    ellipse at center,
    rgba(255, 255, 255, 0.25) 0%,
    rgba(255, 255, 255, 0) 70%
  );
  pointer-events: none;
}
```

## Iconography
Icons follow Apple's preference for clean linear strokes — thin, precise, and optically balanced. They sit comfortably on translucent glass without visual noise. The Lucide set provides the closest open-source match to Apple's SF Symbols style: geometrically clean with consistent 1.5px stroke weight, optically centered, and legible at small sizes against blurred backgrounds.

- Treatment: linear (outline only, no fills).
- Set: Lucide (closest to SF Symbols aesthetic).
- Stroke: 1.5px, matching the lightweight feel of glass surfaces.

## Do's & Don'ts

### ✓ Do
- Use translucent glass panels with backdrop blur as the primary surface treatment.
- Maintain deep spatial hierarchy — let background orbs bleed through glass layers.
- Apply generous whitespace and padding; let content breathe in space.
- Use pill-shaped buttons with subtle glass tints for primary actions.
- Combine outer drop shadows with inner highlights for volumetric depth.

### ✗ Don't
- Use flat opaque card surfaces — they break the Liquid Glass illusion.
- Apply brutalist sharp corners — everything should feel soft and continuous.
- Use pure saturated colors — Liquid Glass filters all color through muted pastel glass.
- Introduce serif fonts — the voice is modern sans-serif only.
- Add heavy decorative patterns or textures — the glass surface is the texture.

## Applications
Liquid Glass is ideal for immersive dashboards, media-rich product showcases, portfolio sites, and any interface that benefits from a sense of spatial depth and premium polish. It excels in dark-mode-first applications where translucent layers can create atmospheric storytelling — think developer tools with ambient personality, music or media players, or landing pages that need to feel simultaneously futuristic and approachable. The style translates beautifully to spatial/VR interfaces and progressive web apps where the "window into depth" metaphor enhances user engagement.
