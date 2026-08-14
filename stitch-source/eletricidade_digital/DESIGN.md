---
name: Eletricidade Digital
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#c3c5d9'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#8d90a2'
  outline-variant: '#434656'
  surface-tint: '#b6c4ff'
  primary: '#b6c4ff'
  on-primary: '#002780'
  primary-container: '#0055ff'
  on-primary-container: '#e3e6ff'
  inverse-primary: '#004dea'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#c8c6c6'
  on-tertiary: '#303030'
  tertiary-container: '#686767'
  on-tertiary-container: '#e9e6e6'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dce1ff'
  primary-fixed-dim: '#b6c4ff'
  on-primary-fixed: '#001551'
  on-primary-fixed-variant: '#0039b3'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e4e2e1'
  tertiary-fixed-dim: '#c8c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#474747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: 0.05em
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
  margin-mobile: 20px
  section-gap-desktop: 160px
  section-gap-mobile: 80px
  unit-base: 8px
---

## Brand & Style

The brand personality is authoritative yet innovative, positioned at the intersection of high-end craftsmanship and cutting-edge technology. The target audience includes tech-driven enterprises and luxury brands seeking a digital partner that balances precision with creativity.

The design style is **Corporate Modern with a Tech-Noir edge**. It utilizes a deep, monochromatic foundation to allow the electric blue accents to signify "energy" and "connectivity." The interface relies on generous whitespace (negative space), precision alignment, and a sophisticated interplay of dark surfaces to evoke a sense of premium quality and technical mastery. The emotional response should be one of trust, high-performance, and exclusivity.

## Colors

The palette is anchored in a dark graphite spectrum to provide depth and a high-end feel.

- **Fundo (Background):** `#0A0A0A` — A deep, almost-black graphite that serves as the canvas.
- **Superfícies (Surfaces):** `#1A1A1A` and `#2E2E2E` — Used for cards, sections, and structural blocks to create subtle hierarchy through tonal layering.
- **Acento Primário (Primary Accent):** `#0055FF` — An "Electric Blue" used sparingly for interactive elements, highlights, and critical brand moments.
- **Tipografia (Typography):** Pure white `#FFFFFF` for primary headings and a muted light grey `#A1A1AA` for secondary body text to maintain readability without overwhelming the dark aesthetic.

## Typography

The typographic system uses a tiered approach to balance bold impact with technical precision.

- **Headlines:** Uses **Plus Jakarta Sans**. It provides a modern, slightly rounded but bold character that feels welcoming yet professional. Use tight letter-spacing for large displays to create a "locked-in" look.
- **Body:** Uses **Inter**. Chosen for its exceptional legibility on dark backgrounds and its systematic, neutral feel.
- **Labels & Data:** Uses **Geist**. This mono-influenced sans-serif adds a "tech" layer to the UI, perfect for small metadata, tags, and technical specifications.

All Portuguese content should respect the tonal weight of the typeface—bold headings for impact (e.g., "Projetos de Impacto") and clean, airy body text for descriptions.

## Layout & Spacing

This design system employs a **Fluid Grid** with an emphasis on asymmetric balance to avoid a "template" appearance. 

- **Desktop:** 12-column grid with wide 24px gutters. Use large vertical gaps (160px) between sections to allow the brand to "breathe" and signal premium quality.
- **Mobile:** 4-column grid with 20px margins. Section gaps are reduced to 80px.
- **Philosophy:** Components should often be offset from the grid or span irregular column counts (e.g., a 7-column main block with a 5-column empty space) to create a sophisticated, editorial layout. Horizontal padding within dark blocks should be generous (at least 48px on desktop).

## Elevation & Depth

Hierarchy is achieved through **Tonal Layering** and **Subtle Glows** rather than heavy shadows.

- **Z-Index 0:** Base background (`#0A0A0A`).
- **Z-Index 1:** Surface blocks (`#1A1A1A`). These should have a very subtle 1px stroke in `#2E2E2E` to define edges without high contrast.
- **Z-Index 2:** Floating elements or active cards. Use a soft, diffused shadow: `0 20px 40px rgba(0, 0, 0, 0.4)`.
- **Accent Depth:** For primary interactive elements, apply a subtle "Electric Blue" outer glow (`box-shadow: 0 0 15px rgba(0, 85, 255, 0.2)`) to simulate a digital light source.
- **Gradients:** Use linear gradients on surfaces sparingly, moving from `#1A1A1A` to `#2E2E2E` at a 135-degree angle to suggest a subtle top-left light source.

## Shapes

The shape language is **Refined & Geometric**. 

- **Standard Radius:** 0.5rem (8px) for cards and input fields. This provides a "slightly rounded" look that feels modern but remains structural.
- **Large Radius:** 1.5rem (24px) for prominent container blocks or featured images to soften the technical edge.
- **Interactive Elements:** Buttons utilize the standard radius; avoid full pills to maintain a more architectural, professional aesthetic.

## Components

- **Buttons:** 
  - *Primary:* Electric Blue background, white text, 8px radius. Subtle scale-up on hover.
  - *Secondary:* Transparent background with a 1px white or light grey border.
- **Cards:** Use `#1A1A1A` background with `#2E2E2E` 1px borders. Padding should be 32px or 40px to reinforce the premium feel.
- **Input Fields:** Darker than the card surface (`#0A0A0A`), 1px border. On focus, the border changes to Electric Blue with a soft glow.
- **Chips/Tags:** Using the **Geist** font, small uppercase text, background `#2E2E2E`, no border.
- **Lists:** Clean lines, using the accent color for bullets or icons to draw the eye.
- **Portfolio Specifics:** Hero images should use a slight darken overlay to ensure white headlines remain legible. Project transitions should be smooth, utilizing the Electric Blue as a "loading" or "accent" line.