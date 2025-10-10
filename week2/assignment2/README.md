# Assignment 2

# Personal Portfolio Page Assignment

**Student Name:** Claudine Valencia
**Course:** CIS 185
**Assignment Two:** Personal Portfolio Page Exploration
**Date:** October 9, 2025

## Project Overview

A single-page portfolio website showcasing my work as a student editor and web developer using CSS Grid, Flexbox, and semantic HTML5.

## CSS Grid Implementation

**Where Grid is used:** The overall page layout `#page`

**How it works:**
- Creates vertical layout for sections of the page: header → nav → main → footer
- Uses `grid-template-areas` to define page regions

```css
#page {
  display: grid;
  grid-template-areas: "header" "nav" "main" "footer";
}
```

## CSS Flexbox Implementation 

**Where Flexbox is used:** Navigation menu `<nav>` and Projects section `section:has(article)`

**How it works:** 
- Navigation - arranges links horizontally in a centered row
- Projects section - creates responsive project card gallery

```css
nav {
  display: flex;
  justify-content: center;
  gap: 1rem;
}

section:has(article) {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
}
```

**Using Both Grid and Flexbox**
- Grid - used to give structure for overall webpage layout
- Flexbox - used for navigation links and project cards responsively
- Both - Flexbox was used for Projects section, Grid was to horizontally align project cards


## Key Elements
- Semantic HTML5 elements (header, nav, main, section, article, footer)
- CSS variables for consistent colors and fonts
- Google Font: "Meow Script" for main heading
- Full-width hero image with cropping as suggested by Claude.ai
- Alt text on all images

## Accessibility Features
- Semantic HTML - header, nav, main, section, footer, article
- Alt text on images - All `<img>` tags have alt attributes
- Heading hierarchy - h1, h2, h3 in order
- Sufficient color contrast (dark text on light background)

## Learning Outcomes

Through this assignment, I learned:

1. **CSS Grid and Flexbox differences** - Understanding when to use Grid for structured layouts compared to Flexbox for flexible arrangements
2. **Layout challenges** - How Flexbox and Grid handle content differently and require careful and meticulous planning
3. **Image optimization** - Techniques like `object-fit: cover` and setting fixed dimensions to make images work within Grid and Flexbox layouts
4. **Accessibility requirements** - Implementing proper semantic HTML, alt text, and color contrast for WCAG compliance
5. **CSS Variables** - Using custom properties for consistent theming across the site
6. **Single-page navigation** - How to use anchor links with `id` attributes to navigate between sections on the same page

## Challenges Encountered

1. **Flexbox and Grid layouts**: It was not easy to understand structuring the page with Grid while using Flexbox for the projects section. It took a tremendous amount of time for trial and error to get them working together properly.
2. **Image sizing and cropping**: Getting images to fit correctly in the layouts required resizing and cropping. Used `object-fit: cover` for the hero image and consistent dimensions for project cards.
3. **Single-page navigation**: Struggled to understand how to make navigation links work on a single page. With AI assistance, I learned to use anchor links (`href="#section"`) that link to section `id` attributes.
4. **Accessibility compliance**: Making sure to follow accessibility standards.

## AI Assistance Disclosure

Parts of this project were created with assistance from Claude.ai:

- CSS Grid template structure for page layout
- Flexbox direction and wrapping properties
- section:first-of-type selector for targeting the hero image
- min-height: 100vh implementation for full viewport height

All AI-generated code has been reviewed and understood before customizing to fit to code. 

## Resources Used

- [MDN HTML Elements Reference](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements)
- [MDN CSS Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [W3C Schools CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp)
- [CSS:root Pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/:root)
- [CSS:has Selector](https://www.w3schools.com/cssref/sel_has.php)
- [Google Fonts](https://fonts.google.com/)
- [Claude.Ai](https://claude.ai/)

## Files Included

- `index.html` - Main HTML file with all implemented elements
- `README.md` - This documentation file
- `css/styles.css` - External stylesheet for CSS
- `images/` - Folder containing images used in webpage

## How to View

1. Clone this repository
2. Open `index.html` in any modern web browser
3. Interact with the various elements to see their functionality

---