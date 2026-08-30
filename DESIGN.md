---
name: Electric Dark Developer System
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
  on-surface-variant: '#c2c6d6'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#8c909f'
  outline-variant: '#424754'
  surface-tint: '#adc6ff'
  primary: '#adc6ff'
  on-primary: '#002e6a'
  primary-container: '#4d8eff'
  on-primary-container: '#00285d'
  inverse-primary: '#005ac2'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#c0c1ff'
  on-tertiary: '#1000a9'
  tertiary-container: '#8083ff'
  on-tertiary-container: '#0d0096'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
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
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 80px
  container-max: 1200px
---

## Brand & Style

This design system is engineered for high-end developer portfolios, blending the precision of SaaS interfaces with the atmospheric depth of modern gaming aesthetics. The personality is professional yet innovative, positioning the developer as a high-tier engineer capable of building complex, high-performance systems.

The visual style utilizes **Glassmorphism** and **Corporate Modern** elements. It relies on deep, layered backgrounds to create a sense of infinite digital space, accented by "electric" glowing elements that draw the eye to key actions and achievements. The aesthetic is defined by its use of light as a material—employing subtle glows, translucent borders, and high-contrast typography to create a premium, tactile feel.

## Colors

The palette is anchored in a deep navy-black (`#05070D`) to provide maximum contrast for the "Electric Blue" and "Indigo" accents. This dark foundation is essential for the glassmorphic effects to appear luminosity-driven rather than just transparent.

- **Primary:** An Electric Blue to Indigo gradient used for high-impact calls to action, active states, and highlights.
- **Secondary/Accent:** Cyan (`#06B6D4`) is used sparingly for terminal-style details, success states, and decorative "micro-glows."
- **Surfaces:** All container surfaces use `#0F121D`, typically with a low-opacity border to simulate glass thickness.
- **Muted Content:** Body text and secondary information use a desaturated gray-blue (`#94A3B8`) to maintain visual hierarchy and reduce eye strain in dark environments.

## Typography

The typography system uses a tri-font approach to balance technical precision with modern style.

- **Space Grotesk** is used for headlines. Its geometric, slightly eccentric letterforms evoke a "cutting-edge" and "tech-focused" personality.
- **Inter** handles all body copy, ensuring maximum readability and a clean, neutral professional feel.
- **JetBrains Mono** is introduced for small labels, tags, and snippets of code, reinforcing the developer-centric aesthetic.

High contrast is maintained by using pure white (`#FFFFFF`) for headlines and the muted gray-blue for body text.

## Layout & Spacing

The design system follows a **Fluid Grid** model with generous whitespace to emphasize the premium nature of the content.

- **Grid:** A 12-column layout for desktop, collapsing to 4 columns on mobile.
- **Rhythm:** An 8px base spacing scale ensures mathematical harmony across all components.
- **Section Spacing:** Major sections are separated by significant vertical gaps (120px - 160px) to allow each part of the portfolio (About, Projects, Experience) to breathe.
- **Responsive Behavior:** On mobile, margins tighten to 20px, and large display typography scales down significantly to ensure it remains within the viewport without breaking words.

## Elevation & Depth

Depth is not achieved through traditional drop shadows, but through **Tonal Layers** and **Glows**:

1.  **The Canvas:** The base background is the deepest layer (`#05070D`).
2.  **The Glass Layer:** Cards and containers (`#0F121D`) feature a 1px border at 10% white opacity. This creates a "glass edge" that catches the light.
3.  **Backdrop Blur:** Floating elements (like navigation bars) must use a `backdrop-filter: blur(12px)` to maintain legibility over moving content.
4.  **Outer Glows:** Interactive elements like primary buttons and featured project cards utilize a "Shadow Glow"—a soft, diffused shadow colored with the primary blue (`rgba(59, 130, 246, 0.3)`) rather than black. This makes the UI feel like it is emitting light.

## Shapes

The design system uses a dual-rounding strategy to create visual interest and hierarchy:

- **Cards & Major Containers:** Use a large radius (`1.5rem` or `24px`) to feel modern, friendly, and soft.
- **Interactive Elements (Pills/Buttons):** Use a smaller, tighter radius (`0.5rem` or `8px`) or a full pill shape for secondary tags. 
- **Portrait:** The user portrait (referenced in the image) should be contained within a card with the standard `1.5rem` radius or rendered as a soft-edged square to align with the grid.

## Components

### Buttons
- **Primary:** Gradient background (`accent_gradient`), white text, and a soft primary glow on hover.
- **Secondary:** Ghost style. Transparent background, 1px white/10% border, subtle white background on hover.

### Cards
- **Project Cards:** Feature an image top-section and a glassmorphic bottom-section. On hover, the border opacity increases from 10% to 30%, and the primary glow intensifies.
- **Skill Chips:** Small, pill-shaped containers using `jetbrainsMono`. Dark background with a Cyan (`#06B6D4`) subtle border.

### Input Fields
- Darkest navy background, subtle internal shadow for an "inset" look, and a Cyan focus ring. Labels always use the `label-md` mono font.

### Portrait Asset
- The user's portrait (`IMAGE_6`) should be displayed with a high-quality filter that slightly cools the color temperature to match the dark navy theme. Use a large border radius and a subtle cyan outer glow to integrate it into the "Electric" aesthetic.