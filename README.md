# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Stats preview card component solution](#frontend-mentor---stats-preview-card-component-solution)
  - [Table of contents](#table-of-contents)
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

- View the optimal layout depending on their device's screen size

### Screenshot

![Stats Preview Card Component](./preview.jpg)

### Links

- Solution URL: [FM](https://www.frontendmentor.io/solutions/responsive-stats-preview-card-using-tailwind-css-and-css-variables-2N5U3nX8h7)
- Live Site URL: [Live Site](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- Tailwind CSS

### What I learned

This project helped me strengthen my skills in responsive design and working with CSS custom properties alongside Tailwind CSS. Here are some key takeaways:

1. **Combining Tailwind CSS with CSS variables** for custom color schemes:
```css
<style type="text/tailwindcss">
  @theme {
    /* Primary Colors */
    --color-navy-950: hsl(233, 47%, 7%); /* main background */
    --color-blue-950: hsl(244, 37%, 16%); /* card background */
    --color-purple-500: hsl(277, 64%, 61%); /* accent color */
  }
</style>
```

2. **Creating responsive image overlays** with blend modes:
```html
<div class="relative w-full h-60 xl:w-1/2 xl:h-auto xl:self-stretch rounded-t-lg xl:rounded-l-none xl:rounded-r-lg overflow-hidden bg-[url('./images/image-header-mobile.jpg')] md:bg-[url('./images/image-header-desktop.jpg')] bg-cover bg-center bg-no-repeat">
  <div class="absolute inset-0 bg-purple-500 mix-blend-multiply"></div>
</div>
```

3. **Implementing mobile-first responsive layouts** with Tailwind's breakpoint system:
```html
<div class="flex flex-col md:flex-row gap-6 md:gap-25 items-center text-center md:text-left">
```

### Continued development

In future projects, I want to focus on:

- Improving accessibility features, particularly for screen readers
- Exploring more advanced CSS Grid layouts
- Implementing CSS animations and transitions for interactive elements
- Optimizing performance for different screen sizes and devices

## Author

- Frontend Mentor - [@Joseph-Abdullaah](https://www.frontendmentor.io/profile/Joseph-Abdullaah)