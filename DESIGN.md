---
name: Cyber Tech Precision
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#bdf4ff'
  on-secondary: '#00363d'
  secondary-container: '#00e3fd'
  on-secondary-container: '#00616d'
  tertiary: '#c4cee2'
  on-tertiary: '#273140'
  tertiary-container: '#a9b3c6'
  on-tertiary-container: '#3c4555'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#9cf0ff'
  secondary-fixed-dim: '#00daf3'
  on-secondary-fixed: '#001f24'
  on-secondary-fixed-variant: '#004f58'
  tertiary-fixed: '#d9e3f7'
  tertiary-fixed-dim: '#bdc7da'
  on-tertiary-fixed: '#121c2a'
  on-tertiary-fixed-variant: '#3d4757'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Space Grotesk
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Space Grotesk
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Space Grotesk
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.25rem
  gutter-mobile: 0.75rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system defines a high-precision, futuristic, and premium digital aesthetic for advanced electronics, smartphone, and logic board micro-soldering repair. The brand personality conveys surgical technical mastery, reliability, and modern luxury. It rejects the generic look of neighborhood repair shops in favor of a cleanroom laboratory workbench aesthetic, inspired by microcircuit architecture, aerospace-grade titanium, and cyberpunk engineering refinement.

Targeted at discerning device owners, high-performance tech enthusiasts, and enterprise fleets requiring rapid, dependable repairs, the interface evokes calm precision, state-of-the-art diagnostic authority, and absolute transparency.

The visual style unites **Dark Mode Precision Minimalism** with **Cyber Glassmorphism**:
- Deep obsidian and ebony backdrops that eliminate visual noise and eye strain.
- Specular metallic gold accents inspired by conductive micro-circuit traces and premium hardware detailing.
- Smoked translucent glass surfaces (`backdrop-filter: blur(16px)`) structured with hairline micro-borders that simulate illuminated chassis edges.
- Subtle neon cyan diagnostics accents representing live signal flows, diagnostic telemetry, and active component testing.

## Colors

The color palette centers on a high-contrast dark foundation accented by precious conductive metals and electric diagnostic telemetry:

- **Primary Gold (`#D4AF37`)**: Reflects circuit contacts, gold plating, and premium tier craftsmanship. Supported by `#F5D77F` (active metallic sheen, hover states, specular highlights) and `#997B24` (subdued circuit tracks, dark-fill accents).
- **Secondary Cyber Cyan (`#00E5FF`)**: Represents active digital current, telemetry, online status, diagnostic signals, and live repair updates. Used deliberately to avoid overwhelming the regal gold-on-black hierarchy.
- **Tertiary Titanium Grey (`#8A94A6`)**: Simulates anodized aluminum and brushed chassis metals; used for secondary labels, passive status indicators, and perimeter borders.
- **Neutral Foundation (`#0A0A0C`)**: Pure void black tinted with an imperceptible ebony undertone. Paired with elevated dark tiers: `#111116` (surface base) and `#191A23` (surface elevated/glass substrate).
- **Semantic Accents**:
  - Success/Calibrated: `#00FF9D` (micro-LED green)
  - Critical/Component Fault: `#FF3366` (laser fault red)
  - Pending/Testing: `#FFB800` (amber warning)

## Typography

The typographic hierarchy combines the technical, geometric character of **Space Grotesk** for display headers, operational metrics, and status badges with the ultra-legible clarity of **Inter** for descriptions, diagnostics specs, and order tracking.

- **Display & Headlines (`Space Grotesk`)**: Conveys technological precision with distinct geometric cuts and mechanical rhythm. Large numbers, service titles, and critical device models use tight tracking (`-0.02em`) to mimic instrumentation readouts.
- **Body & Data (`Inter`)**: Neutral, neutral-grotesque rendering ensures dense diagnostic data, service terms, and quote breakdowns remain readable under low-light or outdoor repair scenarios.
- **Labels & Micro-indicators (`Space Grotesk`)**: Monospaced-inspired uppercase treatments with expanded tracking (`0.06em` to `0.08em`) create a serialized hardware aesthetic (e.g., `SERIAL NO:`, `STAGE 03: MICRO-SOLDERING`).

## Layout & Spacing

The layout is anchored in an 8pt architectural rhythm structured around a responsive 12-column fluid grid on desktop and tablet, collapsing to 4 columns on mobile viewports.

- **Desktop (1024px+)**: 12-column grid, max-width `1280px` centered container, with `2rem` outer padding and `1.25rem` gutters. Allows side-by-side inspection layouts (e.g., Live Service Camera/Microscope feed alongside Part Inventory & Diagnostic Checklist).
- **Tablet (768px - 1023px)**: 8-column layout, `1.5rem` outer margins, `1rem` gutters.
- **Mobile (< 768px)**: 4-column layout, `1rem` outer canvas margin, and `0.75rem` gutters. Touch targets for field technicians and customers always maintain a minimum height of 48px.
- **Rhythm Principle**: Internal card padding matches `space-lg` (`1.5rem`), while micro-gap groupings (badges, chip tags, pinouts) use `space-xs` and `space-sm` to maintain dense, instrument-panel coherence.

## Elevation & Depth

Visual hierarchy does not use soft natural sunlight shadows; instead, it utilizes **layered smoked glass**, **ambient hardware glows**, and **specular micro-borders**:

- **Ground Level (Canvas)**: Solid obsidian `#0A0A0C` overlaid with an optional subtle SVG circuit trace grid at 4% opacity.
- **Surface Level 1 (Cards, Modules)**: Translucent obsidian `#111116` at 85% opacity with `backdrop-filter: blur(14px)`. Border is a crisp `1px solid rgba(212, 175, 55, 0.15)` (subtle gold sheen).
- **Surface Level 2 (Hover / Active Focus / Flyouts)**: Elevated obsidian `#1A1A24` at 90% opacity, bordered by `1px solid rgba(212, 175, 55, 0.45)`, accompanied by a restrained golden contact glow: `box-shadow: 0 0 20px rgba(212, 175, 55, 0.12), 0 8px 32px rgba(0, 0, 0, 0.6)`.
- **Diagnostic / Signal Level (Modals, Overlays, Active Alerts)**: Smoked acrylic backdrop with cyan halo edge: `1px solid rgba(0, 229, 255, 0.35)` and ambient aura `box-shadow: 0 0 25px rgba(0, 229, 255, 0.15)`.

## Shapes

The shape vocabulary is strictly disciplined and architectural. It employs **Level 1 (Soft)** rounding to evoke precision cut smartphone glass, CNC-machined aluminum unibody components, and integrated circuit dies.

- **Base Components (Inputs, Buttons, Cards)**: `4px` to `6px` radius (`rounded-sm`), delivering an authoritative, technical profile without organic blob softness.
- **Diagnostic Badges & Micro-Pills**: `4px` chamfered feel or strict `rounded-sm` geometry. Pill-shapes are restricted only to interactive status toggle toggles or hardware connector chips.
- **Technical Circuit Notches**: Select hero modules and status panels may feature an angled 45-degree chamfered corner (`clip-path` notch) on top-right edges to directly echo the brand logo’s PCB tracing motifs.

## Components

### Buttons
- **Primary Cyber Gold**: Metallic gold gradient fill (`linear-gradient(135deg, #F5D77F 0%, #D4AF37 50%, #B89228 100%)`), sharp obsidian typography (`#0A0A0C`, Space Grotesk Bold, Uppercase), subtle gold edge shine. Hover adds `box-shadow: 0 0 16px rgba(212, 175, 55, 0.45)`.
- **Secondary Titanium Glass**: Smoked translucent surface (`rgba(25, 26, 35, 0.65)`), `1px solid rgba(212, 175, 55, 0.3)`, text in `#F5D77F`. Hover transitions border to full cyan or vibrant gold.
- **Diagnostic Glow (Action)**: Dark background with `1px solid #00E5FF`, cyan text, emitting a subtle neon perimeter pulse during repair tracking or test runs.

### Input Fields
- Deep matte black container (`#0E0E12`) with `1px solid rgba(138, 148, 166, 0.25)`. Monospaced placeholder styling.
- Focus state: Border transitions instantly to `#D4AF37` with an inner and outer micron glow (`box-shadow: 0 0 0 1px #D4AF37, 0 0 12px rgba(212, 175, 55, 0.2)`).

### Cards & Workbenches
- Dark glass panels with razor-thin top highlight line (`linear-gradient(90deg, transparent, rgba(212,175,55,0.4), transparent)`).
- Contains metadata header with serialized font styling and monospace device diagnostic indicators (e.g., `LOGIC BOARD: A2338 • CURRENT STAGE: REBALLING`).

### Status Badges & Chips
- Miniature rectangular tags with rounded corners (`rounded-sm`).
- Consists of a blinking neon micro-dot (`#00FF9D` for "Repaired", `#00E5FF` for "In Diagnosis", `#FFB800` for "Awaiting Component") accompanied by tracked-out Space Grotesk text.

### Progress & Telemetry Bars
- Segmented circuit bar tracks instead of continuous soft bars. Unfilled segments sit in faint titanium `rgba(255, 255, 255, 0.08)`, while active segments illuminate in luminous gold with cyan step markers.