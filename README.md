# CSS3_Transition
CSS transitions allows you to change property values smoothly (from one value to another), over a given duration.  Example: Mouse over the element below to see a CSS transition effect:

How to Use CSS Transitions?
To create a transition effect, you must specify two things:

the CSS property you want to add an effect to
the duration of the effect
Note: If the duration part is not specified, the transition will have no effect, because the default value is 0.

The following example shows a 100px * 100px red <div> element. The <div> element has also specified a transition effect for the width property, with a duration of 2 seconds:

div {
  width: 100px;
  height: 100px;
  background: red;
  -webkit-transition: width 2s; /* Safari */
  transition: width 2s;
}

Change Several Property Values
The following example adds a transition effect for both the width and height property, with a duration of 2 seconds for the width and 4 seconds for the height:

div {
  -webkit-transition: width 2s, height 4s; /* Safari */
  transition: width 2s, height 4s;
}
