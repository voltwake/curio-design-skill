---
version: 1

meta:
  id: discord-2024
  name: Discord 2024
  description: Dark, blurple-accented gaming-community interface with playful illustration energy
  isDark: true
  tags: [playful, tech, friendly, bold, futuristic]
  status: published
  tier: free
  generatedBy: claude

origin:
  era: "2015 launched; current visual ~2021 rebrand through 2024"
  region: "San Francisco, California"
  regionZh: "美国旧金山"
  keyFigures: [Jason Citron, Stanislav Vishnevskiy, Buck (illustration studio), Discord Brand team]
  movements: [Gaming chat platforms, Voice-first communication, Communities-as-servers]

introduction: |
  Discord began as a voice-chat tool for gamers and evolved into a universal community platform used by everyone from study groups to open-source projects. Its 2021 rebrand, led by Buck illustration studio, cemented a visual identity built on the signature "blurple" — a specific blue-purple that lives at #5865F2 — set against dark charcoal backgrounds that feel like a cozy late-night gaming session.

  The design language is deliberately anti-corporate: playful illustrated characters, rounded corners, and a color palette that includes punchy fuchsia, yellow, green, and red accents. Typography uses tight, clean sans-serif headings to keep things readable without feeling stiff. Every surface says "hang out here" rather than "work here."
introductionZh: |
  Discord 最初是为游戏玩家打造的语音聊天工具，后来发展成一个覆盖学习小组、开源社区等各类群体的通用社交平台。2021 年由 Buck 插画工作室主导的品牌重塑，确立了以标志性"blurple"（蓝紫色 #5865F2）为核心、搭配深灰色背景的视觉体系——仿佛深夜与朋友联机时那种温暖而放松的氛围。

  Discord 的设计语言刻意远离企业感：圆润的边角、俏皮的插画角色、明快的品红、黄、绿、红点缀色，加上紧凑利落的无衬线字体，让每一个界面都在说"来这里玩吧"，而不是"来这里上班"。

colors:
  primary:
    "50": "#eef0fe"
    "100": "#d9ddfd"
    "200": "#b3bbfb"
    "300": "#8d99f8"
    "400": "#7380f5"
    "500": "#5865F2"
    "600": "#4752c4"
    "700": "#3c44a1"
    "800": "#2e347a"
    "900": "#212556"
    "950": "#151737"
  secondary:
    "50": "#fdf4ff"
    "100": "#fae4ff"
    "200": "#f4c4fe"
    "300": "#ed9afc"
    "400": "#e36ef8"
    "500": "#EB459E"
    "600": "#c9357f"
    "700": "#a72a68"
    "800": "#822054"
    "900": "#5e1840"
    "950": "#3d0e2b"
  accent:
    "50": "#eafff2"
    "100": "#d0fee2"
    "200": "#a4fcc6"
    "300": "#7af9ab"
    "400": "#57F287"
    "500": "#3dda6e"
    "600": "#2fb857"
    "700": "#259545"
    "800": "#1c7235"
    "900": "#145027"
    "950": "#0c3119"
  neutral:
    "50": "#f2f3f5"
    "100": "#e3e5e8"
    "200": "#c7c9ce"
    "300": "#B9BBBE"
    "400": "#96989d"
    "500": "#72767d"
    "600": "#5c5f66"
    "700": "#4f545c"
    "800": "#40444B"
    "900": "#36393F"
    "950": "#2F3136"
  semantic:
    success: { bg: "#57F287", text: "#ffffff", light: "#2a3d30", border: "#3dda6e" }
    warning: { bg: "#FEE75C", text: "#2F3136", light: "#3d3a24", border: "#d4c14e" }
    error:   { bg: "#ED4245", text: "#ffffff", light: "#3d2425", border: "#c43538" }
    info:    { bg: "#5865F2", text: "#ffffff", light: "#2a2d3d", border: "#4752c4" }
  background:
    page:    "#36393F"
    surface: "#2F3136"
    subtle:  "#40444B"
  text:
    primary:   "#DCDDDE"
    secondary: "#B9BBBE"
    muted:     "#72767d"
    inverse:   "#2F3136"

typography:
  families:
    heading: "'Inter', 'Whitney', -apple-system, BlinkMacSystemFont, sans-serif"
    body:    "'Inter', 'Whitney', -apple-system, BlinkMacSystemFont, sans-serif"
    mono:    "'JetBrains Mono', 'Consolas', 'Courier New', monospace"
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
  lineHeights: { tight: 1.2, snug: 1.3, normal: 1.4, relaxed: 1.5, loose: 1.6 }
  letterSpacing: { tighter: "-0.04em", tight: "-0.015em", normal: "0", wide: "0.05em" }

spacing:
  base: "4px"
  scale: ["2px","4px","6px","8px","12px","16px","24px","32px","48px","64px","96px","128px"]
  container:      { sm: "640px", md: "768px", lg: "1024px", xl: "1280px", full: "100%" }
  gridGap:        { sm: "8px",  md: "16px", lg: "24px", xl: "48px" }
  sectionPadding: { sm: "32px", md: "64px", lg: "96px", xl: "128px" }

borders:
  radius: { none: "0", sm: "4px", md: "8px", lg: "12px", xl: "16px", full: "9999px" }
  color:  { default: "#4f545c", subtle: "#40444B", strong: "#72767d", focus: "#5865F2" }
  width:  { thin: "1px", default: "1px", thick: "2px" }
  style:  "solid"

shadows:
  none: "none"
  xs: "none"
  sm: "none"
  md: "0 2px 8px rgba(0,0,0,0.24)"
  lg: "0 4px 16px rgba(0,0,0,0.32)"
  xl: "0 8px 24px rgba(0,0,0,0.40)"
  2xl: "0 16px 48px rgba(0,0,0,0.48)"
  inner: "inset 0 1px 2px rgba(0,0,0,0.12)"
  focus: "0 0 0 3px rgba(88,101,242,0.5)"

motion:
  level: "playful"
  durations: { instant: "0ms", fast: "100ms", normal: "200ms", slow: "350ms", slower: "500ms" }
  easings:
    default: "cubic-bezier(0.4, 0, 0.2, 1)"
    in:      "cubic-bezier(0.4, 0, 1, 1)"
    out:     "cubic-bezier(0, 0, 0.2, 1)"
    spring:  "cubic-bezier(0.34, 1.56, 0.64, 1)"
  hoverPatterns: [scale, tint, opacity, glow]
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
  treatment: "outline"
  set:       "heroicons"
  size:      { sm: "16px", md: "20px", lg: "24px" }
  stroke:    "2px"

components:
  button:
    primary:   { background: "#5865F2", color: "#ffffff", border: "none", shadow: "none", hoverBackground: "#4752c4", hoverShadow: "none", hoverColor: "#ffffff" }
    secondary: { background: "transparent", color: "#DCDDDE", border: "1px solid #DCDDDE", shadow: "none", hoverBackground: "rgba(220,221,222,0.1)", hoverShadow: "none", hoverColor: "#ffffff" }
    ghost:     { background: "transparent", color: "#B9BBBE", border: "none", shadow: "none", hoverBackground: "rgba(185,187,190,0.08)", hoverShadow: "none", hoverColor: "#DCDDDE" }
    danger:    { background: "#ED4245", color: "#ffffff", border: "none", shadow: "none", hoverBackground: "#c43538", hoverShadow: "none", hoverColor: "#ffffff" }
    sizes:
      sm: { height: "32px", padding: "0 16px", fontSize: "0.875rem" }
      md: { height: "40px", padding: "0 20px", fontSize: "1rem" }
      lg: { height: "48px", padding: "0 24px", fontSize: "1.125rem" }
    borderRadius: "8px"
    fontWeight: 500
    letterSpacing: "-0.015em"
    textTransform: "none"
  input:
    background: "#40444B"
    color: "#DCDDDE"
    border: "1px solid transparent"
    borderRadius: "8px"
    padding: "10px 12px"
    focusBorder: "1px solid #5865F2"
    placeholderColor: "#72767d"
  card:
    base:  { background: "#2F3136", border: "none", borderRadius: "12px", padding: "16px", shadow: "none" }
    hover: { shadow: "0 2px 8px rgba(0,0,0,0.24)", transform: "none" }
---

# Discord 2024

> Video-game UI hospitality — dark, blurple-accented, and playfully inviting community chat design.

## Origin

Discord launched in 2015 as a voice-first chat app for gamers, co-founded by Jason Citron and Stanislav Vishnevskiy in San Francisco. What began as a low-latency gaming comms tool rapidly expanded into a universal community platform used by study groups, DAOs, open-source projects, and friend circles. The "server" metaphor — borrowed from game hosting — gave Discord a spatial quality that Slack and Teams never matched: you didn't join a workspace, you joined a place.

The 2021 rebrand, executed with illustration studio Buck, crystallized the visual identity. The palette shifted from an older "not-quite-blue" to the defined "blurple" at `#5865F2`, accompanied by a cast of playful illustrated characters that pop up across marketing and empty states. Through 2022–2024, the design system matured into a cohesive dark-mode experience that balances information density (channel lists, member rails, chat threads) with the warm, casual energy of the brand's personality.

## Overview

Composition cues:
- **Layout**: Flex-based column/row layouts mimicking the server-sidebar → channel-list → chat → member-rail pattern
- **Content width**: Container-bound for marketing; full-bleed for app-like interfaces
- **Framing**: Solid, layered surfaces — no glass or blur; depth from background color stepping (#36393F → #2F3136 → #40444B)
- **Grid intensity**: Subtle — clean alignment without visible grid lines

## Colors

Discord's palette is built for extended screen time in dark environments. The canonical chat background `#36393F` is a warm charcoal — not pure black, not cold grey — chosen so text remains comfortable for hours. The blurple `#5865F2` is the undisputed hero: it marks primary actions, active states, and brand moments. Supporting accents — fuchsia `#EB459E`, yellow `#FEE75C`, green `#57F287`, and red `#ED4245` — are used sparingly for status indicators, reactions, and illustrative flourishes. The overall effect is a dark room lit by colorful neon signs.

**Role usage**:
- Page background → `colors.background.page` (#36393F)
- Card / sidebar surfaces → `colors.background.surface` (#2F3136)
- Input fields / raised surfaces → `colors.background.subtle` (#40444B)
- Primary actions & active states → `colors.primary.500` (#5865F2)
- Success / online status → `colors.accent` green (#57F287)
- Destructive actions → `colors.semantic.error` (#ED4245)
- Mention highlights / boosts → `colors.secondary` fuchsia (#EB459E)
- Warnings / premium badges → semantic warning yellow (#FEE75C)

## Typography

Discord's type voice is clean, compact, and never stuffy. The platform originally used Whitney (Hoefler & Co.), but Inter serves as the public-facing substitute with near-identical metrics. Body copy sits at 16px with a slightly tighter 1.4 line-height — dense enough for chat but not cramped. Headings use semibold weight with subtle negative letter-spacing (-0.015em) to feel confident without shouting. Uppercase text is avoided; the tone is conversational, like a friend sending a message, not a system barking a notification.

**Text styles**:
- `display-xl` — Inter, 96px, weight 800, line-height 1.0, letter-spacing -0.04em
- `display-lg` — Inter, 64px, weight 700, line-height 1.1, letter-spacing -0.02em
- `heading-1` — Inter, 36px, weight 600, line-height 1.2, letter-spacing -0.015em
- `body-lg` — Inter, 18px, weight 400, line-height 1.4, letter-spacing 0
- `body-md` — Inter, 16px, weight 400, line-height 1.4, letter-spacing 0
- `caption` — Inter, 12px, weight 500, line-height 1.3, letter-spacing 0.05em
- `mono-md` — JetBrains Mono, 14px, weight 400, line-height 1.5, letter-spacing 0

## Spacing & Layout

- Base unit: 4px; primary rhythm at 8px multiples
- Spacing scale: 2 / 4 / 6 / 8 / 12 / 16 / 24 / 32 / 48 / 64 / 96 / 128
- Container max-widths: 640 / 768 / 1024 / 1280px
- Section padding: 32px (mobile) → 64px (tablet) → 96px (desktop) → 128px (hero)
- Grid gaps: 8px (tight lists) / 16px (standard) / 24px (cards) / 48px (section grids)

## Elevation & Depth

Discord achieves depth through background-color layering rather than shadows. The chat area sits at `#36393F`, sidebars step down to `#2F3136`, and interactive surfaces like input fields rise to `#40444B`. Shadows are intentionally absent from most UI — the layered-dark approach provides hierarchy without the fussiness of drop shadows. When shadows do appear (popups, modals, context menus), they are heavy and diffuse, appropriate for dark-on-dark contexts.

- Surface style: layered solid fills, no blur/glass
- Primary depth cue: background-color stepping (3 tiers)
- Shadow usage: reserved for floating overlays (modals, tooltips, popovers)
- Shadow intensity: heavier than light-mode conventions (0.24–0.48 opacity)
- No inner shadows on interactive elements

## Shapes

- Button border-radius: 8px (signature rounded pill-like feel)
- Card / panel border-radius: 12px
- Input border-radius: 8px
- Avatar border-radius: 9999px (full circle)
- Small elements (badges, pills): 4px
- Server icons: 16px radius (squircle) when unselected, full circle when active

## Motion

Discord's motion is bouncy and game-like — UI elements pop in rather than fade in. The spring easing (`cubic-bezier(0.34, 1.56, 0.64, 1)`) produces an overshoot-settle feel on tooltips, modals, and micro-interactions. Durations are short (100–350ms) to keep pace with fast chat. The brand leans into "delightful surprise" moments: emoji picker bounce, reaction pop, notification slide-in. Reduced motion support is present for accessibility.

- Level: playful
- Fast interactions (hover, focus): 100ms
- Standard transitions (panel open, tab switch): 200ms
- Emphasized animations (modal entrance, page transition): 350ms
- Easing: default ease-out; spring for enters; ease-in for exits
- Hover patterns: scale (buttons/icons bounce up), tint (blurple wash on hover), opacity (ghost items), glow (focus rings)

## Techniques

### Blurple Gradient Hero

A multi-stop gradient sweep used in Discord's marketing hero sections — blurple to fuchsia — giving the dark canvas a vibrant, atmospheric glow.

```css
.hero-gradient {
  background: linear-gradient(
    135deg,
    #5865F2 0%,
    #7B68EE 35%,
    #EB459E 100%
  );
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
}

.hero-bg-gradient {
  background: radial-gradient(
    ellipse at 30% 50%,
    rgba(88, 101, 242, 0.3) 0%,
    rgba(235, 69, 158, 0.15) 50%,
    transparent 80%
  );
}
```

### Layered Dark Surface Stack

Discord's three-tier depth system — page, surface, subtle — using only background-color shifts, no shadows. Each layer is visually distinct without any elevation artifacts.

```css
.surface-page {
  background-color: #36393F;
}

.surface-sidebar {
  background-color: #2F3136;
}

.surface-input {
  background-color: #40444B;
  border: 1px solid transparent;
  border-radius: 8px;
  transition: border-color 200ms ease;
}

.surface-input:focus-within {
  border-color: #5865F2;
}
```

### Mention Pill Highlight

The inline mention pill that marks @user, @role, and #channel references in chat — a tinted blurple background with matching text that pops against the dark chat surface.

```css
.mention-pill {
  display: inline;
  padding: 0 4px;
  border-radius: 4px;
  background-color: rgba(88, 101, 242, 0.15);
  color: #dee0fc;
  font-weight: 500;
  cursor: pointer;
  transition: background-color 100ms ease;
}

.mention-pill:hover {
  background-color: rgba(88, 101, 242, 0.35);
  color: #ffffff;
}
```

## Iconography

Discord uses clean outline-style icons at 2px stroke weight, keeping them readable at small sizes against dark backgrounds. Icons appear in channel lists (hash for text, speaker for voice), toolbars, and reaction pickers. The style is friendly and geometric — never ornate or hand-drawn — matching the overall "casual tech" personality.

- Treatment: outline, 2px stroke
- Set: Heroicons-adjacent custom set; Heroicons as substitute
- Sizes: 16px (inline), 20px (toolbar), 24px (navigation)

## Do's & Don'ts

### Do
- Use blurple `#5865F2` exclusively for primary actions and active states
- Keep surfaces dark and layered — depth through color steps, not shadows
- Maintain compact, chat-density spacing for app-like interfaces
- Use playful spring easing for micro-interactions and enters
- Let illustrations and color accents carry the brand personality

### Don't
- Use light backgrounds — Discord's canonical experience is dark mode
- Substitute generic blues for blurple — `#5865F2` is the exact value
- Apply brutalist sharp corners or 0-radius edges
- Strip away personality for sterile minimalism — Discord is deliberately playful
- Use serif typefaces — the brand is sans-serif through and through

## Applications

Discord 2024 is ideal for community platforms, real-time chat interfaces, gaming dashboards, and social apps that need to feel inviting during long sessions. The dark palette with punchy accent colors works exceptionally well for notification-heavy, information-dense UIs where users live for hours at a time. It also suits marketing pages that want to project "fun tech" energy — approachable but capable, colorful but not chaotic.
