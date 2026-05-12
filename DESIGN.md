---
name: Premium Pet Design System
colors:
  surface: '#f8f9ff'
  surface-dim: '#c4dcfd'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef4ff'
  surface-container: '#e4efff'
  surface-container-high: '#dbe9ff'
  surface-container-highest: '#d1e4ff'
  on-surface: '#011d35'
  on-surface-variant: '#414750'
  inverse-surface: '#19324b'
  inverse-on-surface: '#e9f1ff'
  outline: '#727781'
  outline-variant: '#c1c7d2'
  surface-tint: '#1961a1'
  primary: '#003e6f'
  on-primary: '#ffffff'
  primary-container: '#005696'
  on-primary-container: '#a5cbff'
  inverse-primary: '#a1c9ff'
  secondary: '#006e0c'
  on-secondary: '#ffffff'
  secondary-container: '#8ff780'
  on-secondary-container: '#00730d'
  tertiary: '#513900'
  on-tertiary: '#ffffff'
  tertiary-container: '#6e4f00'
  on-tertiary-container: '#fcbf35'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4ff'
  primary-fixed-dim: '#a1c9ff'
  on-primary-fixed: '#001c37'
  on-primary-fixed-variant: '#004880'
  secondary-fixed: '#92fa83'
  secondary-fixed-dim: '#77dd6a'
  on-secondary-fixed: '#002201'
  on-secondary-fixed-variant: '#005307'
  tertiary-fixed: '#ffdea4'
  tertiary-fixed-dim: '#fabd32'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4200'
  background: '#f8f9ff'
  on-background: '#011d35'
  surface-variant: '#d1e4ff'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-lg:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter-desktop: 24px
  gutter-mobile: 16px
  margin-desktop: 40px
  margin-mobile: 20px
---

## Brand & Style

The design system is built on the pillars of **trust, vitality, and sophistication**. It serves a discerning audience of pet owners who view their animals as family members deserving of professional-grade care. The brand personality balances the clinical authority of veterinary science with the warm, nurturing environment of a luxury boutique.

The visual style follows a **Modern Corporate** aesthetic with **Minimalist** influences. It utilizes generous whitespace and a restricted color palette to ensure the vibrant brand colors feel intentional and high-end rather than overwhelming. The interface emphasizes clarity and ease of navigation, evoking an emotional response of reliability and calm.

## Colors

The color strategy for this design system utilizes **Vibrant Blue (#005696)** as the primary anchor, representing stability and expertise. **Forest Green (#228B22)** acts as the secondary color, symbolizing health, nature, and the animal kingdom.

- **Primary (Blue):** Reserved for high-priority actions, navigation headers, and brand-critical iconography.
- **Secondary (Green):** Used for "Success" states, health-related features, and subtle accents in illustrations or secondary buttons.
- **Background:** A soft off-white (#FCFCFA) is used instead of pure white to reduce eye strain and provide a more "editorial" premium feel.
- **Neutral:** A deep slate blue-grey is used for typography to maintain high contrast while feeling more integrated with the brand palette than pure black.

## Typography

This design system employs a sophisticated typographic pairing to signal both elegance and efficiency. 

**Playfair Display** is used for all headlines. Its high-contrast serifs provide a classic, editorial look that elevates the pet store's premium positioning. It should be used with tight tracking in display sizes to maintain a modern edge.

**Manrope** is the workhorse for body copy, UI elements, and labels. Its geometric yet friendly proportions ensure maximum readability across digital devices. Label styles often use uppercase styling with increased letter spacing to create a clear visual hierarchy between content and navigation.

## Layout & Spacing

The design system utilizes a **Fixed Grid** model for desktop to ensure content remains centered and curated, reflecting a high-end retail experience. 

- **Grid System:** A 12-column grid on desktop (1200px max-width) and a 4-column grid on mobile. 
- **Spacing Rhythm:** An 8px linear scale (8, 16, 24, 32, 48, 64) dictates all margins and paddings. 
- **Reflow:** On tablet devices, margins compress to 32px, and gutters remain at 24px. On mobile, the gutters tighten to 16px to maximize screen real estate for product imagery. 
- **Vertical Rhythm:** Sections are separated by large 80px or 120px blocks of whitespace to create a sense of "breathable" luxury.

## Elevation & Depth

To maintain a clean and professional look, this design system avoids heavy shadows in favor of **Ambient Depth** and **Tonal Layers**. 

Depth is primarily achieved through:
1.  **Subtle Surface Tinting:** Using very light shades of the primary blue or neutral slate for background containers (e.g., product filters or cart sidebars).
2.  **Soft Ambient Shadows:** Elements like cards use a high-blur (24px+), low-opacity (4-6%) shadow tinted with the primary blue (#005696) to make them feel integrated into the surface.
3.  **Keyline Borders:** High-readability is supported by 1px borders in a light neutral grey (#E4E7EB) to define boundaries without adding visual weight.

## Shapes

The shape language is **Rounded**, striking a balance between the organic forms of nature and the precision of a professional service. 

- **Standard Radius (8px):** Applied to buttons, input fields, and standard UI containers.
- **Large Radius (16px):** Reserved for product cards, promotional banners, and high-level section containers.
- **Extra Large Radius (24px):** Used for modal overlays and large "Call to Action" sections.

This consistent rounding softens the high-contrast typography and creates an approachable, friendly environment appropriate for a pet-focused brand.

## Components

### Buttons
Primary buttons use the Brand Blue (#005696) with white Manrope text in semi-bold. Secondary buttons use a Forest Green (#228B22) outline or solid fill for "Add to Cart" or "Success" related actions. All buttons have a subtle hover transition where the background color deepens by 10%.

### Input Fields
Inputs feature a 1px neutral border that turns Blue on focus. Labels use the `label-md` style positioned above the field. Error states utilize a desaturated red, ensuring it doesn't clash with the vibrant brand green.

### Cards
Product cards are a signature component. They feature a clean #FFFFFF background, a soft ambient shadow, and 16px corner radius. The product name is set in `headline-md` (Playfair Display) to emphasize the premium nature of the goods.

### Chips & Tags
Used for categories (e.g., "Organic," "Puppy," "Grain-Free"). These use the secondary Green (#228B22) at a 10% opacity for the background and 100% opacity for the text, creating a soft, legible tag system.

### Progress Indicators
For checkout or pet profiles, the system uses a combination of the Blue and Green to show completion. Completed steps are Green (Healthy/Done), while active steps are Blue (Action/Focus).