---
name: Velocity Peak
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
  on-surface-variant: '#454653'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#767684'
  outline-variant: '#c6c5d5'
  surface-tint: '#4853bd'
  primary: '#00044b'
  on-primary: '#ffffff'
  primary-container: '#000c85'
  on-primary-container: '#7884f0'
  inverse-primary: '#bdc2ff'
  secondary: '#ba0034'
  on-secondary: '#ffffff'
  secondary-container: '#e41846'
  on-secondary-container: '#fffbff'
  tertiary: '#745b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#d0a600'
  on-tertiary-container: '#4f3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dfe0ff'
  primary-fixed-dim: '#bdc2ff'
  on-primary-fixed: '#000767'
  on-primary-fixed-variant: '#2e39a4'
  secondary-fixed: '#ffdada'
  secondary-fixed-dim: '#ffb3b5'
  on-secondary-fixed: '#40000c'
  on-secondary-fixed-variant: '#920026'
  tertiary-fixed: '#ffe08b'
  tertiary-fixed-dim: '#f1c100'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#584400'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-xl:
    fontFamily: Anybody
    fontSize: 80px
    fontWeight: '800'
    lineHeight: 88px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Anybody
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Anybody
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Anybody
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 38px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-bold:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 16px
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 14px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style

This design system is engineered to capture the high-octane energy of extreme sports and premium lifestyle performance. The brand personality is **exhilarating, precise, and uncompromising**. It targets an audience that values movement, achievement, and the thrill of the "edge."

The visual style is a fusion of **Corporate Modern** and **High-Contrast Bold**. It utilizes vast amounts of whitespace to signify a premium, high-end product, while aggressive typography and a vibrant color palette ensure the "energy" of the brand is never lost. The interface should feel like a high-precision cockpit—utilitarian but visually striking. Expect sharp transitions, intense color blocks, and a sense of "dynamic tension" created through large-scale type and minimal decorative elements.

## Colors

The palette is derived directly from the iconic silver and blue racing livery, punctuated by high-visibility red and yellow.

- **Primary (Racing Blue):** A deep, saturated blue used for structural elements, headers, and primary brand touchpoints.
- **Secondary (Performance Red):** An aggressive red reserved for high-action items, urgent CTAs, and vital status indicators.
- **Tertiary (Voltage Yellow):** A bright yellow used sparingly for accentuation, highlights, and secondary interactive states to draw the eye without overwhelming the layout.
- **Neutral (Aero Silver):** A range of cool grays and silvers that provide the "clean" backdrop necessary to make the primary colors pop.

The default mode is **Light**, utilizing white and light silver backgrounds to maintain a fresh, breathable aesthetic, though dark containers are used to highlight featured "premium" content.

## Typography

The type system is built for impact and legibility. **Anybody** is the chosen display face; its variable-width nature allows for an industrial, almost technical feel that mimics high-speed telemetry. Use it in ExtraBold for headlines to command attention.

For body copy and functional elements, **Hanken Grotesk** provides a sharp, contemporary sans-serif experience that remains readable even at high densities. 

**Application Rules:**
- Use **all-caps** for labels and buttons to reinforce the assertive tone.
- Maintain tight line-heights for headlines to create a "dense" and powerful visual block.
- Increase letter spacing slightly for labels in all-caps to improve scannability.

## Layout & Spacing

This design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy is centered on "extreme margins"—using significant whitespace at the edges of the screen to drive the user's focus toward the center content, creating a premium editorial feel.

**Spacing Rhythm:**
- A base **8px scale** governs all padding and margins.
- **Section Spacing:** Use large vertical gaps (80px - 120px) between major content blocks to prevent the interface from feeling "cluttered."
- **Component Padding:** Maintain generous internal padding within cards and containers to ensure the "clean" brand promise is met.

## Elevation & Depth

To maintain a clean and modern aesthetic, depth is achieved through **Tonal Layering** and **Low-Contrast Outlines** rather than heavy shadows.

- **Surface Levels:** The base layer is white (#FFFFFF). Elevated containers use a very light silver (#F4F4F4). 
- **Borders:** Instead of shadows, use 1px solid borders in a light gray (#E0E0E0) for cards and inputs.
- **Interaction Depth:** For primary buttons and active states, use a subtle 4px "hard shadow" in Primary Blue to create a tactile, punchy feel that aligns with the "bold" brand personality.
- **Depth through Color:** Background color shifts (e.g., a Blue section following a White section) are used to denote hierarchy and content transitions.

## Shapes

The shape language is **Sharp**. This design system avoids rounded corners to project a feeling of precision, speed, and technical excellence. 

Every element—from buttons and input fields to large image containers—uses a **0px corner radius**. This creates a rigid, grid-locked appearance that feels intentional and aggressive. This sharp geometry is balanced by the fluid, organic shapes found in photography (e.g., liquid splashes, athletes in motion) to create visual contrast.

## Components

**Buttons**
Buttons are strictly rectangular with no roundedness. 
- **Primary:** Background in Performance Red, text in White (All Caps).
- **Secondary:** Background in Racing Blue, text in White (All Caps).
- **Outline:** 2px border in Racing Blue, no background, text in Blue.

**Input Fields**
Fields are defined by a 1px bottom border only, creating a sleek, minimal look. On focus, the border transitions to a 2px Racing Blue line.

**Cards**
Cards use a white background with a thin #E0E0E0 border. They should never have shadows unless they are in a "hovered" state, at which point a 4px hard blue shadow is applied.

**Chips / Tags**
Used for categorizing content (e.g., "F1", "MTB", "Esports"). These are Racing Blue with White text, using the `label-bold` type style.

**Data Indicators**
Small, high-contrast badges using Voltage Yellow for real-time stats or "Live" indicators, ensuring they are the most visible element on the page.