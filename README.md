# Frontend Mentor - Equalizer landing page solution

This is a solution to the [Equalizer landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/equalizer-landing-page-7VJ4gp3DE). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
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
- See hover states for interactive elements


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow


### What I learned

Working on this project helped me identify areas in which I need to improve in terms of time management. Setting strict deadlines leads to better results.
The second "a-ha" moment came when I attempted to use custom properties. I didn't use them frequently, but I'm glad I used them every now and then.
Another thing I had to figure out was how to use relative position and design to replicate nearly the same layout.
The last but not the least aspect of this project was to make icons change color when hovered over.
This project was a lot of fun for me.

Here are some snippets of code:

```html
<h2 class="fs-700">Premium EQ</h2>
```
```css
.mobile-image {
    width: 270px;
    height: 555px;
    position: relative;
    top: -155px;
    left: -200px;
  }
```
```css
.social-icon:hover {
    cursor: pointer;
    filter: invert(73%) sepia(55%) saturate(591%) hue-rotate(327deg) brightness(106%) contrast(102%);
    -webkit-filter: invert(73%) sepia(55%) saturate(591%) hue-rotate(327deg) brightness(106%) contrast(102%);
  }
```


### Continued development

When the opportunity arises, I would like to continue using the filter property to match the color of the image, background, or border that needs to be changed to the layout.


### Useful resources

- [Example resource 1](https://css-tricks.com/almanac/properties/f/filter/) - This helped me for figuring out how tochange the icons color. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.youtube.com/watch?v=lRaL-8qZ0mM&t=3098s) - This is an amazing video which helped me finally understand custom properties and utility classes. I'd recommend it to anyone still learning this concept.


## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)


