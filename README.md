# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### Screenshot

![](/assets/images/Screenshot_desktop_size.png)

![](/assets/images/Screenshot_mobile_screen.png)

### Links

- Solution URL: [GitHub repo](https://github.com/ivanorsolic95/recipe-page/)
- Live Site URL: [Check out my solution](https://recipe-page-my-solution.netlify.app/)

## My process

### Built with

- HTML5
- CSS custom properties
- Flexbox

### What I learned

I learned how to make tables using div elements to make them responsive.

```html
<div class="nutriton-container">
  <div class="nutriton-name">
    <span>Calories</span>
  </div>
  <div class="nutriton-value">
    <span>277kcal</span>
  </div>
</div>

<div class="nutriton-container">
  <div class="nutriton-name">
    <span>Carbs</span>
  </div>
  <div class="nutriton-value">
    <span>0g</span>
  </div>
</div>

<div class="nutriton-container">
  <div class="nutriton-name">
    <span>Protein</span>
  </div>
  <div class="nutriton-value">
    <span>20g</span>
  </div>
</div>

<div class="nutriton-container">
  <div class="nutriton-name">
    <span>Fat</span>
  </div>
  <div class="nutriton-value">
    <span>22g</span>
  </div>
</div>
```

```css
.nutriton-container {
  display: flex;
  font-family: "Outfit", sans-serif;
  color: var(--wenge-brown);
  border-bottom: 1px solid var(--light-grey);
  align-items: center;
  gap: 0.75rem;
}

.nutriton-name {
  width: 50%;
  margin-left: 1em;
}

.nutriton-value {
  grid-column: 2;
  width: 50%;
  font-weight: 700;
  padding: 0.5em;
  display: flex;
  align-items: center;
}

.nutriton-value > span {
  color: var(--nutmeg);
}

.nutriton-container:nth-last-of-type(1) {
  border: none;
}
```

## Author

- Website - [Ivan Orsolic](https://ivanorsolic.live/)
- Frontend Mentor - [ivanorsolic95](https://www.frontendmentor.io/profile/ivanorsolic95)
- Twitter - [orsolic_ivan1](https://x.com/orsolic_ivan1)
