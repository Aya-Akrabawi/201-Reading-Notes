## Read: 14a - CSS Transforms, Transitions, and Animations

**CSS Transforms**:
Transforms allows you to rotate, scale, move, and skew elements. 
```
div {
   width: 200px;
   height: 100px;
   margin-top: 30px;
   background-color: #32CD32;
}
```

**CSS Transitions:**
Transitions allows you to animate from one CSS property value to another. you can combine it with transforms and animate the element position, rotation, or scale.

- transition-property - specifies the property to be transitioned
```
div {
   width: 50px;
   height: 50px;
   background: #32CD32;
   transition: width 3s;
}
div:hover {
   width: 250px;
}
```
- transition-duration - specifies the duration over which transitions should occur
- transition-timing-function - specifies how the pace of the transition changes over its duration
```transition-timing-function: cubic-bezier(0,0,1,1);```
- transition-delay - specifies a delay (in seconds) for the transition effect


**CSS Animations:**
Animations! the property which attract the most attention, Animations have their own specifications, and they allow us to create keyframes, set duration, easing, and more.
```
div {
   animation-name: colorchange;  
   animation-duration: 5s;
}
@keyframes colorchange {
   from { width: 0px; }
   to { width: 100px; }
}
```
these new features came with **CSS3**