# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)


## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Desktop](./screenshots/screenshot-desktop.jpg)
![Desktop-Active](./screenshots/screenshot-desktop-active.jpg)
![Mobil](./screenshots/screenshot-mobil.jpg)

## My process

### Built with

- HTML5
- CSS 
- Flexbox


### What I learned

If I try to put an image inside a <div> element that has borders, there will be an extra white space (around 3px) at the bottom of image. It happens because image is an inline-level element so browser adds some whitespace under the baseline to adjust other inline elements.

The easiest way to get rid of this problem is to change the default display value of the image from inline to block, i.e. apply the style display: block; 
[Tutorial Republic](https://www.tutorialrepublic.com/faq/how-to-remove-white-space-under-an-image-using-css.php)

Switching imiges with HTML for different screensizes using <picture> element.
[W3Schools](https://www.w3schools.com/css/css_rwd_images.asp)

```html
<picture>
      <source media="(min-width: 375px)" srcset="images/image-product-desktop.jpg"/>
      <img src="images/image-product-mobile.jpg" alt="Parfum"/>
</picture>
```

### Continued development

This is the very beginning of my journey. 
I still want to practice HTML and CSS and moving to learn JS in the near future.

### Useful resources

- [freeCodeCamp](https://www.freecodecamp.org/) - This is where I started
- [w3schools](https://www.w3schools.com/) - This site helps me a lot solving specific problems


## Author

- Frontend Mentor - [@K-Muzslay](https://www.frontendmentor.io/profile/K-Muzslay)
