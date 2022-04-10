# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). Frontend Mentor challenges help you improve your coding skills by building realistic projects

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [https://github.com/jssol/sunnysideproject/](https://github.com/jssol/sunnysideproject/)
- Live Site URL: [https://jssol.github.io/sunnysideproject/](https://jssol.github.io/sunnysideproject/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Javascript (ES6);

### What I learned

In html, I learned to deliver responsive images.
In css, I learned to partially style an svg.
In js, I learned to use a nav-toggle button.

```html
<img src="./images/mobile/image-transform.jpg"
        srcset="./images/desktop/image-transform.jpg 720w"
        sizes="(min-width: 720px) 50vw, 100vw"
        alt="image-transform">
```

```css
.social-links__item path {
    fill: #2c7566;
    fill-rule: nonzero;
    transition: fill .3s ease-in-out;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Continued development

In the near future I will be focusing on css positioning, pseudo-elements and learning one css preprocessor (I am thinking about sass) in order to improve in css.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@SivaheraJ](https://www.twitter.com/sivaheraj)
