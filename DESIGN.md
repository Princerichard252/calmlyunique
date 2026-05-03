---
name: Ethereal Bloom
colors:
  surface: '#f9f9fb'
  surface-dim: '#d9dadc'
  surface-bright: '#f9f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f5'
  surface-container: '#eeeef0'
  surface-container-high: '#e8e8ea'
  surface-container-highest: '#e2e2e4'
  on-surface: '#1a1c1d'
  on-surface-variant: '#574146'
  inverse-surface: '#2f3132'
  inverse-on-surface: '#f0f0f2'
  outline: '#8a7176'
  outline-variant: '#ddbfc5'
  surface-tint: '#ab2c5d'
  primary: '#ab2c5d'
  on-primary: '#ffffff'
  primary-container: '#f06292'
  on-primary-container: '#5e002b'
  inverse-primary: '#ffb1c5'
  secondary: '#6b5a60'
  on-secondary: '#ffffff'
  secondary-container: '#f4dce4'
  on-secondary-container: '#716066'
  tertiary: '#735c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cba72f'
  on-tertiary-container: '#4e3d00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9e1'
  primary-fixed-dim: '#ffb1c5'
  on-primary-fixed: '#3f001b'
  on-primary-fixed-variant: '#8b0e45'
  secondary-fixed: '#f4dce4'
  secondary-fixed-dim: '#d7c1c8'
  on-secondary-fixed: '#25181e'
  on-secondary-fixed-variant: '#524249'
  tertiary-fixed: '#ffe088'
  tertiary-fixed-dim: '#e9c349'
  on-tertiary-fixed: '#241a00'
  on-tertiary-fixed-variant: '#574500'
  background: '#f9f9fb'
  on-background: '#1a1c1d'
  surface-variant: '#e2e2e4'
typography:
  h1:
    fontFamily: Noto Serif
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Noto Serif
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Noto Serif
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Plus Jakarta Sans
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
  container-max: 1200px
  gutter: 24px
---

## Brand & Style

The design system is centered on the concept of "Digital Sanctuary"—a space where Web3 community building feels intimate, safe, and premium. The brand personality is feminine, nurturing, and sophisticated, leaning into an anime-inspired aesthetic that prioritizes atmospheric depth over flat utility.

The design style is a hybrid of **Glassmorphism** and **Minimalism**. It utilizes high-transparency layers, soft-focus background blurs, and luminous gradients to create an interface that feels lightweight yet high-end. Visual elements should evoke the feeling of a "magical girl" transformation or a serene sunset, using glowing edges and subtle light leaks to guide the user's attention.

## Colors

The palette is anchored by a vibrant yet soft Coral (#F06292) and a delicate Blush Pink (#FCE4EC). These are complemented by a Metallic Gold (#D4AF37) used sparingly for high-value accents, such as premium badges or active states.

In **Light Mode**, the interface utilizes an off-white base to reduce eye strain, with soft pink overlays providing structural depth. 
In **Dark Mode**, the background shifts to a Deep Charcoal (#1A1A1D) to allow the coral and pink accents to "glow" against the darkness, mimicking a neon-noir anime aesthetic. Gradients should always flow from the primary coral to the secondary pink, eventually fading into the background white or charcoal.

## Typography

The typographic scale creates a tension between the traditional elegance of **Noto Serif** and the contemporary, friendly geometry of **Plus Jakarta Sans**. 

Headlines use Noto Serif to establish a premium, editorial feel. They should be treated with generous top margins to allow the "elegant" character of the serif to breathe. Body copy and UI labels use Plus Jakarta Sans for maximum legibility in high-density community dashboards. For buttons and navigation items, use a medium weight of the body font to maintain a soft but clear presence.

## Layout & Spacing

This design system employs a **Fixed Grid** model for desktop (12 columns) and a **Fluid Grid** for mobile. The spacing rhythm is based on an 8px square grid, but emphasizes large, "airy" margins (48px+) to prevent the UI from feeling cluttered—essential for a "calm" user experience.

Content blocks should be grouped within wide containers with significant padding. Use negative space as a functional element to separate community discussions from navigation, ensuring that the interface feels expansive and unhurried.

## Elevation & Depth

Depth is communicated through **Glassmorphism** and **Ambient Shadows**. Surfaces do not sit on top of the background; they float within it. 

1.  **Primary Surfaces:** Use a 60% opacity white (or 40% charcoal in dark mode) with a 20px background blur (backdrop-filter). 
2.  **Shadows:** Shadows are highly diffused (30px-50px blur) and tinted with the primary coral color at 5-10% opacity, creating a "halo" effect rather than a traditional drop shadow.
3.  **Active States:** Elements being interacted with should gain a 1px inner border in Gold or soft Pink to simulate a delicate light-catch on the edge of glass.

## Shapes

The shape language is consistently **Rounded**. Sharp corners are avoided to maintain the "calm and feminine" narrative. Standard buttons and input fields use a 0.5rem radius, while larger cards and modal containers use 1.5rem (rounded-xl). 

Avatars and specific community "tokens" should be perfectly circular to contrast against the softened rectangular containers of the main UI.

## Components

*   **Buttons:** Primary buttons feature a soft gradient transition from Coral to Pink. They should have a subtle outer glow on hover. Text is always white or high-contrast off-white.
*   **Cards:** Cards are the primary container. They must utilize background blur and a very thin (0.5px) light-pink border to define their edges against the background.
*   **Chips & Tags:** Small, pill-shaped elements with a secondary pink background and primary coral text. These represent community roles or interests.
*   **Inputs:** Minimalist fields with only a bottom border that transitions into a Coral-to-Gold gradient line when focused.
*   **Glow Orbs:** Decorative, non-functional blurred circles of color placed behind key content sections to enhance the anime-inspired atmospheric feel.
*   **Community Milestones:** A custom component using the Gold accent color, featuring a serif heading and a subtle sparkle icon, used to celebrate community growth.