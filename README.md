# The Kingdom Culture Club — Official Website

**Subject Code:** WEDE5020  
**Module Name:** Web Development  
**Project Description:** A responsive 5-page web platform for *The Kingdom Culture Club*, a community organisation dedicated to honoring God through shared automotive passions, community outreach, and skill-building projects.

---

## Part 2 Features & Visual Styling

- **External CSS Architecture:** Styled using `css/style.css` with a global CSS reset (`box-sizing`, margin/padding reset) and custom CSS variables (`:root`).
- **Typography & Units:** Fluid typography scaling implemented using relative units (`rem`, `em`, `%`).
- **Layout Structures:** Combined CSS Flexbox (navigation bar) and CSS Grid (`.grid-container`) for desktop multi-column structures.
- **Interactive Pseudo-Classes:** Active visual feedback added using `:hover`, `:focus`, and `:active` state styling across links, cards, and buttons.
- **Responsive Web Design:** Custom media query breakpoints (`768px` for tablets, `480px` for mobile devices) switching multi-column layouts into single-column mobile views.
- **Responsive Images:** Implemented standard HTML `<picture>` element and `srcset`/`sizes` attributes for bandwidth optimization across devices.

---

## Testing & Device Verification 

The website was systematically tested using Google Chrome and Mozilla Firefox Developer Tools across multiple viewports:
1. **Desktop View (1200px+):** Verified multi-column grid layouts, full horizontal navigation bar, and hover interactions.
2. **Tablet View (768px):** Confirmed fluid scaling using `%` and `rem` units, with structural gap adjustments.
3. **Mobile View (375px - 480px):** Verified single-column stacked layout, touch-friendly vertical navigation buttons, and responsive image scaling without horizontal scrolling.


---

## Feedback & Modification Changelog 

| Date | Task / Issue | Description of Edit & Implementation | Status |
| :--- | :--- | :--- | :--- |
| **2026-08-15** | Part 1 Feedback Review | Refined core mission statement across `about.html` and `index.html` to clearly reflect faith-based automotive community focus. | Completed |
| **2026-08-20** | CSS Integration | Created `css/style.css` external stylesheet and linked all 5 HTML pages. | Completed |
| **2026-08-24** | Base Reset & Theme | Established CSS reset, root color palette (Charcoal `#121212`, Amber Gold `#D4AF37`), and base typography scale. | Completed |
| **2026-09-02** | Desktop Layouts | Implemented CSS Flexbox header nav and CSS Grid layout for project cards and highlights. | Completed |
| **2026-09-08** | Mobile Responsiveness | Added `@media` query breakpoints at `768px` and `480px` to convert desktop grid layouts to single-column mobile stacks. | Completed |
| **2026-09-12** | Responsive Media | Added `picture` element and `srcset` attributes to media containers for adaptive image rendering. | Completed |

---

## References

1. The Independent Institute of Education (IIE), 2026. *Web Development 5020 Module Guide [WEDE5020]*. Johannesburg: The Independent Institute of Education.
2. MDN Web Docs, 2024. *Responsive design & Media Queries*. [online] Available at: <https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Responsive_Design> [Accessed 10 September 2026].
3. World Wide Web Consortium (W3C), 2023. *Responsive Images Syntax (srcset/sizes)*. [online] Available at: <https://www.w3.org/> [Accessed 11 September 2026].

