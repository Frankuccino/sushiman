# Sushiman — Modular Vanilla HTML, CSS & JavaScript Project

Sushiman is a frontend project focused on building a clean, maintainable, and scalable user interface using **vanilla HTML5, CSS3, and JavaScript**.  
The project emphasizes professional file organization, clear separation of concerns, and modular styling without relying on frameworks.

Rather than treating HTML, CSS, and JavaScript as a single monolithic layer, this project intentionally separates responsibilities across semantic HTML sections and section-specific CSS files, all composed through a central stylesheet.

---

## Project Goals

Many beginner projects suffer from:

- Poor file organization
- Unclear naming conventions
- Repetitive (WET) CSS and markup
- Difficult-to-maintain stylesheets that grow unstructured over time

This project addresses those issues by demonstrating:

- A responsibility-based CSS architecture
- Consistent and predictable class naming
- Reusable styles and variables
- A structure designed to scale as the project grows

---

## Styling Architecture

The CSS is organized by **section responsibility**, not by page size or feature count.

Each major HTML section has its own stylesheet (e.g. `header.css`, `hero.css`, `footer.css`), which keeps styles localized and easy to reason about.  
All section styles are imported into a single `style.css` file, which serves as the main entry point for styling.

This approach:

- Reduces coupling between unrelated sections
- Improves maintainability
- Mirrors component-based styling used in modern frameworks while remaining framework-agnostic

The project also follows:

- **BEM (Block–Element–Modifier)** naming conventions
- CSS root variables for theming and consistency
- Utility classes for reuse and layout consistency

---

## Responsiveness

The layout is fully responsive and designed to work across:

- Mobile devices
- Tablets
- Desktop screens

Responsiveness is handled through flexible layouts and media queries rather than device-specific hacks.

---

## Tech Stack

- HTML5 (semantic structure)
- CSS3 (modular architecture, BEM, variables)
- JavaScript (lightweight interactivity)

---

## Future Improvements

- Improve accessibility through semantic refinements and ARIA attributes
- Add a build step for CSS optimization as the project grows
- Migrate sections into reusable components if the project evolves into a larger application
