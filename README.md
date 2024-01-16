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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This is a product review card web component

### Screenshot

![](./images/Screenshot%20.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I solidified my learning of flexbox when splitting the product review card into two sections.

```html
<article>
  <picture>
    <source
      srcset="/images/image-product-desktop.jpg"
      media="(min-width: 640px)"
    />

    <img
      class="mobile-img"
      src="/images/image-product-mobile.jpg"
      alt="mobile-img"
    />
  </picture>
</article>
```

```css
.card > article:first-child {
  border-radius: 1rem 0 0 1rem;
  background-color: black;
  object-fit: cover;
  overflow: hidden;
}
```

### Continued development

Improving my css skills is a must, especially with positioning, and mastering css grid. I will continue to do further card components to refine these skills.

### Useful resources

- [CSS Tricks ](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This helped me get comfortable with using flexbox.

## Author
-Product-review-site- [https://card-component-for-product.netlify.app/] 
- Frontend Mentor - [@jboat86](https://www.frontendmentor.io/profile/jboat86)

## Acknowledgments

Websites such as CSS Tricks and FEM has been of major help while learning to code.
