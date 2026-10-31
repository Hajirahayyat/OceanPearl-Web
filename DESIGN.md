---
name: Ocean Pearl Coastal Dining
colors:
  surface: '#041329'
  surface-dim: '#041329'
  surface-bright: '#2c3951'
  surface-container-lowest: '#010e24'
  surface-container-low: '#0d1c32'
  surface-container: '#112036'
  surface-container-high: '#1c2a41'
  surface-container-highest: '#27354c'
  on-surface: '#d6e3ff'
  on-surface-variant: '#bcc9ce'
  inverse-surface: '#d6e3ff'
  inverse-on-surface: '#233148'
  outline: '#869398'
  outline-variant: '#3d494d'
  surface-tint: '#4cd6fb'
  primary: '#4cd6fb'
  on-primary: '#003642'
  primary-container: '#00b4d8'
  on-primary-container: '#00414f'
  inverse-primary: '#00677d'
  secondary: '#94ccff'
  on-secondary: '#003352'
  secondary-container: '#0378b7'
  on-secondary-container: '#f5f8ff'
  tertiary: '#58d6f1'
  on-tertiary: '#00363f'
  tertiary-container: '#25b4ce'
  on-tertiary-container: '#00414c'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#b3ebff'
  primary-fixed-dim: '#4cd6fb'
  on-primary-fixed: '#001f27'
  on-primary-fixed-variant: '#004e5f'
  secondary-fixed: '#cde5ff'
  secondary-fixed-dim: '#94ccff'
  on-secondary-fixed: '#001d32'
  on-secondary-fixed-variant: '#004b74'
  tertiary-fixed: '#a7edff'
  tertiary-fixed-dim: '#58d6f1'
  on-tertiary-fixed: '#001f25'
  on-tertiary-fixed-variant: '#004e5b'
  background: '#041329'
  on-background: '#d6e3ff'
  surface-variant: '#27354c'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '500'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
---

## Brand & Style

This design system expresses the serene opulence, culinary mastery, and maritime grace of premier coastal gastronomy. Designed for high-net-worth patrons, epicurean travelers, and discerning diners, the aesthetic avoids rustic beach tropes in favor of an ethereal, deep-tide maritime luxury.

The visual direction merges **Minimalist Precision** with **Atmospheric Glassmorphism**:
- Oceanic depth achieved via deep abyss canvases punctuated by bioluminescent turquoise gradients and pearlescent finishes.
- Refined glass surfaces simulating sunlit waters and crystalline coastal sea spray.
- Whispered interactions, graceful typography pairings, and generous breathing room evoking the tranquil calm of open water at twilight.

## Colors

The palette mimics the descent into oceanic depths, framed with pearlescent light:
- **Canvas & Abyss (Neutral #0A192F):** The default dark background layer, anchoring the interface in deep naval mystery. Surface tiers step gradually into midnight indigo tones (`#0F243E`, `#162E4C`).
- **Luminous Cyan (Primary #00B4D8):** Represents ocean shallows kissed by sunlight; utilized for key calls to action, active indicators, and luminous focal points.
- **Ocean Crest (Secondary #0077B6):** A stable, oceanic blue providing intermediate contrast for secondary interactive states, category filters, and container boundaries.
- **Shallow Spray (Tertiary #48CAE4):** Used sparingly for hover glows, micro-interactions, and highlighted culinary tags.
- **Pearl Accents & Surface Light:** Crisp white (`#FFFFFF`) ensures immaculate editorial typography, supported by subtle silver pearl accents (`#E2E8F0`, `#F8FAFC`) at translucent opacities (8% to 18%) for ethereal dividers and glass containment lines.

## Typography

Typography establishes an editorial atmosphere akin to Michelin-starred maritime dining:
- **Headlines (Playfair Display):** Conveys timeless refinement, grand tasting menus, and culinary storytelling. It features high contrast, sculpted serifs, and soft transitional curves. Large headings feature slight negative letter tracking to retain density.
- **Body & Captions (Plus Jakarta Sans):** Balances the heritage serif with a modern, clear sans-serif that remains legible on dark backgrounds and translucent frosted planes.
- **Labels & Badges:** Rendered in uppercase Plus Jakarta Sans with generous letter-spacing (`0.08em` to `0.12em`), providing a structured nautical brass-plate sensibility across dietary tags, tasting course markers, and reservation times.

## Layout & Spacing

The layout model emphasizes expansive, horizontal breathing room reminiscent of coastal horizon lines:
- **Grid Architecture:** Desktop relies on a 12-column responsive grid with a maximum content container of `1280px`. Mobile reflows cleanly to a single-column or 2-column compact card layout.
- **Rhythm & Cadence:** Generous section spacing (`space-2xl`) prevents culinary items and imagery from feeling crowded. Content blocks breathe with soft inner paddings (`space-md` to `space-lg`), highlighting negative space.
- **Reflow Principles:** On desktop, menus and wine lists present as dual-column synchronized spreads. On mobile, components collapse into vertical journeys with sticky glassmorphic reservation bars affixed to the bottom viewport.

## Elevation & Depth

Visual hierarchy abandons traditional muddy dropshadows in favor of luminous underwater optical physics:
- **Base Canvas:** Deep navy (`#0A192F`) acts as the boundless ocean bed.
- **Glassmorphic Tiers:** Floating cards and reservation panels utilize `rgba(15, 36, 62, 0.65)` layered with a `backdrop-filter: blur(16px) saturate(160%)`.
- **Pearl Border Lighting:** Surfaces are framed by an ultra-thin 1px border colored with a gradient: `linear-gradient(135deg, rgba(248, 250, 252, 0.22) 0%, rgba(0, 180, 216, 0.08) 60%, rgba(248, 250, 252, 0.02) 100%)`. This creates a shimmering bevel effect catching ambient overhead light.
- **Ambient Bioluminescence:** Elevated modals and hero calls-to-action emit subtle cyan glows: `box-shadow: 0 12px 32px -8px rgba(0, 180, 216, 0.18), 0 4px 12px rgba(10, 25, 47, 0.6)`.

## Shapes

The design uses a tailored, soft shape geometry (`roundedness: 1`):
- Corners feature discreet, architectural radii (4px base, 8px on cards, 12px on luxury modals) that preserve sleek luxury without harsh industrial edges.
- Interactive elements, such as buttons and wine vintage tags, retain structured geometric discipline with softly eased edges rather than toy-like pill capsules.
- Floating micro-elements (such as image masks and sommelier badges) employ gentle 8px radiuses with polished glass border framing.

## Components

### Buttons
- **Primary (Reserve / Book Table):** Solid cyan gradient (`linear-gradient(135deg, #00B4D8 0%, #0077B6 100%)`) with white bold text, subtly luminous shadow, and a 1px inner pearl border (`rgba(255, 255, 255, 0.2)`).
- **Secondary (Explore Menu / Cellar):** Translucent glass fill (`rgba(255, 255, 255, 0.04)`), crisp 1px border of `#E2E8F0` at 30% opacity, and bright pearlescent text (`#F8FAFC`). Hover shifts background to `rgba(0, 180, 216, 0.12)`.
- **Text Action:** Playfair or Plus Jakarta label with an animated pearl underline that extends from left to right on hover.

### Menu & Seafood Cards
- **Card Body:** Translucent navy background with 16px backdrop blur, framed in delicate pearlescent borders.
- **Media Presentation:** Seafood photography is crowned by an ambient vignette bleeding seamlessly into the card container.
- **Dish Titles & Accents:** Playfair Display headers paired with trailing pearl-dotted rule lines leading to prices rendered in crisp cyan typography.

### Input Fields & Reservation Selectors
- **Form Controls:** Dark recessed base (`rgba(10, 25, 47, 0.8)`) with soft pearl outline (`rgba(226, 232, 240, 0.2)`). 
- **Focus State:** Border transitions smoothly to `#00B4D8` accompanied by an ambient turquoise outer glow (`0 0 0 3px rgba(0, 180, 216, 0.2)`). Placeholder copy is styled in muted silver (`#94A3B8`).

### Chips & Dietary Badges
- **Status Chips (Wild Caught, Raw Bar, Chef's Reserve):** Compact containers using 4px border radiuses, uppercase tracking, `rgba(0, 180, 216, 0.1)` backgrounds, and tertiary cyan borders (`#48CAE4` at 40% opacity).

### Checkboxes & Radios
- Custom metallic boxes and dials surrounded by deep navy styling, filling with a radial cyan gradient and an oyster-white center dot upon selection.

### Bespoke Domain Components
- **Raw Bar Tier Selector:** An architectural step-indicator representing Plateau de Mer seafood tower levels.
- **Cellar & Caviar Pairing Drawer:** A glass slide-out drawer featuring soft backdrop blur and pearl divider lines for curated champagne pairings.