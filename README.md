<div align="center">
  <img 
    src="./price component SASS.png"
    alt="Single price component card"
    height="350px">
</div>

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

## Overview

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc).

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

<div align="center">
  <img
    src="./mobile-design.jpg"
    alt=""
    height="350px">
  <p><em>Mobile design</em></p>
</div>
<div align="center">
  <img
    src="./price component hover.png"
    alt=""
    height="350px">
  <p><em>Hover state design</em></p>
</div>

### Links

- Solution URL: [Single price grid component]()

## My process

### Built with

- Semantic HTML5 markup
- SASS
- Creating a new stacking context, pseudo-elements, and `isolation` property for children inside a parent element with `mix-blend-mode`
- Flexbox and Grid
- Realistic workflow, building from professional Figma design files (design-to-code) 

### What I learned

I'd used `mix-blend-mode` before to blend backgrounds, figuring out how to employ this property on a parent element (background div) without also affecting its children (text element) was an interesting challenge. I eventually solved it by applying to a pseudo-element, then creating a new stacking context and using the `isolation` property on the child elements.

I also learned the basic syntax and functionality of SASS.


### Continued development

This was my first project using SASS. Once I got the hang of it, I enjoyed the syntax and plan to continue using it in future projects to explore additional capabilities. 

### Useful resources

- [SASS documentation](https://sass-lang.com/documentation/) - Official SASS documentation to deep-dive into capabilities. 
- [freeCodeCamp SASS course](https://www.freecodecamp.org/learn/front-end-development-libraries/#sass) - Introductory short course on SASS with practical exercises to get used to the basic syntax.

## Author

- Frontend Mentor - [@rileydevdzn](https://www.frontendmentor.io/profile/rileydevdzn)