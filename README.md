# Week 1: Personal Portfolio Page with Accessibility Audit

## Author
- **Name:** Nancy Ndungu
- **GitHub:** (https://github.com/Riara)
- **Date:** june 24, 2026

## Project Description
A simple personal portfolio webpage built with semantic HTML5. The page introduces me as a web development student and includes my hobbies, a link to my favorite resource, and contact info. As part of the project, I performed a full accessibility audit using Lighthouse and WAVE, then fixed issues like alt text, link descriptions, and meta tags to meet WCAG 2.1 AA standards.

## Technologies Used
- HTML5 - Semantic tags: header, main, section, footer
- CSS3 - Inline styles for responsive image
- Chrome DevTools Lighthouse - Accessibility testing
- WAVE Tool - Visual accessibility checker

## Features
- Semantic HTML structure for screen reader compatibility
- Responsive image with alt text
- Proper heading hierarchy h1 → h2

## How to Run
1. Clone this repository
2. Open `index.html` in your browser
   OR
   Use VS Code Live Server extension and run on `http://localhost:5500`

## Lessons Learned
I learned why accessibility matters for real users. Screen readers rely on `alt` text, `lang` attributes, and proper headings. I also learned how to use Lighthouse to find issues I’d never notice visually, and that good link text should describe the destination, not say "click here".

## Challenges Faced
**Problem**: Lighthouse flagged "Document does not have meta description" and gave low SEO score.  
**Solution**: Added `<meta name="description">` tag in `<head>` with a 150-char summary of the page.

**Problem**: Link text "favorite website" was not descriptive enough for accessibility.  
**Solution**: Changed to "Mozilla Developer Network documentation" so screen reader users know where it goes.

## Screenshots (optional)
![Lighthouse Accessibility Score 98/100](screenshots/lighthouse-score.png)

## Live Demo (if deployed)
[Add link here if you deploy to GitHub Pages / Netlify]
