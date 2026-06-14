# 🌐 Advanced Semantic Portfolio Website

A modern, multi-page personal portfolio website built strictly adhering to **HTML5 semantic standards** and **WCAG (Web Content Accessibility Guidelines)**. The primary objective of this project is to achieve a perfect 100/100 score on Lighthouse Accessibility and SEO audits, showcasing a production-ready, highly inclusive web experience.

---

## 🚀 Project Objectives & Scope

- **Structural Integrity:** Eliminate generic `div` soup in favor of descriptive HTML5 markup.
- **Universal Accessibility:** Ensure seamless navigation for assistive technologies (screen readers) and keyboard-only users.
- **Search Engine Optimization:** Maximize content discoverability using logical heading hierarchies and optimized meta tags.
- **Responsive Fluidity:** Deliver a pixel-perfect user interface that adapts flawlessly across mobile, tablet, and desktop devices.

---

## ✨ Key Features

### 1. Semantic HTML5 Architecture
The layout uses explicit structural elements to help search engines and browsers parse the content effortlessly:
- `<header>` and `<nav>` for centralized site navigation.
- `<main>` to isolate the unique core content of each page.
- `<section>` and `<article>` for independent component blocks like hero sections and project cards.
- `<footer>` for localized legal, copyright, and social references.

### 2. Advanced Accessibility (WCAG Compliant)
- **Skip Navigation:** An accessible `Skip to main content` routing link bypasses repetitive header menus for keyboard-only users.
- **Interactive Focus States:** Custom high-visibility CSS focus indicators (`*:focus-visible`) ensure a clear visual anchor during tab navigation.
- **Screen Reader Enhancements:** Integrated descriptive `aria-*` attributes (e.g., `aria-current="page"`, `aria-describedby`) and meaningful `alt` text for all graphical assets.
- **Accessible Contact Form:** Fully tab-navigable input fields explicitly mapped to their respective `<label>` elements using the `for` attribute.

### 3. Modern Responsive UI & Theming
- **Mobile-First CSS Architecture:** Fluid layouts that scale elegantly from small smartphone screens to ultra-wide desktop monitors using responsive media queries.
- **CSS Grid & Flexbox:** Utilizing advanced 2D Grid layouts for project display configurations and Flexbox for localized component alignment.
- **Dynamic System Themes:** Integrated native Light/Dark mode switching that dynamically adapts based on system-level user preferences while maintaining strict WCAG color contrast safety scores.

---

## 📂 Repository Structure

```text
Portfolio website/
│
├── index.html          # Main landing layout with custom hero units
├── about.html          # Bio configuration & interactive skill matrices
├── projects.html       # Complex grid showcasing web applications
├── contact.html        # WCAG-compliant accessible communication form
│
├── css/
│   └── style.css       # Centralized stylesheet containing advanced architectures
│
└── assets/
    └── profile.jpg     # Professional optimized media assets
