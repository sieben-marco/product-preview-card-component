# Responsive mobile-first solution | Frontend Mentor

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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop Layout](./design/desktop.png)

### Links

- Solution URL: https://github.com/sieben-marco/product-preview-card-component
- Live Site URL: https://sieben-marco.github.io/product-preview-card-component

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Media Queries
- [BEM](https://en.bem.info/methodology/quick-start/) - Block, Element, Modifier

### What I learned

I learned about BEM and Media Queries. I also applied some things that I've learned how layout designs and how to make a web site with mobile-first.

```html
<div class="card">
  <p class="card__price--sale">$149.99</p>
  <p class="card__price--real">$169.99</p>
</div>
```
```css
@media screen and (min-width: 1200px) {
  .card {
    width: 80rem;
  }
  .card__image,
  .card__wrapper {
    width: 40rem;
  }
  .card__wrapper {
    padding: 4.6rem;
  }
}
```

### Continued development

I want to keep learning about web development and improve my js.

### Useful resources

- [CSS Units for font-size](https://medium.com/@dixita0607/css-units-for-font-size-px-em-rem-79f7e592bb97) - This helped me for configure the font-size root.
- [O que você precisa saber](https://www.instagram.com/p/Cf97-jFu24V/?igshid=YmMyMTA2M2Y=) - This is a post which helped me know BEM. **(Portuguese)
- [Utilizando Media Queries](https://www.devmedia.com.br/utilizando-css-media-queries/27085) - This is an amazing article which helped me finally understand Media Queries. **(Portuguese)

## Author

<!-- - Website - [Add your name here](https://www.your-site.com) -->
- Frontend Mentor - [@sieben-marco](https://www.frontendmentor.io/profile/sieben-marco)
- LinkedIn - [Marco Sieben](https://www.linkedin.com/in/sieben-marco/)
