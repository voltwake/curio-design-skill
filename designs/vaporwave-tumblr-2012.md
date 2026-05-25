---
version: 1

meta:
  id: vaporwave-tumblr-2012
  name: "Vaporwave (Tumblr 2012)"
  description: "Dusty pastel nostalgia with VHS glitch, classical busts, and dead-mall dreamscapes — A E S T H E T I C as design system"
  isDark: false
  tags: [vaporwave, retro, decorative, experimental, futuristic]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2010–2014 peak; vaporwave revival ongoing through 2024"
  region: "Internet-native (Tumblr, SoundCloud, 4chan); aesthetic crystallized 2012–2013"
  regionZh: "互联网原生（Tumblr、SoundCloud、4chan）；美学于 2012–2013 年定型"
  keyFigures: ["Daniel Lopatin (Chuck Person)", "James Ferraro", "Macintosh Plus (Vektroid)", "David OReilly"]
  movements: ["Internet art", "post-internet aesthetics", "hauntology", "microgenre culture"]

introduction: |
  Vaporwave began as a musical microgenre — slowed-down 80s smooth jazz and corporate muzak — but its visual identity on Tumblr became a lasting cultural phenomenon. Dusty pastels, classical Roman busts, VHS scan-lines, 90s Windows interfaces, and palm trees merged into a dreamy critique of late-capitalist consumer paradise.

  This design system distills the Tumblr-era vaporwave aesthetic into usable tokens: pink-lavender pastel palettes, retro-tech display type with exaggerated letter-spacing, glitch textures, and that distinctive sunset gradient that evokes dead malls and eternal shopping channels.
introductionZh: |
  蒸汽波起初是一种音乐微流派——将八十年代的丝滑爵士乐和企业背景音乐降速重混——但其在 Tumblr 上形成的视觉身份成为了更持久的文化遗产。尘粉色调、罗马古典半身像、VHS 扫描线、九十年代 Windows 界面和棕榈树，共同编织出一场对晚期资本主义消费天堂的梦幻式哀悼。

  本设计系统将 Tumblr 时代的蒸汽波美学提炼为可用的设计令牌：粉紫色粉彩调色板、复古科技风展示字体配合夸张字距、故障纹理，以及那标志性的日落渐变——唤起废弃购物中心与永恒电视购物频道的幽灵记忆。关键词：Ａ Ｅ Ｓ Ｔ Ｈ Ｅ Ｔ Ｉ Ｃ。

colors:
  primary:
    "50": "#FEF0F6"
    "100": "#FDE1ED"
    "200": "#FCC8DD"
    "300": "#FBB0CE"
    "400": "#FA9CBE"
    "500": "#ff8ec8"
    "600": "#E070A8"
    "700": "#C05488"
    "800": "#9F3C6A"
    "900": "#7E2850"
    "950": "#5E1A3A"
  secondary:
    "50": "#F5F0FA"
    "100": "#EBE0F5"
    "200": "#D8C2EB"
    "300": "#C4A4E0"
    "400": "#B17BD6"
    "500": "#9952c8"
    "600": "#7E42A8"
    "700": "#653588"
    "800": "#4D2868"
    "900": "#381D4E"
    "950": "#241138"
  accent:
    "50": "#F0F8FC"
    "100": "#E0F0F8"
    "200": "#C8E5F2"
    "300": "#B8E0F0"
    "400": "#98D0E8"
    "500": "#b8e0f0"
    "600": "#80C0D8"
    "700": "#58A0B8"
    "800": "#3C8098"
    "900": "#286478"
    "950": "#1A4858"
  neutral:
    "50": "#FDF5F8"
    "100": "#F8E8EE"
    "200": "#F0D4DE"
    "300": "#E6BCCB"
    "400": "#D8A0B4"
    "500": "#C48098"
    "600": "#A8687E"
    "700": "#885466"
    "800": "#6A4050"
    "900": "#4E2E3C"
    "950": "#341E28"
  semantic:
    success: { bg: "#C0E8D8", text: "#2A5C48", light: "#E0F4EC", border: "#80CCA8" }
    warning: { bg: "#F5E0C0", text: "#7A5C28", light: "#FBF0E0", border: "#E8C880" }
    error:   { bg: "#F5C8D0", text: "#8A2A3A", light: "#FBE0E5", border: "#E89CA8" }
    info:    { bg: "#C8D8F0", text: "#2A3C5C", light: "#E0ECF8", border: "#90B0D8" }
  background:
    page:    "#f5d8e8"
    surface: "#FFFFFF"
    subtle:  "#F0D0E0"
  text:
    primary:   "#2d1b4e"
    secondary: "#4a1942"
    muted:     "#885466"
    inverse:   "#f5d8e8"

typography:
  families:
    heading: "'Audiowide', 'Major Mono Display', sans-serif"
    body:    "'VT323', 'Press Start 2P', monospace"
    mono:    "'VT323', 'Courier New', monospace"
    googleFontsImport: "https://fonts.googleapis.com/css2?family=Audiowide&family=Major+Mono+Display&family=Press+Start+2P&family=VT323&family=Bungee+Inline&display=swap"
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
  letterSpacing: { tighter: "-0.04em", tight: "-0.02em", normal: "0", wide: "0.2em", wider: "0.4em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      { sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:        { sm: "8px", md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "8px", md: "12px", lg: "16px", xl: "24px", full: "9999px" }
  color:  { default: "#d4c0ec", subtle: "#F0D0E0", strong: "#9952c8", focus: "#ff8ec8" }
  width:  { thin: "1px", default: "2px", thick: "3px" }
  style: "solid"

shadows:
  none: "none"
  xs: "0 1px 2px rgba(153,82,200,0.08)"
  sm: "0 2px 4px rgba(153,82,200,0.12)"
  md: "0 4px 12px rgba(153,82,200,0.18)"
  lg: "0 8px 24px rgba(255,142,200,0.2)"
  xl: "0 12px 36px rgba(153,82,200,0.25)"
  "2xl": "0 24px 48px rgba(153,82,200,0.3)"
  inner: "inset 0 2px 4px rgba(153,82,200,0.1)"
  focus: "0 0 0 3px rgba(255,142,200,0.5)"

motion:
  level: "lively"
  durations: { instant: "0ms", fast: "120ms", normal: "300ms", slow: "500ms", slower: "800ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.55, 0, 1, 0.45)"
    out:     "cubic-bezier(0, 0.55, 0.45, 1)"
    spring:  "cubic-bezier(0.34, 1.56, 0.64, 1)"
  hoverPatterns: [glow, scale, tint, lift]
  reducedMotion: true

composition:
  layout:        "stack"
  contentWidth:  "container"
  framing:       "glassy"
  gridIntensity: "soft"
  rhythm:        "8px"

surfaceStyle: "glass"
blur:         "12px"

iconography:
  treatment: "linear"
  set:       "phosphor"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "1.5px"

components:
  button:
    primary:
      background: "#ff8ec8"
      color: "#2d1b4e"
      border: "2px solid #E070A8"
      shadow: "0 4px 12px rgba(255,142,200,0.3)"
      hoverBackground: "#FBA0D4"
      hoverShadow: "0 6px 20px rgba(255,142,200,0.45), 0 0 30px rgba(255,142,200,0.2)"
      hoverColor: "#2d1b4e"
    secondary:
      background: "#d4c0ec"
      color: "#2d1b4e"
      border: "2px solid #B17BD6"
      shadow: "0 4px 12px rgba(153,82,200,0.2)"
      hoverBackground: "#E0D0F2"
      hoverShadow: "0 6px 20px rgba(153,82,200,0.35)"
      hoverColor: "#2d1b4e"
    ghost:
      background: "transparent"
      color: "#9952c8"
      border: "2px solid #d4c0ec"
      shadow: "none"
      hoverBackground: "rgba(153,82,200,0.1)"
      hoverShadow: "0 0 16px rgba(153,82,200,0.2)"
      hoverColor: "#7E42A8"
    danger:
      background: "#ff8a9a"
      color: "#FFFFFF"
      border: "2px solid #E07080"
      shadow: "0 4px 12px rgba(255,138,154,0.3)"
      hoverBackground: "#FFA0AE"
      hoverShadow: "0 6px 20px rgba(255,138,154,0.45)"
      hoverColor: "#FFFFFF"
    sizes:
      sm: { height: "32px", padding: "0 16px", fontSize: "0.875rem" }
      md: { height: "40px", padding: "0 24px", fontSize: "1rem" }
      lg: { height: "48px", padding: "0 32px", fontSize: "1.125rem" }
    borderRadius: "12px"
    fontWeight: 700
    letterSpacing: "0.05em"
    textTransform: "uppercase"
  input:
    background: "rgba(255,255,255,0.7)"
    color: "#2d1b4e"
    border: "2px solid #d4c0ec"
    borderRadius: "12px"
    padding: "10px 14px"
    focusBorder: "#ff8ec8"
    placeholderColor: "#885466"
  card:
    base:
      background: "rgba(255,255,255,0.6)"
      border: "1px solid rgba(212,192,236,0.5)"
      borderRadius: "16px"
      padding: "24px"
      shadow: "0 4px 12px rgba(153,82,200,0.18)"
    hover:
      shadow: "0 8px 24px rgba(255,142,200,0.25), 0 0 40px rgba(153,82,200,0.1)"
      transform: "translateY(-2px)"
---

# Vaporwave (Tumblr 2012)

> A E S T H E T I C — dusty pastels, classical busts, VHS glitch, and the eternal dream of a dead mall at sunset.

## Origin

Vaporwave crystallized between 2010 and 2012 as a musical microgenre — Daniel Lopatin's Chuck Person's Eccojams Vol. 1 (2010) and James Ferraro's Far Side Virtual (2011) slowed corporate muzak and smooth jazz into uncanny loops, while Vektroid's Macintosh Plus project released Floral Shoppe (2011), whose cover art — a pink-gridded classical bust against a pastel backdrop — became the movement's Mona Lisa. The sound was a eulogy for 80s consumer optimism; the imagery extended that mourning into visual space.

On Tumblr, anonymous collectives remixed the aesthetic into something larger: dusty pink-purple gradients, Roman sculpture, palm trees silhouetted against neon sunsets, 1990s Microsoft Windows chrome, Japanese katakana used as pure decoration, and convenience-store shelves frozen in time. The keyword was always typed with spaces — A E S T H E T I C — a typographic gesture that itself became a meme. By 2013, vaporwave had leaked from SoundCloud and 4chan's /mu/ board into mainstream internet culture, influencing fashion, graphic design, and a wave of nostalgia-core aesthetics that continues through 2024.

## Overview
Composition cues:
- **Layout**: Stacked compositions with layered translucent panels floating over pastel gradient backgrounds
- **Content width**: Container-based (1024px) to frame dreamy collage layouts
- **Framing**: Glassy — translucent pastel overlays with subtle blur, evoking VHS haze
- **Grid intensity**: Soft — compositions favor dreamy floats and layered transparency over rigid alignment

## Colors
Vaporwave's palette mourns in pastel. The dominant field is dusty rose pink `#f5d8e8`, with lavender `#d4c0ec` and sky blue `#b8e0f0` drifting through as atmospheric accents. Hot pink `#ff8ec8` provides primary action energy — the neon sign flickering in the dead mall. Deep purple `#9952c8` anchors secondary elements with the weight of a sunset's last gasp. Coral `#ff8a9a` and mint `#c0e8d8` appear sparingly as semantic and accent tones. The palette avoids full saturation — everything is slightly dusty, slightly faded, as if viewed through a VHS tape left in the sun.

**Role usage**:
- Page background → `colors.background.page` (dusty rose `#f5d8e8`)
- Card/panel surfaces → `colors.background.surface` (white with translucency)
- Subtle containers → `colors.background.subtle` (deeper dusty pink)
- Primary actions → `colors.primary.500` (hot pink `#ff8ec8`)
- Secondary elements → `colors.secondary.500` (purple `#9952c8`)
- Cool accents → `colors.accent.500` (sky blue `#b8e0f0`)
- Body text → `colors.text.primary` (deep purple `#2d1b4e`)
- Muted labels → `colors.text.muted` (dusty mauve `#885466`)

## Typography
Vaporwave type lives at the intersection of retro-tech display and monospace terminal. Audiowide — a wide, geometric display face — serves as the heading font, its futuristic curves evoking early-2000s tech utopia filtered through VHS nostalgia. VT323, a pixel-perfect monospace reminiscent of VT100 terminals, handles body text and code, grounding every paragraph in CRT-monitor authenticity. The signature move is exaggerated letter-spacing on display text (0.2–0.4em), turning headlines into the iconic W I D E  T E X T that became vaporwave's typographic hallmark. Major Mono Display and Press Start 2P serve as alternates for additional retro dimension.

**Text styles**:
- `display-xl` — Audiowide, 96px, weight 400, line-height 1.0, letter-spacing 0.2em
- `display-lg` — Audiowide, 64px, weight 400, line-height 1.1, letter-spacing 0.2em
- `heading-1` — Audiowide, 48px, weight 400, line-height 1.2, letter-spacing 0.1em
- `body-lg` — VT323, 20px, weight 400, line-height 1.5, letter-spacing 0.05em
- `body-md` — VT323, 18px, weight 400, line-height 1.5, letter-spacing 0.02em
- `caption` — VT323, 14px, weight 400, line-height 1.4, letter-spacing 0.05em
- `mono-md` — VT323, 16px, weight 400, line-height 1.5, letter-spacing 0.05em

## Spacing & Layout
- Base unit: 4px with 8px rhythm for section-level composition
- Scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128px
- Container max-width: 1024px (lg breakpoint)
- Section padding: 64px vertical at md, 96px at lg — generous breathing room for the dreamy aesthetic
- Grid gap: 16px default, 24px for card grids
- Panels float with ample whitespace; density comes from layered transparency, not tight packing

## Elevation & Depth
Vaporwave depth is atmospheric — layers of translucent pastel glass stacked like VHS generations, each slightly hazier than the last. Cards use purple-tinted shadows that feel like light bleeding through a dusty pink sunset. Higher elevations gain a hot-pink glow at the edges, mimicking neon reflections on glass surfaces. The materiality is "frosted acrylic panel in a sunset-lit room" — soft, luminous, never hard-edged.

- Surface style: glass (translucent white panels with backdrop-blur)
- Blur: 12px for glassmorphism overlays
- Shadow ladder: xs (faint purple tint) → sm → md (default card) → lg (pink glow) → xl (purple haze) → 2xl (hero-level neon bloom)
- Focus ring: hot pink glow `0 0 0 3px rgba(255,142,200,0.5)`

## Shapes
- No radius (0): Full-bleed gradient sections, grid floors
- Small radius (8px): Tags, badges, small interactive elements
- Medium radius (12px): Buttons, inputs — the default interactive shape, generously rounded
- Large radius (16px): Cards, modals — soft-cornered translucent panels
- XL radius (24px): Hero panels, featured image containers
- Full (9999px): Avatars, pill badges, floating action buttons

## Motion
Vaporwave motion is dreamy and lively — not bouncy-playful, but floaty and hypnotic. Hover states feel like objects drifting in warm water: gentle lifts paired with expanding neon glows. Transitions use slightly elongated durations to maintain the hazy, slowed-down temporal feel that defines the genre. Everything should feel like it's moving at 0.75x speed — present but unhurried, like a VHS tape playing back a dream.

- Level: lively
- Fast: 120ms (micro-interactions, button press feedback)
- Normal: 300ms (hover transitions, glow expansions)
- Slow: 500ms (panel reveals, gradient shifts)
- Slower: 800ms (page-level transitions, hero fade-ins)
- Default easing: ease-out for most transitions
- Spring easing: `cubic-bezier(0.34, 1.56, 0.64, 1)` for interactive hover lifts
- Hover patterns: glow (pink/purple shadow bloom), scale (1.02–1.05), tint (lavender wash), lift (translateY -2px)
- Reduced motion: all animations collapse to opacity-only fades

## Techniques

### VHS Scanline Overlay
Applies CRT-style horizontal scanlines over any element, creating the signature VHS playback texture.
```css
.vhs-scanlines {
  position: relative;
}
.vhs-scanlines::after {
  content: '';
  position: absolute;
  inset: 0;
  background: repeating-linear-gradient(
    0deg,
    transparent,
    transparent 2px,
    rgba(0, 0, 0, 0.03) 2px,
    rgba(0, 0, 0, 0.03) 4px
  );
  pointer-events: none;
  z-index: 1;
}
```

### Sunset Gradient Hero
The iconic purple-to-pink sunset gradient used as a dramatic hero background, evoking dead-mall twilight and 80s corporate video intros.
```css
.sunset-gradient-hero {
  background: linear-gradient(180deg, #1a0a2e 0%, #2d1b4e 30%, #4a1942 60%, #e84393 100%);
  color: #f5d8e8;
  position: relative;
}
.sunset-gradient-hero::before {
  content: '';
  position: absolute;
  inset: 0;
  background: repeating-linear-gradient(
    0deg,
    transparent,
    transparent 2px,
    rgba(255, 142, 200, 0.04) 2px,
    rgba(255, 142, 200, 0.04) 4px
  );
  pointer-events: none;
}
```

### Chromatic Aberration Text
RGB channel-split effect on display text, mimicking the color fringing of misaligned CRT tubes and VHS playback.
```css
.chromatic-text {
  font-family: 'Audiowide', sans-serif;
  letter-spacing: 0.2em;
  text-transform: uppercase;
  color: #ff8ec8;
  text-shadow:
    -2px 0 #b8e0f0,
    2px 0 #ff8a9a,
    0 0 20px rgba(255, 142, 200, 0.4);
}
```

## Iconography
Icons should feel lightweight and linear — thin strokes that complement the hazy, translucent aesthetic rather than competing with the layered pastel backgrounds. Phosphor icons in linear style provide the right balance of retro charm and clean readability. Icons are typically tinted in the secondary purple or primary pink, occasionally in sky blue for informational contexts.

- Treatment: linear (thin strokes that breathe in the pastel haze)
- Set: Phosphor (versatile, retro-compatible weight)
- Stroke: 1.5px base weight
- Sizes: 16px (inline), 20px (default), 24px (featured)

## Do's & Don'ts
### ✓ Do
- Use hot pink `#ff8ec8` for primary actions and call-to-action elements
- Apply W I D E  L E T T E R - S P A C I N G (0.2em+) on all display headlines
- Layer translucent pastel panels over gradient or dusty-pink backgrounds
- Include VHS scanline overlays and chromatic aberration on hero sections
- Keep the palette in the pink-purple-cyan triangle — all colors slightly dusty

### ✗ Don't
- Apply restrained corporate cleanliness — vaporwave is dreamy maximalism
- Use sharp Swiss minimalism — precision kills the haze
- Create dark, serious moods — vaporwave is dreamy and wistful, not severe
- Use fully saturated rainbow palettes — the spectrum is specifically pink/purple/cyan
- Fall back to modern flat design — every surface should have depth, glow, or translucency

## Applications
Vaporwave (Tumblr 2012) is ideal for creative portfolios, music platforms, retro-themed landing pages, cultural commentary projects, and any digital product that wants to evoke internet nostalgia and post-capitalist dreaminess. It works especially well for event pages, artist profiles, editorial blogs, and aesthetic-first experiences where mood takes priority over information density. The style rewards generous spacing, layered transparency, and a commitment to the pastel-neon duality.
