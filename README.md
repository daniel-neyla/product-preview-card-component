# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges helps me improve my coding skills by building realistic projects. 

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




## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./design/desktop-design.jpg)

This is not actually a screenshot of the component I build, but a picture of the design that I imitated (to see the component that I made click on the link below)

### Links

- Live Site URL: [Click here](https://product-card-jorc.onrender.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox

### What I learned


I do not know you specifically call this, but it chooses the appropriate image depending on the screen width only using HTML:
```html
      <picture>
        <source
          media="(max-width: 375px)"
          srcset="./images/image-product-mobile.jpg"
        />
        <source
          media="(min-width: 376px)"
          srcset="./images/image-product-desktop.jpg"
        />
        <img src="./images/image-product-desktop.jpg" alt="image of product" />
      </picture>
```

The replaced content is sized to maintain its aspect ratio while filling the element's entire content box using CSS:
```css
.proud-of-this-css {
  object-fit: cover;
}
```





### Continued development

I should learn a little more about responsive images in the future. There is still a lot that i haven't covered or forgotten


### Useful resources

- [chat GPT](https://chat.openai.com/) - Powerful AI
- [Odin Project](https://www.theodinproject.com/) - Free frontend course 
- [MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images) - Helped me with responsive image design




