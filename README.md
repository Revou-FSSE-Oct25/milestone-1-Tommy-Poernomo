# Tommy Poernomo — Milestone 1

## Overview
This is a simple multi-page personal website built as part of RevoU FSSE Milestone 1. It showcases my profile, projects, and a way to contact me.

Pages included:
- Home (`index.html`) with a hero section and quick intro.
- About (`pages/about.html`) with bio, education, experience, and skills.
- Projects (`pages/projects.html`) listing sample projects with previews and links.
- Contact (`pages/contact.html`) with a message form.

Primary goals for this milestone were clean semantic HTML, organized CSS, basic accessibility, and simple navigation.

## Features Implemented
- **Semantic layout** using `header`, `main`, `section`, `article`, `nav`, `footer`.
- **Accessible navigation**
  - `aria-label` on navs and buttons.
  - `aria-current` on active menu items.
  - Descriptive `alt` and `figcaption` for images.
- **SEO basics** with `title` and meta `description`, `keywords`, and `author` per page.
- **Consistent styling** via a single stylesheet (`assets/css/style.css`).
- **Responsive-friendly base**
  - Fluid layout with flexbox and scalable typography.
  - Smooth scroll behavior (`html { scroll-behavior: smooth; }`).
- **Contact form** with labeled inputs, HTML5 validation (`required`, `type="email"`), and reset/submit buttons.
- **Internal section navigation** on Projects page (anchor links to sections).
- **Back to top** button on subpages using `window.scrollTo` with smooth behavior.
- **Static asset handling**: favicon, profile image, preview images, and external social icons.
- **Download CV** link from the navigation.

## Technologies Used
- **HTML5** for structure and semantics.
- **CSS3** for styling, layout (flexbox), and smooth scrolling.
- **Vanilla JavaScript (minimal)** for the Back-to-Top button on subpages.
- **Git & GitHub** for version control and project hosting.

---
If you want to preview locally, open `index.html` in your browser.