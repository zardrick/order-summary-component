# Frontend Mentor - Order Summary Card Solution

This is my solution to the [Order Summary Card Challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). This challenge helped me refine my skills in structuring components and styling using Sass.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The Challenge

Users should be able to:

- See hover states for interactive elements

### Screenshot

![Order Summary Screenshot](./design/desktop-preview.jpg)

### Links

- [Github Repository](https://github.com/zardrick/order-summary-component)
- [Live Site](https://zardrick.github.io/order-summary-component)

## My Process

### Built With

- Semantic HTML5 markup
- Flexbox
- Mobile-first workflow
- Sass (SCSS)

### What I Learned

While working on this project, I improved my understanding of:

- Structuring reusable SCSS with `@mixin`
- Handling background images for different screen sizes

Here's a snippet demonstrating my use of mixins:

```scss
@mixin text-style($size, $weight, $color) {
    font-size: $size;
    font-weight: $weight;
    color: $color;
}

.order-summary__title {
    @include text-style(1.5rem, 700, $dark-blue);
}
```

### Continued Development

Going forward, I plan to:

- Improve accessibility by implementing better focus states
- Optimize performance with improved media query management

### Useful Resources

- [MDN Web Docs - CSS Backgrounds](https://developer.mozilla.org/en-US/docs/Web/CSS/background)
- [Sass Documentation](https://sass-lang.com/documentation/)
- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

## Author

- Frontend Mentor - [@Zardrick](https://www.frontendmentor.io/profile/Zardrick)
- Twitter - [@Zardrick](https://www.twitter.com/zardrick1)

## Acknowledgments

A big shoutout to the Frontend Mentor community for their valuable feedback and guidance. Special thanks to those who provided helpful critiques on my SCSS structure.
