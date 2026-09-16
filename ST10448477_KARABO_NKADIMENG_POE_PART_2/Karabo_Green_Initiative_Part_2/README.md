# Karabo Green Initiative — POE Part 2

## Part 2: Designing the Visuals — CSS Styling and Responsive Design

This repository contains the updated Karabo Green Initiative website from Part 1, enhanced for Part 2 with an external CSS stylesheet, desktop layout, responsive breakpoints, responsive images, accessibility-focused interaction states, and documentation.

## Pages
- `index.html` — Home
- `about.html` — About Us
- `services.html` — Our Programmes
- `enquiry.html` — Get Involved
- `contact.html` — Contact
- `style.css` — External stylesheet
- `images/` — Website images and responsive image variants

## CSS and Responsive Design
The website uses one shared external stylesheet (`style.css`) linked to all HTML pages.

### Base styling
- Consistent font family, typography scale, colours, spacing and box sizing.
- CSS custom properties (`:root`) keep colours, spacing and layout values consistent.
- Images use `max-width: 100%` and `height: auto` for flexible sizing.

### Layout
- Flexbox is used for the header and navigation.
- CSS Grid is used for multi-column content sections on larger screens.
- Desktop layouts use wider content areas while smaller screens switch to simplified single-column layouts.

### Breakpoints
- **Large desktop:** 1100px and above
- **Tablet:** 800px–1099px
- **Mobile:** below 600px

Media queries adjust navigation, spacing, typography, forms and content layout.

### Responsive images
Images include `srcset` and `sizes` attributes. Responsive image variants at 400px, 800px and 1200px widths are included in the `images/` folder so the browser can select a suitable resource.

### Interaction and accessibility
- `:hover` and `:focus-visible` states are applied to navigation links and form controls.
- Visible keyboard focus indicators improve accessibility.
- `prefers-reduced-motion` is supported.

## Part 1 Feedback / Corrections Changelog

| Date | Change | Reason |
|---|---|---|
| 16 September 2026 | Reviewed all Part 1 HTML pages and retained the existing semantic structure and content while preparing the site for visual styling. | Required to carry Part 1 work into Part 2 without removing the original content. |
| 16 September 2026 | Added a single external `style.css` file and linked it to all five HTML pages. | Meets Part 2 requirement 2.1 and ensures consistent styling across the website. |
| 16 September 2026 | Added consistent base typography, colours, spacing, borders, shadows and responsive image rules. | Meets the base-style and typography requirements. |
| 16 September 2026 | Added Flexbox navigation/header styling and CSS Grid layouts for larger screens. | Improves desktop structure and demonstrates CSS layout techniques. |
| 16 September 2026 | Added `:hover` and `:focus-visible` states for interactive elements. | Improves usability and keyboard accessibility. |
| 16 September 2026 | Added tablet and mobile media queries with relative units (`rem`, `%`, `clamp()`). | Meets responsive design and relative-unit requirements. |
| 16 September 2026 | Added `srcset` and `sizes` to website images and generated 400px, 800px and 1200px image variants. | Meets the responsive-image requirement and reduces unnecessary image downloads. |
| 16 September 2026 | Added a consistent footer to the pages. | Improves consistency and provides a clear end-of-page element. |

> **Lecturer feedback note:** Replace or expand the first changelog entry with the exact wording of your Part 1 lecturer feedback if your marked Part 1 contains specific corrections. The Part 1 ZIP supplied for this build did not include a separate feedback sheet.

## Screenshot Evidence

Screenshots should be captured using browser developer tools/device emulation and placed in `screenshots/`.

Recommended evidence:
1. Desktop — approximately 1440 × 900
2. Tablet — approximately 768 × 1024
3. Mobile — approximately 390 × 844

The screenshots should show the same website page at different viewport sizes and demonstrate that the layout changes appropriately.

## Git Commit Suggestions

Use descriptive commit messages such as:
- `Add external CSS stylesheet for Part 2`
- `Implement desktop grid and flex layouts`
- `Add responsive breakpoints and mobile navigation`
- `Add responsive image srcset variants`
- `Update README changelog and references`

## References

- Mozilla Developer Network (MDN) Web Docs (n.d.) *CSS: Cascading Style Sheets*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS (Accessed: 16 September 2026).
- Mozilla Developer Network (MDN) Web Docs (n.d.) *CSS media queries*. Available at: https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries (Accessed: 16 September 2026).
- Mozilla Developer Network (MDN) Web Docs (n.d.) *Responsive images*. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML/Guides/Responsive_images (Accessed: 16 September 2026).
- W3C (n.d.) *CSS Flexible Box Layout Module*. Available at: https://www.w3.org/TR/css-flexbox-1/ (Accessed: 16 September 2026).
- W3C (n.d.) *CSS Grid Layout Module*. Available at: https://www.w3.org/TR/css-grid-1/ (Accessed: 16 September 2026).
