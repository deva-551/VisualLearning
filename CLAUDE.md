# Visual Learning Hub — Project Rules

## Responsive Design (MANDATORY)

Every page and component in this application MUST be fully responsive and adaptive across all screen sizes:

- **Mobile phones** (320px–480px): Single-column layouts, touch-friendly tap targets (min 44px), readable font sizes (min 14px body text), no horizontal scrolling
- **Tablets** (481px–768px): Adapted grid layouts (2-column where appropriate), properly scaled visuals and canvases
- **Laptops** (769px–1024px): Full layouts with appropriate spacing
- **Desktops** (1025px+): Max-width containers, centered content, comfortable reading widths

### Rules
- All new pages and modifications MUST include responsive CSS with media queries for at least mobile (<768px) and small mobile (<480px) breakpoints
- Use `clamp()`, `min()`, `max()` for fluid typography and spacing — avoid fixed pixel sizes for fonts
- Use relative units (%, vw, vh, rem) over fixed px where possible
- All interactive elements (buttons, cards, inputs) must be easily tappable on mobile (minimum 44x44px touch target)
- Canvases and SVGs must scale or adapt to container width — never overflow the viewport
- Flexbox layouts must use `flex-wrap: wrap` or switch to `flex-direction: column` on narrow screens
- Grids must use `auto-fill`/`auto-fit` or reduce column count via media queries
- Test every change visually at 375px (iPhone SE), 768px (iPad), and 1440px (desktop) widths
- No horizontal scrolling on any screen size — ever
- Modals/overlays must be usable on mobile with proper padding and scroll behavior
