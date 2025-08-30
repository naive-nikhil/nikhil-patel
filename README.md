# Project File Structure & Customizations

### Layout
- `layout/blank.liquid` – Used because `theme.liquid` included **Header, Newsletter Subscription, and Footer** (not present in the Figma design).

### Templates
- `templates/index.json` – Not newly created, but **layout and section order modified** according to the design.

### Sections
- `sections/navbar.liquid` – Navbar section (customizable from Shopify panel).
- `sections/hero.liquid` – Hero section (customizable from Shopify panel).
- `sections/grid.liquid` – Grid section (displays products dynamically in a grid).

### Assets
- `assets/main.css` – Global styling.
- `assets/section-navbar.css` – Navbar styling.
- `assets/section-hero.css` – Hero styling.
- `assets/section-grid.css` – Grid styling.

### Snippets
- `snippets/custom-button.liquid` – Reusable button (removes duplicacy across sections).

### Media
- **Images & Icons** – Added according to Figma design.