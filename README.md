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

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: (https://github.com/Marrtinerz/Nft-preview-card-component.git)
- Live Site URL: (https://marrtinerz.github.io/Nft-preview-card-component/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Google fonts
- Font awesome icons

### What I learned

I had a slightly difficult time creating the overlay hover effect. I initially used the ::after pseudo element; however, I couldn't get it to only appear once hovered. I played with the display and nested propertie, but it still didn't work. I really didn't want to create another div just for the overlay, but I ended up doing that. The opacity and alpha channel was a nice final touch. I probably could've made the hover effect work if I had applied opacity and alpha channel with the ::after  pseud oelement. 

see below for code snippets:


```css
.overlay {
    position: absolute;
    top: 0;
    width: 100%;
    aspect-ratio: 1;
    border-radius: 7px;
    background: hsla(178, 100%, 50%, 0.5);
    padding: 110px;
    opacity: 0;
    transition: all 0.25s ease;
}

.overlay:hover {
    opacity: 1;
    cursor: pointer;
}
```

### Continued development

I am currently learning javascript. For now, I will continue my classes on Javasript, while perfecting my html and css skills. I'll move up from building components to building full static sites.

### Useful resources

- [Stack Overflow]
- [MDN]

## Author

- Website - [Martins Nnamchi](https://www.your-site.com)
- Frontend Mentor - [@Marrtinerz](https://www.frontendmentor.io/profile/Marrtinerz)
- Twitter - [@marrtinerz](https://www.twitter.com/marrtinerz)


## Acknowledgments

Colt Steel's web developer bootcamp on Udemy. This is where I took my classes.
