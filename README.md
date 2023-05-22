# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)  
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

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/responsive-product-preview-card-component-iSlyqjUh4F)
- Live Site URL: [Live site URL](https://responsive-product-preview-card-component-phi.vercel.app)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

I learned how to use custom properties in html and then manipulate them in css

```html
<button data-icon="shopping-cart">Add to cart</button>
```

then in css i use this property to show a icon svg
```css
.button[data-icon="shopping-cart"]::before{
    content: '';
    width: 15px;
    height: 16px;
    background-image: url("images/icon-cart.svg");
}
```

### Continued development

I will continue doing projects to improve my css grid and responsive layouts
## Author
- Frontend Mentor - [@GasparDroz](https://www.frontendmentor.io/profile/GasparDroz)
- Github - [GasparDroz](https://github.com/GasparDroz)
