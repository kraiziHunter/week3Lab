# Week 3 — CSS Basics Practice

**Student:** Alym Abylkasymov  
**Course:** Web & Internet Technologies  
**Week:** 3  
**Live Demo:** [GitHub Pages / Netlify URL will be placed here upon repository push]

---

## Structure
- `index.html` — Portfolio home page featuring the complete directory of exercises and author information.
- `css/styles.css` — Global external stylesheet with custom properties, media queries, accessibility rules, and demo styles.
- `/beginner/`
  - `ex1.html` — Typography & Text Styling
  - `ex2.html` — CSS Box Model & Sizing
  - `ex3.html` — CSS Selectors & Specificity
  - `ex4.html` — Colors, Gradients & Backgrounds
  - `ex5.html` — Buttons & Interactive Links
- `/intermediate/`
  - `ex6.html` — Flexbox Navigation Bar
  - `ex7.html` — Responsive Pricing Cards
  - `ex8.html` — CSS Positioning & Badges
  - `ex9.html` — Accessible Form Controls
  - `ex10.html` — Transitions & Micro-interactions
- `/challenging/`
  - `ex11.html` — CSS Grid Portfolio Gallery
  - `ex12.html` — Holy Grail Layout (CSS Grid)
  - `ex13.html` — Responsive Dashboard Grid
  - `ex14.html` — Pure CSS Interactive Accordion
  - `ex15.html` — Theme System & Dark Mode

---

## Notes
- **Semantic HTML5:** Built strictly with semantic landmarks (`<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`).
- **External CSS:** 100% external styling contained entirely in `css/styles.css` with zero inline styles.
- **Accessibility (a11y):** Implements skip links (`.skip-link`), `:focus-visible` keyboard rings, semantic hierarchy (`h1` &rarr; `h2` &rarr; `h3`), and WCAG AA contrast standards.
- **Dark Mode Support:** Fully automated dark theme via `@media (prefers-color-scheme: dark)` using modern CSS variables.
- **Responsive Testing:** Verified across 320px, 375px (mobile), 768px (tablet), and 1280px+ (desktop).

---

## How to View
1. Open `index.html` directly in any modern web browser (Google Chrome, Mozilla Firefox, Edge, Safari).
2. Alternatively, serve via live server:
   ```bash
   npx serve .
   ```
3. Navigate between exercises using the category cards or top navigation bar.
