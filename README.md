# Frontend Mentor - Social Links Profile Solution

This is my solution to the [Social Links Profile Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-5Mlz4hV12). Frontend Mentor challenges help developers improve their coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [Useful Resources](#useful-resources)
  - [Author](#author)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)

## Overview

### Screenshot

![Social Links Profile Screenshot](./assets/images/screenshot.png)

### Links

- [Solution Repository](https://github.com/wiceldric75/social-links-profile) 
- [Live Demo](https://wiceldric75.github.io/social-links-profile/)

## My Process
- **Setup**: Structured the project with semantic HTML5 and external CSS, importing the "Inter" font via Google Fonts.
- **HTML**: Designed a clean and accessible layout using descriptive class names and logical content hierarchy.
- **CSS**: Used custom properties for colors, typography, and spacing. Implemented Flexbox for layout and ensured responsiveness with a mobile-first workflow. Styled hover and focus states for interactive elements.
- **Testing**: Verified design accuracy, hover/focus states, and responsiveness across multiple screen sizes.
- **Refinement**: Fine-tuned styles to align with design specifications, focusing on alignment, spacing, and typography.

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### Useful Resources

- [MDN Web Docs - CSS Pseudo-Classes](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) - Helped in styling hover and focus states effectively.
- [Frontend Mentor Slack Community](https://www.frontendmentor.io/slack) - Provided support and valuable feedback during this challenge.
- [CSS Tricks - A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Helped structure and align the layout efficiently.

### Author
- I have over 20 years of professional development experience, starting with a decade in embedded systems where I worked with assembly, C, and C++. For the past 10+ years, I’ve specialized in iPhone application development using Objective-C and Swift. Recently, I’ve ventured into starting my own business, which sparked my interest in web development. After spending months studying HTML, CSS, and JavaScript to build a strong theoretical foundation, I’m now putting those skills into practice through hands-on challenges like those offered by Frontend Mentor.

- **GitHub**: [wiceldric75](https://github.com/wiceldric75)
- **Frontend Mentor**: [@wiceldric75](https://www.frontendmentor.io/profile/wiceldric75)

### What I Learned

This challenge provided insights into crafting accessible and interactive components. Key learnings include:
- Using **CSS pseudo-classes** to style hover and focus states for improved interactivity.
- Structuring components with **Flexbox** to ensure proper alignment and responsiveness.
- Maintaining a clean and reusable stylesheet using **CSS custom properties**.

Here’s a snippet of CSS I’m particularly proud of:
```css
li:hover,
li:focus-within {
  background: var(--color-green, #c4f82a);
  color: #333333;
}
