---
name: Vibrant Poultry
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
  on-surface-variant: '#5b403d'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#8f6f6c'
  outline-variant: '#e4beba'
  surface-tint: '#ba1a20'
  primary: '#af101a'
  on-primary: '#ffffff'
  primary-container: '#d32f2f'
  on-primary-container: '#fff2f0'
  inverse-primary: '#ffb3ac'
  secondary: '#795900'
  on-secondary: '#ffffff'
  secondary-container: '#fec330'
  on-secondary-container: '#6f5100'
  tertiary: '#11651d'
  on-tertiary: '#ffffff'
  tertiary-container: '#307f34'
  on-tertiary-container: '#d8ffd0'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ac'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#930010'
  secondary-fixed: '#ffdfa0'
  secondary-fixed-dim: '#f8bd2a'
  on-secondary-fixed: '#261a00'
  on-secondary-fixed-variant: '#5c4300'
  tertiary-fixed: '#a3f69c'
  tertiary-fixed-dim: '#88d982'
  on-tertiary-fixed: '#002204'
  on-tertiary-fixed-variant: '#005312'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
    fontFamily: Space Grotesk
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1.0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-x: 32px
  stack-sm: 8px
  stack-md: 24px
  stack-lg: 64px
  section-padding: 120px
---

## Brand & Style

The design system is centered on a high-energy, "appetite-first" philosophy. It targets a modern audience seeking quality fast-casual dining, evoking feelings of excitement, hunger, and friendliness. 

The style is **High-Contrast / Modern**, leaning into bold blocks of color and massive typography to create a sense of urgency and flavor. It avoids the traditional "fire and smoke" cliches of rotisserie brands, opting instead for a clean, editorial aesthetic that wouldn't look out of place in a premium food magazine. Large-scale imagery and ample whitespace ensure the "Bold Red" and "Sunny Yellow" remain impactful without becoming overwhelming or cluttered.

## Colors

This design system uses a punchy, warm palette. **Bold Red** is the primary driver for brand recognition and action, used for buttons and primary headers. **Sunny Yellow** acts as a high-visibility accent, perfect for price callouts, promotions, and secondary highlights. 

A deep **Neutral** (near-black) provides the necessary grounding for typography, ensuring professional readability. A tertiary green is introduced specifically for "Fresh" indicators (like the WhatsApp contact or fresh ingredient tags). The background remains a crisp white to allow the food photography to take center stage, while a soft grey surface color is used to distinguish card containers and menu sections.

## Typography

The typography strategy pairs the technical, geometric edge of **Space Grotesk** with the friendly, approachable curves of **Plus Jakarta Sans**. 

Headlines are designed to be loud and impactful, using tight letter-spacing and heavy weights to command attention in the hero and menu sections. For body text, Plus Jakarta Sans provides a warm and legible experience, ensuring that ingredient lists and descriptions are easy to digest. Price points should always utilize the headline font to maintain the energetic brand voice.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop, centered within a 1280px container to ensure a premium, controlled feel. On mobile, it transitions to a fluid single-column layout with generous 24px side margins.

Rhythm is maintained through a base-8 spacing scale. Section vertical padding is intentionally large (120px) to give the high-energy colors and large typography "room to breathe," preventing the design from feeling like a cluttered discount flyer. Grid layouts for the menu and image galleries should use consistent 24px gutters.

## Elevation & Depth

To maintain the "Clean and Modern" aesthetic, this design system avoids heavy drop shadows. Depth is instead achieved through **Tonal Layers** and **Low-Contrast Outlines**. 

Cards use a subtle 1px border in a light grey or a very soft, diffused ambient shadow (5% opacity) to lift them off the background. The primary depth mechanism is color blocking: placing Sunny Yellow elements on top of Bold Red backgrounds, or using the light surface grey to define the boundaries of the menu "Paquetes." This keeps the UI feeling fast, flat, and contemporary.

## Shapes

The shape language is **Rounded**, utilizing a 0.5rem (8px) base radius. This softens the high-contrast color palette, making the "MÁS + POLLO" experience feel friendly and accessible rather than aggressive. 

Buttons and "Add to Cart" elements use a more pronounced `rounded-xl` or full pill-shape to invite interaction. Image containers in the gallery should maintain the standard `rounded-lg` (16px) to give the food photography a modern, app-like appearance.

## Components

- **Buttons:** Primary buttons are Bold Red with white text, utilizing a pill-shape and `label-bold` typography. Hover states should slightly darken the red. Secondary buttons should use a Bold Red outline.
- **Menu Cards:** These should feature a light grey background (`surface_color_hex`) with a Sunny Yellow price tag in the top right corner. Content is center-aligned, mirroring the provided reference imagery but with cleaner typography.
- **Navigation:** A sticky top bar with a transparent background that transitions to solid white on scroll. The logo should be centered or left-aligned, with simple text links in `label-bold`.
- **Social Proof / Press:** Use a "logo wall" style for press mentions, rendered in grayscale with 50% opacity, returning to full color on hover. Customer testimonials should be housed in `rounded-lg` cards with a large Bold Red quotation mark as a decorative element.
- **Image Gallery:** Use a masonry or clean grid layout. Each image should have a subtle hover scale effect (1.05x) to add interactivity without clutter.
- **Contact Chips:** Use a Bold Green background for the WhatsApp contact info to signify "Live" or "Fresh" communication, using white text and the brand's rounded shape language.