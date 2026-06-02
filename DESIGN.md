---
name: Modern Leadership Identity
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#554336'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#887364'
  outline-variant: '#dbc2b0'
  surface-tint: '#8f4e00'
  primary: '#8f4e00'
  on-primary: '#ffffff'
  primary-container: '#ff9933'
  on-primary-container: '#693800'
  inverse-primary: '#ffb77a'
  secondary: '#4b53bc'
  on-secondary: '#ffffff'
  secondary-container: '#8991fe'
  on-secondary-container: '#1b218f'
  tertiary: '#056e00'
  on-tertiary: '#ffffff'
  tertiary-container: '#5dc849'
  on-tertiary-container: '#035000'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdcc2'
  primary-fixed-dim: '#ffb77a'
  on-primary-fixed: '#2e1500'
  on-primary-fixed-variant: '#6d3a00'
  secondary-fixed: '#e0e0ff'
  secondary-fixed-dim: '#bfc2ff'
  on-secondary-fixed: '#00006e'
  on-secondary-fixed-variant: '#3239a3'
  tertiary-fixed: '#8dfc75'
  tertiary-fixed-dim: '#72de5c'
  on-tertiary-fixed: '#012200'
  on-tertiary-fixed-variant: '#035300'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Newsreader
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Newsreader
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Newsreader
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Newsreader
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Work Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Work Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Work Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Newsreader
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style
The design system is engineered to project **Energetic Authority**. It bridges the gap between traditional political gravitas and a forward-thinking urban vision. The aesthetic is high-impact and decisive, steering clear of sterile corporate tropes in favor of a dynamic, movement-oriented visual language.

The style leverages **Modern-Brutalism influenced by Indian heritage**. It uses bold color blocking, strong verticality, and subtle geometric line vectors inspired by traditional motifs to create a sense of cultural rootedness within a high-tech framework. The emotional response should be one of trust, momentum, and civic pride.

## Colors
The palette is a strategic interpretation of national and party identity, optimized for digital accessibility and high-impact messaging.

- **Deep Saffron (#FF9933):** Used exclusively for high-priority calls to action, active states, and urgent announcements. It represents the energy of the leadership.
- **Rich Navy (#000080):** The foundation of the system. Used for headers, navigation, and structural borders to convey stability, experience, and authority.
- **Emerald Green (#138808):** A functional accent reserved for sustainability reports, parks/infrastructure updates, and growth metrics.
- **Soft Off-White (#F9F9F9):** The primary canvas. It reduces eye strain while allowing the vibrant saffron and navy to pop with maximum contrast.

## Typography
The typography system pairs **Newsreader**, a sturdy and authoritative serif, with **Work Sans**, a neutral and reliable sans-serif. 

**Newsreader** is used for all headlines and quotes to evoke a sense of literary tradition and legislative weight. **Work Sans** handles all functional and body content, ensuring that policy details and service information remain legible across all devices. Large display type should use tighter letter-spacing to maintain a "headline" feel, while labels utilize uppercase styling for a disciplined, organized appearance.

## Layout & Spacing
This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. 

The spacing logic follows a strict 8px rhythm to ensure visual alignment. Large "hero" sections should utilize `xl` spacing for vertical margins to create a sense of grandeur. Content containers are capped at 1280px to maintain optimal line lengths for the serif headlines. Layouts should favor asymmetrical compositions to keep the energy high—for example, a large headline spanning 8 columns paired with a secondary CTA in the remaining 4.

## Elevation & Depth
In alignment with the modern-political aesthetic, depth is achieved through **Tonal Layering** and **High-Contrast Outlines** rather than soft shadows. 

- **Surface 0:** The neutral off-white background.
- **Surface 1:** Pure white cards with a 1px Navy (#000080) border at 10% opacity.
- **Accents:** Use Saffron "slabs" (solid rectangular blocks) behind text or images to create pseudo-depth.
- **Overlays:** For background textures, use 2% opacity Navy for Indian geometric line vectors. Avoid blurs or frosted glass effects to maintain a crisp, decisive look.

## Shapes
The shape language is **Soft (Level 1)**. Elements feature a 0.25rem (4px) base radius. This provides a subtle modern touch that softens the "sharpness" of a political campaign without appearing overly playful or consumer-grade. 

- **Buttons:** 4px radius for a solid, blocky feel.
- **Image Containers:** Use sharp corners on the top-left and bottom-right, with 4px radii on the opposing corners to create a custom "architectural" frame effect.
- **Iconography:** Use thick-stroke (2px) geometric icons with slight rounding.

## Components
- **Primary Buttons:** Solid Saffron (#FF9933) with Navy (#000080) text. Bold, uppercase Work Sans labels. No shadows; use a 2px offset "ghost border" on hover.
- **Initiative Cards:** Pure white background, subtle 1px navy border. Headers in Newsreader. Footer area uses a light Green (#138808) tint for status or "Impact" metrics.
- **Input Fields:** Thick 2px bottom border in Navy. High-contrast focus state using Saffron. 
- **Progress Bars:** Used for project tracking. Navy track with Saffron or Green fills depending on the category (General vs. Sustainability).
- **Background Textures:** Implement subtle SVGs of geometric Mandalas or Indian architectural line-work at the edges of the screen, fixed at 3-5% opacity Navy.
- **Chips:** Small, rectangular labels with 2px radius. Navy background with White text for categories like "Press Release" or "Development."