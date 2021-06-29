# HTML-CSS Resume/CV

This is a web-based resume/cv built with the latest web technologies and meant to be a modern replacement of the pdf or paper resume. This project was undertaken to practice my HTML and CSS skills. Have to keep them skills sharp. ☻  

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

### The challenge

To build a web-based version of my pdf resume/cv. Some of the advantages of a web-based resume include:

- Editing a web page is much easier than editing a pdf file.
- Ability to add animations on hover and on page load.
- Ability to make the resume responsive to all manner of screen sizes.

### Links

- Live Site URL: [Live Site on Github](https://wandonium.github.io/ResumeProject/)
- Inspiration: [Template Resume](https://templateflip.com/demo/templates/right-resume/)
- Inspiration: [Codepen project](https://codepen.io/astronaomical/pen/KexYgb)

## My process

Get inspiration from the above examples and try to build something similar but customized to my details.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

How to build a horizontal scroll bar with a hover animation.

```css
.p-languages li .bar {
    width: 50%;
    height: 3px;
    background-color: #ccc;
}

.p-languages .bar .progress {
    height: 3px;
    background-color: #8AC23E;
    border-right: 3px solid #333;
    transform-origin: left;
    /* animation: progress 0.5s 1 ease-in-out; */
}

.p-languages li:hover > .bar .progress {
    animation: progress 0.5s 1 ease-in-out;
}

@keyframes progress {
    0% {
        transform: scaleX(0);
    }

    100% {
        transform: scaleX(1);
    }
}
@keyframes progress2 {
    0% {
        transform: scaleX(0);
    }

    100% {
        transform: scaleX(1);
    }
}
```

How to make a colored link/button glow on hover.

```css
.frameworks a {
    color: #fff;
    background-color: #8AC23E;
    padding: 5px;
    border-radius: 10px;
}

.frameworks a:hover {
    box-shadow: 0 0 20px #8AC23E;
}
```

## Author

- Website - [Hillary Wando](http://hillarywando.com/)
- Codepen - [@Wandonium](https://codepen.io/wandonium)
- Twitter - [@hillarywando](https://www.twitter.com/hillarywando)
