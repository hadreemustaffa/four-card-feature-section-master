# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Github Pages](https://hadreemustaffa.github.io/four-card-feature-section/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

1. In mobile-view, I encountered an overflow problem where I cannot scroll down the overflowing content. Setting overflow to scroll doesn't work. After few minutes of looking, found a solution that was:

```css
body {
	min-height: 0;
}
```

2. Using justify-content to center caused some problem for me. So I changed to `margin: auto` to fix the problems. This also fixed a problem where in mobile-view, top-part of `<header>` overflowed.

### Useful resources

- [Modus Create](https://moduscreate.com/blog/how-to-fix-overflow-issues-in-css-flex-layouts/) - This is where I found the solution for the problem above, such a simple solution.
- [Stack Overflow](https://stackoverflow.com/questions/36988406/flexbox-overflow-top-of-the-element-is-missing) - This post is quite old, but it helped me fixed the problems I had with justify-content center and align-items center.

## Author

- Frontend Mentor - [@hadreemustaffa](https://www.frontendmentor.io/profile/hadreemustaffa)
