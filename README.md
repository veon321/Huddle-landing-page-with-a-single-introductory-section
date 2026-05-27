# Frontend Mentor - Huddle landing page with single introductory section solution

This is a clean, responsive, and modern solution to the Huddle landing page with single introductory section challenge on Frontend Mentor.

## Links

- **Solution URL:** [https://github.com/veon321/Huddle-landing-page](https://github.com/veon321/Huddle-landing-page)
- **Live Site URL:** [https://veon321.github.io/Huddle-landing-page/](https://veon321.github.io/Huddle-landing-page/)

## Built with

- **Semantic HTML5 markup** (including isolated top-level `<header>`, `<main>` content wrapper, and precise structural `<footer>` block)
- **CSS Custom Properties (Variables)** for strict adherence to the design system's thematic color scheme and typography metrics
- **Flexbox layout** for multidirectional alignment (asymmetric desktop row distributions and responsive, centralized vertical column collapsing)
- **Modern CSS Math Functions (`clamp()`)** for fluid logo scaling, completely adaptive component sizing, and dynamic viewport typography
- **Google Fonts** (Poppins & Open Sans)

## Features

- **Fluid Horizontal-to-Vertical Split Flow:** Achieves a highly modular multi-column presentation across desktop viewports using pure Flexbox alignment. The core asset wrapper balances the product illustration against the informational textual stack via an asymmetrical flex distribution layout.
- **Advanced Asset Layering:** Implements viewport-adaptive vector background logic by applying fluid layout scaling rules. The design automatically switches illustration profiles across structural media query pivot points without disrupting interactive DOM element stacking.
- **Dynamic Asset Filtering & Smooth States:** Solves SVG monochrome rendering challenges by applying standard procedural color inversion matrix equations (`filter: invert()`) inside isolated icon anchor structures, ensuring precise state changes during standard hover interactions.
- **Fluid Proportional Spacing:** Eliminates rigid, hardcoded breakpoint snap-points by nesting flexible typography rules directly within global elements, guaranteeing clean layout text flow and proportionate content distribution across standard mobile and high-end desktop viewports.
- **Viewport Protection Logic:** Enforces a structural `min-height: 100vh` constraint on the main root component, combined with strict mobile layout shifts (`align-items: flex-start`), ensuring content blocks remain balanced on desktops while allowing standard scrolling and preventing top-overflow on compact layouts.
