# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flex-box
- Mobile-first workflow

### What I learned

using of box-sizing property in css
using of flex property values

To see how you can add code snippets, see below:

```html
#
```

```css
.equilibrium {
  box-sizing: border-box;
  width: 300px;
  height: 300px;
  padding: 0;
  border-radius: 5%;
}

.details {
  display: flex;
  /* justify-content: space-between; */
  gap: 2rem;
  align-items: center;
  margin-top: 1rem;
  border-bottom: 1px solid hsl(215, 32%, 27%);
  padding-bottom: 1rem;
}

.worth,
.duration {
  display: inline-flex;
  align-items: center;
  gap: 1rem;
}
```
