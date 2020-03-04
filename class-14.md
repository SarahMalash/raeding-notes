# read 14 a:
## Transforms:
 transform property comes in two different settings, two-dimensional and three-dimensional. Each of these come with their own individual properties and values.
 Transform Syntax: 
 1.  transform property
 2.  the value:  specifies the transform type
 3. specific amount inside parentheses.

## 2D Rotate:
 The rotate value provides the ability to rotate an element from 0 to 360 degrees.
*positive value*: will rotate an element clockwise.
*negative*: value will rotate the element counterclockwise.
*The default point of rotation is the center of the element*
## 2D Scale:
The default scale value is 1, therefore any value between .99 and .01 makes an element appear smaller while any value greater than or equal to 1.01 makes an element appear larger.
## 2D Translate:
change the position of an element on the horizontal axis while using the translateY value will change the position of an element on the vertical axis.
*As with the scale value, to set both the x and y axis values at once, use the translate value and declare the x axis value first, followed by a comma, and then the y axis value.*
## 2D Skew: 
is used to distort elements on the horizontal axis, vertical axis, or both. The syntax is very similar to that of the scale and translate values.
## Combining Transforms:
 To combine transforms, list the transform values within the transform property one after the other without the use of commas.
 ## Transform Origin:
 property can accept one or two values. When only one value is specified, that value is used for both the horizontal and vertical axes. If two values are specified, the first is used for the horizontal axis and the second is used for the vertical axis.
 ## Perspective:
 Using the perspective value within the transform property works great for transforming one element from a single, unique perspective. When you want to transform a group of elements all with the same perspective, or vanishing point, apply the perspective property to their parent element.

 # Transitions & Animations:
 ## Transitions:
  an element must have a change in state, and different styles must be identified for each state. The easiest way for determining styles for different states is by using the :hover, :focus, :active, and :target pseudo-classes.

  Transitional Property: determines exactly what properties will be altered in conjunction with the other transitional properties.
## Transitional Properties:
ot all properties may be transitioned, only properties that have an identifiable halfway point. Colors, font sizes, and the alike may be transitioned from one value to another as they have recognizable values in-between one another. 
## Transition Duration:
The duration in which a transition takes place is set using the transition-duration property. 
## Transition Delay:
 The delay sets a time value, seconds or milliseconds, that determines how long a transition should be stalled before executing.
 ## Shorthand Transitions:
 t every transition value in the order of transition-property, transition-duration, transition-timing-function, and lastly transition-delay. Do not use commas with these values unless you are identifying numerous transitions.
 # Animations:
 ## Animations Keyframes:
 To set multiple points at which an element should undergo a transition, use the @keyframes rule. The @keyframes rule includes the animation name, any animation breakpoints, and the properties intended to be animated.
 Animation Name:  for an animation have been declared they need to be assigned to an element. To do so, the animation-name property is used with the animation name, identified from the @keyframes rule, as the property value. The animation-name declaration is applied to the element in which the animation is to be applied to.

 #  8 really simple effects that will add life to your UI:
 1. Fade in: draw attention to a call to action
 2. Change color.
 3. Grow & Shrink.
 4. Rotate elements.
 5. Square to circle.
 6. 3D shadow.
 7. Swing.
 8. Inset border.











 






















