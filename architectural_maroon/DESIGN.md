---
name: Architectural Maroon
colors:
  surface: '#fdf8fa'
  surface-dim: '#ddd9db'
  surface-bright: '#fdf8fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f2f4'
  surface-container: '#f1edef'
  surface-container-high: '#ece7e9'
  surface-container-highest: '#e6e1e3'
  on-surface: '#1c1b1d'
  on-surface-variant: '#564242'
  inverse-surface: '#313032'
  inverse-on-surface: '#f4eff1'
  outline: '#897171'
  outline-variant: '#dcc0c0'
  surface-tint: '#a33b44'
  primary: '#5b0214'
  on-primary: '#ffffff'
  primary-container: '#7a1c28'
  on-primary-container: '#ff898f'
  inverse-primary: '#ffb3b4'
  secondary: '#9e3f47'
  on-secondary: '#ffffff'
  secondary-container: '#fd898f'
  on-secondary-container: '#75202a'
  tertiary: '#5c0012'
  on-tertiary: '#ffffff'
  tertiary-container: '#840520'
  on-tertiary-container: '#ff898d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdada'
  primary-fixed-dim: '#ffb3b4'
  on-primary-fixed: '#40000b'
  on-primary-fixed-variant: '#83232e'
  secondary-fixed: '#ffdada'
  secondary-fixed-dim: '#ffb3b5'
  on-secondary-fixed: '#40000b'
  on-secondary-fixed-variant: '#7f2831'
  tertiary-fixed: '#ffdad9'
  tertiary-fixed-dim: '#ffb3b4'
  on-tertiary-fixed: '#40000a'
  on-tertiary-fixed-variant: '#8e1026'
  background: '#fdf8fa'
  on-background: '#1c1b1d'
  surface-variant: '#e6e1e3'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.025em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses curatorial authority, spatial elegance, and architectural distinction. Built for a premium venue reservation ecosystem, the interface evokes the quiet confidence of a high-end monograph while maintaining the frictionless utility expected of modern digital concierge services.

The design movement combines **Minimalism** with **Modern Tactile Restraint**:
- Generous spatial margins and intentional negative space reflect architectural drafting discipline.
- Deep maroon surfaces provide regal weight, balancing clean white planar surfaces.
- Sharp typographic rhythm paired with subtly rounded structural geometry creates an editorial, humanized luxury aesthetic.
- The interface evokes feelings of exclusivity, structural precision, calm discernment, and bespoke hospitality.

## Colors

The palette relies on deliberate contrast between profound vinous maroons and clean, luminous surfaces.

### Primary Spectrum
- **Primary Brand (`#7A1C28`)**: Deep Burgundy. Used for primary interactive triggers, active navigation markers, key architectural labels, and dominant accents.
- **Deep Maroon / Primary Dark (`#63121E`)**: Anchoring shade for hover states, prominent headers, solid dark panels, and structural footers.
- **Vibrant Maroon / Accent (`#9B1C2E`)**: Energetic wine accent reserved for badges, availability callouts, highlights, and critical micro-interactions.

### Canvas & Surface Hierarchy
- **Canvas Base (`#FBF8F9`)**: Warm, tinted alabaster background that avoids clinical glare and softens high-resolution photography.
- **Surface Neutral (`#F5F0F2`)**: Secondary neutral tone for inactive controls, nested section cards, dividers, and table headers.
- **Pure White (`#FFFFFF`)**: Strictly applied to floating cards, active panels, modals, and input fields to elevate them crisply above the canvas.

### Content & Text
- **Text Primary (`#1E1215`)**: Deep obsidian-maroon for ultra-high legibility without pure black harshness.
- **Text Secondary (`#6B585C`)**: Muted plum-gray for architectural metadata, floor specs, and secondary descriptors.
- **Border Subtle (`#EADEE2`)**: Soft structural outlines anchoring floating containers.

## Typography

Plus Jakarta Sans is utilized across all typographic roles. Its clean geometric underpinnings evoke contemporary architectural identity, while humanist terminal cuts prevent sterile detachment.

- **Headlines (`headline-xl`, `headline-lg`)**: Tight tracking (`-0.025em` to `-0.02em`) gives architectural titles a modern, editorial density. Headings should be displayed in deep maroon `#63121E` or high-contrast primary text `#1E1215`.
- **Body (`body-lg`, `body-md`)**: Relaxed line heights ensure high readability for venue narratives, amenity indices, and technical booking terms.
- **Labels & Micro-copy (`label-lg`, `label-md`, `caption`)**: Subtle positive tracking (`0.01em` to `0.04em`) ensures architectural metrics (e.g., square footage, seating capacity, acoustics ratings) remain distinct at compact scales.

## Layout & Spacing

The layout is built upon an architectural grid with deliberate breathing room around physical assets and venue photography.

### Grid Structure
- **Desktop (>= 1200px)**: 12-column fluid grid, `3rem` section margins, and `1.5rem` gutters. Maximum content bound sits at `1440px`.
- **Tablet (768px - 1199px)**: 8-column grid with `2rem` outer margins and `1.25rem` gutters.
- **Mobile (<= 767px)**: 4-column responsive grid with `1.25rem` margins and `1rem` gutters. Sticky bottom actions reserve `space-lg` buffer clearance.

### Spacing Cadence
- Use `space-xs` (4px) and `space-sm` (8px) for internal pill padding and pairing iconography to labels.
- Use `space-md` (16px) for intra-component flow: input interior padding, metadata clusters, and card headers.
- Use `space-lg` (24px) for card body padding and stack margins between descriptive modules.
- Use `space-xl` (40px) for layout section divisions and structural content grouping.

## Elevation & Depth

Spatial hierarchy relies on layered architectural planes, subtle warm-tinted ambient shadows, and crisp surface borders rather than dense drop shadows.

- **Level 0 (Flat Canvas)**: Background `#FBF8F9`. Passive substrate.
- **Level 1 (Structural Cards & Modules)**: Pure white `#FFFFFF` surface bordered by a 1px solid stroke in `#EADEE2`. Supported by an ultra-diffuse ambient shadow: `0px 4px 20px -2px rgba(99, 18, 30, 0.04)`.
- **Level 2 (Interactive Hover & Focus Panels)**: Pure white `#FFFFFF`, border shifts to `#7A1C28` at 30% alpha, with elevated depth: `0px 12px 32px -4px rgba(99, 18, 30, 0.08)`.
- **Level 3 (Overlays, Date Selectors, Booking Drawer)**: Pure white `#FFFFFF` or deep maroon `#63121E` container with `0px 24px 48px -8px rgba(30, 18, 21, 0.16)`.
- **Glass Shading**: Semi-translucent panels (e.g., sticky venue summary bars) utilize `rgba(255, 255, 255, 0.85)` with `16px` backdrop-blur and a 1px border of `rgba(234, 222, 226, 0.6)`.

## Shapes

The geometric silhouette combines softened contemporary curves with architectural stability.

- **Base Radius (`0.5rem` / 8px)**: Used on small controls, badge tags, form text fields, and segmented control chips.
- **Large Radius (`1rem` / 16px)**: Standard for primary interactive buttons, standard imagery cutouts, and venue feature callouts.
- **Extra Large Radius (`1.5rem` / 24px)**: Reserved for primary architectural cards, booking panels, modals, and spatial showcase containers.
- **Image Treatment**: All venue gallery viewports feature `rounded-xl` (1.5rem) or `rounded-2xl` masking with an inner `1px inset rgba(0,0,0,0.04)` border to emulate framed structural models.

## Components

### Buttons
- **Primary**: Solid Deep Burgundy `#7A1C28` with `#FFFFFF` text. Height 48px, horizontal padding `1.5rem`, `rounded-lg` (16px). Hover elevates to `#63121E` with subtle lift.
- **Secondary**: Pure `#FFFFFF` surface with 1.5px solid `#7A1C28` stroke and `#7A1C28` text. Hover fills to `#F5F0F2`.
- **Ghost/Tertiary**: Transparent surface with `#7A1C28` text, transitioning to `#F5F0F2` background on active contact.

### Cards & Venue Containers
- Structural cards feature `#FFFFFF` fill, `1.5rem` border radius, 1px `#EADEE2` outline, and `1.5rem` interior padding.
- Card media modules include an integrated gradient vignette overlay at the base for capacity and pricing labels in crisp white typography.

### Chips & Filters
- **Filter Chips**: Inactive state features `#F5F0F2` background, `#6B585C` text, and border-free silhouette (`rounded-md`).
- **Selected Filter**: Deep burgundy `#7A1C28` fill with `#FFFFFF` text and smooth scale transition.

### Inputs & Selectors
- Background is `#FFFFFF` with a 1px `#EADEE2` border, `0.75rem` radius, and `0.875rem 1rem` padding.
- Active focus state introduces a 1.5px border of `#7A1C28` paired with a delicate `0 0 0 3px rgba(122, 28, 40, 0.1)` focus halo.

### Checkboxes & Radios
- Unchecked boxes feature a 1.5px stroke of `#6B585C` on `#FFFFFF`.
- Checked state transitions cleanly to `#7A1C28` solid fill with a sharp white geometric checkmark or inner core dot.

### Architectural Floor Plan & Spec Drawer
- Specialized slide-over panel with `#FFFFFF` background, high-elevation Level 3 shadow, containing structural dimension badges, BIM/CAD download triggers, and high-contrast capacity tables styled with `#F5F0F2` row striping.