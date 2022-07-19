# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

### Screenshot

![screenshot](./screenshot.png)

### Links

- Solution URL: [https://github.com/king-oldmate/FEM-stats-preview-card-component](https://github.com/king-oldmate/FEM-stats-preview-card-component)
- Live Site URL: [https://king-oldmate.github.io/FEM-stats-preview-card-component/](https://king-oldmate.github.io/FEM-stats-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

I attempted this basic component because I wante to go back to basics and use pure CSS3 (rather than TailwindCSS, which I've been relying upon for a while). The most challenging aspect of this then was to keep track of the `@media` queries (as TailwindCSS uses class-prefixes).

I also learnt some nifty stuff, such as blending background images and colours.

```css
.header-img {
  background-image: linear-gradient(hsl(277, 64%, 61%), hsl(277, 64%, 61%)),
    url("./images/image-header-mobile.jpg");
  background-blend-mode: multiply;
}
```

### Continued development

Mainly just want to keep using CSS rather than Tailwind and ensure that I have it completely mastered. I should perhaps pick up SASS and get used to that at the same time while I'm at it.

## Author

- Website - [Raymond Zeaiter](https://www.raymond-zeaiter.au)
- Frontend Mentor - [@king-oldmate](https://www.frontendmentor.io/profile/king-oldmate)
- Twitter - [@RayZeaiter](https://www.twitter.com/RayZeaiter)
