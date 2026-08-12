---
name: Mars Capital Sovereign
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#0060a8'
  on-secondary: '#ffffff'
  secondary-container: '#47a1ff'
  on-secondary-container: '#003663'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#271901'
  on-tertiary-container: '#98805d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#d3e4ff'
  secondary-fixed-dim: '#a2c9ff'
  on-secondary-fixed: '#001c38'
  on-secondary-fixed-variant: '#004881'
  tertiary-fixed: '#fcdeb5'
  tertiary-fixed-dim: '#dec29a'
  on-tertiary-fixed: '#271901'
  on-tertiary-fixed-variant: '#574425'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
  mars-red: '#E53935'
  mars-green: '#43A047'
  mars-orange: '#FB8C00'
  pure-white: '#FFFFFF'
  slate-border: '#E2E8F0'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 72px
    fontWeight: '700'
    lineHeight: 80px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '600'
    lineHeight: 38px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.1em
  stat-value:
    fontFamily: Plus Jakarta Sans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: -0.03em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  section-padding: 120px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system embodies a "Sovereign Corporate" aesthetic—an evolution of traditional finance into the modern, high-tech era. It targets institutional investors and high-net-worth individuals, evoking feelings of stability, immense scale, and technological superiority.

The visual direction combines **Minimalism** with **High-Contrast framing**. Extensive white space and a "Soft Slate" canvas provide a prestigious, breathable environment, while "Deep Navy" headers and footers act as architectural anchors to frame the light-themed content. To differentiate from standard corporate designs, it utilizes a "Neon Utility" layer: brand colors are applied as vibrant, glowing accents specifically for data visualization and statistical breakthroughs, suggesting energy and growth within a structured framework.

## Colors

The palette is rooted in **Deep Navy Blue (#0F172A)**, used for primary typography and structural "containment" (headers and footers). This creates a high-contrast boundary for the **Soft Slate (#F8FAFC)** and **Pure White (#FFFFFF)** background layers.

Interactive states and data metrics utilize the "Mars Accents." These are high-chroma variants of Red, Blue, Green, and Orange. When used in statistical displays, these colors should be paired with a subtle `0 0 12px` outer glow (drop-shadow) of the same hue to create the "glowing neon" effect requested for brand identity.

## Typography

This design system uses **Plus Jakarta Sans** for headlines and brand-heavy moments to provide a sophisticated, geometric look with a contemporary edge. **Inter** is utilized for body text and functional labels to maintain maximum legibility and a systematic, professional feel.

Statistical values (KPIs) should use the `stat-value` style, often paired with the glowing neon color utility. Ensure that `display-lg` is reserved only for primary hero sections on desktop to maintain the "spacious" corporate feel.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop, centered with a max-width of 1280px to ensure a premium, controlled reading experience. The defining characteristic of this system is the **120px vertical section padding**, which creates significant breathing room between major content blocks.

- **Desktop (1440px+):** 12-column grid, 24px gutters, 80px side margins.
- **Tablet (768px - 1024px):** 8-column grid, 20px gutters, 40px side margins. Section padding reduced to 80px.
- **Mobile (<768px):** 4-column grid, 16px gutters, 20px side margins. Section padding reduced to 64px.

## Elevation & Depth

Hierarchy is established through **Tonal Layering** and **Subtle Shadows**. 

1.  **Base Layer:** Soft Slate (#F8FAFC) for the overall page background.
2.  **Raised Layer:** Pure White (#FFFFFF) cards or containers.
3.  **Elevation:** White containers use a "Sovereign Shadow"—a very soft, large-radius blur (`0 10px 30px rgba(15, 23, 42, 0.05)`) paired with a 1px "Slate Border" (#E2E8F0) to ensure crispness.
4.  **Interactive Depth:** On hover, cards transition to a slightly deeper shadow (`0 20px 40px rgba(15, 23, 42, 0.08)`) and a 1px primary-colored border.

Statistical displays should ignore traditional elevation and instead use the **Backdrop Glow** utility, where the color itself creates the sense of depth against the background.

## Shapes

The design system utilizes **Soft (Level 1)** roundedness. This provides a subtle modern touch without compromising the "Prestigious Corporate" seriousness. 

- **Small elements (Inputs, Buttons, Chips):** 0.25rem (4px).
- **Medium elements (Cards, Modals):** 0.5rem (8px).
- **Large elements (Hero sections):** 0.75rem (12px).

Avoid pill-shaped or fully rounded buttons to maintain the structured, architectural feel of the brand.

## Components

### Buttons
- **Primary:** Deep Navy (#0F172A) background, White text. No shadow, 4px corner radius.
- **Secondary:** Transparent background, 1px Slate Border, Navy text.
- **Ghost:** Transparent background, Navy text, subtle slate background on hover.

### Cards
- Pure White background, 1px Slate Border, Sovereign Shadow.
- Card headers should use `label-caps` for a professional, categorized look.

### Input Fields
- White background, 1px Slate Border.
- On focus: Border changes to Blue (#1E88E5) with a subtle 2px blue outer glow.

### Statistical Displays
- Value text uses `stat-value` style.
- Apply `text-shadow: 0 0 15px [brand-color]` to create the "glowing neon" effect.
- Label text beneath stats should be `label-caps` in a muted Navy.

### Navigation (The Frame)
- **Header:** Deep Navy background with White logo and menu items for high-contrast framing.
- **Footer:** Deep Navy background, providing a "heavy" base to the layout.