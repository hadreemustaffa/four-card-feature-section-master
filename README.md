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
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

In mobile-view, I encountered an overflow problem. Setting overflow to scroll doesn't work. After few minutes of looking, found a solution that was:

```css
body {
	min-height: 0;
}
```

### Useful resources

- [Modus Create](https://moduscreate.com/blog/how-to-fix-overflow-issues-in-css-flex-layouts/) - This is where I found the solution for the problem above, such a simple solution.

## Author

- Frontend Mentor - [@hadreemustaffa](https://www.frontendmentor.io/profile/hadreemustaffa)
