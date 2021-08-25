# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 
## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)


## Overview

### The challenge

The design should be able to be viewed properly on desktop and mobiles.

### Screenshot

![desktop view](./screenshots/project-8.png)
<p align="center">
  <img src="./screenshots/project-8-mobile.png">
</p>

## My process

### Built with

- Semantic HTML5 markup
- CSS properties
- CSS grid system

### What I learned

I learnt how to construct the layout with divs in HTML and grid property in CSS and how to resize divs with the grid system to make it easy to turn the design to a responsive one

for example:

This is the grid container in desktop view
```css
.card-grid {
  display: grid;
  grid-template-columns: 320px 320px;
  grid-template-rows: 220px 260px;
  background-color: white;
  border-radius: 7px;
  overflow: hidden;
}
```
and this is the grid container in the mobile view
```css
.card-grid {
    grid-template-columns: auto;
    grid-template-rows: 260px 230px 230px;
  }
}
```
And as usual the magic happens and grid layout fit on mobile screens 


### Continued development

I will practice more on using the grid system because it makes your page easy to response changes in width and height and make it easy to adapt on any screen with few lines of code

## Author

- Behance - [Mahmoud Ashraf](https://www.behance.net/m_ashraffarouk/)
- Frontend Mentor - [@m-Ash1](https://www.frontendmentor.io/profile/m-Ash1)
- Twitter - [@m_ashraffarouk](https://www.twitter.com/m_ashraffarouk)

