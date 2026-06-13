---
name: Aura Premium Marketplace
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1c'
  surface-container: '#202020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e3bfb1'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#303030'
  outline: '#aa8a7d'
  outline-variant: '#5b4137'
  surface-tint: '#ffb598'
  primary: '#ffb598'
  on-primary: '#591c00'
  primary-container: '#ff6000'
  on-primary-container: '#531a00'
  inverse-primary: '#a63c00'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#4a4949'
  on-secondary-container: '#bab8b7'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#939494'
  on-tertiary-container: '#2b2d2d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbce'
  primary-fixed-dim: '#ffb598'
  on-primary-fixed: '#370e00'
  on-primary-fixed-variant: '#7e2c00'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474646'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
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
    lineHeight: '1.5'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
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
  container-max: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is engineered for an ultra-high-end secondary market, blending the velocity of a startup with the prestige of a luxury house. The personality is **Elite, Precise, and Cinematic**. 

The aesthetic leverages **Glassmorphism** to create a sense of depth and transparency, signaling a modern, "billion-dollar" tech stack. It prioritizes high-fidelity imagery, treating every listing like a gallery piece. The interface remains unobtrusive, using frosted glass surfaces and subtle blurs to maintain focus on the products while providing a tactile, multi-layered user experience.

## Colors
This design system utilizes a **Luxury Dark** foundation to make the primary brand color radiate energy.

- **Vibrant Premium Orange (#FF6000):** Used exclusively for primary actions, price tags, and critical brand touchpoints. It represents energy and high-value transactions.
- **Deep Charcoal & Pure Black:** The primary background colors (#000000 to #121212) provide the "infinite" canvas required for cinematic depth.
- **Crisp White:** Reserved for high-contrast typography and essential icons.
- **Glass Surfaces:** Semi-transparent grays with background blurs (e.g., `rgba(255, 255, 255, 0.05)`) create the layered effect.

## Typography
Typography is used to establish clear hierarchy and a sense of authority. 

**Montserrat** is the display typeface, chosen for its geometric precision and bold, modern character. It should be used for headlines and price displays to convey confidence. **Inter** handles all functional and body text, providing maximum readability and a systematic, technical feel. High contrast between weights (Bold headlines vs. Regular body) is essential to the "billion-dollar" aesthetic.

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous white space (or "black space") to allow elements to breathe.

- **Grid:** A 12-column system for desktop with 24px gutters. On mobile, transition to a 2-column grid for product feeds to maximize image size.
- **Margins:** Large outer margins (64px+) on desktop focus the user's eye on the central content gallery.
- **Rhythm:** Spacing follows an 8px linear scale. Use larger increments (48px, 64px) between sections to maintain the premium, un-cluttered feel.

## Elevation & Depth
This design system rejects traditional shadows in favor of **Glassmorphism and Cinematic Layering**.

1.  **Base Layer:** Solid #000000.
2.  **Surface Layer:** Background blurs (20px-40px) with a subtle white inner stroke (1px, 10% opacity) to define edges.
3.  **Floating Elements:** Use "Ambient Glows"—subtle, large-radius orange or white blurs behind cards—to indicate focus or high-priority listings.
4.  **Transitions:** All depth changes should feel fluid. When hovering over a card, the background blur should intensify and the element should slightly scale (1.02x).

## Shapes
Shapes are intentionally soft and approachable to balance the intensity of the dark theme. 

Standard components use a **0.5rem (8px)** radius. Feature cards and high-end product containers utilize **1rem (16px)** or **1.5rem (24px)** for a more modern, "app-like" feel. Interactive elements like buttons should never have sharp corners; they must feel tactile and polished.

## Components
- **Glass Cards:** The signature component. Feature a 1px border (`rgba(255,255,255,0.1)`), backdrop-filter blur (20px), and a dark-tinted translucent background.
- **Primary Buttons:** Solid #FF6000 with white text. On hover, apply a subtle orange outer glow. Use large padding (16px 32px) and Montserrat SemiBold.
- **Input Fields:** Dark background (#1E1E1E) with a 1px border that glows orange on focus. Text should be Crisp White.
- **Price Tags:** Floating badges using the primary orange. Typography should be Montserrat Bold with slight letter-spacing.
- **Chips:** Small, pill-shaped glass elements for categories (e.g., "Luxury Watches", "Supercars").
- **Product Gallery:** Edge-to-edge imagery within cards, utilizing a "Ken Burns" subtle zoom effect on hover for a cinematic experience.