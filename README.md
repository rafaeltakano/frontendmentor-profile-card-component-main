# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://rafaeltakano.github.io/frontendmentor-profile-card-component-main/](https://rafaeltakano.github.io/frontendmentor-profile-card-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Sass](https://sass-lang.com/) - For styles

### What I learned

I learned that using and positioning background images are a lot more flexible than I thought

```css
body {
  display: flex;
  flex-direction: column;

  align-items: center;
  justify-content: center;
  min-height: 100vh;

  background-color: var(--clr-dark-cyan);
  background-image: $--pattern-top, $--pattern-bottom;
  background-position: $--position-top, $--position-bottom;
  background-repeat: no-repeat;
}
```

## Author

- LinkedIn - [Rafael Takano](https://www.linkedin.com/in/rafaeltakano1/)
- Frontend Mentor - [@rafaeltakano](https://www.frontendmentor.io/profile/rafaeltakano)

## Acknowledgments

I used the [Vanza Setia](https://www.frontendmentor.io/profile/vanzasetia) code to align the background images.
