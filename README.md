# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Social links profile solution](#frontend-mentor---social-links-profile-solution)
  - [Table of contents](#table-of-contents)
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
- View a responsive profile card that contains social links.
- Hover over buttons to see interactive state changes.
- Open respective social links in a new tab when a button is clicked.

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [GitHub Repository](https://github.com/dantvi/social-links-profile)
- Live Site URL: [DT Code](https://social-links-profile.dtcode.se/)

## My process

### Built with

- Semantic HTML5 markup: For a well-structured and accessible layout.
- CSS custom properties: Simplified theme management with variables.
- Flexbox: Used for layout alignment and centering elements.
- JavaScript: Added interactivity for button functionality to open links.
- Mobile-first workflow: Ensured design is responsive across devices.

### What I learned

This challenge allowed me to refine my skills in:
- Hover States: 
  - Creating engaging hover effects using CSS transitions.
- Responsiveness: 
  - Adjusting component dimensions with media queries for an optimal user experience.
- Component Design:
  - Creating a reusable profile card structure that can be easily modified for different users.
- JavaScript Interaction:
  - Implementing the openLink() function for dynamic button functionality. 

```js
function openLink(webpage) {
    window.open(webpage);
}
```

### Continued development

In future projects, I plan to:
- Explore additional interactive elements, such as hover animations.
- Focus on accessibility improvements, such as ensuring keyboard navigation works seamlessly.
- Integrate API-based profile data to dynamically populate user information.

### Useful resources

- [MDN Web Docs: Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout) - Helpful for centering and aligning elements.
- [CSS Tricks: Transitions](https://css-tricks.com/almanac/properties/t/transition/) - Guided the implementation of hover effects.

## Author

- Frontend Mentor - [@dantvi](https://www.frontendmentor.io/profile/dantvi)
- GitHub - [@dantvi](https://github.com/dantvi)
- LinkedIn - [@danieltving](https://www.linkedin.com/in/danieltving/)

## Acknowledgments

Thanks to Frontend Mentor for providing this creative challenge. The clear design and requirements allowed me to focus on refining my front-end skills and experimenting with interactive JavaScript elements.
