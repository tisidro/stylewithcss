![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 8*](https://www.digitalocean.com/community/tutorials/how-to-use-links-and-buttons-with-state-pseudo-classes-in-css) 
## How To Use Links and Buttons with State Pseudo-Classes in CSS.
## What I learned and how it applies in my Github page example:

- Pseudo-classes allow changes in state to initiate style changes.

- Pseudo-classes are indicated by writing selector:pseudo-class.

- The selector:hover pseudo-class  displays an alternative style when the cursor hovers on an element. It gives a cue that this is an element you can interact with and you are passing over it.

- The selector:focus pseudo-class  displays an alternative style when an element has "focus" or a user has tabbed over to it. This is important for accessibility to allow people to know where they are when navigating with a keyboard. Make sure the style change is noticeable to the user!

- The selector:active pseudo-class  displays an alternative style when the user successfully interacts with the element. For example, if a user has clicked the mouse, active can allow a color change that gives a cue that the click occurred.

- The selector:visited pseudo-class indicates to the user that they previously interacted with an element. For example, if a user has clicked a link visited can allow a color change that gives a cue to the user they already clicked the link previously in their session. This can be a bit distracting with a button, so it's best to group visited and hover pseudo-classes together on buttons. That way, you don't leave a button text with an odd color after clicking it (unless you really want to!).

- The selector:transition pseudo-class  allows you to blend and animate the styles from one state to the next state so the changes are not abrupt.
This pseudo-class combines the transition-property, transition-duration, and transition-timing-function properties. 

- For transition-property, you can use "all" to specify all properties that change between the states or specify one property. Duration indicates how long the transition lasts. Transition-timing-function controls how the animation will play out over time, enabling you to make subtle changes to enhance the animation.

- A transition-timing-function set to linear tells the browser to move from one value to the next in a constant increment throughout the duration. n contrast, value of ease-in-out will create an animation that starts off slow, speeds up in the middle, and slows down to the end. This feels more snappy and natural.
