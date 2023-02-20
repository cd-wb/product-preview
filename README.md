# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- Changing the image frome mobile to desktop 

### Screenshot

1. Desktop

![](./images/screenshot-descktop.png)

---

2. Mobile

![](./images/screenshot-mobile.png)

### Links

- Solution URL: [Solution URL here](https://github.com/cd-wb/product-preview)
- Live Site URL: [Live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- and extention Vim for Vscode

### What I learned

```css
:root{
    --dc-color: hsl(158, 36%, 37%);
    --cream-color: hsl(30, 38%, 92%);
    --vdb-color: hsl(212, 21%, 14%);
    --dgb-color: hsl(228, 12%, 48%);
    --wt-color: hsl(0, 0%, 100%);

    --srif-font: 'Fraunces', serif;
    --ssrif-font: 'Montserrat', sans-serif;

    --siz-font: 2rem;
}
.button:is(:hover, :focus) {
    background-color:hsl(157, 66%, 18%) ;
}
```

### Useful resources

- [Normalize.css](https://necolas.github.io/normalize.css/) - This helped me to makes browsers render all elements more consistently and in line with modern standards
- [Youtube Video | Kevin Powell](https://www.youtube.com/watch?v=McC4QkCvbaY) - This is an amazing article which helped me finally understand si(). I'd recommend it to anyone still learning CSS Selectors

## Author

- Frontend Mentor - [codeWeb](https://www.frontendmentor.io/profile/kop-left)

