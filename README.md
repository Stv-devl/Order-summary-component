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

- Solution URL: [Add solution URL here](https://stv-devl.github.io/Order-summary-component/)

## My process

I used a Grid for center the card. Last time I did the same with flexbox but it's working well with Grid.

I used a grid with 2 lignes for separate the image and the texte.

I used a grid with 3 columns for separate element of the payement card.

I used margin for adjusting the texts.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

I practice about using Grid to center and positioning objects. Idea was to use less margin.

Exemple=> Grid to help to sizing the image.

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

I think this kind of work can be done with less codes and easier... I just have to find how.

## Author

- Website - [Steven-Dev](https://github.com/Stv-devl)
- Frontend Mentor - [@Stv-devl](https://www.frontendmentor.io/profile/yourusername)
