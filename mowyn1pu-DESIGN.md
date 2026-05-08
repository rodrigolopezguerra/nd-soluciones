---
name: Premium Architectural Identity
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#c1c9be'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#8b9389'
  outline-variant: '#414940'
  surface-tint: '#a0d3a3'
  primary: '#a0d3a3'
  on-primary: '#083917'
  primary-container: '#437149'
  on-primary-container: '#bff3c1'
  inverse-primary: '#3b6841'
  secondary: '#bbc8d5'
  on-secondary: '#26323c'
  secondary-container: '#3c4853'
  on-secondary-container: '#aab7c3'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#656767'
  on-tertiary-container: '#e5e6e6'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#bcefbe'
  primary-fixed-dim: '#a0d3a3'
  on-primary-fixed: '#002109'
  on-primary-fixed-variant: '#22502b'
  secondary-fixed: '#d7e4f1'
  secondary-fixed-dim: '#bbc8d5'
  on-secondary-fixed: '#111d26'
  on-secondary-fixed-variant: '#3c4853'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  display-xl:
    fontFamily: Playfair Display
    fontSize: 72px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
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
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin: 64px
  section-gap: 120px
  container-max-width: 1280px
---

## Brand & Style

The design system is engineered to evoke a sense of structural integrity, heritage, and elite professionalism. It targets high-net-worth investors and corporate entities within the real estate and construction sectors. 

The aesthetic sits at the intersection of **Minimalism** and **Corporate Modernism**, utilizing high-contrast editorial typography to convey a "boutique" feel while maintaining the rigorous precision of an architectural firm. The visual narrative is driven by deep, expansive backgrounds that allow high-quality architectural photography and technical line drawings to emerge as focal points. Every element is designed to feel intentional, grounded, and permanent.

## Colors

The color palette is dominated by a "Midnight Navy" foundation, providing a canvas of depth and stability. 
- **Primary:** The "Forest Emerald" (#437149) is used sparingly for calls to action, active states, and as a brand identifier, symbolizing growth and sustainability.
- **Surface:** The background is near-black (#05111a), with elevated surfaces using a slightly lighter navy to create depth without relying on traditional shadows.
- **Typography:** Pure White is reserved for major headlines to maximize contrast, while a "Muted Slate" grey is used for secondary information to reduce visual noise.

## Typography

This design system utilizes a high-contrast typographic pairing to balance tradition with modernity. 

**Playfair Display** is the primary display face, used for large headlines and section titles. Its elegant serifs and high stroke contrast suggest luxury and editorial authority. **Inter** provides a functional, neutral counterpoint for body copy and UI elements, ensuring legibility across technical descriptions and forms. 

Emphasis is placed on generous line heights and tight letter spacing for display text to maintain a sophisticated, structured appearance.

## Layout & Spacing

The design system employs a **Fixed Grid** model. Content is contained within a 1280px central wrapper to ensure a curated reading experience on wide displays. 

A 12-column system governs the layout, with 24px gutters. Spacing follows a strict 8px base unit. Large vertical gaps (120px+) between sections are mandatory to provide "breathing room," reinforcing the premium nature of the brand. Horizontal margins are generous, pushing the content inward to focus the eye on the high-end imagery and serif headlines.

## Elevation & Depth

Depth in the design system is achieved through **Tonal Layering** and **Subtle Dividers** rather than aggressive shadows. 

1.  **Surfaces:** Cards and containers use a subtle background shift (from #05111a to #0a1a26) to indicate elevation.
2.  **Outlines:** Low-opacity white or emerald borders (1px) are used to define boundaries on interactive elements.
3.  **Dividers:** Horizontal and vertical lines are thin (0.5px - 1px) and set to 10-15% opacity, mimicking the fine lines of architectural blueprints.
4.  **Imagery:** Depth is enhanced by using background blurs behind text overlays on architectural photography, ensuring text remains the primary focus.

## Shapes

The shape language is primarily **Rectilinear** to mirror the structural nature of construction and architecture. 

A very subtle "Soft" corner radius (4px) is applied to buttons and input fields to prevent the UI from feeling overly aggressive or dated. However, image containers and service cards should maintain sharp (0px) or minimal (4px) corners to preserve a clean, professional grid. Decorative elements, like line icons, should follow a consistent stroke weight (1.5px to 2px) with sharp terminals.

## Components

### Navigation Bar
The header is transparent or semi-opaque navy with a persistent 'Solicitar reunión' button. The button uses the Primary Emerald background with white text, positioned on the far right.

### Buttons
- **Primary:** Emerald background, white text, 4px border-radius.
- **Secondary/Ghost:** 1px white or emerald border, transparent background, with a small arrow icon $(\rightarrow)$ for directional cues.

### Service Cards
A vertical stack featuring a high-quality image on top, followed by a thin emerald icon, a serif title, and sans-serif descriptive text. Borders between cards should be minimal or non-existent, relying on grid alignment for structure.

### Contact Form
Inputs utilize a dark background (#0a1a26) with 1px slate-grey borders. The active state shifts the border to Emerald. Labels are small, uppercase, and positioned above the inputs to maintain an architectural, "form-style" look.

### Footer
A high-density component with 4-5 columns of navigation. It includes the logo, social links (LinkedIn, Instagram), and a bottom-aligned copyright bar separated by a subtle 1px divider. The background remains the darkest navy (#05111a).