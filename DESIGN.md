---
name: Heritage & Precision
colors:
  surface: '#fdf9f1'
  surface-dim: '#dddad2'
  surface-bright: '#fdf9f1'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f7f3eb'
  surface-container: '#f1ede6'
  surface-container-high: '#ece8e0'
  surface-container-highest: '#e6e2da'
  on-surface: '#1c1c17'
  on-surface-variant: '#444748'
  inverse-surface: '#31302b'
  inverse-on-surface: '#f4f0e8'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#795553'
  on-secondary: '#ffffff'
  secondary-container: '#ffcfcb'
  on-secondary-container: '#7a5653'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#241a00'
  on-tertiary-container: '#a08000'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#ffdad7'
  secondary-fixed-dim: '#eabcb8'
  on-secondary-fixed: '#2e1413'
  on-secondary-fixed-variant: '#5f3e3c'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#fdf9f1'
  on-background: '#1c1c17'
  surface-variant: '#e6e2da'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
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
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

This design system establishes a visual language of "Refined Utility," bridging the artisanal world of bespoke tailoring with the scientific precision of livestock consultancy. The brand personality is rooted in excellence and craftsmanship, targeting high-net-worth individuals and industry professionals who value both tradition and innovation.

The design style is **Timeless Luxury with a Modern Technical Layer**. It utilizes a sophisticated mix of:
- **Minimalism:** Strategic use of negative space to allow high-quality imagery of textiles and livestock to breathe.
- **Glassmorphism:** Employed sparingly for navigation and floating action panels to denote a forward-thinking, innovative edge.
- **Corporate Modernism:** Balanced layouts and structured grids that evoke trust and reliability.
- **Tactile Details:** Subtle gradients and soft shadows that mimic the depth of fine fabrics and the organic textures of nature.

## Colors

The palette is designed to feel grounded yet prestigious. 

- **Matte Black (#111111):** Used for primary typography and structural elements to provide a sense of authority.
- **Rich Chocolate Brown (#4A2C2A):** Serves as the "warmth" in the palette, connecting the earthiness of livestock care with the heritage of tailoring.
- **Metallic Gold (#D4AF37):** Used strictly as an accent color for CTAs, success states, and premium signifiers.
- **Warm Cream (#F7F3EB):** The primary surface color for cards and containers, softening the high contrast between black and white.
- **Pure White (#FFFFFF):** The base background color to ensure a clean, modern aesthetic.

**Gradients:** Use a "Gilded Sheen" gradient (Linear 45deg: #D4AF37 to #B8962E) for interactive luxury elements.

## Typography

The system uses **Playfair Display** to signal heritage and editorial elegance. It is reserved for headings and significant pull-quotes. For body text and functional UI, **Plus Jakarta Sans** (a modern alternative to Poppins with better legibility and a slightly more "tech-luxe" feel) is used to maintain a clean, professional atmosphere.

**Hierarchy Rules:**
- Titles should use "Title Case" for a more formal appearance.
- Use `label-caps` for section headers and overlines to add a structured, corporate rhythm.
- Paragraphs should maintain generous line spacing to ensure readability on high-density displays.

## Layout & Spacing

The layout philosophy follows a **Fixed-Fluid Hybrid Grid**. 
- Content is centered within a 1280px max-width container on desktop.
- On mobile, margins reduce to 20px to maximize screen real estate.
- A 12-column grid is used for desktop, 8 columns for tablet, and 4 columns for mobile.

Spacing follows an 8px base unit. To maintain the luxury feel, "Negative Space" is treated as a core design element; do not crowd components. Use larger padding (48px+) between distinct content sections to create a sense of calm and deliberate pacing.

## Elevation & Depth

Depth is conveyed through a combination of **Glassmorphism** and **Ambient Shadows**.

1.  **Surfaces:** Cards use the Warm Cream (#F7F3EB) color with a very thin (1px) border in 10% Matte Black.
2.  **Shadows:** Use "Feathered Earth" shadows—soft, wide-dispersion shadows with a slight Brown (#4A2C2A) tint to the hex value (e.g., `rgba(74, 44, 42, 0.08)`).
3.  **Glassmorphism:** Navigation bars and modal overlays use a 20px backdrop blur with a 70% opacity White fill. This creates a "frosted lens" effect that feels high-tech and clean.
4.  **Transitions:** All elevation changes (hovering over a card) should use a slow, 300ms cubic-bezier transition to evoke a feeling of "smoothness" and weight.

## Shapes

The design system uses a **Rounded (Level 2)** shape language. This provides a balance between the organic nature of livestock and the sharp precision of tailoring tools.

- **Standard Elements (Buttons, Inputs):** 0.5rem (8px).
- **Cards & Containers:** 1rem (16px).
- **Floating Action Buttons:** Full pill-shaped (rounded-full).

Avoid 0px sharp corners, as they appear too aggressive for a "Care" brand. Avoid 3px "soft" corners as they can feel dated; the 8px-16px range ensures a contemporary, premium look.

## Components

### Buttons
- **Primary:** Matte Black background, White text, 8px rounded corners. On hover, background shifts to Rich Chocolate Brown.
- **Secondary (Luxury):** Metallic Gold background with a subtle linear gradient. Matte Black text.
- **Ghost:** 1px Matte Black border, transparent background.

### Input Fields
- Understated design: 1px border (#4A2C2A at 20% opacity), Warm Cream background. 
- Focus state: Border changes to Metallic Gold with a 2px outer glow (shadow).

### Cards
- Elevated by a soft Brown-tinted shadow. 
- Content within cards should have a minimum of 32px internal padding.

### Lists & Navigation
- Use the `label-caps` typography for navigation items. 
- Active states are indicated by a 2px Gold underline or a small Gold dot below the text.

### Distinctive Elements
- **ZIZ Care Badge:** A circular or pill-shaped tag with a Glassmorphism background used for livestock health status.
- **ZIZ Craft Label:** An elegant, typography-focused label with a Metallic Gold border used for bespoke tailoring product details.