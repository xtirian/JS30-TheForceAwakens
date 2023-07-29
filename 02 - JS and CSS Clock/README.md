# JS - Clock

This is a solution from [JS + CSS Clock Challenge](https://javascript30.com/). JavaScript30 is a chain of challenges that help you improve your coding and problem solving skills with JS.

## Table of contents

- [Overview](#overview)
- [Screenshot](#screenshot)
- [Links](#links)
- [My process](#my-process)
- [Built with](#built-with)
- [What I learned](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)

## Overview

A clock builded with CSS and animeted with JS

### Screenshot

![](./Screenshot.png)

### Links

- Solution URL: [Git Repository](https://github.com/xtirian/JS30-TheForceAwakens/tree/main/02%20-%20JS%20and%20CSS%20Clock)
- Live Site URL: [🔥 JS Drum Kit](https://js-clock-rust.vercel.app/)

## My process

### Built with

- JavaScript
- transform-origin, transform, trasition and trasition-timing-function
- DOM Manipulation

### What I learned

In this project I noted that we needed to do 3 things:

- Get the time
- calculate what degree it correspond to the actul time
- DOM Manipulating to set the time in the screen

The first thing I learned was the "transform-origin" attribute.

```css
.hand {
  transform-origin: 100%;
}
```
it allows you to change the axle of the transformation in this element for his end, so the rotation axle will be the center of the clock. Without it, the element rotates in it self, because the default is the origin in 50%

The next thing was the transition-timing-function, that gives you differents types of animation during the trasition. I should remember this propoerty so I could use when animating an progress bar

In the script, it was pretty easy to get the results. Just a remider, when you are using "getElement" or "querySelector", that could return more the one element, the system will return as a node list or an array EVEN if there is only one element to return. So you have to put the "[0]" to define that you want the first element not the array.


### Useful resources

## Author

- Linkedin - [Clique aqui](https://www.linkedin.com/in/mf-cunha/x)
- GitHub - [Clique aqui](https://github.com/xtirian/)

