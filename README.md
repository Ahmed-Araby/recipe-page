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

#### Tablet viewport

### Mobile viewport

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
- li::marker pseudo element is refering to the box around the list style (bullet, number, etc...)
- li:before is also refering to list item style (bullet point, number, etc..) and it has more freedom in styles over the ::marker pseudo element.
- we can define sequence to be used as list item style (number, alpheat, etc..) using counter() css function.
- list item properties controlling the list item marker (bullet point, numbers, etc..) {list-style-position, list-style-type, ....}
- by default the list item marker (bullet point, numbers, etc..) are positioned outside the list item box and they can be configured to be rendered inside the list item box.
- the list item marker (bullet point, numbers, etc..)  are not part of the list item box flow whenb they are positioned outside the list item.
- the list item element has display property set to list-item and any element with display property set to list-item will get a marker pseudo element by default.
- the marker pseudo element vanish when display of the list item is changed for example set to flex.
- when a child element overflow from its container element, the padding-bottom won't have visual effect.
