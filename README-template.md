# Frontend Mentor - Product preview card component solution

This is my solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).

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
  - [AI Collaboration](#ai-collaboration)

- [Author](#author)

## Overview

### The challenge

The goal of this challenge was to build the product preview card as closely as possible to the provided design.

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![Screenshot](Screenshot.png)

### Links

- Solution URL: [Add solution URL here](#)
- Live Site URL: [https://anwar-9112.github.io/product-preview-card-component-main/](#)

## My process

### Built with

- Semantic HTML5
- CSS
- CSS Grid
- Flexbox
- Media queries
- Responsive images with the `<picture>` element
- Google Fonts

### What I learned

This project helped me practice turning a Figma design into a responsive webpage using HTML and CSS.

Some of the main things I learned and practiced were:

- Using CSS Grid to create the two-column desktop layout.
- Using Flexbox for smaller layouts and for aligning elements such as the price and button.
- Using media queries to change the layout for smaller screens.
- Using the `<picture>` element to display different images for desktop and mobile.
- Using `object-fit` to control how the product image fits inside its container.
- Creating hover states for interactive elements such as the Add to Cart button.
- Converting Figma measurements from pixels to `rem` values for typography.
- Making fixed-width elements more responsive with values such as `min()`.
- Paying attention to spacing, padding, border radius, typography, and colors when translating a design into CSS.

One problem I worked through was making the mobile button responsive. Instead of simply making it `width: 100%`, I used `width: min(286px, 100%)`. This keeps the button close to the intended design width while allowing it to shrink on smaller screens.

### Continued development

In future projects, I want to continue improving my ability to translate designs into CSS accurately and build responsive layouts without relying too much on fixed dimensions.

I also want to improve my CSS organization and learn to structure reusable styles more effectively as my projects become larger.

For future projects, I also want to practice making smaller Git commits while building so that my commit history clearly shows the different stages of development.

### Useful resources

- [Frontend Mentor](https://www.frontendmentor.io/) — I used the challenge design and requirements as the main reference for building the project.
- [MDN Web Docs](https://developer.mozilla.org/) — A useful reference for understanding HTML and CSS features while working on the project.

### AI Collaboration

I used ChatGPT as a learning and debugging assistant during this project.

I used it to review my HTML and CSS, explain CSS concepts when I was unsure about them, help identify layout and responsive design issues, and review the project before publishing it.

I also used AI to discuss improvements based on feedback from previous Frontend Mentor projects. Instead of having the project written for me, I used the feedback to understand why certain CSS decisions could be improved and then made the changes myself.

## Author

- GitHub: [Anwar-9112](https://github.com/Anwar-9112)
- Frontend Mentor: [@Anwar-9112](https://www.frontendmentor.io/profile/Anwar-9112)
