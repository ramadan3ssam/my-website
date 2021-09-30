# My Personal Website

## Table of contents

- [Overview](#overview)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Author](#author)

## Overview

### personal Responsive website using HTML & CSS only. 

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

The most thing I learned to do in this project is to add burger bar icon in the mobile screen without JS,
here is how I do that:

```html
  <div class="links">
     <i class="fas fa-bars bar-icon"></i>
     <ul>
        <li class="active"><a href="#">Home</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact </a></li>
        <li>
           <a href="#" target="_blank" style="text-align: center">
             <i class="fab fa-github github fa-2x"><span class="icon-label"> Source Code</span></i>
           </a>
        </li>
    </ul>
 </div>
```
```css
 nav .links .bar-icon {display: none;}
 nav ul {
    display: flex;
    justify-content: space-between;
    align-items: center;
 }

@media (max-width:767px) {
 nav .links .bar-icon {
        display: block;
        font-size: 25px;
 }
 nav ul {display: none;}
 nav .links:hover ul {
        display: block;
        flex-direction: column;
 }
}
```

### Continued development

This website will be updated continuously as I learned new langauges and technologies,
As well, I will update the design and add some JS in the future.

## Author

### I will be happy to listen to your feedback:

- Website - [Ramadan Essam](https://www.ramadan3ssam.live)
- Codepen - [Ramadan Essam](https://codepen.io/ramadan3ssam)
- Twitter - [@ramadan3ssam](https://www.twitter.com/ramadan3ssam)
- Facebook - [Ramadan Essam](https://www.facebook.com/ramadan3ssam)