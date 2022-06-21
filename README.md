# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- See hover states for interactive elements

### Screenshot

For desktop :

![](./design/Screenshot%20desktop.png)

For mobile :

![](./design/Screenshot%20mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I try to center the object using a Grid at the <Section class="container">, last time I did the same with flexbox but it's working well with Grid.
I use a grid with 2 lignes for separate the image and the texte
I use a grid with 3 columns for separate element of the payement card
I use margin for adjusting the texts.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I practice about using grid for center and positioning the object. The idea was to use les margin. But still have a lot anyway.

Exemple=> Grid for help with the size of image. The image will automatically be smaller when we reduce screen for mobile :

```css =>
.grid1 {
  display: grid;
  grid-template-rows: 31.43% 68.57%;
  background: var(--Verypaleblue);
  box-shadow: 0px 20px 30px 0px hsla(225, 55%, 55%, 0.2);
  border-radius: 18px;
  width: 450px;
  height: 700px;
  margin: auto;
}
```

### Continued development

I think this kind of work can be done with less code and easier... I just have to find how.

## Author

- Website - [Steven-Dev](https://github.com/Stv-devl)
- Frontend Mentor - [@Stv-devl](https://www.frontendmentor.io/profile/yourusername)
