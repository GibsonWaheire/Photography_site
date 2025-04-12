# Design Plan for Photography Portfolio Website

## Project Objective

The goal of this website is to showcase a collection of photographs using clean, accessible, and responsive design built with HTML and CSS. The website includes sections such as navigation, a featured favorites list, a full gallery, and a personal biography.

---

## Layout and Structure

The layout was planned to include the following sections:

1. **Navigation Bar**  
   Fixed to the top, links to Home, About, Services, and Contact.  
   Simple horizontal flex layout with hover effects.

2. **Header Section**  
   Contains the website's headline and a short description.  
   Centered both vertically and horizontally using flexbox.

3. **Favorite Photos Section**  
   Displays a list of favorite photos with equal size thumbnails and captions.  
   Styled using object-fit and grid/flex layout for responsiveness.

4. **Gallery Section**  
   Grid layout to display all photos. Each image has a title and uniform styling.

5. **Biography Section**  
   Two-column layout with profile image and a short paragraph using `<strong>` and `<em>`.

---

## Visual Design Choices

- **Font:** Arial, sans-serif (simple, readable)
- **Color scheme:**  
  - Backgrounds: white / light gray  
  - Navigation bar: black with white text  
  - Accent: soft borders and hover color
- **Spacing:** Consistent padding and margins using rem units
- **Image Styling:** `object-fit: cover` for consistent aspect ratios
- **Responsiveness:** Uses media queries and flex-wrap to adapt for mobile screens

---

## Frameworks, Methodologies, and Concepts Used

- **Box Model** — to manage spacing and alignment.
- **CSS Flexbox** — used for navigation, header centering, and photo layouts.
- **Semantic HTML** — using tags like `<section>`, `<header>`, `<nav>`, and `<footer>`.
- **Responsive Design Principles** — images, containers, and text scale properly on all screen sizes.
- **Pseudoclasses** — `a:hover` for nav links and image interactions.
- **Custom Styling** — implemented manually using pure CSS without any external frameworks.

---

## Tools Used

- VSCode
- Git + GitHub
- GitHub Pages
- Markdown for documentation
