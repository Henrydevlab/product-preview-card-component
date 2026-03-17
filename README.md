# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)  
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [https://github.com/Henrydevlab/product-preview-card-component](https://github.com/Henrydevlab/product-preview-card-component)
- Live Site URL: [https://henrydevlab.github.io/product-preview-card-component/](https://henrydevlab.github.io/product-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- `<picture>` tag for responsive image art-direction
- Google Fonts (Montserrat & Fraunces)

### What I learned

During this project, I focused on handling responsive images efficiently. Using the `<picture>` element allowed me to swap the product image based on the viewport width without using heavy JavaScript.

```html
<picture class="product-image">
  <source media="(min-width: 600px)" srcset="./images/image-product-desktop.jpg">
  <img src="./images/image-product-mobile.jpg" alt="Product image">
</picture>

```

I also practiced using CSS variables to manage the specific HSL color values provided in the style guide, making the code much easier to maintain.

### Continued development

In future projects, I want to:

* Deepen my understanding of **CSS Grid** for more complex dashboard layouts.
* Improve **Web Accessibility (A11y)**, such as ensuring all interactive elements have highly visible focus states for keyboard users.

## Author

- Frontend Mentor - [@henrydevlab](https://www.frontendmentor.io/profile/henrydevlab)
- Twitter - [@henrydevlab](https://www.x.com/henrydevlab)