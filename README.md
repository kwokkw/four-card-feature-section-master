# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Four card feature section solution](#frontend-mentor---four-card-feature-section-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)

## Overview

A more complex CSS grid challenges. 

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Github repo](https://github.com/kwokkw/four-card-feature-section-master)
- Live Site URL: [Github live site](https://kwokkw.github.io/four-card-feature-section-master/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
  - grid-template areas
- Mobile-first workflow

### What I learned

```css

.cards-container {
        grid-template-columns: 1fr 1fr 1fr;
        grid-gap: 30px;
    }

.cards-container__card-cyan {
        /* grid-column-start: 1;
        grid-column-end: 2;
        grid-row-start: 2;
        grid-row-end: 4; */
        grid-area: 2/ 1/ span 2/ span 1;
    }

.cards-container__card-red {
    /* grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 1;
    grid-row-end: 3; */
    grid-area: 1/ 2/ span 2/ span 1;
}

.cards-container__card-blue {
    /* grid-column-start: 3;
    grid-column-end: 4;
    grid-row-start: 2;
    grid-row-end: 4; */
    grid-area: 2/ 3/ span 2/ span 1;
}

.cards-container__card-orange {
    /* grid-column-start: 2;
    grid-column-end: 3;
    grid-row-start: 3;
    grid-row-end: 5; */
    grid-area: 3/ 2/ span 2/ span 1;
}

```

## Author

- Frontend Mentor - [@kwokkw](https://www.frontendmentor.io/profile/kwokkw)
