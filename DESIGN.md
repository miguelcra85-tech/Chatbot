---
name: Premium B2B Strategy System
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
  on-surface-variant: '#d1c5b4'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#9a8f80'
  outline-variant: '#4e4639'
  surface-tint: '#e9c176'
  primary: '#e9c176'
  on-primary: '#412d00'
  primary-container: '#c5a059'
  on-primary-container: '#4e3700'
  inverse-primary: '#775a19'
  secondary: '#c8c6c5'
  on-secondary: '#303030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#c6c6c7'
  on-tertiary: '#2f3131'
  tertiary-container: '#a4a5a5'
  on-tertiary-container: '#393b3b'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4201'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-sm:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 20px
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
    lineHeight: '1.6'
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
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
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style
The design system is engineered for "Migue Strategy" to project an aura of elite performance, strategic clarity, and understated luxury. It merges the functional precision of high-end productivity tools like Linear with the aspirational aesthetics of Apple and Stripe.

The visual style is **Minimalist-Glassmorphism**. It relies on high-contrast foundations, generous whitespace, and sophisticated material effects. The goal is to create a workspace that feels like a premium physical office: quiet, focused, and composed of high-quality materials. Every interaction should feel intentional, using subtle micro-interactions to provide feedback without cluttering the cognitive load of the B2B user.

## Colors
This design system utilizes a palette of high-contrast neutrals punctuated by a singular, luxurious accent. 

- **Primary (Metallic Gold):** Used sparingly for high-value calls to action, active states, and brand signatures. It should feel like a foil stamp on matte paper.
- **Backgrounds:** The "Dark Mode" (primary) uses a deep black (#000000) for true depth, while "Light Mode" uses a pure white (#FFFFFF). 
- **Surface Tones:** Graphite grey is used to create hierarchical layers, providing a softer alternative to pure black for containers and sidebars.
- **Accents:** Use semi-transparent whites and blacks to create the glassmorphic effects, ensuring that the background colors bleed through subtly to maintain the "material" feel.

## Typography
The system uses **Inter** exclusively to achieve a systematic, utilitarian, and modern corporate feel. The typographic hierarchy is built on tight leading and negative letter-spacing for large headlines to emulate high-end editorial layouts.

- **Display & Headlines:** Use SemiBold or Bold weights with slight negative tracking to create a "dense" and authoritative look.
- **Body Text:** Standardized at 16px for optimal legibility with a generous 1.6 line height to ensure clarity in data-dense B2B environments.
- **Labels:** Small labels use a medium/semibold weight and slight letter spacing for improved scannability in navigation and table headers.

## Layout & Spacing
The design system follows a **Fixed-Fluid Hybrid** layout. Content resides within a 1200px max-width container for desktop to maintain readability, while utilizing a fluid 12-column grid for internal dashboard components.

- **Grid:** 12 columns with 24px gutters. 
- **Rhythm:** An 8px linear scale governs all padding and margins, ensuring mathematical harmony across the UI.
- **Responsive Behavior:** 
  - **Desktop (1200px+):** Full 12 columns, 64px side margins.
  - **Tablet (768px - 1199px):** 8 columns, 32px side margins.
  - **Mobile (<767px):** 4 columns, 16px side margins. Stacked layouts become the default for complex data tables.

## Elevation & Depth
Depth in this design system is achieved through **Tonal Layering** and **Backdrop Blurs** rather than heavy shadows.

- **The Glass Effect:** Surface containers use a semi-transparent background (e.g., `rgba(255, 255, 255, 0.05)` in dark mode) with a `backdrop-filter: blur(20px)`. 
- **Borders:** Instead of shadows, use "Inner Glow" borders. A 1px solid stroke with 10-15% opacity (White in dark mode, Black in light mode) creates a crisp edge that suggests elevation.
- **Shadows:** Reserved for floating elements like dropdowns and modals. Use a "Large Ambient" shadow: `0 20px 40px rgba(0,0,0,0.3)`.
- **Tonal Tiers:** Level 0 is the background. Level 1 is the primary content card. Level 2 is for interactive elements like inputs or nested cards.

## Shapes
The shape language is sophisticated and controlled. By utilizing a "Rounded" (0.5rem) base, the system avoids the "bubbly" look of consumer apps while remaining more approachable than sharp-edged brutalist designs.

- **Base Radius:** 8px (0.5rem) for standard buttons, inputs, and small cards.
- **Large Radius:** 16px (1rem) for main content containers and modal windows.
- **Pill Radius:** Used exclusively for status chips (e.g., "Active", "Pending") to differentiate them from interactive buttons.

## Components
Consistent component styling reinforces the premium B2B identity.

- **Buttons:** 
  - *Primary:* Solid Gold (#C5A059) with Black text. No shadow, but a slight scale-down effect on click (0.98x).
  - *Secondary:* Glassmorphic (Blured background) with a 1px white border at 20% opacity.
- **Input Fields:** Flat dark background with a bottom-only border that transitions to Gold on focus. Use placeholder text in a subtle grey.
- **Cards:** Use the glassmorphic style. Ensure a 1px border is applied to give the "glass" a physical edge. Padding should be a minimum of 24px (md).
- **Chips/Badges:** Small, capitalized text with a subtle background tint of the status color (e.g., subtle green for 'Success') and high-contrast text.
- **Lists/Tables:** High-density with subtle 1px dividers. Hover states should use a slight background highlight (`rgba(255,255,255,0.03)`).
- **Interactive Micro-animations:** All transitions (hover, focus, page entry) must use a "Quartic" easing function (0.25, 1, 0.5, 1) for a smooth, high-end feel.