---
name: Atelier Editorial
colors:
  surface: '#faf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#faf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f3f1'
  surface-container: '#efeeeb'
  surface-container-high: '#e9e8e5'
  surface-container-highest: '#e3e2e0'
  on-surface: '#1a1c1a'
  on-surface-variant: '#444748'
  inverse-surface: '#2f312f'
  inverse-on-surface: '#f2f1ee'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5f5e5b'
  on-secondary: '#ffffff'
  secondary-container: '#e1dfdb'
  on-secondary-container: '#63635f'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#241a00'
  on-tertiary-container: '#a08000'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474646'
  secondary-fixed: '#e4e2dd'
  secondary-fixed-dim: '#c8c6c2'
  on-secondary-fixed: '#1b1c19'
  on-secondary-fixed-variant: '#474744'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#faf9f6'
  on-background: '#1a1c1a'
  surface-variant: '#e3e2e0'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 68px
    letterSpacing: -0.03em
  display-hero-mobile:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 44px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: -0.03em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 30px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: -0.025em
  headline-md-mobile:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 30px
    letterSpacing: -0.02em
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.02em
  title-editorial:
    fontFamily: Playfair Display
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0em
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.12em
  label-caps-subtle:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '500'
    lineHeight: 12px
    letterSpacing: 0.15em
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 3rem
---

## Brand & Style

The design system embodies modern quiet luxury and high-end editorial curation, drawing inspiration from high-fashion lookbooks, museum catalogues, and minimalist architectural volumes. It addresses discerning, design-literate consumers who value restraint, craft, and understated elegance over fleeting trends.

### Visual Aesthetic & Philosophy
- **Editorial Minimalism:** Visual weight is driven by full-bleed imagery, generous whitespace, and sharp typographic tension rather than heavy decorative elements.
- **Architectural Rigor:** Layouts rely on structural hairline divisions, deliberate proportions, and strict grid alignments that mirror modern physical art spaces.
- **Atmospheric Quietude:** Interfaces act as a neutral, bespoke frame that allows garments, textures, and silhouettes to hold full center stage. Motion is deliberately deliberate, quiet, and weighted.

## Colors

The palette is rooted in classical editorial paper stocks and museum finishes. Pure digital white (`#FFFFFF`) is avoided in favor of warm, tactile off-whites that simulate heavy bond paper.

### Palette Architecture
- **Primary Canvas (`#FAF9F6`):** Warm alabaster background creating a non-glare, organic foundation.
- **Secondary Surface (`#F2F0EB`):** Soft stone gray used exclusively for secondary containers, collection cards, and subtle module differentiation.
- **Primary Ink (`#111111`):** Deep carbon black for headings, primary body copy, solid call-to-action surfaces, and stark contrast elements.
- **Secondary Ink (`#666666`):** Balanced neutral grey for supporting copy, garment specs, and tertiary descriptions.
- **Borders & Dividers (`#E5E5E5`):** Razor-thin hairline frames separating grid modules without visually breaking fluid eye movement.
- **Strikethrough & De-emphasized (`#999999`):** Archival pricing, sold-out statuses, and inactive pagination indicators.
- **Accent Highlight (`#D4AF37`):** Muted atelier gold reserved strictly for membership tiers, exclusive badge strokes, and micro-highlights. Used with strict restraint (never as large surface fills).

## Typography

The typographical pairing relies on high-contrast drama between the classical high-contrast serif (`Playfair Display`) and the clean geometry of `Plus Jakarta Sans`.

### Editorial Rules
- **Headline Tightness:** All serif headings must employ negative tracking (`-0.03em` to `-0.02em`) to mirror the bespoke typography seen in printed editorial fashion mastheads. Italic variants are reserved for poetic descriptors or seasonal motifs.
- **Micro-Labels & Meta:** Use `label-caps` strictly in uppercase (`text-transform: uppercase`). The wide letter-spacing (`0.12em` to `0.15em`) ensures clarity at small dimensions while signaling high-fashion tagging (e.g., `FABRIC / 100% VIRGIN CASHMERE`, `EDITION 01/24`).
- **Body Rhythm:** Body text remains natural and balanced with relaxed line-heights to support effortless storytelling and detailed garment specifications.

## Layout & Spacing

The layout is built upon architectural grid balance, asymmetric editorial storytelling, and generous negative space that allows garments to breathe.

### Grid & Composition
- **Desktop (12 Columns):** 12-column fluid grid bounded by generous outer canvas margins (`margin-desktop: 4rem`) and `2.5rem` gutters. Used for alternating full-width hero spreads, 2-column asymmetric lookbook modules, and 4-column product showcases.
- **Tablet (8 Columns):** Standardized 8-column layout with `2rem` margins and `1.5rem` gutters.
- **Mobile (4 Columns):** Strict 4-column system with `1.25rem` margins and `1rem` gutters. Full-bleed vertical image cards (3:4 or 4:5 ratios) ensure high impact on smaller screens.
- **Vertical Ryhthm:** Section divides leverage extended vertical spacing (`space-xl` scaled dynamically up to `6rem` - `8rem` on large viewports) to evoke physical gallery transitions.

## Elevation & Depth

True luxury interfaces avoid synthetic drop shadows or volumetric extrusion. Depth in this design system is strictly graphic, architectural, and tactile.

### Dimensional Principles
- **No Drop Shadows:** Default elements sit flush on the surface canvas. Shadows are omitted entirely in favor of flat planar transitions.
- **Surface Layering:** Hierarchy is generated by resting `#F2F0EB` (Soft Stone) containers directly on `#FAF9F6` (Alabaster) planes.
- **Hairline Framing:** Crisp 1px `#E5E5E5` borders define perimeter zones, sticky navigation bands, and filter drawers without adding visual bulk.
- **Floating Overlays & Sheets:** Contextual panels (cart drawer, filter slide-outs, size guides) enter flush against the viewport edges with a solid `#FAF9F6` fill, framed by a single 1px left or right `#111111` or `#E5E5E5` border line and accompanied by a quiet, semi-transparent neutral veil (`rgba(17, 17, 17, 0.35)`).

## Shapes

The shape language is strictly architectural and uncompromising. Elements adopt a sharp `0px` radius (or an absolute maximum of 1px for rendered vector glyphs) to project modern precision, reminiscent of freshly cut paper and framed gallery prints.

### Spatial Treatment
- **Buttons, Inputs, Cards:** Absolute rectangular corners (`0px`).
- **Media Assets:** Crisp cut edges without rounding. Photographic assets rely on precise aspect ratios: `3:4` for editorial looks, `1:1` for detail swatches, and `16:9` or `4:5` for cinematic hero modules.
- **Badges & Micro-tags:** Rectangular blocks with razor-sharp borders and zero curvature.

## Components

### Buttons & Interactive Triggers
- **Primary CTA:** Solid `#111111` background, `#FAF9F6` text, 0px border radius, uppercase typography (`label-caps`), dynamic padding (`14px 28px`). Hover state: subtle opacity drop to `0.88` or background shift to `#333333`.
- **Secondary Button:** Hairline border (1px `#111111`), transparent background, `#111111` text. Hover state: invert to solid `#111111` with `#FAF9F6` text.
- **Text Links:** Clean inline text accompanied by a fine 1px bottom underline offset by 4px, animating out on hover.

### Form Inputs & Selectors
- **Text Inputs:** Minimalist underline style or boxed field with 1px `#E5E5E5` border, expanding to 1px `#111111` on active focus. No glow effects. Labels render above the field in `label-caps` using `#666666`.
- **Checkboxes & Radios:** Sharp 0px square boxes for both types (radios differentiated with an internal sharp 6px solid black square when selected). 1px `#111111` border.
- **Dropdowns / Filters:** Minimalist triggers with micro directional chevrons (`8px`), opening flat un-shadowed panels bounded by 1px `#E5E5E5`.

### Product Cards & Editorial Tiles
- **Structure:** Strict image container on top with zero padding inside the card. Aspect ratio fixed to `3:4`.
- **Background:** Soft Stone (`#F2F0EB`) behind isolated product cutouts, or full-bleed location photography.
- **Card Meta:** Positioned below the media. Title in `title-editorial` or `body-md` in `#111111`, category in `label-caps` in `#666666`, price structured with current price (`#111111`) and strikethrough archive price (`#999999`).
- **Interactive Badges:** Placed at the top-left margin of the image with a hairline `#E5E5E5` border and `#FAF9F6` surface (`NEW ARRIVAL`, `LIMITED EDITION`, `ARCHIVE`).

### Size & Color Selectors
- **Size Selector:** Sharp grid blocks with 1px `#E5E5E5` borders. Selected size fills with solid `#111111` and `#FAF9F6` text. Unavailable sizes show a diagonal 1px strike across the box with `#999999` text.
- **Color Swatches:** 18px square color blocks framed with a 1px `#E5E5E5` outline, separated by a 2px offset border when active.

### Drawers & Navigation
- **Header:** Sticky, translucent warm alabaster (`rgba(250, 249, 246, 0.92)`) with a subtle `backdrop-filter: blur(8px)` and a bottom 1px `#E5E5E5` border.
- **Slide-out Cart & Details Panel:** Anchored flush to the right viewport. Full-height, `#FAF9F6` surface with clean internal line dividers between line items.