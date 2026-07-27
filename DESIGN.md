---
name: Industrial Precision
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#514534'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#847562'
  outline-variant: '#d6c4ae'
  surface-tint: '#815500'
  primary: '#815500'
  on-primary: '#ffffff'
  primary-container: '#e69e1c'
  on-primary-container: '#593a00'
  inverse-primary: '#ffb94c'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#5c5f63'
  on-tertiary: '#ffffff'
  tertiary-container: '#aaacb1'
  on-tertiary-container: '#3d4044'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffddb2'
  primary-fixed-dim: '#ffb94c'
  on-primary-fixed: '#291800'
  on-primary-fixed-variant: '#624000'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1b1b1c'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e0e2e7'
  tertiary-fixed-dim: '#c4c6cb'
  on-tertiary-fixed: '#191c1f'
  on-tertiary-fixed-variant: '#44474b'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Hanken Grotesk
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 24px
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
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: '1.2'
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  max-width: 1280px
---

## Brand & Style

The design system is engineered for PT ANDALAN CAHAYA GEMILANG to project an image of technical mastery, industrial reliability, and corporate authority. It targets B2B stakeholders, project managers, and procurement officers in the electrical and engineering sectors.

The visual direction follows a **Corporate / Modern** style infused with **Brutalism-lite** elements—utilizing heavy borders, high-contrast intersections, and structural geometry. The aesthetic is inspired by electrical diagrams and architectural blueprints, where every line has a purpose and every element communicates strength. The interface should feel like a high-performance tool: efficient, uncompromising, and highly structured.

## Colors

The palette is anchored by "Industrial Amber," a high-visibility orange that signifies energy and safety. This is paired with "Deep Charcoal" for a grounded, authoritative feel.

- **Primary (Industrial Amber):** Used for calls to action, highlights, and critical technical data. It evokes the glow of power and machinery.
- **Secondary (Deep Charcoal):** The foundation for text and structural elements, providing a stark contrast that ensures legibility.
- **Surface Tints:** A range of cool grays are used to differentiate technical specifications and background sections without introducing unnecessary color.
- **Semantic Colors:** Standardized success (green) and error (red) colors should be slightly desaturated to maintain the professional, industrial tone.

## Typography

The typography system uses a tri-font approach to balance impact, readability, and technical character.

- **Hanken Grotesk** is the primary display face. Its sharp, contemporary geometry mirrors industrial precision. Use it in Bold or ExtraBold for all headings to create a sense of scale and power.
- **Inter** provides a highly legible, neutral foundation for all body copy and long-form technical descriptions.
- **JetBrains Mono** is used sparingly for labels, tags, and technical specs (voltage, dimensions, part numbers). The monospaced nature reinforces the engineering and "data-driven" aesthetic of the company.

## Layout & Spacing

This design system utilizes a **Fixed Grid** philosophy for desktop to maintain a controlled, editorial feel, transitioning to a fluid model for smaller devices.

- **Grid:** A 12-column grid system is used for desktop (1280px max-width). Elements should align strictly to these columns to evoke architectural order.
- **Rhythm:** An 8px base unit governs all padding and margins. Vertical spacing should be generous between sections (80px - 120px) to allow the heavy photography and bold type to breathe.
- **Technical Accents:** Use "geometric intersections" where background color blocks or borders meet at sharp 90-degree angles, echoing the interlocking patterns found in the reference images.

## Elevation & Depth

To maintain a professional and "hard" industrial feel, this design system avoids soft shadows and organic depth. 

- **Tonal Layering:** Hierarchy is achieved through color blocking. Primary surfaces are White or Light Gray (#F5F5F5), while "Technical Containers" use Charcoal (#1E1E1E) or Deep Orange (#E69E1C).
- **Hard Borders:** Use 1px or 2px solid borders in Charcoal or Orange to define card boundaries and input fields.
- **Zero Elevation:** Do not use box-shadows. If an element needs to feel elevated, use a high-contrast offset border (a "hard shadow") or a simple color shift.
- **Background Watermarks:** Large-scale, low-opacity geometric patterns (based on the company logo or circuit patterns) can be used to add depth to large white spaces.

## Shapes

The shape language is strictly **Sharp (0)**. In the context of engineering and electrical infrastructure, right angles represent stability and structural integrity. 

- **Square Edges:** All buttons, cards, images, and input fields must have 0px border-radius.
- **Angled Cuts:** For decorative elements or specialized buttons, use 45-degree chamfered corners (clipped corners) to mimic the industrial aesthetics of heavy machinery and metal casing.
- **Circular Accents:** Use perfect circles exclusively for "status" indicators or specific image masking (as seen in the reference material) to provide a single, intentional point of visual contrast against the otherwise rectangular grid.

## Components

- **Buttons:** High-contrast blocks with no rounded corners. Primary buttons are Industrial Amber with Deep Charcoal text. Hover states should involve a simple color inversion or a thick black border offset.
- **Input Fields:** 2px solid Charcoal borders. Labels should use JetBrains Mono in all-caps for a "spec-sheet" feel.
- **Cards:** Defined by a 1px Charcoal border. Headers within cards should have an Amber top-border (3px) to signify active status or importance.
- **Chips/Labels:** Use the monospaced font. They should look like physical industrial tags or serial number plates—rectangular with high-contrast backgrounds.
- **Data Visualizations:** Graphs and charts should use strict linear paths (no smoothing) and the primary Amber/Charcoal palette to reinforce technical accuracy.
- **Process Indicators:** Use "circuit-style" connectors—thin lines with circular nodes—to visually link steps in a service process or project timeline.