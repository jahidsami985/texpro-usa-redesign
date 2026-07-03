---
name: Industrial Prestige
colors:
  surface: '#fbf9fb'
  surface-dim: '#dbd9dc'
  surface-bright: '#fbf9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f5'
  surface-container: '#efedf0'
  surface-container-high: '#e9e7ea'
  surface-container-highest: '#e4e2e4'
  on-surface: '#1b1b1d'
  on-surface-variant: '#44474d'
  inverse-surface: '#303032'
  inverse-on-surface: '#f2f0f3'
  outline: '#75777e'
  outline-variant: '#c5c6ce'
  surface-tint: '#4f5f7b'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#0a1c35'
  on-primary-container: '#7484a3'
  inverse-primary: '#b7c7e8'
  secondary: '#835500'
  on-secondary: '#ffffff'
  secondary-container: '#feae2c'
  on-secondary-container: '#6b4500'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1a1c1c'
  on-tertiary-container: '#838484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#b7c7e8'
  on-primary-fixed: '#0a1c35'
  on-primary-fixed-variant: '#374762'
  secondary-fixed: '#ffddb4'
  secondary-fixed-dim: '#ffb955'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#633f00'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c7'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#454747'
  background: '#fbf9fb'
  on-background: '#1b1b1d'
  surface-variant: '#e4e2e4'
  gold: '#F5A623'
  navy-deep: '#081a33'
  surface-muted: '#fbf9fb'
  border-glass: rgba(232, 237, 243, 0.5)
typography:
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  margin-desktop: 40px
  margin-mobile: 16px
  gutter: 24px
  section-padding: 80px
  container-max-width: 1280px
---

## Brand & Style
The brand identity is built on the pillars of **Precision, Scale, and Reliability**. It targets B2B decision-makers in the global apparel supply chain, evoking an emotional response of security and professional excellence. 

The visual style is **Corporate / Modern** with a subtle **Glassmorphic** layer for navigation. It utilizes deep industrial navy tones contrasted against clinical whites and high-contrast gold accents to signify premium service and operational authority. The aesthetic is clean, structured, and expansive, reflecting the vast scale of global manufacturing.

## Colors
The palette is dominated by **Navy Deep** (#081a33), representing stability and the industrial sector. **Gold** (#F5A623) serves as the primary action color, used sparingly for high-value conversions like "Request Quote" to create immediate visual hierarchy.

The background system relies on a very clean **Surface White** (#fbf9fb) with subtle grey containers to separate content sections. Transparency is used strategically in the navigation bar to maintain a sense of depth and modernity without sacrificing legibility.

## Typography
The system uses **Inter** exclusively to achieve a systematic, utilitarian, and highly legible look across all touchpoints. 

- **Headlines:** Use heavy weights (600-700) with tight letter spacing for a commanding presence.
- **Body:** Standardized on 16px and 18px for high readability in information-dense sections.
- **Labels:** Uppercase or high-tracking labels are used for navigation and small headers to create an architectural feel.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for large screens (centered 1280px container) and a fluid model for mobile devices. 

- **Vertical Rhythm:** Sections are separated by a generous 80px padding to allow the brand's expansive imagery to breathe.
- **Grid:** A standard 12-column grid is utilized for desktop, transitioning to a single-column stack on mobile.
- **Safe Areas:** Desktop margins are set at 40px, while mobile scales down to 16px to maximize screen real estate.

## Elevation & Depth
Depth is conveyed through a mix of **Tonal Layers** and **Ambient Shadows**.

- **Level 1 (Surface):** The base background of the site.
- **Level 2 (Panels):** Used for cards and secondary navigation, utilizing a subtle shadow (`0px 4px 20px rgba(8, 26, 51, 0.08)`) to lift elements off the page.
- **Level 3 (Interactive):** The fixed TopNavBar uses a glassmorphism effect (90% opacity white with 12px blur) to maintain context of the content beneath while providing a clear interface layer.
- **Overlays:** Dark navy overlays (70% opacity) are applied to hero images to ensure the white text maintains accessible contrast ratios.

## Shapes
The design uses a **Soft** shape language. Buttons and structural containers use a default radius of 0.125rem (2px) to 0.25rem (4px). This sharp-yet-refined rounding reinforces the industrial and precise nature of garment manufacturing. Full rounding (pill-shaped) is avoided to maintain a serious, corporate tone.

## Components

- **Buttons:**
    - **Primary:** Solid Gold background, white text, bold font-weight. High impact.
    - **Secondary/Outline:** 2px white border with transparent background for use on dark hero sections.
    - **Ghost:** Borderless with thin outlines (20% opacity) for utility actions like "Download Profile".

- **Navigation:** Fixed height (80px), using Inter font with active states marked by a bottom border in Tertiary-Fixed (Gold/Cream).

- **Cards/Value Props:** Simple layouts using Material Symbols (Outlined) in Navy. Icons should be 32px-40px.

- **Footer:** Deep Navy background with Surface-Dim text colors to create a clear "end of page" signal. Links use a gold hover state for consistency.

- **Inputs:** (Extended Guidance) Should use 1px borders in `outline-variant` with a focus state matching the `primary` navy color.