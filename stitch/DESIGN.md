---
name: Kinetic Noir
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#b9caca'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#849495'
  outline-variant: '#3a494a'
  surface-tint: '#00dce5'
  primary: '#e9feff'
  on-primary: '#003739'
  primary-container: '#00f5ff'
  on-primary-container: '#006c71'
  inverse-primary: '#00696e'
  secondary: '#a7ffb3'
  on-secondary: '#003915'
  secondary-container: '#00ee70'
  on-secondary-container: '#00662c'
  tertiary: '#fef8ff'
  on-tertiary: '#3c0090'
  tertiary-container: '#e5d7ff'
  on-tertiary-container: '#751fff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#63f7ff'
  primary-fixed-dim: '#00dce5'
  on-primary-fixed: '#002021'
  on-primary-fixed-variant: '#004f53'
  secondary-fixed: '#66ff8f'
  secondary-fixed-dim: '#00e46b'
  on-secondary-fixed: '#00210a'
  on-secondary-fixed-variant: '#005322'
  tertiary-fixed: '#e9ddff'
  tertiary-fixed-dim: '#d1bcff'
  on-tertiary-fixed: '#23005b'
  on-tertiary-fixed-variant: '#5700c9'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
  surface-deep: '#0A0A0C'
  surface-elevated: '#16161A'
  electric-blue: '#00F5FF'
  neon-lime: '#32FF7E'
  vivid-purple: '#7000FF'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 72px
    fontWeight: '800'
    lineHeight: 80px
    letterSpacing: -0.04em
  display-lg-mobile:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
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
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

The design system is engineered for a high-impact creative professional, blending the high-octane energy of gaming aesthetics with the precision of premium SaaS interfaces. The brand personality is innovative, technical, and vibrant, positioned to evoke a sense of forward-thinking mastery.

The visual style is a fusion of **Modern Minimalism** and **Glassmorphism**. It utilizes "dark space" to create depth, allowing vibrant geometric accents and 3D elements to serve as focal points. The layout is structured yet dynamic, moving away from cluttered overlays toward intentional, high-contrast compositions that feel both experimental and authoritative.

## Colors

This design system utilizes a "Deep Tech" palette. The foundation is a near-black neutral (`#0A0A0C`), providing a canvas for high-luminance accents.

- **Primary (Electric Blue):** Used for primary actions, active states, and critical branding elements.
- **Secondary (Neon Lime):** Reserved for highlights, success states, and secondary calls to action to provide a "gaming" punch.
- **Tertiary (Vivid Purple):** Applied to gradients and decorative geometric overlays to add depth and a creative edge.
- **Surface Strategy:** Backgrounds should remain dark to maintain a high-contrast environment. Use subtle shifts in lightness to define container boundaries rather than heavy borders.

## Typography

The typography strategy pairs technical precision with expressive geometry.

- **Headlines:** Uses **Sora** for its wide, modern geometric structure. It should be typeset with tight letter-spacing to create a "locked-in" professional look.
- **Body:** Uses **Inter** for maximum readability across long-form descriptions and project details.
- **Labels/Technical:** Uses **JetBrains Mono** for small labels, categories, and metadata. This reinforces the "tech/developer" aspect of the creative portfolio.

## Layout & Spacing

The layout follows a **Fluid Grid** system based on an 8px base unit. 

- **Grid:** A 12-column grid is used for desktop, 6-column for tablet, and 2-column for mobile.
- **Section Spacing:** Generous vertical padding (120px+) is required between sections to create the "dark space" aesthetic, allowing individual components to breathe.
- **Alignment:** While the grid is strict, decorative geometric accents (diagonal lines, mesh gradients) should intentionally break the grid or bleed off the edges of the viewport to create kinetic energy.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Luminous Layering** rather than traditional shadows.

- **Surfaces:** Use a semi-transparent fill (e.g., `rgba(255, 255, 255, 0.05)`) with a high-saturation backdrop blur (20px-40px).
- **Borders:** "Ghost borders" are preferred—thin 1px strokes with a linear gradient (top-left to bottom-right) that transitions from a low-opacity white to a transparent state.
- **Glow:** For interactive elements, use "Ambient Glow"—a soft, outer drop-shadow tinted with the primary or secondary color, with a large blur radius (30px+) and low opacity (0.2).

## Shapes

The shape language is primarily **Rounded (0.5rem)**, providing a sophisticated balance between the sharp angles of the "gaming" aesthetic and the softness of modern UI. 

- **Interactive Elements:** Buttons and small cards use the standard `rounded` (8px) radius.
- **Large Containers:** Hero sections or main gallery cards use `rounded-xl` (24px) to emphasize the glassmorphic container style.
- **Geometric Accents:** Decorative background elements should feature 45-degree angles to maintain the "angled" legacy of the brand, but with precise, clean execution.

## Components

- **Buttons:** Primary buttons feature a solid Electric Blue fill with black text. Secondary buttons are "Ghost" style with a 1px Neon Lime border and a subtle hover glow.
- **Glass Cards:** Used for project galleries. They must include a `backdrop-filter: blur()`, a subtle inner gradient, and a 1px border. 3D floating job graphics should be centered within these cards.
- **Chips/Badges:** Small, technical-looking tags using JetBrains Mono. Use the tertiary purple for category labels with a very low opacity background.
- **Inputs:** Darker than the background surface with a 1px bottom border that animates to the primary color on focus.
- **Navigation:** A floating, glassmorphic header bar with a blur effect that persists at the top of the viewport. Link states should use a subtle vertical dash or underline in Neon Lime.