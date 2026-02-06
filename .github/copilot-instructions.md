# Copilot Instructions for Ank Agrawal Portfolio

## Project Context
This is a single-page professional portfolio for Ank Agrawal, an Actuarial Practice and AI/Risk Analysis specialist. The project is built using a "Premium Glassmorphism" aesthetic and depends on Materialize CSS and FontAwesome.

## Tech Stack
- **Frontend**: HTML5, Materialize CSS (Framework), FontAwesome 6, Material Icons.
- **Animations**: Typed.js for dynamic hero text.
- **Deployment**: GitHub Pages (User Site: `ank-actuary.github.io`).

## Architecture & Conventions
- **Single Page Structure**: The entire site lives in `index.html`. Do not split into multiple pages unless requested.
- **Glassmorphism Aesthetic**: Use `.glass-card` for content sections. Maintain low-opacity backgrounds (`rgba(255, 255, 255, 0.03)`), backdrop blurs, and light-blue accent glows (`--accent-glow: #00d2ff`).
- **Responsive Navigation**:
    - **Desktop**: Inline list in `<nav>`.
    - **Mobile**: Uses Materialize Sidenav (`#mobile-nav`). Any new navigation links must be updated in both places.
- **Asset Management**: 
    - Images must be placed in `img/`.
    - Reference the high-resolution profile `img/ank.jpeg` and university logo `img/university.png`.
- **Resume Integration**: Embedded via `<iframe>` with `#toolbar=0` in the `src` to provide a clean, integrated PDF viewing experience.

## Critical Workflows
- **GitHub Authentication**: Use SSH key for authentication when pushing to GitHub.
- **Deployment**: Pushing to `main` branch triggers an automatic build/deploy on GitHub Pages.
- **Rebranding History**: The project was transitioned from a "Shubham" template. Avoid any logic relating to sorting visualizers or original audio clips as they have been sanitized.

## Messaging Strategy
- Focus on **Actuarial Rigor** and **AI Intelligence**.
- Use "Strategic Vision" over "About Me".
- Highlight **IFoA** progress (CS1, CS2, CM1, etc.) in the Education section.
- Keywords (Risk Analysis, Actuarial Practice) should be visible in the header and hero sections on both mobile and desktop.
