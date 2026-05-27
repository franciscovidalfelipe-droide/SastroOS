---
name: SastreOS
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#20201f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c6c6cc'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#909096'
  outline-variant: '#45474b'
  surface-tint: '#c2c6d4'
  primary: '#c2c6d4'
  on-primary: '#2b303b'
  primary-container: '#0f141e'
  on-primary-container: '#7a7e8b'
  inverse-primary: '#595e6b'
  secondary: '#e9c349'
  on-secondary: '#3c2f00'
  secondary-container: '#af8d11'
  on-secondary-container: '#342800'
  tertiary: '#c8c6c0'
  on-tertiary: '#30312c'
  tertiary-container: '#141410'
  on-tertiary-container: '#7f7f79'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dee2f1'
  primary-fixed-dim: '#c2c6d4'
  on-primary-fixed: '#171c26'
  on-primary-fixed-variant: '#424752'
  secondary-fixed: '#ffe088'
  secondary-fixed-dim: '#e9c349'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#574500'
  tertiary-fixed: '#e4e2dc'
  tertiary-fixed-dim: '#c8c6c0'
  on-tertiary-fixed: '#1b1c18'
  on-tertiary-fixed-variant: '#474742'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: EB Garamond
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: EB Garamond
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: EB Garamond
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: EB Garamond
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  container-max-width: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system embodies the "Classic Gentleman" aesthetic, blending the heritage of bespoke tailoring with the precision of modern computing. It is designed for the artisan who values tactile quality, rhythmic order, and quiet luxury.

The visual direction follows a **refined minimalism**. It avoids loud patterns in favor of rich textures and expansive whitespace, evoking the feeling of a clean, high-end atelier. The interface feels bespoke—meticulously measured and perfectly fitted—utilizing thin strokes and subtle depth to guide the eye without breaking the sense of calm.

## Colors
This design system utilizes a palette rooted in traditional menswear.
- **Midnight Navy & Deep Charcoal:** Used for primary backgrounds and surfaces to create a sense of depth and focus.
- **Ivory:** Reserved for primary body text and high-contrast iconography, providing a softer, more premium feel than pure white.
- **Refined Metallic Gold:** Used sparingly as an accent for focus states, primary actions, and "hallmark" branding elements.
- **Semantic Tones:** Success states use an Emerald Green (the color of fine silk lining), while alerts use Deep Burgundy (evoking wax seals).
- **Chart Palette:** A collection of muted, sophisticated tones (Slate, Sage, Pewter, and Driftwood) to ensure data visualization remains secondary to the overall aesthetic.

## Typography
Typography is the "thread" of this design system. We pair **EB Garamond** for editorial-style headings to instill a sense of history and authority, with **Hanken Grotesk** for UI elements and body copy to ensure legible, modern functionality.

Key typographic rules:
- **Optical Sizing:** Display headings should utilize generous line heights.
- **Case Styling:** Labels and small headers should often use uppercase with increased letter spacing to mimic the embossed labels found inside custom suits.
- **Hierarchy:** Contrast is achieved through font-family switching rather than excessive weight changes.

## Layout & Spacing
The layout philosophy is based on **The Drafting Table**—a 12-column fluid grid that allows for significant "dead space" to emphasize quality over quantity.

- **Margins:** Desktop views utilize wide 64px margins to frame the content, much like a matted photograph. 
- **Rhythm:** An 8px linear scale governs all padding and margins to maintain mathematical harmony.
- **Adaptability:** On mobile, margins compress to 16px, and the grid collapses to a single column, but the generous vertical breathing room (padding) remains to preserve the premium feel.

## Elevation & Depth
Elevation is conveyed through **Tonal Layering** and **Thin Outlines** rather than heavy shadows.

- **Surfaces:** We use a "Level 0" (Deep Charcoal) for the base and "Level 1" (Midnight Navy) for floating containers.
- **Borders:** All containers feature a 0.5px or 1px border. The border color is a faint Gold or Ivory with 20% opacity, mimicking the delicate edge of a pattern paper.
- **Shadows:** Use only one "Signature Shadow"—a very long, soft, low-opacity shadow (Color: #000, 40% Alpha, 30px Blur) used exclusively for modal windows or primary call-to-action cards to make them appear to float slightly above the workbench.

## Shapes
The shape language is **Soft (0.25rem)**. 

To maintain the "tailored" aesthetic, we avoid aggressive rounding. Buttons and cards feature subtle 4px corners, suggesting the sharp but handled edges of premium fabric swatches. Pill shapes are used strictly for status indicators (chips) to provide a visual break from the structural rectangular grid.

## Components
- **Buttons:** Primary buttons are Ivory with Navy text; secondary buttons are "Ghost" style with a 1px Gold border. Hover states should subtly increase the gold border opacity.
- **Cards:** Use "The Swatch Card"—a container with a subtle background texture (a faint linen pattern overlay at 2% opacity) and a thin top-border in Gold.
- **Input Fields:** Bottom-border only by default, mimicking a tailor's chalk line. On focus, a subtle ivory glow appears behind the text.
- **Lists:** High-density lists are avoided. Each list item should have ample padding (16px+) and be separated by a hairline divider.
- **Measurement Inputs:** Specialized components for tailors (e.g., inch/cm toggles) should use the Sans-Serif font for clarity, but the numerical values should be slightly larger to emphasize the data.
- **The "Needle" Cursor:** A custom interaction state where the cursor transforms into a precise crosshair or needle-point when hovering over interactive canvas elements.