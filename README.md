# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](./image.png)
![](./image2.png)

### Links

- Solution URL: [Add solution URL here](https://github.com/denissoboslai13/frontend-mentor-product-review/blob/main/index.html)
- Live Site URL: [Add live site URL here](https://denissoboslai13.github.io/frontend-mentor-product-review/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid
- Tailwind CSS

### What I learned

I learned how to set up different structure on different screen sizes, flexbox on mobile, grid on the desktop, and also how to use the picture tag, which was one thing before i started where i went, "How do i even do that?", but it ended up being quite simple.

```html
<picture class="-ml-8 -mr-8 mb-8 sm:mr-0 sm:mb-0 sm:ml-0">
  <source media="(min-width:640px)" srcset="images/image-product-desktop.jpg" />
  <img src="images/image-product-mobile.jpg" class="block w-full h-full" />
</picture>
```

### Continued development

I want to keep working with flexbox and grid, using grid made my life so much easier on the desktop design, but styling pictures still feels a bit foreign to me, so i want to focus on that.

### Useful resources

- [Tailwind CSS](https://tailwindcss.com/) - Still just tailwind docs, obviously massively helpful.
- [W3Schools picture tag](https://www.w3schools.com/tags/tag_picture.asp) - This helped me explain how the picture tag works and how to use different images for different screen sizes.

### AI Collaboration

Once again, sadly I did have to use Claude for some help, when working with the picture tag this strange white box kept appearing at the bottom of my page, which was due to some mismatched styling, but other than that i try to stay far away from AI for this project.

## Author

- Frontend Mentor - [@denissoboslai13](https://www.frontendmentor.io/profile/denissoboslai13)
