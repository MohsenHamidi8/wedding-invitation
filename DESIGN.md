---
name: Aeterna Wedding
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#4d4635'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#7f7663'
  outline-variant: '#d0c5af'
  surface-tint: '#735c00'
  primary: '#735c00'
  on-primary: '#ffffff'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#e9c349'
  secondary: '#5d5f5b'
  on-secondary: '#ffffff'
  secondary-container: '#e0e0db'
  on-secondary-container: '#62635f'
  tertiary: '#6c5485'
  on-tertiary: '#ffffff'
  tertiary-container: '#c4a8df'
  on-tertiary-container: '#523b6a'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e3e3de'
  secondary-fixed-dim: '#c6c7c2'
  on-secondary-fixed: '#1a1c19'
  on-secondary-fixed-variant: '#454744'
  tertiary-fixed: '#efdbff'
  tertiary-fixed-dim: '#d8bbf4'
  on-tertiary-fixed: '#26103e'
  on-tertiary-fixed-variant: '#533d6c'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 80px
    fontWeight: '700'
    lineHeight: 90px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0.01em
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 28px
  accent-calligraphy:
    fontFamily: Great Vibes
    fontSize: 42px
    fontWeight: '400'
    lineHeight: 48px
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.2em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 32px
  margin-desktop: 80px
  margin-mobile: 24px
  container-max: 1200px
---

## Brand & Style

The design system is anchored in the concept of "Eternal Romance," blending the gravitas of traditional luxury with the fluid, ethereal nature of modern digital design. It targets a high-end audience seeking a cinematic, story-driven experience for wedding invitations. The emotional response is one of awe, intimacy, and timelessness.

The aesthetic fuses **Luxury Minimalism** with **Glassmorphism**. Surfaces feel like frosted crystal or polished pearl, utilizing high-contrast typography and generous whitespace to create an editorial feel. The "Apple-level polish" is achieved through subtle depth, soft neomorphic shadows that suggest physical texture, and ultra-smooth transitions that mimic the slow-motion grace of a cinematic wedding film.

## Colors

The palette is a sophisticated curation of warm, luminous neutrals and metallic accents. **Ivory** and **Pearl** serve as the primary background layers to maintain a soft, non-clinical light mode. **Elegant Black** is reserved for high-contrast typography and structural anchors.

**Gold and Rose Gold** are primarily used as "Light-catching" elements. Gold gradients must be applied sparingly—mostly to borders, icons, or text accents—to ensure they feel like precious metal rather than a digital graphic. The **Champagne** tone acts as a bridge between the white surfaces and the metallic accents, often used for subtle hover states or secondary backgrounds.

## Typography

This design system uses a tri-font hierarchy to balance authority, clarity, and emotion.
- **Playfair Display** (Headings): High-contrast serifs provide a classic "Vogue" editorial aesthetic. Use for names, dates, and section titles.
- **Inter** (Body): Provides a modern, functional counterpoint. Its neutrality ensures the wedding details (itinerary, RSVP forms) remain legible and grounded.
- **Great Vibes** (Accents): Used for short, emotive phrases ("Always & Forever") or as decorative initials. It should never be used for critical information.

**Styling Note:** For Display headings, use a subtle text-shadow (very low opacity) to mimic the way light hits physical foil-pressed paper.

## Layout & Spacing

The layout philosophy follows a **Fixed Centered Grid** for desktop to mimic the feel of a printed invitation card floating in space. For tablet and mobile, it transitions to a **Fluid Grid** with generous safe areas.

Spacing is expansive. Whitespace is treated as a premium "material" rather than empty space. 
- **Rhythm:** Use multiples of 8px, but lean toward larger gaps (64px, 80px, 128px) between major sections to allow the imagery and typography to breathe.
- **Photo Grids:** Editorial-style grids should use asymmetrical layouts (e.g., a large vertical image spanning 8 columns paired with two smaller squares on the remaining 4) to maintain a dynamic, non-repetitive visual flow.

## Elevation & Depth

Depth is conveyed through a combination of **Glassmorphism** and **Soft Neumorphism**:
- **Surfaces:** Use backdrop-blur (minimum 20px) on semi-transparent Ivory (#FCFBF766) layers. This creates the "Frosted Glass" effect.
- **Shadows:** Instead of harsh black shadows, use multi-layered ambient shadows. A primary soft shadow (blur 40px, opacity 5%) combined with a tight, slightly darker shadow (blur 4px, opacity 8%) creates a "raised card" effect.
- **Illumination:** Apply a 1px inner border to glass elements, using a gold-to-transparent gradient to simulate the way light catches the edge of a beveled glass pane.

## Shapes

The shape language is "Softly Architectural." 
- **Primary Elements:** Use a subtle 0.25rem (Soft) radius for a modern, sharp-yet-approachable look. 
- **Glass Cards:** May use a slightly larger radius (0.5rem) to differentiate themselves from the page structure.
- **Buttons:** Magnetic buttons should maintain the standard 0.25rem radius or be completely square to emphasize the luxury/fashion influence. Avoid pill shapes as they feel too "app-like" for this specific cinematic narrative.

## Components

### Magnetic Shimmer Buttons
Buttons use a "Magnetic" interaction—when the cursor nears, the button subtly gravitates toward it. The background is a solid **Elegant Black** or **Gold Gradient**, but on hover, a "shimmer" light-sweep effect travels across the surface.

### Glass Cards
The primary container for information. These are semi-transparent (Backdrop-filter: blur) with a 1px **Soft Gold** border. They should appear to float slightly above the background imagery.

### Photo Grids
Editorial-style grids with thin (1px) Ivory gutters. Each photo should have a subtle parallax effect on scroll to increase the "cinematic" depth.

### Input Fields
Minimalist underline-style inputs or ghost-boxes with very low-opacity Ivory backgrounds. Focus states are indicated by the underline transforming into a **Gold Gradient** line.

### RSVP Chips
Used for selection (Attending / Not Attending). These should use a neomorphic "pressed" state when selected, looking like they have been physically stamped into the pearl surface.

### Decorative Dividers
Use a single 1px horizontal line that fades out at the edges, with a small **Great Vibes** accent or a gold dot in the center to mark the transition between narrative sections.