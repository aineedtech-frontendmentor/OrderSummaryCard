# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). 
Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)

## Overview

### The challenge

Users should be able to 
- build an order summary card using HTML and CSS 
- see hover states for interactive elements
- build a responsive website

### Screenshot of the final product

![](https://github.com/aineedtech-frontendmentor/OrderSummaryCard/blob/master/images/Screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

##### Background Image
By default, background image is repeated so it covers the entire element.
The background image can be specifies to show only once and cover the whole page by following:
```css
body {
    height: 100vh;
    background-image: url(images/pattern-background-desktop.svg);
    background-repeat: no-repeat;
    background-color: hsl(225, 100%, 94%);
    background-size: contain;
} 
```

##### Center Div
There are several ways to center a div:
1.
```css
body {
    display: flex;
    align-items: center;
    justify-content: center;
}
```

2. 
```css
body {
    display: grid;
    place-items: center;
}
```

##### Apply shadow to a button
```css
.proceed {
    box-shadow: 0px 5px 20px hsl(224, 23%, 55%);
}
```

### Continued development
I wish to learn more about CSS and be able to apply flex and grid and center a div more confidently.



