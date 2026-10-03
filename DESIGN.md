---
name: Luminous Glass Developer Portfolio
colors:
  surface: '#121317'
  surface-dim: '#121317'
  surface-bright: '#38393e'
  surface-container-lowest: '#0d0e12'
  surface-container-low: '#1a1b20'
  surface-container: '#1f1f24'
  surface-container-high: '#292a2e'
  surface-container-highest: '#343439'
  on-surface: '#e3e2e8'
  on-surface-variant: '#bcc8ce'
  inverse-surface: '#e3e2e8'
  inverse-on-surface: '#2f3035'
  outline: '#879398'
  outline-variant: '#3d484d'
  surface-tint: '#5bd5fc'
  primary: '#93e2ff'
  on-primary: '#003543'
  primary-container: '#4cc9f0'
  on-primary-container: '#005266'
  inverse-primary: '#006780'
  secondary: '#ffb1c6'
  on-secondary: '#650031'
  secondary-container: '#e20476'
  on-secondary-container: '#fffbff'
  tertiary: '#eacbff'
  on-tertiary: '#4b007d'
  tertiary-container: '#d9a7ff'
  on-tertiary-container: '#7105b6'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b7eaff'
  primary-fixed-dim: '#5bd5fc'
  on-primary-fixed: '#001f28'
  on-primary-fixed-variant: '#004e61'
  secondary-fixed: '#ffd9e1'
  secondary-fixed-dim: '#ffb1c6'
  on-secondary-fixed: '#3f001c'
  on-secondary-fixed-variant: '#8e0048'
  tertiary-fixed: '#f2daff'
  tertiary-fixed-dim: '#e0b6ff'
  on-tertiary-fixed: '#2e004e'
  on-tertiary-fixed-variant: '#6b00af'
  background: '#121317'
  on-background: '#e3e2e8'
  surface-variant: '#343439'
typography:
  display-hero:
    fontFamily: Inter
    fontSize: 4.5rem
    fontWeight: '800'
    lineHeight: 5rem
    letterSpacing: -0.04em
  display-hero-mobile:
    fontFamily: Inter
    fontSize: 2.75rem
    fontWeight: '800'
    lineHeight: 3.25rem
    letterSpacing: -0.03em
  headline-lg:
    fontFamily: Inter
    fontSize: 2.5rem
    fontWeight: '700'
    lineHeight: 3rem
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Inter
    fontSize: 1.75rem
    fontWeight: '600'
    lineHeight: 2.25rem
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Inter
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.75rem
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.75rem
  body-md:
    fontFamily: Inter
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.5rem
  body-sm:
    fontFamily: Inter
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.25rem
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 0.875rem
    fontWeight: '500'
    lineHeight: 1.25rem
    letterSpacing: -0.01em
  label-meta:
    fontFamily: Inter
    fontSize: 0.75rem
    fontWeight: '600'
    lineHeight: 1rem
    letterSpacing: 0.06em
rounded:
  sm: 0.5rem
  DEFAULT: 1rem
  md: 1.5rem
  lg: 2rem
  xl: 3rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  gutter-lg: 2rem
  margin: 2rem
  margin-sm: 1rem
  margin-lg: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system expresses a forward-looking, technically refined aesthetic engineered specifically for high-impact software engineering portfolios. It sits at the intersection of dark-mode minimalism and dynamic glassmorphism, capturing the atmosphere of a high-performance integrated development environment bathed in neon ambient illumination.

The visual style relies on translucent glass layers floating above deep obsidian canvas tones, illuminated by vibrant chromatic radiance. The intent is to evoke precision, technical depth, and effortless modernity. Components feel tactile yet weightless, offering deep contrast that highlights technical proficiencies, project milestones, architecture diagrams, and syntax-highlighted code.

## Colors

The color architecture is built upon a 10-step spectral spectrum ranging from vibrant cyan through deep indigo to electric magenta: `#4cc9f0`, `#4895ef`, `#4361ee`, `#3f37c9`, `#3a0ca3`, `#480ca8`, `#560bad`, `#7209b7`, `#b5179e`, and `#f72585`.

- **Primary (`#4cc9f0`)**: Represents active execution states, high-priority links, and technical highlights. Used in conjunction with `#4361ee` for cool neon gradients.
- **Secondary (`#f72585`)**: Highlights creative impact, primary calls-to-action, commit activity spikes, and primary key metrics.
- **Tertiary (`#7209b7`)**: Serves as the atmospheric midpoint, providing anchor transitions in gradient meshes and ambient glow backdrops.
- **Neutral Canvas (`#0b0c10` to `#050508`)**: A deep, saturated void that provides the infinite-contrast stage required for semi-transparent glass layers and glowing diffuse lights.

Gradients flow primarily in diagonal vectors (`135deg`), using the cyan-to-magenta ramp for dynamic headers, glowing borders, and interactive states.

## Typography

Typography prioritizes high-legibility digital presentation. **Inter** serves as the display, headline, and body family, leveraging variable font technology to optimize optical weights and dense tracking at large display sizes. Headlines leverage tight, negative tracking to create a unified editorial look, frequently accented with linear gradient text clips moving from `#4cc9f0` through `#b5179e` to `#f72585`.

**JetBrains Mono** is utilized for metadata, tags, metrics, commit hashes, code blocks, and micro-labels, providing an unmistakable engineering tone that aligns with software architecture.

## Layout & Spacing

The layout is built around a responsive 12-column fluid grid that locks to a maximum content width of 1280px to maintain reading ergonomics.

- **Desktop (≥ 1024px)**: 12-column layout with `gutter-lg` (2rem) and `margin-lg` (4rem). Ample negative space allows background ambient glow spheres to seep between project cards and interactive modules.
- **Tablet (768px – 1023px)**: 8-column layout with `gutter` (1.5rem) and `margin` (2rem). Complex multi-column project displays reflow into balanced 4-column split views.
- **Mobile (< 768px)**: 4-column layout with `gutter-sm` (1rem) and `margin-sm` (1rem). Dense vertical arrangement where card padding adjusts down to preserve horizontal screen real estate for technical descriptions and charts.

## Elevation & Depth

Elevation is rendered through optical physics and backdrop filtration rather than traditional drop shadows:

1. **Ambient Backdrops**: Fixed or slowly moving circular blur orbs (`filter: blur(120px)`) positioned behind the UI canvas, tinted with `#7209b7`, `#3a0ca3`, and `#f72585` at 15% to 30% opacity.
2. **Glassmorphism Layers**:
   - **Base Glass (Cards & Panels)**: `rgba(255, 255, 255, 0.04)` to `rgba(255, 255, 255, 0.07)` background fill, backed by `backdrop-filter: blur(16px)` and an inner border of `1px solid rgba(255, 255, 255, 0.12)`.
   - **Raised Glass (Floating Overlays, Modals, Menus)**: `rgba(255, 255, 255, 0.1)` with `backdrop-filter: blur(24px)`, framed by `1px solid rgba(255, 255, 255, 0.2)` and a soft ambient specular shadow (`0 20px 40px -15px rgba(0, 0, 0, 0.6)`).
   - **Interactive Glow**: On hover, interactive glass modules brighten their surface fill to `rgba(255, 255, 255, 0.1)` and illuminate their perimeter with a gradient border shine or an outer glow (`0 0 24px rgba(76, 201, 240, 0.3)`).

## Shapes

The design system incorporates a high-radius curve vocabulary (`3` - Pill-shaped / Fluid). 

- Interactive controls, status badges, filter chips, and primary buttons employ full pill shapes (`rounded-full` / `9999px`) to emphasize fluidity and glass-lens aesthetics.
- Content containers, technical showcase cards, and code windows apply `rounded-2xl` (1rem to 1.5rem), creating smooth enclosures that contrast comfortably with sharp internal code typefaces.

## Components

### Buttons
- **Primary Pill**: Fully rounded pill shape with a linear gradient background (`#f72585` to `#7209b7` or `#4361ee` to `#4cc9f0`), white text, and a semi-translucent inner glow. Hover triggers an exterior neon drop-shadow (`box-shadow: 0 0 20px rgba(247, 37, 133, 0.4)`).
- **Glassmorphic Pill**: Transparent background (`rgba(255, 255, 255, 0.06)`), `backdrop-filter: blur(12px)`, and a 1px dual-tone gradient border (`rgba(255, 255, 255, 0.3)` fading to `rgba(76, 201, 240, 0.3)`). Hover transitions fill to `rgba(255, 255, 255, 0.12)`.

### Cards & Project Showcases
- Surface composed of `rgba(255, 255, 255, 0.05)`, border of `1px solid rgba(255, 255, 255, 0.15)`, and `rounded-2xl`.
- Window header bar on technical cards includes terminal-like decorative window controls (miniature translucent dots) and a monospace repository path.
- Smooth transition on hover: translate Y by `-4px`, border brightens to `rgba(76, 201, 240, 0.4)`, and diffuse colored shadows project beneath.

### Chips & Badges
- Compact pill-shaped elements using `JetBrains Mono` at `label-meta` or `label-code` sizes.
- Semi-transparent background fills matching category contexts (e.g., `#4cc9f0` at 10% opacity for languages, `#f72585` at 10% for frameworks) bordered with `1px solid currentColor` at 20% opacity.

### Form Inputs & Terminal Inputs
- Field backgrounds use inset dark glass (`rgba(0, 0, 0, 0.3)`), `backdrop-filter: blur(8px)`, and `rounded-xl`.
- Subtle resting border `rgba(255, 255, 255, 0.1)`. Focus states activate a vibrant cyan border (`#4cc9f0`) with an outward diffuse glow ring (`box-shadow: 0 0 0 3px rgba(76, 201, 240, 0.2)`).

### Checkboxes & Radios
- Miniature glass squares (`rounded-md`) and circles (`rounded-full`) with `1px solid rgba(255, 255, 255, 0.2)`.
- Checked state fills with a gradient from `#4361ee` to `#4cc9f0` featuring a high-contrast white checkmark icon or pip.

### Interactive Code Blocks
- Framed in dark elevated glass with syntax highlighting tuned to match the system palette (cyan keys, pink strings, purple operators).
- Features a floating glass "Copy" button in the upper right quadrant that transitions to a green confirmation state upon action.