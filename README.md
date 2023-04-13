# Frontend Mentor - Product preview card component solution

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
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements

### Screenshot

![](desktop-screenshot.png)

### Links

- Solution URL: (https://github.com/rrebolledo90/product-preview-card.git)
- Live Site URL: [Add live site URL here](https://rrebolledo90.github.io/product-preview-card/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- CSS Grid

### What I learned

````css
@media only screen and (max-width) {
   This is my first experience working with media queries. Learned that this can be used to adapt your website on screen size across various devices. This can be overused, therefore it's important to make your site as reponsive as possible, however, @media can be very helpful.
}: 
  
```css 
.background-image: url {
} 

````css
display:grid: First time using grid, finding it helpful to position items. 


### Continued development

This was challenging but also a fun little project. It took a little longer than I anticipated. When I first looked at the challenge I thought it would be fairly easy as I thought I only had to create a desktop version, but little did I know the challenge also needed to be responsive to various screen sizes. As a result, I had to research a few new concepts that I was not familiar with such as rem and em. The most time consuming was the @media queries. I finally got that to work. When I adapt the screen size to below 600px, the layout changes from a horizontal to vertical landscape, which I think is really cool. If you look closely, you will notice that the bottom left mobile background image is rounded. I am not sure why, but I did not specify this in my @media code. I think it is inheriting this from horizontal landscape code, I could not figure out how to resolve this. I also had to use flexbox with my vertical landscape because the grid display I originally used was being overridden, when I looked closer I noticed that the width was changing to my desktop.jpeg image, which was shifting my mobile.jpeg image. I could not figure out how to solve this as well. I think It might have to do with some inheritance, but I was able to fix it by utilizing flexbox.


### Useful resources

- (Dev Dreamer) - YouTube channel, gave me more information on media queries and also background images.
- [Keven Powell] - YouTube channel, helped me understand background images a little more, and also responsive units. 
