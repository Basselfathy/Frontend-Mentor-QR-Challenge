# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![Screenshot 2024-11-03 223415](https://github.com/user-attachments/assets/f4b22273-926b-4d41-8cdf-a0bfa1d05d5b)

### Links

- Solution URL: [Solution URL](https://github.com/Basselfathy/Frontend-Mentor-QR-Challenge)
- Live Site URL: [live site URL](https://basselfathy.github.io/Frontend-Mentor-QR-Challenge/)

## My process

### Built with

- Semantic HTML
- CSS custom properties
- Flexbox

### What I learned

* Using css variables and rem units :

```css
:root {
    /* Color Variables */
    --color-900: #1F314F; /* Dark Blue */
    --color-500: #68778D; /* Medium Blue */
    --color-300: #D5E1EF; /* Light Blue */
    --color-100: #FFFFFF; /* White */

    /* Font Sizes and Line Heights */
    --fs-large: 1.375rem;
    --fw-large:700;
    --lh-large: 120%;
    --ls-large: 0px;

    --fs-small: 0.9375rem;
    --fw-small:400;
    --lh-small: 140%;
    --ls-small: 0.0125rem;

    /* Spacing Variables */
    --space-500: 2.5rem;
    --space-300: 1.5rem;
    --space-200: 1rem;
}
```

* BEM methodology:

  ```html
  <div class="card__text">
  ```

  ```css
  .card__text{
      padding: 0 var(--space-200);
  }
  ```

## Author

- Github - [Basselfathy](https://github.com/Basselfathy)
- Frontend Mentor - [@Basselfathy](https://www.frontendmentor.io/profile/Basselfathy)
