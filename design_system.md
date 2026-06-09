# Academic Cyberpunk Portfolio Design System

## Brand & Style
The brand personality is **"Academic Cyberpunk"**—a fusion of high-level engineering precision and futuristic urban energy. It targets technical recruiters, fellow developers, and visionary founders who value both rigorous logic and cutting-edge aesthetics.

The UI should evoke a sense of **"sophisticated rebellion"**, feeling like a high-end IDE or a secure terminal interface from the near future. The design style leans heavily into **Glassmorphism** and **Corporate-Futurism**, utilizing translucent layers, vibrant background blurs, and razor-sharp precision. Every element should feel intentional, functional, and technologically advanced.

---

## Colors
The palette is rooted in deep obsidian tones to provide maximum contrast for neon accents.

- **Backgrounds**: Use `#0a0a0a` (Deep Black) for the primary canvas and `#1a1a1a` (Dark Gray) for elevated surface containers.
- **Accents**: `#00d2ff` (Electric Blue) serves as the primary action color and focal point for terminal-like highlights. `#9d50bb` (Neon Purple) is used for secondary accents, data visualization, and depth-creating gradients.
- **Functional Colors**: Use Electric Blue for "Success/Active" states and a muted version of Neon Purple for "Warning/Pending" states.

### Named Colors Hex List
- **background**: `#131313`
- **surface**: `#131313`
- **surface_bright**: `#3a3939`
- **surface_container**: `#201f1f`
- **surface_container_high**: `#2a2a2a`
- **surface_container_highest**: `#353534`
- **surface_container_low**: `#1c1b1b`
- **surface_container_lowest**: `#0e0e0e`
- **surface_dim**: `#131313`
- **primary**: `#a5e7ff`
- **primary_container**: `#00d2ff`
- **secondary**: `#edb1ff`
- **secondary_container**: `#6e208c`
- **tertiary**: `#dfdcdb`
- **outline**: `#859399`
- **outline_variant**: `#3c494e`

---

## Typography
The typography system balances the technical rigor of **JetBrains Mono** for structural elements and headers with the high legibility of **Inter** for long-form content.

- **Headers**: All headlines use JetBrains Mono. Apply a `text-shadow` effect (`0 0 8px primary_color_hex`) to simulate a glowing CRT or holographic display.
- **Body**: Inter is used for all descriptive text to ensure the "academic" part of the persona remains readable and professional.
- **Labels**: Use JetBrains Mono in All Caps for small technical details, tags, and badges to reinforce the developer-centric aesthetic.

---

## Layout & Spacing
The layout follows a **Fixed Grid** model on desktop, centered to create a focused, dossier-like appearance.

- **Desktop**: 12-column grid with a 1200px max-width. Use 24px gutters.
- **Mobile**: Single column with 16px side margins.
- **Rhythm**: Use an 8px base unit. Spacing between major sections should be generous (stack-lg) to allow the background blurs and glass effects to "breathe" without visual clutter.
- **Transitions**: Implement staggered entrance animations for grid items to mimic a system loading sequence.

---

## Elevation & Depth
Depth is achieved through **Glassmorphism** and light-based hierarchy rather than traditional shadows.

- **Surface Tiers**: Background is the lowest level. Use a `backdrop-filter: blur(12px)` and `background: rgba(26, 26, 26, 0.7)` for elevated cards.
- **Borders**: Instead of heavy shadows, use 1px solid borders. For active or hovered elements, use a linear gradient border (Electric Blue to Neon Purple).
- **Glows**: Use low-opacity radial gradients (20% opacity) behind primary sections to create an atmospheric "screen glow" effect that sits behind the UI layers.

---

## Shapes
The shape language is **"Soft-Technical."** Elements use a consistent 0.25rem (4px) corner radius to feel precise and engineered, avoiding the playfulness of large rounds while steering clear of the harshness of sharp 0px corners.

- **Standard Elements**: 4px radius.
- **Large Containers**: 8px radius.
- **Badges/Chips**: 2px radius or sharp edges to emphasize a "microchip" or "tag" aesthetic.

---

## Components
- **Buttons**: Primary buttons use a solid Electric Blue background with black text. On hover, apply a `0 0 15px` glow effect. Secondary buttons use a "Ghost" style with a 1px Neon Purple border.
- **Glassmorphic Cards**: Apply `backdrop-filter: blur(16px)` with a very subtle white border at 10% opacity. Use these for project showcases.
- **Tech Badges**: Small, monochromatic tags using JetBrains Mono. Use a light Electric Blue background at 10% opacity with a solid 1px border.
- **Input Fields**: Dark background (`#0a0a0a`) with a subtle Electric Blue bottom border that expands to full width on focus.
- **Dynamic Timeline**: A vertical 1px line using a gradient from Electric Blue to Neon Purple. Milestones are represented by glowing 8px squares rather than circles.
- **Code Blocks**: High-contrast containers with `#1a1a1a` background and a "Terminal" header featuring three colored window controls (Red, Yellow, Green).
