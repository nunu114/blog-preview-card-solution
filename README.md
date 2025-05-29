# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

Blog preview card made using HTML and CSS with flex box and clamp() technique.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/screenshot.png)

### Links

- Solution URL: [https://github.com/nunu114/blog-preview-card-solution.git](https://github.com/nunu114/blog-preview-card-solution.git)
- Live Site URL: [https://blog-preview-card-nunu.netlify.app/](https://blog-preview-card-nunu.netlify.app/)

## My process

Design the basic structure in HTML and then style it in CSS using flex box. 

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- clamp()

### What I learned

I learned how to use flex box and rem units once again. It's still hard but I'm slowly understanding how to use it effectively.
I also learned how to make responsive font size without using media query. I used clamp() instead. Even though I'm still not comfortable using rem unit, learning new technique that uses that unit is quite fun. I know there may be better way to do this but I'm happy that it works.

```css
.content h1 {
  font-size: clamp(1.25rem, 2.5vw, 1.5rem);
}
```

### Continued development

Still in my journey of getting comfortable using rem unit and flex box.

### Useful resources

- [clamp()](https://developer.mozilla.org/en-US/docs/Web/CSS/clamp) - This helped me for responsive font size without using media query.
- [Positioning image within div](https://www.sitepoint.com/community/t/images-breaking-out-of-div/1868/7) - This helped me to fix a problem positioning an image within div element.

## Author

- Website - [Nurika](https://github.com/nunu114)
- Frontend Mentor - [@nunu114](https://www.frontendmentor.io/profile/nunu114)

## Acknowledgments
