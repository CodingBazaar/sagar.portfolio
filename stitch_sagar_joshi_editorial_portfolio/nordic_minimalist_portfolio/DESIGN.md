---
name: Nordic Minimalist Portfolio
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f4'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#45464c'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f0f1f1'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#575e70'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#141b2b'
  on-primary-container: '#7d8497'
  inverse-primary: '#c0c6db'
  secondary: '#585f6c'
  on-secondary: '#ffffff'
  secondary-container: '#dce2f3'
  on-secondary-container: '#5e6572'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1b1b1b'
  on-tertiary-container: '#848484'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dce2f7'
  primary-fixed-dim: '#c0c6db'
  on-primary-fixed: '#141b2b'
  on-primary-fixed-variant: '#404758'
  secondary-fixed: '#dce2f3'
  secondary-fixed-dim: '#c0c7d6'
  on-secondary-fixed: '#151c27'
  on-secondary-fixed-variant: '#404754'
  tertiary-fixed: '#e2e2e2'
  tertiary-fixed-dim: '#c6c6c6'
  on-tertiary-fixed: '#1b1b1b'
  on-tertiary-fixed-variant: '#474747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Inter
    fontSize: 36px
    fontWeight: '600'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
    letterSpacing: 0em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
    letterSpacing: 0em
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.05em
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

The design system embodies modern Swiss and Nordic minimalism: restrained, confident, and meticulously organized. It caters to discerning creative directors, architects, design technologists, and modern craft studios who require a showcase where the work remains the primary visual focal point.

Key pillars of this style include:
- **Absolute Reductive Clarity:** Elimination of superfluous decorative motifs, gradients, and heavy stylistic treatments.
- **Generous Spatial Ratios:** Ample negative space that frames imagery, editorial text, and structural data.
- **Functional Precision:** Strict alignment, crisp boundaries, deliberate typographic rhythm, and seamless interaction states.

## Colors

The palette is monochromatic and high-contrast, leaning on tonal shifts between pure whites, tinted neutrals, and deep carbon accents to structure the experience.

- **Primary Canvas (`#ffffff`):** Pure, clean white serving as the baseline field for content and viewport boundaries.
- **Surface & Containers (`#f8f9fa`):** A soft, neutral tint used for secondary backgrounds, interactive wells, subtle cards, and preview frames.
- **Text & High Emphasis (`#111827`):** Deep charcoal/carbon delivering balanced legibility without the harshness of raw ink.
- **Muted & Metadata (`#6b7280`):** Neutral gray dedicated to captions, secondary metadata, breadcrumbs, and inactive controls.
- **Structural Lines (`#e5e7eb`):** Whispering hairline borders providing spatial definition without visual noise.
- **Accent / Emphasis (`#000000`):** Solid black reserved strictly for primary interactive states, active indicators, and high-impact calls to action.

## Typography

Typographic scale is structured through strict geometric sans-serif rules, leaning exclusively on Inter for universal cross-platform clarity. 

- Tight tracking (`-0.03em` to `-0.01em`) on larger scale elements ensures dense, modern headlines without feeling crowded.
- Body text retains natural tracking and extended line heights (`1.5` to `1.6`) to maintain effortless scanning across diverse viewport widths.
- Metadata and uppercase labels employ slight tracking expansions (`+0.04em` to `+0.05em`) to balance small font sizes with legibility.

## Layout & Spacing

The layout is built on a 12-column grid system bounded by maximum content constraints:
- **Desktop (1280px+):** 12 columns, 1.5rem (`24px`) gutters, centered layout capped at a maximum width of `1440px` with 3rem (`48px`) minimum outer margins.
- **Tablet (768px – 1024px):** 8 columns, 1.5rem gutters, with `2rem` page padding.
- **Mobile (< 768px):** 4 columns, 1rem (`16px`) gutters, with 1.25rem (`20px`) outer page padding.

Spacing strictly adheres to an 8pt architectural rhythm, with 4px intervals for fine-grained alignments. Structural vertical breaks between case studies and major thematic chapters leverage `space-2xl` (`64px`) or multiples thereof to promote uninterrupted flow and visual respite.

## Elevation & Depth

This design system avoids dropped shadows, synthetic glows, and heavy skeuomorphic layering. Hierarchy and physical depth are communicated strictly through:

1. **Surface Tone Shifts:** Floating surfaces, sticky bars, and project cards transition from pure `#ffffff` to subtle surface neutral `#f8f9fa`.
2. **Hairline Outlines:** 1px borders using `#e5e7eb` define containers, card partitions, and tables without visual clutter.
3. **Layer Transparency:** Sticky navigation systems utilize an optical blur (`backdrop-filter: blur(12px)`) with `rgba(255, 255, 255, 0.85)` background, preserving context while navigating deep case studies.
4. **Interactive Contrast Shift:** Interactive elements assert elevation during `:hover` or `:focus` via border darkenings (`#111827`) rather than y-axis displacement or shadow blooms.

## Shapes

The geometry follows a restrained, soft-architectural profile (`roundedness: 1`):
- Standard interactive elements, inputs, and project cards utilize a `4px` (`0.25rem`) border radius.
- Modals, large image containers, and floating preview panes leverage `8px` (`0.5rem`).
- Small system indicators, badges, and tags feature modest `4px` rounding, avoiding oval or circular pill shapes to maintain the Nordic architectural structure.

## Components

### Buttons
- **Primary:** Solid `#111827` background, `#ffffff` text, 4px border radius. Padding: `10px 18px`. Hover: shifts to `#000000`. Active: micro scale transition (`scale(0.99)`).
- **Secondary / Ghost:** Transparent background, 1px solid `#e5e7eb`, `#111827` text. Hover: `#f8f9fa` background with `#111827` border.
- **Text Link:** `#111827` body text with a solid 1px bottom border spaced 2px below baseline; transitions to `#6b7280` on hover.

### Chips & Filter Tags
- Compact height (`28px`), 4px border radius, 1px solid `#e5e7eb`, `#6b7280` text.
- Active state: `#111827` background, `#ffffff` text, no border.

### Project & Media Cards
- Base: `#ffffff` canvas with an optional 1px hairline border in `#e5e7eb` or borderless atop `#f8f9fa` backgrounds.
- Image containers maintain fixed aspect ratios (16:10 or 4:3) with 4px border radius and `overflow: hidden`.
- Hover: Image subtly scales (`scale(1.02)`) over `400ms cubic-bezier(0.16, 1, 0.3, 1)`; titles remain static or shift in underline opacity.

### Form Inputs
- Background `#ffffff`, 1px solid border `#e5e7eb`, 4px corner radius.
- Typography: `14px` body text.
- Focus: 1px solid `#111827` with no offset glow ring.
- Placeholder text: `#6b7280`.

### Checkboxes & Radios
- Checkboxes: 16px square, 3px border radius, 1px solid `#e5e7eb`. When checked: `#111827` fill with white checkmark glyph.
- Radio buttons: 16px circle, 1px solid `#e5e7eb`. When selected: `#111827` border with inner 6px `#111827` solid dot.

### Lists & Project Indexes
- Clean horizontal rows separated by 1px hairline `#e5e7eb` dividers.
- Flex layout with project title on the left and client, discipline, and year aligned cleanly to the right in `#6b7280`.
- Hover: Row highlights gently with a `#f8f9fa` background fill across full column width.