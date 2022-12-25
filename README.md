# Frontend Mentor - NFT preview card component solution

This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
- [The challenge](#the-challenge)
- [Links](#links)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)

## Overview

Build an NFT preview card component.

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Links

- Solution URL: [https://github.com/jrc17/nft-preview-card-component-main]
- Live Site URL: [https://jrc17.github.io/nft-preview-card-component-main/]

### Built with

- HTML
- CSS
- Flexbox

### What I learned

I learn how to create the hover effect over an image.

```css
.images {
  position: relative;
}
.images::before {
  content: "";
  display: block;
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: #00fff7;
  border-radius: 8px;
  opacity: 0;
}
.images:hover .nft-view-image {
  opacity: 1;
}
.images:hover::before {
  opacity: 0.5;
}
.nft-image {
  width: 100%;
  height: 100%;

  align-self: center;
  border-radius: 8px;
}
.nft-image:hover {
  cursor: pointer;
}
```

### Useful resources

- https://www.youtube.com/watch?v=6-QoF1qY9Bw - I learnt how to make hover effect over an image from this video

## Author

- Frontend Mentor - [@jrc17](https://www.frontendmentor.io/profile/jrc17)
