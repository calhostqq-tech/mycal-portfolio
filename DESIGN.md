---
name: Kinetic Ether
colors:
  surface: '#141313'
  surface-dim: '#141313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353434'
  on-surface: '#e5e2e1'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#849495'
  outline-variant: '#3a494b'
  surface-tint: '#00dbe7'
  primary: '#e1fdff'
  on-primary: '#00363a'
  primary-container: '#00f2ff'
  on-primary-container: '#006a71'
  inverse-primary: '#00696f'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#f7f8f8'
  on-tertiary: '#2f3131'
  tertiary-container: '#dbdbdb'
  on-tertiary-container: '#5e6060'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#74f5ff'
  primary-fixed-dim: '#00dbe7'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#141313'
  on-background: '#e5e2e1'
  surface-variant: '#353434'
typography:
  display-2xl:
    fontFamily: sora
    fontSize: 72px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  display-lg:
    fontFamily: sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-md:
    fontFamily: sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: -0.01em
  body-lg:
    fontFamily: geist
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  body-md:
    fontFamily: geist
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: 0em
  label-mono:
    fontFamily: jetbrainsMono
    fontSize: 13px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  stack-sm: 16px
  stack-md: 32px
  stack-lg: 64px
---

## Brand & Style

The design system is engineered to evoke the feeling of a premium, high-fidelity command center. It targets a sophisticated audience of tech leaders and innovators, blending the utilitarian precision of developer tools with the cinematic luxury of high-end hardware interfaces.

The aesthetic is **Futuristic Minimalism**, drawing heavily from "spatial" UI patterns. It utilizes deep canvas depths, light-emitting accents, and high-refractive glass surfaces to create a sense of physical presence in a digital environment. The emotional response is one of calm intelligence, technical mastery, and exclusivity.

## Colors

The palette is anchored in a "Deep Space" black, providing a void-like canvas where content appears to float. 

- **Canvas Background:** `#020202` is the absolute base.
- **Luminous Cyan:** Used for primary actions, active states, and data visualizations. It represents the "intelligence" layer.
- **Electric Violet:** Used for secondary accents, gradients, and hover states. It provides a sense of luxury and depth.
- **Glass Borders:** A low-opacity white (`rgba(255, 255, 255, 0.08)`) is used to define the edges of glass surfaces without breaking the minimalist flow.
- **Surface Overlays:** Subtle gradients from `#0a0a0a` to `#020202` are used to create structural hierarchy.

## Typography

This design system utilizes a tiered typographic approach to balance futuristic display with technical readability.

1.  **Display (Sora):** Used for heroic statements and section headers. Its geometric structure provides a high-tech, premium feel. Use tight tracking on larger sizes.
2.  **Body (Geist):** Optimized for technical legibility and modern aesthetics. It provides a clean, neutral "developer" feel inspired by Vercel's design language.
3.  **Labels & Code (JetBrains Mono):** Used for metadata, tags, and small utility text. The monospaced nature reinforces the "Full Stack" identity of the product.

## Layout & Spacing

The layout philosophy follows a **Fluid Spatial Grid**. Content is housed within a central 1200px container, but background elements (like glass blurs and gradient glows) should bleed to the edges of the viewport to maintain a cinematic feel.

- **Grid:** 12-column layout for desktop with 24px gutters.
- **Vertical Rhythm:** Multiples of 8px (the "unit"). Use `stack-lg` (64px) for major section breaks to ensure a sense of "premium whitespace."
- **Safe Zones:** Use 20px side margins on mobile to prevent glass card borders from touching the screen edges.
- **Adaptive Reflow:** On tablet/mobile, 12 columns collapse to 4. Grid-spanning elements (like cards) should transition from `span-4` to `span-full`.

## Elevation & Depth

Depth is the defining characteristic of this design system. It is achieved through **Optical Layering** rather than traditional drop shadows.

- **Level 0 (Canvas):** The base `#020202` layer.
- **Level 1 (Glass):** Background blur (32px to 64px) with a semi-transparent fill (`rgba(10, 10, 10, 0.4)`). A 1px border with a subtle top-down linear gradient simulates light hitting the edge.
- **Level 2 (Hover/Active):** An inner glow effect using the Primary or Secondary colors at very low opacity (5-10%) to suggest the element is "energized."
- **Light Sources:** Use large, blurred "radial orbs" of Cyan and Violet behind glass surfaces to create a sense of chromatic depth.

## Shapes

The shape language is controlled and sophisticated. 

- **Base Radius:** 0.5rem (8px) for inputs and smaller elements.
- **Container Radius:** 1rem (16px) for cards and main UI blocks.
- **Interactive Radius:** 1.5rem (24px) for primary buttons to give them a distinct, tactile feel compared to the structural containers.

Avoid sharp 0px corners to maintain the "Apple spatial" influence, which favors organic, rounded enclosures.

## Components

### Glass Cards
The signature component. Cards must have a `backdrop-filter: blur(40px)`. The border should be a subtle gradient from `white/10` at the top left to `white/02` at the bottom right. On hover, apply a `box-shadow` of the primary color with a massive blur (100px) at 10% opacity to create a "bloom" effect.

### Interactive Buttons
Buttons use a "Magnetic" interaction. The text remains centered while the background container follows the cursor slightly within its bounds.
- **Primary:** Gradient background (Cyan to Violet), white text, no border.
- **Secondary:** Glass background, 1px Cyan border, Cyan text.

### Inputs
Fields are dark and recessed. Use a `1px` solid border that transitions to a Primary Color glow on focus. Labels should always use the `label-mono` typography style.

### Smooth-Scrolling Containers
All scrollable areas must implement `scroll-behavior: smooth` and custom scrollbars that are thin (4px), dark, and only visible on hover to maintain the minimalist aesthetic.

### Progress Bars & Data
Use "Glow-lines" — 2px tall lines with a `box-shadow` of the same color to simulate a neon filament.