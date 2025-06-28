# Frontend Mentor - Product preview card component solution

This is my solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). This project helped me practice responsive layouts, flexbox, and semantic HTML.

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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements (like the button)

### Screenshot

<!-- Screenshot will be added soon -->

### Links

- **Solution URL:** [Frontend Mentor Solution Page](https://www.frontendmentor.io/solutions/your-solution-link)
- **Live Site URL:** [Live Preview](https://your-live-site-url.netlify.app)

## My process

### Built with

- Semantic HTML5
- CSS custom properties (variables)
- Flexbox
- Mobile-first workfl
- Media queries

### What I learned

This project helped reinforce:

- **How to use `flex-direction: column` on mobile and switch to `row` using media queries**
- Setting responsive images with `<picture>` and `srcset`
- Using `object-fit: cover` to make an image fill its container without distortion
- Centering with `min-height: 100vh` and `display: flex`

Here’s a snippet I’m proud of:
```css
@media (min-width: 37.5rem) {
  .product {
    flex-direction: row;
  }

  .product__img img {
    height: 100%;
    object-fit: cover;
  }
}
```
### Continued development

In the future, I’d like to:

- Improve my grid layout skills
- Practice more with responsive typography and `clamp()`
- Build more reusable components using utility-first CSS or a framework

### Useful resources

- [MDN Web Docs - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/flexbox) – Great reference for layout behavior
- [Frontend Mentor Discord](https://discord.gg/frontendmentor) – Helpful community for feedback and advice

## Author

- Name – **Abdul Subhan**
- Frontend Mentor – [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- GitHub – [@yourusername](https://github.com/yourusername)

## Acknowledgments

Thanks to the Frontend Mentor community and [Kevin Powell](https://www.youtube.com/@KevinPowell) for CSS tips and layout tutorials!
