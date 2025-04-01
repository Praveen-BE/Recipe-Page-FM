# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)

  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

- [Credits](#credit)

## Overview

### Screenshot

- Laptop View
  ![ImageLaptop](./mySolutionImage/Screenshot%202025-04-01%20at%2023-23-13%20FM%20Recipe.png)
- Mobile View
  ![imageMobile](./mySolutionImage/Screenshot%202025-04-01%20at%2023-24-28%20FM%20Recipe.png)

### Links

- Solution URL: Github Repository [Recipe-Page-FM](https://github.com/Praveen-BE/Recipe-Page-FM)
- Live Site URL: [Recipe-Page-FM](https://praveen-be.github.io/Recipe-Page-FM/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

- i put index.html in .prettierignore i don't want to search paragaph😂.
- and i use [Josh Comeau](https://www.joshwcomeau.com/css/custom-css-reset/?from=newsletter) css reset and i commented 3 and 10 th point.
- i create html markup based on desktop view
- after complete the markup i remove index.html from prettierignore

- i added :root css variable added value base on [style-guild.md](./style-guide.md)

- i spend more than 1 hour to write HTML and
- i think i spend more than 6 hours for the applying css and adjust layout anyway i complete this🥳.

### What I learned

- adjusting the bullet by creating new one is realy tough i learn this in the project by searching google and youtube

```base
ul li {
  position: relative;
  margin-right: 0px;
  list-style-type: none;
}

ul li::before {
  content: "•";
  position: absolute;
  left: -40px;
  top: 50%;
  transform: translate(0%, -50%);
  font-weight: bold;
}
```

## Credits

- stackoverflow
- Frontend Mentor
- Kevin Powell
- Google
- Phone
- Laptop
- VS Code
