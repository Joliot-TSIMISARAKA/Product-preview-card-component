# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Screenshot](#screenshot)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
-   [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover and focus states for interactive elements

### Screenshot

![](screenshot.jpg)

### Links

-   Solution URL: [Front-end mentor](https://www.frontendmentor.io/solutions/responsive-product-preview-card-using-flexbox-GGB_DP7fBP)
-   Live Site URL: [Vercel](https://product-preview-card-component-nu-rose.vercel.app/)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS custom properties
-   Flexbox
-   Mobile-first workflow

### What I learned

-Making use of the picture tag to decide which image to display based on user screen sizes

```html
<picture class="header__picture">
    <source
        class="header__sourceset"
        srcset="images/image-product-desktop.jpg"
        media="(min-width: 600px)"
    />
    <img class="header__image" src="images/image-product-mobile.jpg" alt="" />
</picture>
```

### Continued development

I'm going to dive deeper intot responsive techniques

## Author

-   Frontend Mentor - [@Joliot-TSIMISARAKA](https://www.frontendmentor.io/profile/Joliot-TSIMISARAKA)
-   Twitter - [@JoliotSitraka](https://x.com/JoliotSitraka)
