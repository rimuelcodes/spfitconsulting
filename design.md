---
name: Obsidian Kinetic
colors:
  surface: '#131314'
  surface-dim: '#131314'
  surface-bright: '#3a393a'
  surface-container-lowest: '#0e0e0f'
  surface-container-low: '#1c1b1c'
  surface-container: '#201f20'
  surface-container-high: '#2a2a2b'
  surface-container-highest: '#353436'
  on-surface: '#e5e2e3'
  on-surface-variant: '#cec2d6'
  inverse-surface: '#e5e2e3'
  inverse-on-surface: '#313031'
  outline: '#988d9f'
  outline-variant: '#4c4354'
  surface-tint: '#dbb8ff'
  primary: '#dbb8ff'
  on-primary: '#470083'
  primary-container: '#7928ca'
  on-primary-container: '#e1c4ff'
  inverse-primary: '#7f30d0'
  secondary: '#d3fbff'
  on-secondary: '#00363a'
  secondary-container: '#00eefc'
  on-secondary-container: '#00686f'
  tertiary: '#c0c1ff'
  on-tertiary: '#1000a9'
  tertiary-container: '#4244d0'
  on-tertiary-container: '#cbcbff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#efdbff'
  primary-fixed-dim: '#dbb8ff'
  on-primary-fixed: '#2b0052'
  on-primary-fixed-variant: '#6600b7'
  secondary-fixed: '#7df4ff'
  secondary-fixed-dim: '#00dbe9'
  on-secondary-fixed: '#002022'
  on-secondary-fixed-variant: '#004f54'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#131314'
  on-background: '#e5e2e3'
  surface-variant: '#353436'
typography:
  display-hero:
    fontFamily: Sora
    fontSize: 4.5rem
    fontWeight: '600'
    lineHeight: '1.05'
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Sora
    fontSize: 2.75rem
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.03em
  headline-xl:
    fontFamily: Sora
    fontSize: 3rem
    fontWeight: '600'
    lineHeight: '1.15'
    letterSpacing: -0.035em
  headline-xl-mobile:
    fontFamily: Sora
    fontSize: 2rem
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Sora
    fontSize: 2rem
    fontWeight: '500'
    lineHeight: '1.25'
    letterSpacing: -0.025em
  headline-md:
    fontFamily: Sora
    fontSize: 1.5rem
    fontWeight: '500'
    lineHeight: '1.3'
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Sora
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Geist
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: '1.7'
    letterSpacing: -0.01em
  body-md:
    fontFamily: Geist
    fontSize: 0.9375rem
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: -0.005em
  body-sm:
    fontFamily: Geist
    fontSize: 0.8125rem
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-mono:
    fontFamily: Geist
    fontSize: 0.6875rem
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.08em
  label-caps:
    fontFamily: Sora
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: 0.12em
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-tablet: 2.5rem
  margin-desktop: 5rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system defines an architectural, computational aesthetic crafted for elite technology advisory and digital transformation practices. The identity merges high-contrast editorial minimalism with the kinetic luminescence of advanced machine intelligence. It rejects frivolous ornament in favor of strict rectilinear discipline, hyper-refined micro-details, and expansive spatial rhythms.

The visual presence evokes the atmosphere of an executive mission-control suite or a cinematic laboratory: deep obsidian voids, razor-sharp 1px coordinate boundaries, and laser-precise chromatic transitions from electric violet into cybernetic cyan. Every interface surface communicates definitive authority, engineering rigor, and structural permanence.

## Colors

The palette operates on an absolute dark-mode foundation, rooted in `#0B0B0C` (Void Obsidian) and `#121316` (Deep Midnight). Surface elevation tiers ascend subtly through `#15161A` to `#1C1E24`, separated not by fuzzy shadows but by structural `#262833` hairline delineation.

Accents are deployable in focused bursts:
- **Primary Violet (`#7928CA`):** Symbolizes computation, executive luxury, and depth.
- **Secondary Cyan (`#00F0FF`):** Represents dynamic telemetry, critical telemetry states, and data flows.
- **Spectral Data Gradient:** A linear vector transitioning from `#00F0FF` through `#6366F1` to `#7928CA`, reserved exclusively for active states, key metric highlights, and cinematic divider strokes.

Foreground contrast is strictly balanced: Primary headlines utilize `#FFFFFF` (Stark White), while metadata, technical subheaders, and tabular figures leverage `#94A3B8` and `#64748B` (Titanium Slate). Inactive architectural gridlines sit at `#1E2029`.

## Typography

The typographic hierarchy establishes tension between the sculpted, geometric posture of `Sora` and the stark, developer-grade precision of `Geist`.

- **Headlines (`Sora`):** Rendered with negative tracking and disciplined line heights. Large display scales embrace an architectural presence, grounding editorial section anchors with weight and confidence.
- **Body & Metrics (`Geist`):** Delivers uncompromised legibility for dense technical consulting narratives, analytical breakdowns, and transformation roadmaps.
- **Metadata & Technical Overlays (`label-mono` / `label-caps`):** Must always be set uppercase with deliberate positive tracking (`0.08em` to `0.12em`), providing an authentic computational telemetry aesthetic across coordinate stamps, phase numbers, and system states.

## Layout & Spacing

Layouts adhere to an uncompromising modular framework built on an 8pt base coordinate rhythm. 

- **Grid Framework:** A 12-column structural grid across desktop (1024px+) with generous 2.5rem gutters, condensing to an 8-column layout on tablet (768px-1023px) and a 4-column layout on mobile (<768px).
- **Structural Framing:** Interfaces rely on continuous 1px perimeter gutters. Key sections feature technical coordinate lines extending to the canvas edge, terminated by subtle 4px corner registration ticks (`+` markers) at intersecting columns.
- **Editorial Whitespace:** Generous vertical sections leverage `space-2xl` and `space-3xl` to preserve high-prestige executive pacing, preventing visual overcrowding despite high data density.

## Elevation & Depth

This design system deliberately excludes heavy, blurry dropshadows in favor of razor-sharp surface contrasts, hairline structural borders, and targeted luminescent back-glows.

1. **Surface Strata:**
   - **Canvas Level 0 (`#0B0B0C`):** Base vacuum layer.
   - **Container Level 1 (`#121316`):** Standard panel background, outlined with `1px solid #262833`.
   - **Overlay Level 2 (`#18191E`):** Floating navigation and flyout dialogs, outlined with `1px solid #323544`.
2. **Hairline Geometry:** Depth is reinforced through crisp `1px` borders. Surfaces never blend into each other; they clip with microscopic clarity.
3. **Photon Bleed (Accent Glow):** When interactive cards or active hero elements achieve focus, depth is signaled via an ultra-concentrated perimeter gradient stroke or an ultra-diffused atmospheric back-glow: `box-shadow: 0 0 30px -10px rgba(121, 40, 202, 0.35)`.

## Shapes

The shape grammar adheres strictly to a 0px rectilinear paradigm. All containers, interactive triggers, cards, dialogs, and tags terminate in pure right angles. 

Corners must never be softened with standard corner radii; precision is communicated through structural rigidity. Corner treatments are articulated exclusively via 1px border intersections, micro-chamfer cutouts, or surgical crosshair markers located at bounding edges.

## Components

### Buttons & Interactive Triggers
- **Primary Action:** Solid `#FFFFFF` fill with `#0B0B0C` typography in `Geist` medium, 0px border radius, accompanied by a dynamic `1px` accent inset on hover.
- **Secondary Action:** Transparent base, `1px solid #262833` border, white text. On hover, the border transforms to the Cyan-to-Violet gradient (`#00F0FF` to `#7928CA`) with an instantaneous ambient back-glow.
- **Kinetic Magnetism:** CTAs feature directional arrow icons configured on an inline track that shifts `+4px` horizontally on interaction.

### Cards & Telemetry Containers
- **Construction:** Grounded in `#121316` with a uniform `1px solid #262833` stroke.
- **Metadata Badges:** Top-pinned uppercase mono identifiers (e.g., `// REF: DATA_01`) set in `#64748B`.
- **Hover State:** The container border transitions to `#7928CA` with subtle localized radial lighting centered on the cursor position.

### Chips & Precision Badges
- Strict rectangular tags featuring `padding: 0.25rem 0.5rem`.
- Inactive: `#18191E` fill with `1px solid #262833` and `#94A3B8` text.
- Active: `#7928CA` tinted background (`rgba(121, 40, 202, 0.15)`), `1px solid #7928CA` stroke, and bright `#00F0FF` telemetry dot.

### Form Inputs & Selectors
- Dark recessed background (`#0E0F12`), `1px solid #262833` perimeter.
- Focus State: Hard switch to `1px solid #00F0FF` with a subtle zero-blur horizontal indicator bar beneath the input.
- Typography: `#FFFFFF` input text with `#64748B` placeholder values in `Geist`.

### Selection Controls (Checkbox & Radio)
- Rectangular 16x16px boxes with absolute 0px border radius.
- Unchecked: `#121316` surface, `1px solid #262833`.
- Checked: `#7928CA` fill containing a pure geometric cyan (`#00F0FF`) center pixel block.

### Horizontal Showcase & Timeline
- Segmented linear stage rail with numeric coordinate readouts (`01 / 04`).
- Visual progress tracks utilize an ultra-thin 1px line that fills with the kinetic gradient (`#00F0FF` to `#7928CA`) as stages advance.
