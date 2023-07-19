# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![Mobile](./screenshots/Screenshot%20Frontend%20Mentor%20QR%20code%20component%20-%20mobile.png)

### Links

- Solution URL: [Frontend Mentor](https://www.frontendmentor.io/solutions/flexbox-qr-code-component-nFXnO2wAuJ)
- Live Site URL: [GitHub Pages](https://n-d-m.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

With the help of this project I learnt that you can make the body itself a flex container, which makes centering objects both vertically and horizontally very easy. I also learnt that using 100vh -1 is the best way to avoid a scroll bar when it isn't necessary.

```css
body {
  font-family: outfit, sans-serif;
  background-color: var(--color-lightGray);
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 99vh;
}
```

### Continued development

In my next projects I want to focus on the the best practices on where to declare variables or globar attributes.

## Author

- GitHub - [n-d-m](https://github.com/n-d-m)
- Frontend Mentor - [@n-d-m](https://www.frontendmentor.io/profile/n-d-m)

## Acknowledgments

Thank you Stack Overflow as usual!
