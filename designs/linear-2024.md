---
version: 1

meta:
  id: linear-2024
  name: Linear 2024
  description: Near-black, violet-accented dev-tool minimalism with surgical typographic precision
  isDark: true
  tags: [modernist, minimal, tech, professional, editorial]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2019 founded; current visual language stabilized ~2022–2024"
  region: "San Francisco, California (remote-first; Finnish founders)"
  regionZh: "美国旧金山（远程优先；芬兰裔创始人）"
  keyFigures: [Karri Saarinen, Tuomas Artman, Aaron Iker]
  movements: [Swiss typography, Dev-tool minimalism, Dark-mode-first design]

introduction: |
  Linear is a project-management tool that became the design benchmark for "dev-tool aesthetic" in 2024. Founded by former Airbnb design-system lead Karri Saarinen and engineer Tuomas Artman, its interface pairs a near-black background with restrained indigo-violet accents, Inter Display typography, and animations timed to the millisecond.

  The result is an interface of extreme precision — no decoration, no gradients on UI surfaces, no wasted pixels. Linear proved that density and elegance are not opposing forces, and its visual language has been widely imitated across the SaaS landscape.
introductionZh: |
  Linear 是一款项目管理工具，到 2024 年已成为"开发者工具美学"的设计标杆。由前 Airbnb 设计系统负责人 Karri Saarinen 与工程师 Tuomas Artman 在旧金山联合创立，其界面以近乎纯黑的背景搭配克制的靛紫色点缀、Inter Display 字体排版，以及精确到毫秒的动效。

  最终呈现的是一个极致精密的界面——没有装饰、没有渐变、没有一个多余的像素。Linear 证明了信息密度与优雅可以共存，其视觉语言在整个 SaaS 行业被广泛效仿。

colors:
  primary:
    "50": "#eceefb"
    "100": "#d5d8f5"
    "200": "#abb2eb"
    "300": "#828be1"
    "400": "#7078d9"
    "500": "#5e6ad2"
    "600": "#4b55a8"
    "700": "#3d4589"
    "800": "#2e346a"
    "900": "#20244b"
    "950": "#141631"
  secondary:
    "50": "#eef0f6"
    "100": "#d6dae6"
    "200": "#adb5cd"
    "300": "#8490b4"
    "400": "#6b779f"
    "500": "#4e5a82"
    "600": "#3e4868"
    "700": "#333b56"
    "800": "#282e43"
    "900": "#1c2030"
    "950": "#11141f"
  accent:
    "50": "#eceefb"
    "100": "#d5d8f5"
    "200": "#abb2eb"
    "300": "#828be1"
    "400": "#7078d9"
    "500": "#5e6ad2"
    "600": "#4b55a8"
    "700": "#3d4589"
    "800": "#2e346a"
    "900": "#20244b"
    "950": "#141631"
  neutral:
    "50": "#f7f7f8"
    "100": "#ebebed"
    "200": "#d1d1d5"
    "300": "#a8a8af"
    "400": "#7c7c85"
    "500": "#56565e"
    "600": "#3e3e44"
    "700": "#2c2c31"
    "800": "#1c1d1f"
    "900": "#111213"
    "950": "#08090a"
  semantic:
    success: { bg: "#2da44e", text: "#ffffff", light: "#132a1c", border: "#238c3f" }
    warning: { bg: "#d29922", text: "#ffffff", light: "#2a2110", border: "#b58318" }
    error:   { bg: "#cf222e", text: "#ffffff", light: "#2a1215", border: "#b01c25" }
    info:    { bg: "#5e6ad2", text: "#ffffff", light: "#181a2a", border: "#4b55a8" }
  background:
    page:    "#08090a"
    surface: "#111213"
    subtle:  "#1c1d1f"
  text:
    primary:   "#f7f7f8"
    secondary: "#a8a8af"
    muted:     "#56565e"
    inverse:   "#08090a"

typography:
  families:
    heading: "'Inter Display', 'Inter', -apple-system, BlinkMacSystemFont, sans-serif"
    body:    "'Inter', -apple-system, BlinkMacSystemFont, sans-serif"
    mono:    "'JetBrains Mono', 'IBM Plex Mono', 'Consolas', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500;700&display=swap"
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
  lineHeights: { tight: 1.15, snug: 1.3, normal: 1.5, relaxed: 1.625, loose: 1.8 }
  letterSpacing: { tighter: "-0.04em", tight: "-0.02em", normal: "-0.01em", wide: "0.05em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      { sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:        { sm: "8px",  md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "4px", md: "6px", lg: "8px", xl: "12px", full: "9999px" }
  color:  { default: "#1c1d1f", subtle: "#15161a", strong: "#2c2c31", focus: "#5e6ad2" }
  width:  { thin: "1px", default: "1px", thick: "2px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(0,0,0,0.2)"
  sm: "0 2px 4px rgba(0,0,0,0.2)"
  md: "0 4px 8px rgba(0,0,0,0.24)"
  lg: "0 8px 16px rgba(0,0,0,0.28)"
  xl: "0 12px 24px rgba(0,0,0,0.32)"
  2xl: "0 24px 48px rgba(0,0,0,0.40)"
  inner: "inset 0 1px 2px rgba(0,0,0,0.12)"
  focus: "0 0 0 3px rgba(94,106,210,0.4)"

motion:
  level: "restrained"
  durations: { instant: "0ms", fast: "100ms", normal: "200ms", slow: "350ms", slower: "500ms" }
  easings:
    default: "cubic-bezier(0.25, 0.1, 0.25, 1)"
    in:      "cubic-bezier(0.42, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.58, 1)"
    spring:  "cubic-bezier(0.34, 1.3, 0.64, 1)"
  hoverPatterns: [opacity, tint, lift]
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
  stroke:    "1.5px"

components:
  button:
    primary:   { background: "#5e6ad2", color: "#ffffff", border: "none", shadow: "none", hoverBackground: "#4b55a8", hoverShadow: "none", hoverColor: "#ffffff" }
    secondary: { background: "rgba(255,255,255,0.06)", color: "#f7f7f8", border: "1px solid #1c1d1f", shadow: "none", hoverBackground: "rgba(255,255,255,0.10)", hoverShadow: "none", hoverColor: "#ffffff" }
    ghost:     { background: "transparent", color: "#a8a8af", border: "none", shadow: "none", hoverBackground: "rgba(255,255,255,0.06)", hoverShadow: "none", hoverColor: "#f7f7f8" }
    danger:    { background: "#cf222e", color: "#ffffff", border: "none", shadow: "none", hoverBackground: "#b01c25", hoverShadow: "none", hoverColor: "#ffffff" }
    sizes:
      sm: { height: "28px", padding: "0 10px", fontSize: "0.8125rem" }
      md: { height: "32px", padding: "0 14px", fontSize: "0.875rem" }
      lg: { height: "40px", padding: "0 20px", fontSize: "0.9375rem" }
    borderRadius: "6px"
    fontWeight: 500
    letterSpacing: "-0.01em"
    textTransform: "none"
  input:
    background: "#15161a"
    color: "#f7f7f8"
    border: "1px solid #1c1d1f"
    borderRadius: "4px"
    padding: "6px 10px"
    focusBorder: "1px solid #5e6ad2"
    placeholderColor: "#56565e"
  card:
    base:  { background: "#111213", border: "1px solid #1c1d1f", borderRadius: "8px", padding: "16px", shadow: "none" }
    hover: { shadow: "0 1px 2px rgba(0,0,0,0.2)", transform: "none" }
---

# Linear 2024

> Surgical dark-mode minimalism — near-black backgrounds, indigo-violet accents, and typographic precision that defined dev-tool aesthetic in 2024.

## Origin

Linear launched in 2019 as a modern issue tracker built by Karri Saarinen and Tuomas Artman, both Finnish expats in San Francisco. Saarinen, who had previously led Airbnb's design system, brought an obsessive attention to typographic detail and spacing. Artman, an engineer, ensured the interface matched the performance expectations of its developer audience. The product was born from frustration with Jira's bloat and the belief that project management software should feel as fast and precise as a code editor.

By 2022, Linear's visual language had crystallized into what the industry now calls "Linear-like" design: a near-black canvas (#08090a), a single indigo-violet accent (#5e6ad2), Inter Display headings at medium weight, and animations timed with Aaron Iker-inspired precision. The aesthetic proved so influential that competitors and unrelated SaaS products — Vercel, Resend, Cal.com — adopted the same dark, tight-grid, border-over-shadow vocabulary through 2023 and 2024.

## Overview

Composition cues:
- **Layout**: Tight CSS grid layouts with precise 4px/8px alignment; sidebar-plus-content panels
- **Content width**: Container-bound (max ~1280px) with generous negative space
- **Framing**: Bordered — near-invisible 1px borders (#1c1d1f) separate surfaces; no frosted glass, no blurred panels
- **Grid intensity**: Strong — every element snaps to a strict spatial grid; asymmetric but deliberate

## Colors

Linear's color philosophy is extreme restraint. The near-black background #08090a (never pure #000, which is too harsh) provides a quiet canvas. Text sits at #f7f7f8 — not pure white either, softened just enough to reduce contrast fatigue during long sessions. The sole accent is Linear's signature indigo-violet #5e6ad2, deployed only for primary actions, active states, and brand moments. Everything else is grayscale: row separators at #1c1d1f, secondary surfaces at #111213, muted text at #56565e. The palette is so monochromatic that any color at all — a green success badge, a red error state — feels like an event.

**Role usage**:
- Page background → `colors.background.page` (#08090a)
- Card / panel surfaces → `colors.background.surface` (#111213)
- Input fills / subtle surfaces → `colors.background.subtle` (#1c1d1f)
- Primary actions & active states → `colors.primary.500` (#5e6ad2)
- Primary text → `colors.text.primary` (#f7f7f8)
- Secondary / label text → `colors.text.secondary` (#a8a8af)
- Row separators & borders → `colors.neutral.800` (#1c1d1f)
- Focus rings → indigo at 40% opacity

## Typography

Linear's type voice is quiet authority. Inter Display at medium weight (500–600) handles headings — generously sized but never heavy or bold, with tight letter-spacing (-0.02em) that gives headlines a composed, editorial feel. Body text uses Inter at regular weight with subtle negative tracking (-0.01em), a detail that tightens paragraph texture without feeling cramped. Monospaced data — issue IDs, commit hashes, code references — appears in JetBrains Mono at 13–14px, maintaining the engineering-tool identity. There are no display-size headlines screaming for attention; even the largest marketing text stays measured and controlled.

**Text styles**:
- `display-xl` — Inter Display, 72px, weight 600, line-height 1.05, letter-spacing -0.04em
- `display-lg` — Inter Display, 56px, weight 600, line-height 1.1, letter-spacing -0.03em
- `heading-1` — Inter Display, 32px, weight 500, line-height 1.2, letter-spacing -0.02em
- `body-lg` — Inter, 16px, weight 400, line-height 1.5, letter-spacing -0.01em
- `body-md` — Inter, 14px, weight 400, line-height 1.5, letter-spacing -0.01em
- `caption` — Inter, 12px, weight 500, line-height 1.3, letter-spacing 0
- `mono-md` — JetBrains Mono, 13px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout

- Base unit: 4px; primary rhythm at 4px multiples (Linear is tighter than 8px-base systems)
- Spacing scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128
- Container max-widths: 640 / 768 / 1024 / 1280px
- Section padding: 32px (mobile) → 64px (tablet) → 96px (desktop) → 128px (hero)
- Grid gaps: 8px (tight lists) / 16px (standard) / 24px (cards) / 48px (section grids)
- Sidebar width: typically 220–240px, content fills remaining space

## Elevation & Depth

Linear achieves hierarchy through borders and background-color stepping, not shadows. The page sits at #08090a, surfaces rise to #111213, and interactive areas step up to #15161a or #1c1d1f. Borders at #1c1d1f — barely visible against the dark canvas — delineate cards, table rows, and panels. Shadows are nearly absent from the UI; when they do appear (dropdowns, command palette), they're minimal and dark-on-dark. The overall effect is a flat, print-like surface where spatial relationships are implied by tone, not elevation.

- Surface style: flat — no glass, no layering effects
- Primary depth cue: background-color stepping (3–4 tiers of near-black)
- Borders preferred over shadows for all surface separation
- Shadow usage: reserved for floating overlays (command palette, dropdowns)
- Shadow intensity: very soft — 0 1px 2px rgba(0,0,0,0.2) at most

## Shapes

- Button border-radius: 6px (tight rounded rectangle)
- Card / panel border-radius: 8px
- Input border-radius: 4px (tighter than cards, more utilitarian)
- Avatar border-radius: 9999px (full circle)
- Small elements (badges, status dots): 4px
- Large containers (modals, sheets): 12px

## Motion

Linear's motion is restrained and precise — every animation serves a purpose, none exist for decoration. Transitions are fast (100–200ms), eased with a subtle deceleration curve that feels crisp rather than bouncy. The command palette opens with a quick fade-scale; sidebar items highlight with an instant opacity change; focus rings appear without transition. This is the motion vocabulary of a precision instrument: responsive, quiet, invisible when working well. Aaron Iker's influence shows in the timing curves — technically perfect but emotionally neutral.

- Level: restrained
- Fast interactions (hover, focus): 100ms
- Standard transitions (panel switch, dropdown open): 200ms
- Emphasized animations (command palette, page transition): 350ms
- Easing: smooth deceleration default; no bounce or overshoot
- Hover patterns: opacity (menu items dim/brighten), tint (violet wash on interactive elements), lift (subtle translateY -1px on cards)

## Techniques

### Radial Glow Accent

Linear's marketing pages use a subtle radial gradient glow behind hero sections — a violet-to-transparent bloom that provides atmospheric depth without decorating the UI surface itself.

```css
.radial-glow {
  position: absolute;
  inset: 0;
  background: radial-gradient(
    ellipse 60% 50% at 50% 0%,
    rgba(94, 106, 210, 0.15) 0%,
    rgba(94, 106, 210, 0.05) 40%,
    transparent 70%
  );
  pointer-events: none;
}
```

### Near-Invisible Border Row

Linear's signature list rows use borders so faint they're almost subliminal — just enough to separate items without creating visual noise. The border color matches the subtle background tier.

```css
.list-row {
  display: flex;
  align-items: center;
  padding: 6px 12px;
  border-bottom: 1px solid #1c1d1f;
  transition: background-color 100ms ease;
}

.list-row:hover {
  background-color: rgba(255, 255, 255, 0.03);
}

.list-row:last-child {
  border-bottom: none;
}
```

### Command Palette Overlay

Linear's ⌘K command palette — a dark, centered modal with a search input and instant-filter results, the signature interaction pattern of the app.

```css
.command-palette {
  position: fixed;
  top: 20%;
  left: 50%;
  transform: translateX(-50%);
  width: 560px;
  max-height: 420px;
  background: #111213;
  border: 1px solid #1c1d1f;
  border-radius: 12px;
  box-shadow: 0 16px 48px rgba(0, 0, 0, 0.5);
  overflow: hidden;
  animation: palette-in 150ms cubic-bezier(0.25, 0.1, 0.25, 1);
}

.command-palette input {
  width: 100%;
  padding: 14px 16px;
  background: transparent;
  border: none;
  border-bottom: 1px solid #1c1d1f;
  color: #f7f7f8;
  font-size: 15px;
  font-family: 'Inter', sans-serif;
  outline: none;
}

@keyframes palette-in {
  from { opacity: 0; transform: translateX(-50%) scale(0.98); }
  to   { opacity: 1; transform: translateX(-50%) scale(1); }
}
```

## Iconography

Linear uses thin, linear-stroke icons — clean and geometric with a 1.5px stroke weight that reads crisply at small sizes against dark backgrounds. The icon language is purely functional: status indicators, navigation markers, action triggers. No illustrative or decorative icons exist in the product — every icon is a tool, not an ornament.

- Treatment: linear, 1.5px stroke
- Set: Lucide (closest match to Linear's custom set)
- Sizes: 16px (inline/table), 20px (toolbar/sidebar), 24px (navigation)

## Do's & Don'ts

### ✓ Do
- Use Linear violet #5e6ad2 exclusively for primary actions and interactive focus states
- Keep the background at #08090a — never pure black, never lighter than near-black
- Use Inter Display at medium weight (500–600) for headings, not bold
- Prefer borders over shadows for surface separation
- Maintain 4px-grid precision — every measurement should be a multiple of 4

### ✗ Don't
- Use pure black #000 as a background (too harsh, anti-Linear)
- Apply decorative gradients to UI surfaces (radial glow is for marketing only)
- Introduce loud accent colors beyond the violet family
- Use heavy shadows or any skeuomorphic depth effects
- Set wide letter-spacing on body text (Linear tracks tight, not loose)

## Applications

Linear 2024 is the definitive template for developer tools, internal dashboards, and SaaS products that want to project technical sophistication. The near-black palette with surgical violet accents works exceptionally well for data-dense interfaces — issue trackers, code review tools, analytics dashboards, CI/CD platforms — where information density must coexist with visual calm. It also suits marketing sites for technical products that want to signal "we are the tool that engineers choose for themselves."
