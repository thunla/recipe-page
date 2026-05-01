# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the recipe page depending on their device's screen size
- See hover states for interactive elements (e.g., the attribution links)

### Screenshot

![](./preview.jpg)

### Links

- Solution URL: TBD
- Live Site URL: TBD

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (CSS variables)
- Flexbox
- Responsive images (`object-fit`) and media queries

### What I learned

This challenge was good practice for keeping styles consistent using CSS variables, and for handling responsive images cleanly.

```css
:root {
  --stone-100: hsl(30, 54%, 90%);
  --brown-800: hsl(14, 45%, 36%);
  --rose-50: hsl(330, 100%, 98%);
}

.recipe-header img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  border-radius: 16px;
}
```

### Continued development

In a future iteration, I want to:

- Improve the typography scale and spacing to match the design more closely
- Add explicit focus styles (keyboard navigation) for better accessibility
- Clean up HTML structure and validate markup

### Useful resources

- [MDN: object-fit](https://developer.mozilla.org/en-US/docs/Web/CSS/object-fit) - Helpful for keeping the hero image cropped nicely across screen sizes.
- [MDN: border-collapse](https://developer.mozilla.org/en-US/docs/Web/CSS/border-collapse) - Useful reference for styling the nutrition table.

### AI Collaboration

I used GitHub Copilot to help draft and refine this README based on the Frontend Mentor template.

## Author

- Name - ThuNguyen
- Frontend Mentor - TBD

## Acknowledgments

Challenge by [Frontend Mentor](https://www.frontendmentor.io).
