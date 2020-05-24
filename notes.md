# Advanced CSS and Sass: Flexbox, Grid, Animations and More! Notes

## Section 2

### Lecture 6:

**Topics:**

- basic reset using universal selector

- project wide font definitions

- clip parts of elements using clip-path

clip-path: polygon(x y, x y, x y, x y);  
x is horizontal, y is vertical. y is positive down the page.  
img coordinates start at top left and go clockwise  

generate clip-path: https://bennettfeely.com/clippy/  

To make a triangle:  
 
clip-path: polygon(50% 0, 50% 0, 100% 100%, 0 100%);  

### Lecture 7

**Topics:**

- center anything with transform, top and left properties

```
 position: absolute;
 top: 50%;
 left: 50%;
 transform: translate(-50%, -50%);
```

### Lecture 8

**Topics:**

- CSS animations using @keyframes and animation property

```
 animation-name: moveInLeft;
 animation-duration: 1s;
 animation-timing-function: ease-out;
 /* animation-delay: 3s; */
 /* animation-iteration-count: 3; */

 @keyframes moveInLeft {
 0% {
   opacity: 0;
   transform: translateX(-100px);
 }

 80% {
   transform: translateX(10px);
 }

 100% {
   opacity: 1;
   transform: translate(0);
 }
}
```

### Lecture 9

**Topics:**

- what pseudo-element and pseudo-classes are
- how and why to use ::after pseudo-element
- hover animation using transition

transition goes on the initial state, so .btn:link,
.btn:visited

then the transforms will follow the transition properties.

### Lecture 10

**Topics:**
