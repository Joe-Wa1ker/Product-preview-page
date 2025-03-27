# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- See hover and focus states for interactive elements

### Screenshot

Screenshots are available in the screenshots folder.

### Links

- Solution URL: https://github.com/Joe-Wa1ker/Product-preview-page
- Live Site URL: https://joe-wa1ker.github.io/Product-preview-page/

## My process

- Sketched out HTML and overarching CSS on paper
- Built out HTML and CSS (mobile-first)
- Amended HTML by replacing <img> with <picture> and nested <source> and <img> elements so that the two different pictures could be used when the screensize became too wide, added media queries in parralel which included a change in flex-direction for the main container. 
- Played with different screen sizes to introduce a couple of different breakpoints.

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Grid
- Mobile-first workflow
- Media queries

### What I learned

Though my I am still very much a novis, I now feel I have a good grasp of the box model which has helped a lot with my troubleshooting - I find I am now able to arrive quickly at potential solutions before having to google/youtube things for suggestions (which up until now, I had been doing pretty much immediately). During my planning I was also able to anticipate a lot better, e.g. I knew I would have to use a flexbox on the main container and change the flex direction to get the desired shift in layout, from the outset. 

Specifics:

- Using 'align-content: center;', without flexbox, within semantic elements to centre content vertically - super handy and cuts down on code needed. Still use 'margin: auto;' on the child to centre horizontally. 
- Using the picture element to swap out images that are optimized for different screensizes, first time doing this and the first time I had heard of it. 
- Using media queries, first time done properly, though I have played around with these before where they probably weren't necessary. 

### Continued development

- I can see custom functions becoming more useful, I need to get to grips with them.
- More practise with media queries.

## Author

- Website - https://github.com/Joe-Wa1ker
- Frontend Mentor - https://www.frontendmentor.io/profile/Joe-Wa1ker


