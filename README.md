# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7).

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
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](design/screenshot-testimonials-grid-section.png)


### Links

- Solution URL: [Solution URL here](https://www.frontendmentor.io/solutions/testimonials-grid-section-solution-GsNnqfiW4)
- Live Site URL: [Live site URL @Vercel](https://prj-05-testimonials-grid-section.vercel.app/)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

How to use CSS nth-of-type:
```css
.card:nth-of-type(3) .testimonial-headline {
  color: var(--Very-dark-grayish-blue);
  padding-right: 40px;
}
.card:nth-of-type(5) .testimonial-headline {
  color: var(--Very-dark-grayish-blue);
}
```
CSS Grid:
```css
.container {
  display: grid;
  grid-template-columns: 1;
  margin: 100px 30px 100px 30px;
  gap: 20px;
}
```

### Continued development

In future projects I plan to use Tailwindcss for CSS styling and vite as Frontend development environment.

### Useful resources

- [:nth-of-type()](https://developer.mozilla.org/es/docs/Web/CSS/:nth-of-type) - The :nth-of-type() CSS pseudo-class matches elements of a given type (tag name), based on their position among a group of siblings.
- [CSS Grid Layout](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Grid_Layout) - CSS Grid Layout excels at dividing a page into major regions or defining the relationship in terms of size, position, and layer, between parts of a control built from HTML primitives.

## Author

- Website - [Gustavo Sanchez](https://www.gusanche.dev)
- Frontend Mentor - [@gusanchedev](https://www.frontendmentor.io/profile/gusanchedev)
- Github - [@gusanchedev](https://www.github.com/gusanchedev)
- Twitter - [@gusanchedev](https://www.twitter.com/gusanchedev)
- Linkedin - [gusanchedev](https://www.linkedin.com/in/gusanchedev/)

## Acknowledgments

Thanks to Mariapaz for being my friend and support 💙