# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

![](./screenshot.png)
![](./screenshot-mobile.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Flexbox
- CSS Grid

### What I learned

This challenge helped me test and implement my knowledge of CSS Grid. It also gave me a better understanding of responsive design. As someone who recently started learning CSS, it helped me test what I learnt in a hands on way. 
Here is some code I am proud of!

```css
  @media(max-width:768px){
      .price-grid{
          grid-template-columns: repeat(1, 1fr);
      }
      .top{
          grid-column: 1;
      }
      .bottom-one{
          border-bottom-left-radius: 0px;
      }
      .bottom-two{
          border-bottom-right-radius: 5px;
          border-bottom-left-radius: 5px;
      }
  }

```

### Continued development

I want to challenge myself more with complicated CSS Grid designs so I can become extremely well-versed with it.

## Author

- Frontend Mentor - [@ftmae](https://www.frontendmentor.io/profile/ftmae)
- GitHub - [@ftmae](https://github.com/ftmae)
