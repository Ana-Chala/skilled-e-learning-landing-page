# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot
![](./screenshot.jpg)

![image](https://user-images.githubusercontent.com/121057105/224022218-241f7b99-c639-43c7-bc17-693ffc4fa0c9.png)



### Links

- Live Site URL: [Add live site URL here]https://ana-chala.github.io/skilled-e-learning-landing-page/



### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

during the work on this project, I have learned how to build fully responsive  web-page, for mobile, desktop and tablet screen sizes, I followed mobile-first method
I  learned how to hide images 
```css
.hero-image-tablet{
  display:none
}
```
and appear whenever it's necessery
```css
.hero-image-tablet{
    display: block;
    margin-left:374px;
    margin-top: -608px;
    overflow: hidden;
}
```


### Continued development
I want my project to be more responsive, for desktop screen (width:1440) I used grid ,but couldnt decrease gap between grid columns and my web page for desktop don't look like exactly as on design.

```css
@media  screen and (min-width:1440px) {
.card-container{
    display:grid;
    grid-template-columns: 322px 322px 322px;
    grid-template-rows: 350px 350px;
   justify-items: center;
   justify-content: space-evenly;
}
}
```


### Useful resources

I used resources mostly from youtube , google, intenet.
- for example:(https://www.w3schools.com/css/css_grid.asp)
-for example:  https://www.w3schools.com/cssref/sel_hover.php
 
## Author

- Website - [Ana Chalagashvili](https://www.your-site.com)





