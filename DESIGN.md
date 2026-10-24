---
name: Warm Editorial Atelier
colors:
  surface: '#fcf9f4'
  surface-dim: '#dcdad5'
  surface-bright: '#fcf9f4'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ee'
  surface-container: '#f0ede9'
  surface-container-high: '#ebe8e3'
  surface-container-highest: '#e5e2dd'
  on-surface: '#1c1c19'
  on-surface-variant: '#544340'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0eb'
  outline: '#87726f'
  outline-variant: '#dac1bd'
  surface-tint: '#95473d'
  primary: '#95473d'
  on-primary: '#ffffff'
  primary-container: '#d97d70'
  on-primary-container: '#581912'
  inverse-primary: '#ffb4a9'
  secondary: '#675d52'
  on-secondary: '#ffffff'
  secondary-container: '#ecddd0'
  on-secondary-container: '#6b6156'
  tertiary: '#865046'
  on-tertiary: '#ffffff'
  tertiary-container: '#c5877b'
  on-tertiary-container: '#4d221a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4a9'
  on-primary-fixed: '#3d0503'
  on-primary-fixed-variant: '#773027'
  secondary-fixed: '#efe0d3'
  secondary-fixed-dim: '#d2c4b7'
  on-secondary-fixed: '#221a12'
  on-secondary-fixed-variant: '#4f453c'
  tertiary-fixed: '#ffdad3'
  tertiary-fixed-dim: '#fbb6a8'
  on-tertiary-fixed: '#351009'
  on-tertiary-fixed-variant: '#6a3930'
  background: '#fcf9f4'
  on-background: '#1c1c19'
  surface-variant: '#e5e2dd'
typography:
  headline-2xl:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-2xl-mobile:
    fontFamily: Playfair Display
    fontSize: 38px
    fontWeight: '600'
    lineHeight: 46px
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
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
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
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
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
  code-inline:
    fontFamily: JetBrains Mono
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
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
  margin: 4rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses a refined, curated, and scholarly technical presence. It bridges high-end editorial elegance with the structural rigor of information technology. The interface conveys intellectual curiosity, craftsmanship, meticulous attention to detail, and approachable sophistication. 

Targeting engineering hiring managers, technical founders, and design-led technology teams, the aesthetic avoids the sterile, dark terminal clichés of typical developer portfolios. Instead, it frames software engineering, systems architecture, and technical projects as deliberate, high-craft disciplines.

The visual style blends **Editorial Minimalism** with **Tactile Soft Glass**:
- Warm, light-bathed cream canvases evoking archival stationery.
- Sculptural typography contrasts between delicate editorial serifs and functional geometric sans.
- Tactile, feather-light surface layers featuring quiet inner glows, micro-borders, and pill-formed interaction points.

## Colors

The palette employs warm tactile naturals grounded by deep espresso typography, animated by soft, terracotta-tinted blush accents.

### Color Roles & Implementation
- **Canvas Base (`#FAF7F2`)**: Soft parchment tone providing non-fatiguing, atmospheric light without the clinical glare of pure `#FFFFFF`.
- **Primary Accent (`#D97D70`)**: Earthy rose terracotta. Used selectively for key interactive moments, primary actions, active timeline nodes, and focal highlights.
- **Secondary Surface (`#EADBCE` / `#F4EFEA`)**: Warm almond-beige tiers used for contextual containers, hover states, code snippet backing, and divider rules.
- **Tertiary Accent (`#E8A598` / `#F7D6D0`)**: Delicate petal tint applied to decorative pill badges, subtle radial glows, selection states, and micro-interactions.
- **Text & Structure (`#2D2926` / `#5A524D`)**: Deep espresso black for primary headings and body; warm slate-charcoal for secondary metadata, timestamps, and captioning. Ensure text never falls below WCAG AAA contrast ratios on neutral backdrops.

## Typography

The type system balances the classical elegance of `Playfair Display` with the pristine, modern geometric clarity of `Plus Jakarta Sans`.

- **Headings**: Use `Playfair Display` for major storytelling anchors: Hero titles, project names, section intros, and thesis themes. Keep italics reserved for expressive punch words (e.g., *"scalable" systems*, *"thoughtful" architecture*).
- **Body & Interfaces**: `Plus Jakarta Sans` provides open apertures and neutral legibility, ideal for technical abstracts, technical stack lists, and interactive UI states.
- **Code & Tech Specs**: Use a warm-tinted `JetBrains Mono` for repository metrics, commit tags, API route pills, and technical specs to reinforce the Information Technology background with poise.

## Layout & Spacing

The layout is built upon an intentional, rhythmic **12-column fixed/max-width grid** (maximum canvas width: `1200px`) centered with generous breathing room.

- **Desktop (1024px+)**: 12 columns with 24px (`1.5rem`) gutters and 64px (`4rem`) outer margins. Editorial side notes and metadata sit in 3-column side rails, with primary project case studies occupying 9 columns.
- **Tablet (768px - 1023px)**: 8 columns, 20px gutters, and 32px margins. Reflow secondary side rails above or below main blocks.
- **Mobile (320px - 767px)**: 4 columns, 16px (`1rem`) gutters, and 20px (`1.25rem`) horizontal margins. Cards reflow strictly into single-column vertical stacks.
- **Vertical Rhythm**: Generous section spacing (`space-xl` scaled dynamically up to 5rem between distinct portfolio chapters) allows technical work to be ingested without cognitive fatigue.

## Elevation & Depth

Depth in this system is ethereal and tactile, avoiding heavy dropped cast shadows in favor of multi-layered ambient light, sub-pixel borders, and subtle inner glows.

- **Base Canvas**: Flat `#FAF7F2`.
- **Level 1 (Card & Section Containers)**: Elevated via translucent fill `rgba(255, 255, 255, 0.7)` supported by a dual treatment:
  - An ambient drop: `box-shadow: 0 10px 30px -10px rgba(45, 41, 38, 0.04)`.
  - An inner glow: `box-shadow: inset 0 1px 1px 0 rgba(255, 255, 255, 0.9)`.
  - A hairline boundary: `border: 1px solid rgba(234, 219, 206, 0.6)`.
- **Level 2 (Interactive Floating Elements, Flyouts, Popovers)**:
  - Fill: `rgba(255, 255, 255, 0.88)` with `backdrop-filter: blur(12px)`.
  - Shadow: `0 18px 40px -12px rgba(45, 41, 38, 0.08)`.
  - Border: `1px solid rgba(217, 125, 112, 0.2)`.

## Shapes

The shape vocabulary uses soft, inviting geometries with distinct hierarchies:
- **Small interactive elements (Badges, Chips, Pills, Buttons)**: Fully pill-shaped (`border-radius: 9999px`) to invite touch and denote active state or technical categorization.
- **Medium cards & feature panels**: `rounded-2xl` (1.5rem / 24px) for harmonious framing of code previews, project cover mockups, and resume blocks.
- **Outer Hero / Featured project wrappers**: `rounded-3xl` (2rem / 32px) to establish a distinctive, friendly architectural envelope.

## Components

### Buttons
- **Primary**: Solid terracotta `#D97D70` background with crisp white `#FFFFFF` text, fully pill-shaped (`9999px`). On hover, transitions smoothly to `#C86C60` with a subtle glow: `box-shadow: 0 4px 16px rgba(217, 125, 112, 0.35)`.
- **Secondary**: Frosted cream background `#F4EFEA`, border `1px solid #EADBCE`, text `#2D2926`. On hover, adopts a warm tint `#EADBCE` with an espresso text shift.
- **Ghost/Tertiary**: Text-only `#5A524D` with an animated terracotta underline that expands from center on hover.

### Chips & Badges
- **Skill / Tech Stack Pills**: Height: 28px, pill-shaped. Background `#F7D6D0` at 40% opacity, border `1px solid rgba(232, 165, 152, 0.5)`, text `#2D2926` in `label-sm` weight.
- **Status Indicators (e.g., "Available for hire Q3")**: Pill badge featuring a soft pulsating emerald or terracotta ping dot alongside `#5A524D` typography.

### Project & Case Study Cards
- Built with `rounded-2xl` boundaries, frosted surface `rgba(255, 255, 255, 0.65)`, backdrop blur `8px`, and `1px solid rgba(234, 219, 206, 0.7)`.
- Cards feature an inner highlight `inset 0 1px 0 rgba(255, 255, 255, 0.8)`. On hover, card raises smoothly (`transform: translateY(-4px)`) and the outer border warms to `#E8A598`.

### Input Fields & Contact Elements
- Generous 48px height, rounded at `0.75rem` (12px).
- Background: `#FAF7F2` with `1px solid #EADBCE`.
- Focus state: Border transitions to `#D97D70` with an outer focus ring `box-shadow: 0 0 0 3px rgba(247, 214, 208, 0.4)`.

### Code Snippets & Architecture Previews
- Background `#2D2926` (espresso charcoal) nested inside the light-cream cards, rounded at `1rem`, providing high-contrast clarity for terminal commands, GitHub repos, and database schemas while preserving the overarching warm palette.