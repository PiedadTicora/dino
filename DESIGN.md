---
name: Tectonic Precision
colors:
  surface: '#121316'
  surface-dim: '#121316'
  surface-bright: '#38393c'
  surface-container-lowest: '#0d0e11'
  surface-container-low: '#1b1b1f'
  surface-container: '#1f1f23'
  surface-container-high: '#292a2d'
  surface-container-highest: '#343538'
  on-surface: '#e3e2e6'
  on-surface-variant: '#d1c5b8'
  inverse-surface: '#e3e2e6'
  inverse-on-surface: '#2f3034'
  outline: '#998f83'
  outline-variant: '#4d463c'
  surface-tint: '#e0c298'
  primary: '#e2c399'
  on-primary: '#402d0f'
  primary-container: '#c5a880'
  on-primary-container: '#513d1d'
  inverse-primary: '#725b38'
  secondary: '#c0c6d7'
  on-secondary: '#2a313d'
  secondary-container: '#404755'
  on-secondary-container: '#aeb5c5'
  tertiary: '#c1c8d5'
  on-tertiary: '#2a313b'
  tertiary-container: '#a6adb9'
  on-tertiary-container: '#3a414b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#fedeb2'
  primary-fixed-dim: '#e0c298'
  on-primary-fixed: '#281800'
  on-primary-fixed-variant: '#584323'
  secondary-fixed: '#dce2f4'
  secondary-fixed-dim: '#c0c6d7'
  on-secondary-fixed: '#151c28'
  on-secondary-fixed-variant: '#404755'
  tertiary-fixed: '#dce3f0'
  tertiary-fixed-dim: '#c0c7d3'
  on-tertiary-fixed: '#151c25'
  on-tertiary-fixed-variant: '#404752'
  background: '#121316'
  on-background: '#e3e2e6'
  surface-variant: '#343538'
typography:
  display-hero:
    fontFamily: Space Grotesk
    fontSize: 5rem
    fontWeight: '400'
    lineHeight: 5.25rem
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Space Grotesk
    fontSize: 2.75rem
    fontWeight: '400'
    lineHeight: 3rem
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 3rem
    fontWeight: '500'
    lineHeight: 3.5rem
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 2rem
    fontWeight: '500'
    lineHeight: 2.375rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 1.75rem
    fontWeight: '500'
    lineHeight: 2.125rem
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.625rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
    letterSpacing: 0em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.375rem
    letterSpacing: 0.01em
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 0.75rem
    fontWeight: '500'
    lineHeight: 1rem
    letterSpacing: 0.08em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 0.6875rem
    fontWeight: '600'
    lineHeight: 0.875rem
    letterSpacing: 0.12em
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 2rem
  space-xl: 3.5rem
  space-2xl: 6rem
---

## Brand & Style

This design system embodies the tension between industrial precision and bespoke luxury. It serves an audience of architects, interior curators, and design collectors who value materiality, structural permanence, and understated refinement. The interface acts as a silent gallery—austere yet tactile, technical yet deeply sophisticated.

The aesthetic fuses **Architectural Minimalism** with **Industrial Brutalist Restraint**:
- Monolithic structures, disciplined grids, and hairline delineations emulate raw metal fabrication and architectural blueprints.
- High editorial whitespace frames heavy metallic volumes, treating each piece of furniture like a structural monument.
- Micro-interactions are deliberate and dampened, mimicking the frictionless glide of milled steel drawers, brass pivots, and architectural hardware.

## Colors

The palette draws inspiration directly from the metallurgist’s studio and architectural foundry. It operates primarily in deep, light-absorbing darks to allow metallic finishes and curated photography to gleam with restrained authority.

- **Foundational Darks**: Base canvas is Deep Carbon (`#121316`), paired with Surface Gunmetal (`#1A1C20`) to establish tonal planes without stark contrast.
- **Structural Steels**: Brushed Steel Mid-tones (`#2C2F36`, `#4B5260`) and Polished Nickel (`#9CA3AF`) govern structural hair lines, metadata, secondary toggles, and technical diagrams.
- **Architectural Accent**: Aged Brass (`#C5A880`) is reserved strictly for focal points—active states, checkout highlights, and premium dimension tags. A brighter burnished gold (`#D4AF37`) functions as an interactive hover flash.
- **Typographic Clarity**: Off-White Chalk (`#F8F9FA`) provides high-legibility typographic contrast while mitigating the glare of pure white.

## Typography

The typographical pairing anchors architectural discipline against crisp contemporary digital product conventions:

- **Headlines (Space Grotesk)**: Chosen for its structural geometries, mechanical precision, and architectural lineage. Character shapes feel drafted rather than merely drawn. Use lower tracking on large sizes for a monument-carved presence.
- **Editorial & Body (Plus Jakarta Sans)**: Balances modern geometric balance with humanized readability, rendering structural specs, material certifications, and narratives effortlessly legible.
- **Spec Data & Metadata (JetBrains Mono)**: Injected for industrial dimensioning (weight, tolerances, alloys, millimeter measurements, serial codes). It adds the clinical feel of structural engineering blueprints.
- **Case Rule**: All category tags and specification markers utilize uppercase tracking (`label-caps` and `label-mono`).

## Layout & Spacing

The layout model mimics an architect’s drafting board: expansive, calculated, and disciplined.

- **Grid Architecture**: A 12-column responsive fluid grid bounded by a maximum content width of `1680px`. 
  - **Desktop (≥ 1024px)**: 12 columns with `2.5rem` gutters and `4rem` external framing margins.
  - **Tablet (768px - 1023px)**: 8 columns with `1.5rem` gutters and `2rem` external margins.
  - **Mobile (< 768px)**: 4 columns with `1rem` gutters and `1.25rem` margins.
- **Rhythm**: Generous vertical cadences (`space-xl` to `space-2xl`) frame individual furniture pieces in isolation, avoiding the cluttered aesthetic of conventional consumer e-commerce.
- **Modular Cadence**: Sections snap to vertical and horizontal division lines (1px steel rules), grounding modular product listings like precision-machined joints.

## Elevation & Depth

To avoid breaking the minimalist, industrial ethos, depth is articulated through **tonal planes** and **micro-hairline containment**, never blurry drop shadows.

- **Zero Drop-Shadows**: Shadows are completely eliminated across baseline components. No blurry ambient drop shadows exist in the core UI.
- **Layered Sheet Metal Stacking**: Depth is achieved via surface tonal shifts:
  - Base canvas: `#121316`
  - Floating panels / drawers / drawers-out: `#1A1C20`
  - Inspection drawers / overlays: `#22252B`
- **Precision Hairlines (Ghost Seams)**: Boundaries between surfaces are demarcated using 1px borders colored in Brushed Steel (`#2C2F36` at default, transitioning to `#4B5260` on interaction).
- **Backdrop Diffusion**: Modals and sticky structural bars use frosted dark-metallic glass (`rgba(18, 19, 22, 0.82)` with `20px` background blur) to keep focus anchored while retaining spatial context.

## Shapes

The form language is strictly **monolithic and geometric (Sharp, Level 0)**. 

- Radii across the system are set to `0px`. Corners are sharp and orthogonal, reflecting cold-rolled sheets, laser-cut plates, and extruded metallic beams.
- Any attempt to soften with rounded corners erodes the heavy architectural gravity of the system.
- Pill forms and bubble elements are strictly banned. Tags, indicators, chips, and modals must remain pure rectangles and squares.

## Components

### Buttons & Interactive Controls
- **Primary Action (Aged Brass Monolith)**: Solid background in `#C5A880` with dark charcoal text (`#121316`), zero border radius, sharp corners. On hover, background shifts seamlessly to Burnished Gold (`#D4AF37`) with a subtle `translateX(4px)` arrow icon response.
- **Secondary Action (Milled Frame)**: Transparent background, 1px solid `#4B5260` border, `#F8F9FA` text. On hover, background transitions to `#1A1C20` and border illuminates to `#9CA3AF`.
- **Text Link / Technical Trigger**: JetBrains Mono uppercase with an underline that expands from 0% to 100% width on hover.

### Product Cards
- Defined by a 1px border (`#2C2F36`) framing an expansive aspect ratio (4:5 or 1:1) photographic viewport.
- Canvas background inside card: `#1A1C20`.
- Meta-information is docked at the base: Title in `Space Grotesk`, dimensions and alloy spec tags in `label-mono` (`#9CA3AF`), and price in `Aged Brass` (`#C5A880`).
- Hover triggers an image transition showing fabrication detail or a 360-degree exploded view, with a discrete brass corner indicator.

### Input Fields & Selectors
- Flat surfaces embedded into `#121316` with a bottom-only or fully enclosed 1px hairline (`#2C2F36`).
- Floating labels in `JetBrains Mono` that lock into an architectural upper-case state when focused.
- Active focus state: Hairline shifts cleanly to `#C5A880` without outer glow.

### Checkboxes & Radio Elements
- Sharp 16x16px squares.
- Unchecked: 1px border `#4B5260` with `#121316` inner fill.
- Checked: Solid `#C5A880` fill with a pure black `#121316` architectural check mark or inner square pip.

### Material Swatches & Chips
- Rectangular blocks displaying physical materials (e.g., Cold Rolled Steel, Patinated Brass, Brushed Titanium).
- Active state delineated by an outer 1px hairline offset in `#C5A880` separated by a 2px dark air gap.

### Specialized Architectural Components
- **Spec Sheet Drawer**: A sliding side-sheet with technical CAD line drawings, isometric views, load tolerances, and material certifications.
- **Dimension Overlay Switch**: A global toggle that overlays true millimeter dimensions directly on product imagery using vector callout lines and `#C5A880` mono callouts.