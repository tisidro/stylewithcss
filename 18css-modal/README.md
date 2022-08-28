![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 18*](https://www.digitalocean.com/community/tutorials/how-to-use-opacity-and-transparency-to-create-a-modal-in-css) 
## How To Use Opacity and Transparency to Create a Modal in CSS

### What I learned and how it applies in my Github page example:

- A modal, a UI element (also known as a light box) appears in front of the rest of your page’s content with a trigger, like pushing a button to “open” it.
- The modal effect is a combination of the `opacity` and `pointer-events` properties and the `:target` pseudo-class.
- Showing and hiding elements is done by creating a `:target state` with `opacity`. 
- For example: this can be done by setting `opacity` to zero on .modal-container, and setting `opacity` to 1 on `.modal-container:target`, then creating id of “my-id” on `.modal-container` class and apply the id to href link on `button`, setting `pointer-events` to “none” on `.modal-container` you can make it invisible by default. 
- Then if you set `pointer-events` to “all” it will be visible when targeted.
- To cause a modal to fade in and out of view you can add a `transition property` to the `.modal-container`.
- The `transition` has three settings: transition property-- transition time --how to transition. Ease-in, one transition type—starts slow, speeds up , slows again
- Alpha channels create transparent color values. This is helpful for context as it allows users to see they are on a pop-up modal and the main content is behind the modal.
- Example:  background-color: `rgba(0,0,0,0.75)`. 
- The fourth number is the alpha channel, which works like the `opacity` property and is a decimal point value from 0 to 1. An adjustment to the alpha channel causes the color to become transparent.
- Hexadecimal color values consist of three pairs of a combination of 0 to 9 or a to f and equate to a number ranging from 0 to 255. 
- If you have a hex color such as `#f7baf7`, you can add a two-digit alpha channel to the end. 00 would be fully transparent. 2f is slightly less transparent. 44 would be more opaque.
- 
- Example: `box-shadow: 0 1rem 2rem #000a` creates drop shadow on modal, but softens it with alpha channel a (short for aa--numerical value of 170 or 66% transparency.) This makes shadow more subtle but still useful to provide depth.
- The `color: transparent` property and value keeps text from rendering on a page
- You can create an X shape using only `linear gradient()` as follows:
```
.modal-close {
  color: transparent;
  display: block;
  height: 1.5rem;
  width: 1.5rem;
  overflow: hidden;
  background-image:
    linear-gradient(
      to top right,
      transparent 48%,
      white 48%,
      white 52%,
      transparent 52%
    ),
    linear-gradient(
      to top left,
      transparent 48%,
      white 48%,
      white 52%,
      transparent 52%
    );
}
```
- Transition animations that appear to be a gradient animation can be created on a button (or other element) with the use of the `transparent` and alpha channel color values.
- Just set up a new background gradient that differs from what you have on the buttons, then add a transition to it. The gradient will change from one style to the other when you hover over it.
