# capstone-Himanshi-Yadav-lab5

# Wanderlust — Responsive Travel Agency Website

## 1. Project Title & Theme
- **Project Title:** Wanderlust — Indian Mountain Escapes & Coastal Getaways
- **Theme:** Travel Agency Website (Web Development I — Lab Assignment 5 Capstone)
- **Team:** 4-Member Student Project
- **Tech Stack:** HTML5 & CSS3 (Flexbox, CSS Grid, CSS custom properties, keyframe animations, and media queries)

## 2. Short Description of Sections Implemented
- **Header & Navigation (`<header>`, `<nav>`):** Brand logo and name (`Wanderlust`), skip-to-main-content link, internal navigation links, and a `Plan a Trip` call-to-action button that scrolls away naturally when scrolling down.
- **Cursor-Panning Poster Hero (`<section>`):** Full-bleed Himalayan mountain hero with cursor-responsive panning, twilight slate scrim overlay, display typography, trip CTA button, and editorial caption.
- **Popular Destinations (`<section>`, `<article>`):** Four destination cards highlighting Indian mountain spots (Spiti Valley, Kasol & Parvati Valley, Manali & Solang Ridge) alongside a beach escape (South Goa & Gokarna).
- **Signature Tour Packages (`<section>`, `<article>`):** Three tour package cards (`Spiti & High-Pass Expedition`, `Manali & Kasol Pine Retreat`, and `Goa & Gokarna Cove Escape`) with duration pills, ratings, pricing, included perks, and booking links.
- **Traveler Photo Board (`<section>`, `<figure>`):** Multi-photo gallery grid featuring mountain ridges, pine forests, and coastal views with captions.
- **Sample Itinerary & Traveler Essentials (`<section>`, `<aside>`):** Four-day Manali & Solang itinerary timeline paired with a traveler essentials sidebar.
- **Traveler Reviews (`<section>`, `<article>`):** Three explorer testimonial cards with star ratings, quotes, and portraits.
- **Trip Inquiry Form (`<section>`, `<form>`):** Accessible inquiry form with `<label>` elements, required fields, placeholders, destination selector, travel month input, and notes textarea.
- **Footer (`<footer>`):** Brand summary, navigation links, contact details, and copyright notice.

## 3. Breakpoints Used & Main Layout Techniques
- **Layout Techniques:**
  - **CSS Flexbox:** Used for the header bar, navigation list, hero CTA group, itinerary timeline rows, and package card alignment.
  - **CSS Grid:** Used for the 4-column destination grid, 3-column package and review grids, photo board, itinerary + aside layout, inquiry form layout, and footer grid.
  - **CSS Variables & Relative Units:** Defined `:root` custom properties for the twilight slate-blue and pine-dusk color palette, typography, spacing, border radii, shadows, and `0.25s ease` transitions using `rem`, `%`, `vh`, and `vw` units.
  - **Animation:** Includes a `@keyframes` entrance animation on the hero stage and subtle hover transitions across cards and buttons.
- **Responsive Breakpoints:**
  - **Desktop (`> 1024px`):** Multi-column grids and horizontal navigation bar.
  - **Tablet (`≤ 1024px`):** Two-column card/photo grids and stacked itinerary and inquiry sections.
  - **Mobile & Small Screens (`≤ 768px` and `≤ 480px`):** Single-column grids (`1fr`), stacked header navigation, and adjusted spacing/font sizing.

## 4. To Open (Local) & GitHub Pages
- **Run Locally:**
  1. Clone or download the repository folder `capstone--Rudraksh-Soni-lab5`.
  2. Open `index.html` directly in a web browser or run it via a local development server (such as VS Code Live Server).
- **GitHub Pages (Optional):**
  - **Repository:** https://github.com/himanshiyadav2409-sys/capstone-Himanshi-Yadav-lab5
  - **Live Website:** https://himanshiyadav2409-sys.github.io/capstone-Himanshi-Yadav-lab5/
