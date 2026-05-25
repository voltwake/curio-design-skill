---
version: 1

meta:
  id: spotify-dark
  name: Spotify Dark
  description: Pure black-on-green streaming interface — the canonical dark-mode music UI
  isDark: true
  tags: [tech, friendly, bold, minimal, modern]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2008 launched; signature green-on-black visual ~2010–2024"
  region: "Stockholm, Sweden"
  regionZh: "瑞典斯德哥尔摩"
  keyFigures: [Daniel Ek, Tobias Ahlin, Spotify Brand Team]
  movements: [Music streaming interfaces, Media-rich dark UI, Album-art-driven design]

introduction: |
  Spotify launched in 2008 from Stockholm and quickly defined what digital music looks like. Its visual identity — phosphor green #1db954 set against a near-black #121212 canvas — became the universal shorthand for "streaming app." The interface is built around album art as the primary visual element, with card-based grids, pill-shaped play buttons, and a restrained typographic system that keeps everything readable at a glance.

  The design system prioritizes content over chrome. Surfaces are flat and dark, typography is clean and unadorned, and the signature green appears only where interaction matters most: play buttons, progress bars, active states. Spotify Wrapped proved the brand's visual fluency extends beyond the app itself, turning data visualization into a shareable cultural moment every December.
introductionZh: |
  Spotify 于 2008 年在瑞典斯德哥尔摩诞生，迅速定义了数字音乐的视觉范式。其标志性的磷光绿 #1db954 搭配近黑色 #121212 画布，成为全球"流媒体应用"的视觉代名词。界面以专辑封面为核心视觉元素，卡片式网格布局、药丸形播放按钮和克制的字体系统让一切信息一目了然。

  这套设计体系始终将内容置于界面装饰之上——平坦的深色表面、干净的无衬线字体，标志性绿色只在最关键的交互节点出现：播放键、进度条、激活状态。每年十二月的 Spotify Wrapped 更证明了这套视觉语言的延展力，将个人数据可视化变成了一场全民社交狂欢。

colors:
  primary:
    "50": "#e6f9ef"
    "100": "#c2f0d8"
    "200": "#8ae4b4"
    "300": "#52d890"
    "400": "#2ecc77"
    "500": "#1db954"
    "600": "#18a348"
    "700": "#148c3d"
    "800": "#0f6e30"
    "900": "#0b5224"
    "950": "#073618"
  secondary:
    "50": "#f0f0f0"
    "100": "#e0e0e0"
    "200": "#c2c2c2"
    "300": "#a3a3a3"
    "400": "#858585"
    "500": "#535353"
    "600": "#474747"
    "700": "#3b3b3b"
    "800": "#2a2a2a"
    "900": "#1a1a1a"
    "950": "#121212"
  accent:
    "50": "#e6f9ef"
    "100": "#c2f0d8"
    "200": "#8ae4b4"
    "300": "#52d890"
    "400": "#2ecc77"
    "500": "#1db954"
    "600": "#18a348"
    "700": "#148c3d"
    "800": "#0f6e30"
    "900": "#0b5224"
    "950": "#073618"
  neutral:
    "50": "#f5f5f5"
    "100": "#e8e8e8"
    "200": "#d4d4d4"
    "300": "#b3b3b3"
    "400": "#8a8a8a"
    "500": "#6a6a6a"
    "600": "#535353"
    "700": "#404040"
    "800": "#2a2a2a"
    "900": "#181818"
    "950": "#121212"
  semantic:
    success: { bg: "#1db954", text: "#000000", light: "#0f2e1c", border: "#18a348" }
    warning: { bg: "#f59b23", text: "#000000", light: "#2e2210", border: "#d4861e" }
    error:   { bg: "#e22134", text: "#ffffff", light: "#2e1216", border: "#c41c2c" }
    info:    { bg: "#2e77d0", text: "#ffffff", light: "#121e2e", border: "#2566b3" }
  background:
    page:    "#121212"
    surface: "#181818"
    subtle:  "#282828"
  text:
    primary:   "#ffffff"
    secondary: "#b3b3b3"
    muted:     "#6a6a6a"
    inverse:   "#000000"

typography:
  families:
    heading: "'Plus Jakarta Sans', 'Inter', 'Manrope', -apple-system, BlinkMacSystemFont, sans-serif"
    body:    "'Plus Jakarta Sans', 'Inter', 'Manrope', -apple-system, BlinkMacSystemFont, sans-serif"
    mono:    "'JetBrains Mono', 'Fira Code', 'Consolas', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&family=JetBrains+Mono:wght@400;500;700&display=swap"
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
  lineHeights: { tight: 1.1, snug: 1.25, normal: 1.4, relaxed: 1.5, loose: 1.7 }
  letterSpacing: { tighter: "-0.04em", tight: "-0.02em", normal: "0", wide: "0.05em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      { sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:        { sm: "8px",  md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "4px", md: "6px", lg: "8px", xl: "12px", full: "9999px" }
  color:  { default: "#333333", subtle: "#282828", strong: "#535353", focus: "#1db954" }
  width:  { thin: "1px", default: "1px", thick: "2px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(0,0,0,0.3)"
  sm: "0 2px 4px rgba(0,0,0,0.3)"
  md: "0 4px 8px rgba(0,0,0,0.4)"
  lg: "0 8px 16px rgba(0,0,0,0.4)"
  xl: "0 12px 24px rgba(0,0,0,0.5)"
  2xl: "0 20px 40px rgba(0,0,0,0.6)"
  inner: "inset 0 1px 2px rgba(0,0,0,0.2)"
  focus: "0 0 0 3px rgba(29,185,84,0.4)"

motion:
  level: "restrained"
  durations: { instant: "0ms", fast: "120ms", normal: "250ms", slow: "400ms", slower: "600ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.4, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.2, 1)"
    spring:  "cubic-bezier(0.34, 1.2, 0.64, 1)"
  hoverPatterns: [scale, opacity, tint]
  reducedMotion: true

composition:
  layout:        "grid"
  contentWidth:  "full-bleed"
  framing:       "solid"
  gridIntensity: "soft"
  rhythm:        "8px"

surfaceStyle: "flat"
blur:         "none"

iconography:
  treatment: "outline"
  set:       "lucide"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "1.5px"

components:
  button:
    primary:   { background: "#1db954", color: "#000000", border: "none", shadow: "none", hoverBackground: "#1ed760", hoverShadow: "none", hoverColor: "#000000" }
    secondary: { background: "transparent", color: "#ffffff", border: "1px solid #727272", shadow: "none", hoverBackground: "transparent", hoverShadow: "none", hoverColor: "#ffffff" }
    ghost:     { background: "transparent", color: "#b3b3b3", border: "none", shadow: "none", hoverBackground: "rgba(255,255,255,0.07)", hoverShadow: "none", hoverColor: "#ffffff" }
    danger:    { background: "#e22134", color: "#ffffff", border: "none", shadow: "none", hoverBackground: "#f03241", hoverShadow: "none", hoverColor: "#ffffff" }
    sizes:
      sm: { height: "32px", padding: "0 16px", fontSize: "0.875rem" }
      md: { height: "40px", padding: "0 24px", fontSize: "1rem" }
      lg: { height: "48px", padding: "0 32px", fontSize: "1rem" }
    borderRadius: "9999px"
    fontWeight: 700
    letterSpacing: "0.05em"
    textTransform: "none"
  input:
    background: "#2a2a2a"
    color: "#ffffff"
    border: "1px solid transparent"
    borderRadius: "6px"
    padding: "10px 12px"
    focusBorder: "1px solid #1db954"
    placeholderColor: "#6a6a6a"
  card:
    base:  { background: "#181818", border: "none", borderRadius: "8px", padding: "16px", shadow: "0 4px 8px rgba(0,0,0,0.3)" }
    hover: { shadow: "0 8px 16px rgba(0,0,0,0.4)", transform: "none" }
---

# Spotify Dark

> Album-art-forward, green-on-black streaming interface — the genre-defining dark-mode music UI.

## Origin

Spotify launched in 2008 from Stockholm, Sweden, founded by Daniel Ek and Martin Lorentzon. By 2010–2013, the signature visual identity had crystallized: a near-black background at `#121212`, the phosphor-green brand color `#1db954`, and an interface that treated album art as its primary decorative element. The proprietary Spotify Circular typeface — a softly geometric Helvetica derivative — gave everything a friendly, approachable voice. Former Spotify designer Tobias Ahlin became known for his explorations of UI animation, establishing micro-interaction patterns that influenced the broader streaming category.

What made Spotify's design canonical was restraint. While competitors added gradients, textures, and visual noise, Spotify stripped back. The dark canvas served a functional purpose — album art pops against black in a way it never does against white — and the green accent was used surgically: play buttons, progress indicators, active states. Spotify Wrapped, launched as a year-end data visualization, proved the system could flex into bold, colorful territory while remaining unmistakably Spotify. The result is a design language copied by Apple Music, YouTube Music, Tidal, and dozens of audio products worldwide.

## Overview

Composition cues:
- **Layout**: Grid-based card layouts for browse, playlists, and artist pages; album art tiles as primary visual unit
- **Content width**: Full-bleed for app shells; container-bound for marketing and settings
- **Framing**: Solid, flat surfaces — no glass or blur; album art provides all visual richness
- **Grid intensity**: Soft — clean card grids with consistent gaps, no visible grid lines

## Colors

Spotify's color philosophy is extreme restraint. The near-black `#121212` background (never pure `#000`) keeps album artwork vibrant and reduces eye strain during long listening sessions. Spotify Green `#1db954` is deployed only for interactive highlights — play buttons, active nav items, progress bars — making it impossible to miss what's tappable. Secondary text at `#b3b3b3` provides hierarchy without competing with album art. The system deliberately avoids multiple accent colors; the green-on-black signature is the entire brand in two values.

**Role usage**:
- Page background → `colors.background.page` (#121212)
- Card / playlist tile surfaces → `colors.background.surface` (#181818)
- Input fields / hover surfaces → `colors.background.subtle` (#282828)
- Play buttons, active states, progress bars → `colors.primary.500` (#1db954)
- Primary text / headings → `colors.text.primary` (#ffffff)
- Secondary text / metadata → `colors.text.secondary` (#b3b3b3)
- Muted / disabled text → `colors.text.muted` (#6a6a6a)
- Button text on green → `colors.text.inverse` (#000000)

## Typography

Spotify's type voice is round, clean, and unassuming — it never competes with the album art. The proprietary Spotify Circular is a softly geometric sans-serif; Plus Jakarta Sans is the closest publicly available match with its rounded terminals and warm geometry. Headings use bold weight with tight letter-spacing for impact, while body text at regular weight maintains an easy, scannable rhythm. Text sizes are kept relatively compact — Spotify is a content-dense app — and uppercase is avoided entirely in the core UI, reinforcing the conversational, non-corporate tone.

**Text styles**:
- `display-xl` — Plus Jakarta Sans, 96px, weight 800, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Plus Jakarta Sans, 64px, weight 700, line-height 1.1, letter-spacing -0.02em
- `heading-1` — Plus Jakarta Sans, 32px, weight 700, line-height 1.2, letter-spacing -0.02em
- `body-lg` — Plus Jakarta Sans, 18px, weight 400, line-height 1.5, letter-spacing 0
- `body-md` — Plus Jakarta Sans, 16px, weight 400, line-height 1.4, letter-spacing 0
- `caption` — Plus Jakarta Sans, 12px, weight 500, line-height 1.25, letter-spacing 0.05em
- `mono-md` — JetBrains Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout

- Base unit: 4px; primary rhythm at 8px multiples
- Spacing scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128
- Container max-widths: 640 / 768 / 1024 / 1280px
- Section padding: 32px (mobile) → 64px (tablet) → 96px (desktop) → 128px (hero)
- Grid gaps: 8px (tight lists) / 16px (standard cards) / 24px (browse grids) / 48px (section blocks)

## Elevation & Depth

Spotify achieves depth through flat, opaque surfaces at different lightness values rather than shadows or blur. The page sits at `#121212`, cards rise to `#181818`, and interactive elements like inputs and hover states step to `#282828`. Shadows are barely present — a faint 4–8px blur at high opacity beneath cards gives just enough lift to separate art tiles from the canvas. There is no glass, no blur, no gradient layering on structural elements. Album art is the only source of visual complexity.

- Surface style: flat, opaque fills — no glass or blur
- Primary depth cue: background-color stepping (3 tiers: #121212 → #181818 → #282828)
- Shadow usage: subtle card shadows only; barely visible
- Shadow intensity: 0.3–0.4 opacity, dark-on-dark
- No decorative gradients on structural surfaces

## Shapes

- Card / playlist tile border-radius: 8px (the Spotify card signature)
- Button border-radius: 9999px (full pill — the iconic play button shape)
- Input border-radius: 6px
- Avatar / artist image border-radius: 9999px (full circle)
- Small elements (chips, tags): 4px
- Album art tiles: 6px radius

## Motion

Spotify's motion is restrained and purposeful — it serves navigation, not decoration. Transitions are smooth and quick, helping users flow between browse, search, and now-playing views without disruption. Hover states use subtle scale and opacity shifts; the play button on card hover fades in with a gentle lift. Page transitions are near-instant. The system avoids bouncy springs or playful overshoots — the mood is calm and focused, like good background music: present but never distracting.

- Level: restrained
- Fast interactions (hover, focus): 120ms
- Standard transitions (view switch, drawer open): 250ms
- Emphasized animations (now-playing reveal, full-screen mode): 400ms
- Easing: ease-out for enters, ease-in for exits, smooth default
- Hover patterns: scale (play button lift on card hover), opacity (fade-in controls), tint (green highlight on active)

## Techniques

### Album-Art Gradient Backdrop

Spotify extracts dominant colors from album art and projects a soft radial gradient behind the content header — giving each playlist and artist page a unique, immersive feel without any custom design work.

```css
.album-gradient-backdrop {
  position: relative;
  background: linear-gradient(
    180deg,
    var(--dominant-album-color, #1db954) 0%,
    #121212 60%
  );
  padding: 64px 32px 32px;
}

.album-gradient-backdrop::after {
  content: "";
  position: absolute;
  inset: 0;
  background: linear-gradient(
    180deg,
    transparent 0%,
    rgba(18, 18, 18, 0.6) 40%,
    #121212 100%
  );
  pointer-events: none;
}
```

### Green Pill Play Button

The iconic Spotify play button — a full-pill green circle with black icon that appears on card hover with a subtle scale-up entrance. The defining interactive element of the entire streaming genre.

```css
.play-button {
  width: 48px;
  height: 48px;
  border-radius: 9999px;
  background-color: #1db954;
  color: #000000;
  border: none;
  display: flex;
  align-items: center;
  justify-content: center;
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
  opacity: 0;
  transform: translateY(8px);
  transition: opacity 250ms ease, transform 250ms ease, background-color 120ms ease;
}

.card:hover .play-button {
  opacity: 1;
  transform: translateY(0);
}

.play-button:hover {
  background-color: #1ed760;
  transform: scale(1.06);
}
```

### Dark Card with Art Slot

The standard Spotify browse card — a dark `#181818` rectangle with album art occupying the top half, text metadata below, and a hover state that lifts the entire card with a subtle background shift.

```css
.spotify-card {
  background: #181818;
  border-radius: 8px;
  padding: 16px;
  transition: background-color 250ms ease;
  cursor: pointer;
  position: relative;
  overflow: hidden;
}

.spotify-card:hover {
  background: #282828;
}

.spotify-card .art {
  width: 100%;
  aspect-ratio: 1;
  border-radius: 6px;
  object-fit: cover;
  margin-bottom: 16px;
}

.spotify-card .title {
  color: #ffffff;
  font-weight: 700;
  font-size: 1rem;
  margin-bottom: 4px;
  overflow: hidden;
  text-overflow: ellipsis;
  white-space: nowrap;
}

.spotify-card .subtitle {
  color: #b3b3b3;
  font-size: 0.875rem;
  font-weight: 400;
}
```

## Iconography

Spotify uses clean, thin outline icons with a 1.5px stroke weight — lighter than most systems, matching the restrained visual language. Icons are functional markers (play, pause, skip, heart, shuffle) rather than decorative elements; they recede until needed. The style is geometric and rounded, echoing the soft terminals of Spotify Circular.

- Treatment: outline, 1.5px stroke
- Set: Lucide (clean geometry, rounded joins match Circular's personality)
- Sizes: 16px (inline metadata), 20px (toolbar controls), 24px (navigation)

## Do's & Don'ts

### Do
- Use `#121212` as the canonical page background — not pure black, not charcoal
- Reserve Spotify Green `#1db954` exclusively for interactive elements: play buttons, progress, active states
- Make album art the dominant visual element — cards and grids should showcase photography
- Use full-pill (9999px) radius for primary action buttons
- Keep typography clean and compact — let content breathe, not type

### Don't
- Use pure black `#000000` — too harsh; `#121212` is the canonical Spotify ground
- Introduce multiple secondary accent colors — green is the only accent
- Design light-mode-first — this is a dark-mode-canonical system
- Apply brutalist or maximalist decoration — Spotify is restrained
- Use serif fonts — the brand is rounded sans-serif throughout

## Applications

Spotify Dark is the definitive template for media-rich dark interfaces — music players, podcast apps, video streaming dashboards, and any product where visual content (art, photography, video thumbnails) needs to dominate. The restrained palette and flat surfaces make it ideal for long-session apps where eye strain matters. It also suits creative tool dashboards, portfolio galleries, and any interface that treats imagery as the primary UI element rather than decorative afterthought.
