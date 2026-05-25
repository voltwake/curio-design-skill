---
version: 1

meta:
  id: memphis-sottsass-1981
  name: "Memphis (Sottsass 1981)"
  description: "Clashing candy colors, asymmetric geometry, and terrazzo confetti celebrating postmodern anti-taste"
  isDark: false
  tags: [decorative, bold, friendly, historical, playful]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "1981–1987; influence persists to present"
  region: "Milan, Italy"
  regionZh: "意大利米兰"
  keyFigures: [Ettore Sottsass, Michele de Lucchi, Nathalie du Pasquier, George Sowden]
  movements: [Postmodernism, Anti-Bauhaus, Pop Art]

introduction: |
  The Memphis Group exploded onto the design scene in 1981, rejecting the austere rationalism of modernism with clashing colors, kitsch laminate patterns, and gleeful asymmetry. Founded by Ettore Sottsass in Milan, the collective turned "bad taste" into a manifesto — every piece a deliberate provocation against harmony.

  Their influence radiates through decades of playful branding, from 1980s music videos to today's Slack illustrations. Memphis proves that joy, irreverence, and visual noise can be a design philosophy, not a design crime.

introductionZh: |
  1981年，孟菲斯设计团体在米兰横空出世，以撞色、廉价贴面和肆意的不对称几何，向现代主义的冷静理性发起了一场色彩暴动。创始人埃托·索特萨斯将"坏品味"变成了一种宣言——每件作品都在向和谐与秩序挑衅。

  从八十年代的MTV音乐录影带到今天Slack和Notion的品牌插画，孟菲斯的精神一直在回响。它证明了喧闹、快乐和视觉冲突本身就是一种设计哲学，而非设计事故。

colors:
  primary:
    "50": "#fff0f6"
    "100": "#ffe0ed"
    "200": "#ffb8d4"
    "300": "#ff8fbb"
    "400": "#ff669f"
    "500": "#ff3d8b"
    "600": "#e6286f"
    "700": "#bf1a55"
    "800": "#99123e"
    "900": "#730d2e"
    "950": "#4d0720"
  secondary:
    "50": "#e6fbfb"
    "100": "#ccf7f8"
    "200": "#80eced"
    "300": "#40e3e4"
    "400": "#1adcde"
    "500": "#00d4d6"
    "600": "#00b3b5"
    "700": "#008c8d"
    "800": "#006768"
    "900": "#004a4b"
    "950": "#003233"
  accent:
    "50": "#fffbe6"
    "100": "#fff7cc"
    "200": "#ffef99"
    "300": "#ffe766"
    "400": "#ffdf42"
    "500": "#ffd72d"
    "600": "#e6be14"
    "700": "#bf9c0a"
    "800": "#997b05"
    "900": "#735c02"
    "950": "#4d3d01"
  neutral:
    "50": "#faf6e8"
    "100": "#f5edd4"
    "200": "#ebe0b8"
    "300": "#ddd09a"
    "400": "#c9b97a"
    "500": "#b3a362"
    "600": "#968749"
    "700": "#756935"
    "800": "#544c26"
    "900": "#36311a"
    "950": "#1e1b0f"
  semantic:
    success: { bg: "#5fdc5f", text: "#1a4d1a", light: "#d9f5d9", border: "#3cb83c" }
    warning: { bg: "#ffd72d", text: "#5c4a00", light: "#fff7cc", border: "#e6be14" }
    error:   { bg: "#ff3d8b", text: "#4d0720", light: "#ffe0ed", border: "#e6286f" }
    info:    { bg: "#2155cd", text: "#ffffff", light: "#d4e0ff", border: "#193fa0" }
  background:
    page:    "#faf6e8"
    surface: "#ffffff"
    subtle:  "#f5edd4"
  text:
    primary:   "#1e1b0f"
    secondary: "#544c26"
    muted:     "#968749"
    inverse:   "#faf6e8"

typography:
  families:
    heading: "'Archivo Black', 'Anton', Impact, sans-serif"
    body:    "'Space Grotesk', 'Inter', system-ui, sans-serif"
    mono:    "'Space Mono', 'Fira Code', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Archivo+Black&family=Space+Grotesk:wght@300;400;500;600;700&family=Space+Mono:wght@400;700&display=swap"
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
  container: { sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:   { sm: "12px", md: "20px", lg: "32px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "4px", md: "8px", lg: "16px", xl: "24px", full: "9999px" }
  color:  { default: "#1e1b0f", subtle: "#ddd09a", strong: "#1e1b0f", focus: "#2155cd" }
  width:  { thin: "1px", default: "3px", thick: "5px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "2px 2px 0 rgba(30,27,15,0.15)"
  sm: "3px 3px 0 rgba(30,27,15,0.20)"
  md: "4px 4px 0 rgba(30,27,15,0.25)"
  lg: "6px 6px 0 rgba(30,27,15,0.30)"
  xl: "8px 8px 0 rgba(30,27,15,0.35)"
  "2xl": "12px 12px 0 rgba(30,27,15,0.40)"
  inner: "inset 2px 2px 0 rgba(30,27,15,0.10)"
  focus: "0 0 0 4px rgba(33,85,205,0.4)"

motion:
  level: "playful"
  durations: { instant: "0ms", fast: "100ms", normal: "200ms", slow: "350ms", slower: "500ms" }
  easings:
    default: "cubic-bezier(0.34, 1.56, 0.64, 1)"
    in:      "cubic-bezier(0.55, 0, 1, 0.45)"
    out:     "cubic-bezier(0, 0.55, 0.45, 1)"
    spring:  "cubic-bezier(0.34, 1.8, 0.64, 1)"
  hoverPatterns: [lift, scale, tint, glow]
  reducedMotion: true

composition:
  layout:        "grid"
  contentWidth:  "wide"
  framing:       "bordered"
  gridIntensity: "strong"
  rhythm:        "8px"

surfaceStyle: "layered"
blur:         "none"

iconography:
  treatment: "filled"
  set:       "phosphor"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "2px"

components:
  button:
    primary:   { background: "#ff3d8b", color: "#ffffff", border: "3px solid #1e1b0f", shadow: "4px 4px 0 #1e1b0f", hoverBackground: "#e6286f", hoverShadow: "2px 2px 0 #1e1b0f", hoverColor: "#ffffff" }
    secondary: { background: "#00d4d6", color: "#1e1b0f", border: "3px solid #1e1b0f", shadow: "4px 4px 0 #1e1b0f", hoverBackground: "#00b3b5", hoverShadow: "2px 2px 0 #1e1b0f", hoverColor: "#1e1b0f" }
    ghost:     { background: "transparent", color: "#1e1b0f", border: "3px solid #1e1b0f", shadow: "none", hoverBackground: "#ffd72d", hoverShadow: "2px 2px 0 #1e1b0f", hoverColor: "#1e1b0f" }
    danger:    { background: "#ff3d8b", color: "#ffffff", border: "3px solid #730d2e", shadow: "4px 4px 0 #730d2e", hoverBackground: "#e6286f", hoverShadow: "2px 2px 0 #730d2e", hoverColor: "#ffffff" }
    sizes:
      sm: { height: "32px", padding: "4px 12px", fontSize: "0.875rem" }
      md: { height: "44px", padding: "8px 20px", fontSize: "1rem" }
      lg: { height: "56px", padding: "12px 28px", fontSize: "1.125rem" }
    borderRadius: "4px"
    fontWeight: 700
    letterSpacing: "0.05em"
    textTransform: "uppercase"
  input:
    background: "#ffffff"
    color: "#1e1b0f"
    border: "3px solid #1e1b0f"
    borderRadius: "4px"
    padding: "10px 14px"
    focusBorder: "3px solid #2155cd"
    placeholderColor: "#968749"
  card:
    base:  { background: "#ffffff", border: "3px solid #1e1b0f", borderRadius: "8px", padding: "24px", shadow: "6px 6px 0 #1e1b0f" }
    hover: { shadow: "3px 3px 0 #1e1b0f", transform: "translate(3px, 3px)" }
---

# Memphis (Sottsass 1981)

> Clashing candy colors, squiggly geometry, and terrazzo confetti — the anti-taste design revolution that made "ugly" beautiful.

## Origin

The Memphis Group formed in December 1980 when Ettore Sottsass gathered a circle of young designers in his Milan apartment. Named after Bob Dylan's "Stuck Inside of Mobile with the Memphis Blues Again" — which happened to be playing on repeat that evening — the collective debuted at the Salone del Mobile in September 1981 with a furniture collection that scandalized the design world: the Carlton bookcase, a totemic zigzag of clashing laminate colors, became their instant icon.

Memphis deliberately rejected the "good taste" dogma of Italian modernism. Inspired by Pop Art, kitsch, and suburban consumer culture, the group embraced cheap plastic laminates printed with terrazzo speckle and squiggle patterns, day-glo colors that clashed on purpose, and asymmetric forms that refused to resolve into elegance. Though the group disbanded in 1987, their DNA lives on in every playful tech brand, 80s-revival graphic, and Saved by the Bell rerun.

## Overview

Composition cues:
- **Layout**: Grid-based but deliberately asymmetric — elements are placed off-axis, rotated, or scaled unexpectedly within the grid.
- **Content width**: Wide — Memphis fills the canvas. Negative space is decorated, not empty.
- **Framing**: Bordered — thick black outlines (3–5px) define every surface, echoing the bold laminate edge-banding of the original furniture.
- **Grid intensity**: Strong — the grid is visible, but rhythm is intentionally broken by oversized or misaligned elements.

## Colors

Memphis color philosophy is anti-harmony by design. Colors are chosen for maximum clash and energy — hot pink slams into electric turquoise, sunshine yellow screams next to cobalt blue, and lime green punctuates the chaos. The palette descends from Pop Art's commercial exuberance filtered through 1980s Italian irreverence. The neutral base is a warm cream reminiscent of terrazzo flooring, speckled with dark flecks to avoid sterility. No color should ever "match" its neighbor — if two adjacent elements feel harmonious, one of them is wrong.

**Role usage**:
- Page background → `colors.background.page` (#faf6e8 cream, optionally with terrazzo pattern overlay)
- Primary actions & hero accents → `colors.primary.500` (hot pink #ff3d8b)
- Secondary accents & interactive highlights → `colors.secondary.500` (electric turquoise #00d4d6)
- Tertiary / warning / fun emphasis → `colors.accent.500` (sunshine yellow #ffd72d)
- Borders & outlines → `colors.text.primary` (#1e1b0f, near-black)
- Cobalt blue for info states and link accents → semantic info (#2155cd)
- Lime green for success states → semantic success (#5fdc5f)
- Body text → `colors.text.primary` on cream backgrounds

## Typography

Memphis typography is loud, chunky, and unapologetic. Headings shout in Archivo Black — a geometric sans with maximum weight and zero delicacy, echoing the blocky letterforms of 1980s Italian design posters. Body text in Space Grotesk stays geometric but readable, keeping the family resemblance without competing for attention. Every heading should feel like it could be silkscreened onto a laminate surface at 200% scale.

**Text styles**:
- `display-xl` — Archivo Black, 96px, weight 400 (Archivo Black has one weight), line-height 1.0, letter-spacing -0.02em
- `display-lg` — Archivo Black, 64px, weight 400, line-height 1.05, letter-spacing -0.02em
- `heading-1` — Archivo Black, 48px, weight 400, line-height 1.1, letter-spacing 0
- `heading-2` — Archivo Black, 36px, weight 400, line-height 1.15, letter-spacing 0
- `body-lg` — Space Grotesk, 18px, weight 400, line-height 1.6, letter-spacing 0
- `body-md` — Space Grotesk, 16px, weight 400, line-height 1.5, letter-spacing 0
- `caption` — Space Grotesk, 13px, weight 500, line-height 1.4, letter-spacing 0.05em
- `mono-md` — Space Mono, 14px, weight 400, line-height 1.6, letter-spacing 0

## Spacing & Layout

- Base unit: 8px — all spacing snaps to an 8px grid.
- Scale: 8, 16, 24, 32, 48, 64, 96, 128px.
- Container max-width: 1280px for standard content, but hero sections often bleed wider.
- Section padding: 64–96px vertical, allowing large decorative shapes to breathe.
- Grid gap: 20–32px — generous enough that thick borders don't crowd each other.
- Memphis layouts break the grid intentionally: expect rotated elements, overlapping shapes, and items that cross column boundaries.

## Elevation & Depth

Memphis depth is cartoonish and literal — hard-edged offset shadows that look like a physical object casting a shadow at 45°. No soft gaussian blur, no subtle ambient occlusion. Shadows are solid blocks of near-black, displaced to the bottom-right. Higher elevation = larger offset. The effect is deliberately flat-but-3D, like a popup book or screenprint with misregistered layers.

- Surface style: layered — elements stack visually with clear separation.
- Blur: none — Memphis shadows are crisp, never blurred.
- Shadow ladder: xs (2px offset) → sm (3px) → md (4px) → lg (6px) → xl (8px) → 2xl (12px).
- All shadows use the same near-black (#1e1b0f) at varying opacity.

## Shapes

- Default corner radius: 4–8px (slightly rounded, never pill-shaped for rectangles).
- Buttons: 4px radius — blocky and assertive.
- Cards: 8px radius with thick 3px black borders.
- Tags/badges: 4px radius, solid saturated fill.
- Decorative shapes: circles, triangles, zigzag lines, and squiggles use no radius (they're SVG/CSS shapes, not rounded rectangles).
- Asymmetric corners encouraged on hero cards: e.g., 0px top-left, 24px bottom-right.

## Motion

Memphis motion is bouncy, exaggerated, and toy-like. Elements pop in with overshoot, wobble slightly on hover, and snap into place with spring easings. Nothing fades gently — things arrive with enthusiasm and leave with a cartoon poof. The spring easing (`cubic-bezier(0.34, 1.8, 0.64, 1)`) overshoots intentionally, mimicking the physical bounciness of Memphis rubber and plastic furniture.

- Level: playful.
- Durations: fast interactions (100ms), standard transitions (200ms), entrances (350ms).
- Default easing: spring with overshoot.
- Hover patterns: lift (translate-y + shadow grow), scale (1.05× pop), tint (background color swap to clashing hue), glow (colored box-shadow pulse).
- Reduced motion: respected — falls back to opacity-only transitions.

## Techniques

### Terrazzo Confetti Background
A scattered dot-and-shape pattern on the page background, evoking the terrazzo laminate finishes of original Memphis furniture.
```css
.terrazzo-bg {
  background-color: #faf6e8;
  background-image:
    radial-gradient(circle 3px, #ff3d8b 100%, transparent 100%),
    radial-gradient(circle 2px, #00d4d6 100%, transparent 100%),
    radial-gradient(circle 4px, #ffd72d 100%, transparent 100%),
    radial-gradient(circle 2px, #2155cd 100%, transparent 100%),
    radial-gradient(circle 3px, #5fdc5f 100%, transparent 100%);
  background-size: 180px 160px, 220px 200px, 200px 180px, 240px 220px, 260px 240px;
  background-position: 10px 20px, 80px 100px, 150px 50px, 40px 160px, 120px 130px;
}
```

### Hard-Offset Shadow Card
Thick-bordered card with a solid, non-blurred shadow offset to the bottom-right — the signature Memphis "pop-up" depth effect.
```css
.memphis-card {
  background: #ffffff;
  border: 3px solid #1e1b0f;
  border-radius: 8px;
  padding: 24px;
  box-shadow: 6px 6px 0 #1e1b0f;
  transition: transform 200ms cubic-bezier(0.34, 1.56, 0.64, 1),
              box-shadow 200ms cubic-bezier(0.34, 1.56, 0.64, 1);
}
.memphis-card:hover {
  transform: translate(3px, 3px);
  box-shadow: 3px 3px 0 #1e1b0f;
}
```

### Zigzag Divider
A CSS-only zigzag border separator inspired by the angular geometries found on Memphis textile patterns and the Tahiti lamp.
```css
.zigzag-divider {
  position: relative;
  height: 20px;
  background:
    linear-gradient(135deg, #ff3d8b 25%, transparent 25%) -10px 0,
    linear-gradient(225deg, #ff3d8b 25%, transparent 25%) -10px 0,
    linear-gradient(315deg, #00d4d6 25%, transparent 25%),
    linear-gradient(45deg, #00d4d6 25%, transparent 25%);
  background-size: 20px 20px;
  background-color: #faf6e8;
}
```

## Iconography

Memphis icons should be bold and filled, matching the chunky weight of the typography and thick border language. Phosphor icons in their "Fill" variant provide the right density — outlines feel too delicate for the Memphis energy. Icons can be tinted in any of the palette's clashing colors; monotone icon sets would contradict the movement's love of polychrome.

- Treatment: filled — solid shapes, maximum visual weight.
- Set: Phosphor (Fill variant).
- Stroke: 2px for any outline-mode fallbacks.

## Do's & Don'ts

### ✓ Do
- Use at least three clashing saturated colors in every composition — monotone is the enemy.
- Apply thick black borders (3–5px) to buttons, cards, and containers for the signature Memphis frame.
- Scatter decorative geometric shapes (triangles, circles, squiggles) in backgrounds and margins.
- Use hard-offset, non-blurred shadows to create a playful pop-up depth effect.
- Let headings be oversized and shouty — scale them bigger than feels comfortable.

### ✗ Don't
- Use restrained or harmonious color palettes — Memphis demands deliberate clash and saturation.
- Set headings in serif typefaces — Memphis typography is geometric sans, always.
- Leave large areas of empty white space — Memphis fills the canvas with pattern, color, and shape.
- Apply muted, dusty, or desaturated tones — every color should feel like it's turned up to 11.
- Arrange elements in symmetrical, orderly grids — break alignment, rotate, overlap, surprise.

## Applications

Memphis design translates brilliantly to playful consumer-facing products: landing pages for creative tools, children's educational apps, event and festival branding, portfolio sites for illustrators and designers, and any brand that wants to signal fun over formality. It's the natural choice when a project needs to feel youthful, energetic, and deliberately anti-corporate — the digital equivalent of a room full of Sottsass furniture where nothing matches and everything delights.
