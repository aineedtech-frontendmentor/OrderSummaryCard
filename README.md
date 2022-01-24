# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). 

Frontend Mentor is a resource for developers looking to improve their front-end skills. The challenges help you improve your coding skills by building realistic projects using HTML, CSS, and JavaScript. 

This Order Summary Card challenge is meant for Newbie who wants to practice their HTML and CSS skills.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot-of-the-final-product)
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

<img src="https://github.com/aineedtech-frontendmentor/OrderSummaryCard/blob/master/images/Screenshot.png" alt="drawing" width="500"/>

### Links

- Live Site URL: [Live site URL](https://aineedtech-frontendmentor.github.io/OrderSummaryCard/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

#### 1) Background Image
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

#### 2) Center Div
There are several ways to center a div:
```css
body {
    display: flex;
    align-items: center;
    justify-content: center;
}
```
 
```css
body {
    display: grid;
    place-items: center;
}
```

#### 3) Apply shadow to a button
```css
.proceed {
    box-shadow: 0px 5px 20px hsl(224, 23%, 55%);
}
```

### Continued development
I wish to learn more about CSS and be able to apply flex and grid and center a div more confidently.



