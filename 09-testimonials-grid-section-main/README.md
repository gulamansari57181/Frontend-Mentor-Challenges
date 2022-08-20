# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- Pure CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

About CSS Grid and its functioning

```css
/* main-container */

.grid-col-span-2 {
  grid-column: span 2;
}

.grid-testimonial {
  min-height: 100vh;
  width: 100%;
  padding: 1em 4em;
  background-color: hsl(210, 46%, 95%);
  display: grid;
  gap: 1.5em;
  grid-template-columns: 1fr 1fr 1fr 1fr;
}

/* To position last tetimonial smartly */

.testimonial:last-child {
  grid-column: 4;
  grid-row-start: 1;
  grid-row-end: 3;
}
```

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

## Author

- Linkedin - [Follow me on linkedin](https://www.linkedin.com/in/mohd-gulam-ansari-4950601a0/)
- Frontend Mentor - [@gulamansari57181](https://www.frontendmentor.io/profile/yourusername)
