# Frontend Mentor - Four Card Feature Section Solution

This is my solution to the [Four Card Feature Section challenge](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK/hub) on Frontend Mentor. This challenge helped me practice using CSS Grid and Flexbox to build a responsive layout with a desktop-first approach.

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Continued Development](#continued-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![Screenshot of the solution "desktop"](./images/screenshot-desktop.png.png)
![Screenshot of the solution "phone"](./images/screenshot-phone.pngscreenshot-desktop.png.png)

### Links

- [Solution URL](https://github.com/yourusername/four-card-feature-section)
- [Live Site URL](https://yourusername.github.io/four-card-feature-section/)

## My Process

### Built With

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Desktop-first workflow

### What I Learned

In this project, I followed a desktop-first workflow, designing for larger screens initially and then adjusting the layout for smaller devices. Here are the steps and techniques I used:

1. **CSS Grid Layout for Desktop:** I used CSS Grid to create the layout for desktop devices, allowing for precise control over the placement and sizing of elements.

```css
.hero-sec {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-template-rows: repeat(4, 1fr);
  grid-gap: 2rem;
}
