# NFT card component - Frontend Mentor

## Welcome! 👋

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Quick video demonstration 👩‍💻

https://user-images.githubusercontent.com/107133029/173848448-91c0014c-2c96-458a-8094-9879abdd0cd3.mov

## Table of contents

- [Overview](#overview)
  - [Links to the solution](#links-to-solution)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Lessons to remember](#lessons-to-remember)
- [Author](#author)

## Overview

### Links to solution

- Solution: [Solution on Frontend Mentor](https://www.frontendmentor.io/solutions/responsive-nft-card-component-using-css-flexbox-OYoGIzlii1) , [HTML](https://github.com/terka-codes/NFT-card-component/blob/main/index.html), [CSS](https://github.com/terka-codes/NFT-card-component/blob/main/styles.css)
- Live site: [here](https://terka-codes.github.io/NFT-card-component/)

### Screenshot

![NTF card Component](https://user-images.githubusercontent.com/107133029/173850161-1c842828-f37f-4fd4-bb91-009ce6aed971.png)


## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- A lot of Flexbox

### What I learned

Wow, this time, I struggled a lot. Even though it seemed really easy, it wasn't so much. I used a lot of flexboxes to make the website responsive and aligned as it should be. I knew how to use flexbox, but my knowledge was just basic. Now I am more comfortable using flexbox, and I can imagine how the attributes define my design. 

In this project, I started using more rem and em units to get used to them, but I still have a long way to go with getting the hang of them. 

I also learned how to do a picture overlay. It seemed impossible to do, but once I watched a tutorial, I found it relatively simple.

And most importantly, I learned I should do a mobile design first. I learned the hard way. This project was supposed to be my 3rd Frontend Mentor project, but it's the second because the one before that, I did the desktop design first, and then it seemed impossible to do the mobile version. So I started a new one before remaking it again.

This is the part with the overlay image. I am posting it here because I want to remember how to do that in the future.

```css
#card > #eq-img > a > #icon {
    position: absolute;
    top: 0;
    left: 0;
    background-color: hsl(178, 100%, 50%, 0.5);
    width: 100%;
    aspect-ratio: 1 / 1;
    border-radius: 1rem;
    display: flex;
    justify-content: center;
    align-items: center;
    opacity: 0;
}

#card > #eq-img > a > #icon:hover {
    opacity: 1;
}
```

I also struggled to make the footer not overflow the website, and this is how I made it stay at the bottom. 

```css
footer {
    background-color: hsl(216, 50%, 16%);
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 2em;
}

footer p {
    font-weight: 400;
    font-size: 1.1rem;
    color: hsl(0, 0%, 100%, 0.5);
}
```

### Lessons to remember

- Start mobile first! 📱
- Flexbox is a friend 🐶
- Overlay images aren't hard 😌
- Start learning Grid! 👩‍💻

## Author

- Frontend Mentor - [@terka-codes](https://www.frontendmentor.io/profile/terka-codes)
- Twitter: [@TerkaCodes](https://twitter.com/TerkaCodes)
