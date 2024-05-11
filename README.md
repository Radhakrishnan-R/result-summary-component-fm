# Frontend Mentor - Results summary component solution

This is a solution to the [Results summary component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/results-summary-component-CE_K6s0maV). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 


## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot

![](./Screen%20Shot.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [(https://radhakrishnan-r.github.io/result-summary-component-fm/)]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

On this project I learnt how to use ::before psuedo class to add linear gradient to a button element and it was great!

```css
button:before{
    background-image: linear-gradient(hsl(252, 100%, 67%), hsl(241, 81%, 54%));
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    content: "Continue";
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 15px;
    z-index: -1;
    opacity: 0;
    transition: opacity 0.15s;
}
```



## Author

- Website - [Radhakrishnan R](https://radhakrishnans-portfolio.webflow.io/)
- Frontend Mentor - [Radhakrishnan-R](https://www.frontendmentor.io/profile/Radhakrishnan-R)

