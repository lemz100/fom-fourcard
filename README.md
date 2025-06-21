# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

```css
    .cards {
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        justify-items: center;
    }

    .card {
        max-width: 280px;
        aspect-ratio: 1 / 1;
    }

    .card.cyan {
        grid-row: 1 / 3;
    }
    .card.blue {
        grid-row: 1 / 3;
        grid-column: 3 / 3;
    }
    .card.cyan, .card.blue {
        align-self: center;
    }

    .card.red, .card.orange {
        grid-column: 2/3;
    }

    -Used grid pacement to place the red and orange card in the middle and the blue and cyan in their grids.
    -Aligned single card items to the center of their grid, while constraining size to 280px (WxH) to ensure they stay within the grid.
    -
```

### Continued development

Getting good at responsive designing, continue to challenge myself
    -Learn about responsive designing for very wide screens (2560px etc.)

## Author

- Frontend Mentor - [@lemz100](https://www.frontendmentor.io/profile/lemz100)

