# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

./"NFT card.png"

### Links

- Solution URL: ()
- Live Site URL: ()

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Pseudo CSS styles
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

I learned about pseudo code in CSS and using pseudo to create hover effects

Code that I'm proud of is:
```css

    .image-container::before {
        content: url('./images/icon-view.svg');
        display: flex;
        justify-content: center;
        align-items: center;
        width: 100%;
        height: 100%;
        position: absolute;
        transform: scale(0);
    }

    .image-container::after {
        content: '';
        background-color: hsl(178, 100%, 50%);
        opacity: 0.3;
        width: 100%;
        height: 100%;
        position: absolute;
        transform: scale(0);
        top: 5%;
        border-radius: 15px;
    }

    .image-container:hover::before, .image-container:hover::after {
        transform: scale(1);
        cursor: pointer;
    }

### Continued development

Pseudo Code is one thing that I want to spend more time on.

### Useful resources

- https://www.youtube.com/watch?v=xoRbkm8XgfQ&t=5s Helped with Pseudo Code

## Author

- Frontend Mentor - [@Okkie14](https://www.frontendmentor.io/profile/Okkie14)
-Github - [@Okkie14](https://github.com/Okkie14)