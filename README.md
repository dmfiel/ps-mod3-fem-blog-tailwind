# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

This project shows a sample blog post card design with graphics, categorization, author avatars, and resposive sizing.

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](/assets/images/Screenshot%202025-05-01%20091735.png)

## My process

I downloaded the starter files and opened them as a new project in VSCode. HTML tweaks and CSS were created by hand with input from the design on Figma.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

The biggest learning was that to vertically center the entire page, you sometimes need to style the html and body to take 100% of the viewport height. Also, the element sizing on Figma includes the padding, which needs to be subtracted for the CSS values.

```css
html,
body {
  height: 100%;
}
```

## Author

David Fiel

- Website - [Add your name here](https://fiel.us)

## Acknowledgments

Thanks to Per Scholas!
