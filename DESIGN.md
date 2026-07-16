---
name: Aura Portfolio System
colors:
  surface: '#f9f9f8'
  surface-dim: '#dadad9'
  surface-bright: '#f9f9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f3'
  surface-container: '#eeeeed'
  surface-container-high: '#e8e8e7'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#444748'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1f0'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1c1b1b'
  on-primary-container: '#858383'
  inverse-primary: '#c8c6c5'
  secondary: '#5d5e66'
  on-secondary: '#ffffff'
  secondary-container: '#e3e1ec'
  on-secondary-container: '#63646c'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1b1a'
  on-tertiary-container: '#868382'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1c1b1b'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#e3e1ec'
  secondary-fixed-dim: '#c6c5cf'
  on-secondary-fixed: '#1a1b22'
  on-secondary-fixed-variant: '#46464e'
  tertiary-fixed: '#e6e2df'
  tertiary-fixed-dim: '#cac6c4'
  on-tertiary-fixed: '#1c1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#f9f9f8'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display:
    fontFamily: Outfit
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Outfit
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Outfit
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Outfit
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
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-mobile: 20px
  section-gap-desktop: 160px
  section-gap-mobile: 80px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered for high-end developer portfolios, emphasizing technical precision through a lens of extreme minimalism. The brand personality is quiet, confident, and sophisticated, aiming to evoke a sense of calm authority and meticulous craftsmanship. 

The aesthetic style is **Minimalist with a High-Contrast Focus on Content**. It avoids unnecessary ornamentation, relying on perfect alignment, generous whitespace, and intentional typographic hierarchy to guide the viewer. The interface should feel like a premium digital gallery where the work—not the UI—is the protagonist.

## Colors

The palette is strictly low-contrast and monochromatic to ensure a "paper-like" tactile quality. 

- **Light Mode:** Uses a base of off-white (#F9F9F8) to reduce screen glare and mimic high-quality stationery. Borders and secondary text use soft grays to maintain a gentle visual flow.
- **Dark Mode:** Transitions to deep charcoals (#0F0F0F) rather than pure black to preserve detail in shadows and reduce eye strain.

Primary actions and headings use the strongest ink color (near-black in light mode, near-white in dark mode), while all auxiliary information is pushed back using muted shades.

## Typography

This design system utilizes a pairing of **Outfit** for expressive, geometric headings and **Inter** for highly legible, functional body text. 

- **Headings:** Set with tight letter-spacing and substantial line-height to create a structural, architectural feel. 
- **Body Text:** Uses a generous line-height (1.6) to maximize readability and reinforce the feeling of "open air" within the content blocks.
- **Labels:** Small caps or tracked-out labels are used for metadata (e.g., dates, categories) to differentiate technical data from narrative text.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to ensure line lengths remain optimal for reading. 

- **Grid:** A 12-column grid with wide gutters (24px). Elements should frequently "breath" by occupying only the center 8 columns or offsetting to create asymmetrical interest.
- **Rhythm:** Vertical spacing is aggressive. Large gaps between sections (160px) act as a visual reset, signaling the transition between different projects or life chapters.
- **Responsive:** On mobile, margins shrink to 20px, and the 12-column grid collapses into a single-column stack, prioritizing vertical flow and touch-friendly targets.

## Elevation & Depth

This design system avoids shadows entirely. Depth is communicated through **Low-Contrast Outlines** and **Tonal Layering**.

- **Layers:** Surface elevations are created by subtle shifts in background color (e.g., a slightly darker gray card on a lighter gray background).
- **Outlines:** Hairline borders (1px) are the primary tool for containment. They should be just visible enough to define a boundary without creating a "heavy" box.
- **Interaction:** Hover states should not use "lift" or shadows. Instead, use subtle background color shifts or border color transitions to indicate interactivity.

## Shapes

The shape language is strictly **Soft (0.25rem)**. This slight rounding takes the "edge" off the brutalist structure, making the UI feel more approachable and modern while maintaining a disciplined, professional grid. Large elements like project cards or hero images should use `rounded-lg` (0.5rem) to maintain visual proportion.

## Components

- **Buttons:** Minimalist bordered style. 1px solid border with the primary text color. No background fill unless it is the primary Call to Action. On hover, the background fills with the text color, and the text inverts.
- **Project Cards:** Flat, grid-aligned containers. No shadows. Use a hairline border or a subtle tonal shift for the background. Images within cards should be desaturated by default, regaining color on hover.
- **Tech Stack Chips:** Flat, unbordered chips using a slightly different shade than the card background. Typography is `label-sm`.
- **Input Fields:** Bottom-border only or very subtle 1px outlines. Focus states are indicated by a change in border color—never an outer glow.
- **Lists:** Clean vertical stacks with hairline dividers. Use `label-md` for list headers to maintain a disciplined, data-heavy look for experience sections.