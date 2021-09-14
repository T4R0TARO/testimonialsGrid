# Frontend Mentor - Testimonials grid section solution

This is a solution to the [Testimonials grid section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/testimonials-grid-section-Nnw6J7Un7). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)




## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot
![image](https://user-images.githubusercontent.com/76195521/133347544-af117b90-6ce9-4ec7-a49a-daba7904d82e.png)
![image](https://user-images.githubusercontent.com/76195521/133347594-73257f16-5dd9-4aca-a615-3f9c99f06aaa.png)



### Links

- Solution URL: [Git Repo](https://github.com/T4R0TARO/testimonialsGrid)
- Live Site URL: [Git Pages](https://t4r0taro.github.io/testimonialsGrid/)

## My process

1. Prep HTML structure for layout 
2. Mobile First (Layout) 
3. Desktop (Layout)
4. Mobile Styles
5. Desktop Styles
6. Review padding and margin

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

First time implementing order with flex box and grid. Change the order of the cards when page grow to desktop size
```css
    .item3 {
    background-color: var(--white);
    order: 1;
  }

    @media screen and (min-width: 1100px){
    .gridWrapper {
      display: grid;
      height: 100vh;
      grid-template-columns: repeat(4, 1fr);
      grid-auto-rows: minmax(300px, auto);
      max-width: 1446px;
    }
    .item3 {
     grid-row: span 2;
     order: 0;
    }
```

### Continued development

To get more grid practice: develop a tablet version and reorder the grid or shift the cards to a different layout


## Author

- Website - [Joshua Manansala](https://github.com/T4R0TARO)
- Frontend Mentor - [@T4R0TARO](https://www.frontendmentor.io/profile/T4R0TARO)
- Twitter - [@taro_code](https://twitter.com/taro_code)

