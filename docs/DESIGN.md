---
name: Modern Vietnamese Heritage
colors:
  surface: '#fdf9eb'
  surface-dim: '#dedacd'
  surface-bright: '#fdf9eb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f8f4e6'
  surface-container: '#f2eee0'
  surface-container-high: '#ece8da'
  surface-container-highest: '#e6e2d5'
  on-surface: '#1c1c14'
  on-surface-variant: '#5d403b'
  inverse-surface: '#323128'
  inverse-on-surface: '#f5f1e3'
  outline: '#916f6a'
  outline-variant: '#e6bdb7'
  surface-tint: '#bf080b'
  primary: '#b40006'
  on-primary: '#ffffff'
  primary-container: '#da251d'
  on-primary-container: '#fff3f1'
  inverse-primary: '#ffb4a9'
  secondary: '#b3176d'
  on-secondary: '#ffffff'
  secondary-container: '#ff5ba9'
  on-secondary-container: '#64003a'
  tertiary: '#705d00'
  on-tertiary: '#ffffff'
  tertiary-container: '#c9a900'
  on-tertiary-container: '#4c3f00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad5'
  primary-fixed-dim: '#ffb4a9'
  on-primary-fixed: '#410001'
  on-primary-fixed-variant: '#930004'
  secondary-fixed: '#ffd9e4'
  secondary-fixed-dim: '#ffb0cd'
  on-secondary-fixed: '#3e0021'
  on-secondary-fixed-variant: '#8c0053'
  tertiary-fixed: '#ffe16d'
  tertiary-fixed-dim: '#e9c400'
  on-tertiary-fixed: '#221b00'
  on-tertiary-fixed-variant: '#544600'
  background: '#fdf9eb'
  on-background: '#1c1c14'
  surface-variant: '#e6e2d5'
typography:
  headline-xl:
    fontFamily: Libre Caslon Text
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Libre Caslon Text
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-lg-mobile:
    fontFamily: Libre Caslon Text
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.3'
  headline-md:
    fontFamily: Libre Caslon Text
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  quote:
    fontFamily: Libre Caslon Text
    fontSize: 22px
    fontWeight: '400'
    lineHeight: '1.5'
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
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1200px
---

## Brand & Style
The design system bridges the historical weight of Vietnamese revolutionary ethics with the vibrant, digital-first energy of Gen Z. It evokes a sense of "Respectful Modernity"—honoring the past through traditional motifs while ensuring the interface feels as fluid and responsive as a contemporary social platform.

The visual style is a hybrid of **Minimalism** and **Tactile/Skeuomorphic** design. We utilize the clean, spacious layouts of modern SaaS products but ground them with the organic textures of "Giấy Dó" (traditional paper) and the geometric precision of Dong Son patterns. The emotional response should be one of pride, clarity, and curiosity.

## Colors
The palette is deeply rooted in Vietnamese symbolism. 
- **Revolutionary Red (#DA251D):** Used for primary actions, critical headings, and progress indicators. It represents strength and the national flag.
- **Lotus Pink (#EE4D9B):** Used for interactive highlights, decorative elements, and success states, bringing a youthful, floral softness to the UI.
- **Imperial Gold (#FFD700):** Reserved for achievements, "Golden Quotes," and high-value rewards within the interactive experience.
- **Ancient Paper (#F9F5E7):** The global background color. It reduces eye strain and provides a tactile, "library" feel that distinguishes the product from standard white-screen educational tools.
- **Dark Charcoal (#1A1A1A):** Used for body text to ensure high legibility against the cream background.

## Typography
The typography strategy contrasts the literary authority of **Libre Caslon Text** (Headings) with the contemporary accessibility of **Be Vietnam Pro** (Body). 

Headings should be treated with editorial care, using larger font sizes and tighter letter spacing for a newspaper-masthead effect. Body text prioritizes legibility with generous line heights. Use the `quote` style for historical excerpts, often paired with a subtle vertical red line or a lotus icon as a bullet point.

## Layout & Spacing
The system uses a **Fixed Grid** on desktop to maintain an editorial feel, transitioning to a **Fluid Grid** on mobile. 
- **Desktop:** 12-column grid with a 1200px max-width.
- **Tablet:** 8-column grid with 24px gutters.
- **Mobile:** 4-column grid with 16px margins.

Spacing follows an 8px base unit. Narrative sections should employ significant vertical padding (80px–120px) to create a "breathing" effect between different historical eras or story chapters. Interactive components like quiz cards use a tighter internal padding (24px) to feel compact and focused.

## Elevation & Depth
Depth is achieved through **Tonal Layers** rather than heavy shadows. 
- **Surface 0:** The "Ancient Paper" base background.
- **Surface 1:** Cards and interactive containers use a pure white or very light cream background with a subtle 1px border in #DA251D (at 10% opacity).
- **Surface 2:** Active or hovered elements use a "floating" effect created by a soft, diffused shadow tinted with the primary red (e.g., `box-shadow: 0 8px 24px rgba(218, 37, 29, 0.08)`).

Dong Son motifs should be applied as low-opacity SVG backgrounds (3–5% opacity) to Surface 0 to provide texture without interfering with text legibility.

## Shapes
The shape language is **Soft**. This choice balances the geometric nature of traditional Vietnamese architectural motifs with the friendliness required for an educational tool. 
- Standard buttons and cards use a 0.25rem (4px) corner radius.
- Interactive "pills" for categories or tags use the `rounded-xl` (12px) setting to provide visual variety and a modern touch.

## Components
- **Navigation:** A fixed top bar featuring a "Revolutionary Red" progress line indicating reading progress. Menu items use the `label-md` style.
- **Interactive Story Cards:** Large-format cards with a "Giấy Dó" texture overlay. Images should use a subtle sepia or high-contrast filter to align with the historical theme.
- **Infographic Lists:** Used for timelines. Steps are marked by "Lotus" icons or numbers in "Imperial Gold."
- **Quiz UI:** Selection buttons should have a thick 2px border that turns "Revolutionary Red" when selected. Success states should utilize "Lotus Pink" confetti or icons.
- **Call-to-Action Buttons:** Primary buttons are solid #DA251D with white text; secondary buttons are outlined in #DA251D with a cream background.
- **Historical Quotes:** Centered, italicized blocks using the `quote` typography, framed by decorative "Dong Son" corner brackets.