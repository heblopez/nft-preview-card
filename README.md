# Make It Real - NFT Preview Card

This is a solution to the **NFT Preview Card** project of the Make It Real course.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

- View the optimal design according to your device screen size.
- View hover for interactive elements.

### Screenshot

![Desktop view](/assets/screenshot.png)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

This project especially helped me to reinforce advanced or unusual CSS properties.

```html
  <figure class="nft-image">
    <img src="/assets/image-equilibrium.jpg" alt="NFT-image">
    <img class="view-icon" src="/assets/icon-view.svg" alt="view-icon">
  </figure>
```
```css
  .nft-image::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: var(--cyan);
    mix-blend-mode: hard-light;
    opacity: 0;
    transition: opacity 0.5s ease;
  }
```

### Continued development

Working on this project made me realize that there are still advanced CSS topics to learn, such as the `mix-blend-mode` property that sets how the content of an element should blend with its background color.

### Useful resources

- [mix-blend-mode - CSS](https://developer.mozilla.org/es/docs/Web/CSS/mix-blend-mode) - This CSS property helped me to make the hover effect of the card.

## Author

- Website - [Heberth López](https://www.heblopez.web.app)

## Acknowledgments

A special thanks to the MakeItReal team for the knowledge and support provided in each class and the feedback received on each project.
