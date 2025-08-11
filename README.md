# Recipe Page

This is my solution for the [Recipe Page challenge on Frontend Mentor]((https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm)).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)

## Overview
The Recipe Page challenge is about creating a response page that fill the screen for mobile devices viewport and convert to card centered in the viewport for tablet and desktop. the page includes picture of the meal, ingredients, instructions to prepare the meal and nutrition facts.

### Screenshot
#### Desktop viewport
![recipe-page-in-desktop-viewport](https://github.com/Ahmed-Araby/recipe-page/blob/main/documentation/gifs/recipe-page-in-desktop-viewport.gif)

#### Tablet viewport
![recipe-page-in-tablet-viewport](https://github.com/Ahmed-Araby/recipe-page/blob/main/documentation/gifs/recipe-page-in-tablet-viewport(w%20768%2C%20H%201024).gif)

### Mobile viewport
![recipe-page-in-mobile-viewport](https://github.com/Ahmed-Araby/recipe-page/blob/main/documentation/gifs/recipe-page-in-mobile-viewport(w%20375%2C%20H%20667).gif)

### Links

- Solution URL: [https://github.com/Ahmed-Araby/recipe-page](https://github.com/Ahmed-Araby/recipe-page)
- Live Site URL: [https://ahmed-araby.github.io/recipe-page/](https://ahmed-araby.github.io/recipe-page/)

## My process
* define the design system using css variables and classes.
* set global styles.
* layout the HTML structure.
* style for the mobile view port, then the tablet viewport and lastely the Desktop viewport.
* document and deploy my solution.
  
### Built with
- Semantic HTML5 markup
- Flexbox
- CSS variables
- Media Queries
- custom variable font file


### What I learned
- li::marker pseudo element is refering to the box around the list marker (bullet point, number, etc...)
- li::before pseudo element is also refering to the list item marker (bullet point, number, etc..) and it has more freedom in styles over the ::marker pseudo element.
- we can set the sequence used for item marker (number, alpheat, etc..) of an ordered list using counter() css function. the counter need to be defined first.
- list item properties controlling the list item marker (bullet point, numbers, etc..) are {list-style-position, list-style-type, ....}
- by default the list item marker (bullet point, numbers, etc..) is positioned outside the list item box and it can be configured to be rendered inside the list item box.
- the list item marker (bullet point, numbers, etc..)  is not part of the list item box flow when it is positioned outside the list item.
- the list item element has display property set to list-item and any element with display property set to list-item will get a marker pseudo element by default.
- the marker pseudo element vanish when display property of the list item is changed for example when set to flex.
- when a child element overflow from its container element the padding-bottom won't have visual effect.
- the following url specified within the css file is relative to the css file
  ``` @font-face {
    font-family: "Young Serif";
    src: url("./assets/fonts/young-serif/YoungSerif-Regular.ttf");
  }
  ```
