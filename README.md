# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#product-preview-card)
  - [Links](#links)
  - [Built with](#vs-studio)
  - [What I learned](#scaling)
- [Author](#koragami)

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- GSAP

### What I learned

I learned more about using clamp to avoid so many @media uses and scale it for every device especially em and rem (I found em to work the best)

```css
body {
  width: clamp(30vw, min(50vw, 40em), 75vw);
}
```

## Author

- Frontend Mentor - [@koragami](https://www.frontendmentor.io/profile/yourusername)
