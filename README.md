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
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Source Code](https://github.com/OAguilaLira/qr-code-component-main)
- Live Site URL: [See a live demo](https://oaguilalira.github.io/qr-code-component-main/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- CSS Grid
- Mobile-first workflow

### What I learned

While working on this project, I strengthened several core HTML and CSS concepts. One of the key takeaways was the proper use of semantic HTML elements to build a clear and accessible structure.

I used tags like `<main>`, `<article>`, `<figure>`, `<header>`, and `<footer>`, which improve both code readability and accessibility for screen readers, as well as SEO.

```html
<main>
  <article id="QR-container">
    <figure id="QR-image-container">
      <img src="./images/image-qr-code.png" alt="QR" />
    </figure>
    <div id="text-zone">
      <header>
        <h3 id="titulo-text-zone">
          Improve your front-end skills by building project.
        </h3>
      </header>
      <p id="parrafo-text-zone">
        Scan the QR code to visit Frontend Mentor and take your coding
        skills to the next level
      </p>
    </div>
  </article>
</main>
```


I also practiced CSS layout techniques, especially using Grid to center the component both vertically and horizontally on the screen. I'm particularly proud of this part of the CSS:

```css
main {
  display: grid;
  place-items: center;
  height: 100vh;
}
```


In addition, I worked on applying styles like rounded corners, soft shadows for depth, and a clean, minimalist color palette. Here's how I styled the card component:

```css
#QR-container {
  width: 320px;
  padding: 16px 16px 40px;
  background-color: white;
  border-radius: 20px;
  box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}
```

I also learned how to properly include external fonts from Google Fonts and made sure to use descriptive alt attributes for images to enhance accessibility.

This project helped me solidify my understanding of semantic structure, responsive layout, and writing clean, accessible code.

## Author

- Website - [Add your name here](oaguilalira.github.io/Portafolio/)
- Frontend Mentor - [@yourusername](http://frontendmentor.io/profile/AguilaxO)
