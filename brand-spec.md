# Brand Spec — Tatá Bracho 7720

## Color Tokens (OKLch derived from HEX)

| Token | HEX | OKLch | Usage |
|-------|-----|-------|-------|
| --bg-deep | #011555 | oklch(18% 0.12 260) | Deep navy base, primary backgrounds |
| --bg-navy | #021E70 | oklch(22% 0.15 260) | Structural areas, cards |
| --bg-royal | #012EA0 | oklch(32% 0.18 260) | Gradients, transitions |
| --accent-vibrant | #0443CA | oklch(42% 0.22 260) | Buttons, CTAs, highlights |
| --accent-electric | #1880EE | oklch(58% 0.20 255) | High-energy elements, links, numbers |
| --fg-light | #EFEFF3 | oklch(94% 0.01 250) | Primary text on dark, light surfaces |

## Gradient Definitions

```css
--gradient-primary: linear-gradient(135deg, #011555 0%, #021E70 40%, #012EA0 70%, #0443CA 100%);
--gradient-hero: radial-gradient(ellipse 80% 60% at 50% 20%, #012EA0 0%, #021E70 40%, #011555 100%);
--gradient-card: linear-gradient(145deg, rgba(2,30,112,0.9) 0%, rgba(1,21,85,0.95) 100%);
--gradient-accent: linear-gradient(90deg, #0443CA 0%, #1880EE 100%);
```

## Typography

- **Display/Headlines**: System UI stack, weight 700-800, tracking-tight (-0.02em)
- **Body**: System UI stack, weight 400-500, line-height 1.6
- **UI/Caption**: System UI stack, weight 500, uppercase, letter-spacing 0.08em

## Layout Posture Rules

1. **Depth through layers**: Multiple gradient backgrounds, translucent overlays (rgba with 0.1-0.3 opacity), subtle border glows
2. **Fluid organic shapes**: SVG waves, curved dividers, floating orbs with blur filters
3. **Accent budget**: Electric blue (#1880EE) used sparingly — primary CTA, number 7720, key highlights only
4. **No warm colors**: Strictly blue/white palette — no orange, yellow, red, green
5. **Mobile-first responsive**: 360px → 1920px with fluid clamp() scaling
6. **Electoral compliance footer**: Fixed pattern on every page