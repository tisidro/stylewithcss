![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 20*](https://www.digitalocean.com/community/tutorials/how-to-style-figure-and-image-html-elements-with-css) 
## How To Style Common Form Elements with CSS

### What I learned and how it applies in my Github page example:

- HTML form structure consists of inter-connected attribute values in order to function correctly.
- To learn more about how to structure forms in HTML, see the [Mozilla Web Docs page on web form structure](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form).
- Form styling can be reset with the `appearance` property by setting `appearance: none` on the form properties. 
- You can use a group selector as follows:
    ```
    button,
	fieldset,
	input,
	legend,
	select,
	textarea {
  	    appearance: none;
	} 

    ```
- most browsers still require a vendor prefix added to the property name to property apply properties to future browser versions. 
- A vendor prefix is a special coded addition prepended to the property name as an identifier for a specific browser. 
- For Chrome, Safari, and recent versions of Edge and Opera, that prefix is `-webkit-`. Firefox uses the `-moz-` prefix.
- It’s helpful to add consistent structure to data entry elements (font, padding, etc).
- You can also add extra height to text area to make it easier for the user to see/keep track of what they are entering.
- For an element selector, you can specify an image indicating a drop-down action as follows:
    ```
	select {
  	background: url("images/down-arrow.svg") no-repeat center right 0.75rem;
	}
    ```
- Adding `radio` buttons and checkboxes is achieved through the input[type=“ “]
- Example: 
    ```
    input[type="radio"],
	input[type="checkbox"] {
  	height: 1.5em;
  	width: 1.5em;
  	vertical-align: middle;
	}

	input[type="radio"] {
  	border-radius: 50%;
	}
    ```
- Setting the border radius as above to 50% with an equal width/height value creates a circular `radio` button.
- Filled-in `radio` buttons are styled as follows:
     ```
     input[type="radio"]:checked {  
        background-image: radial-gradient(  hsl(213, 73%, 50%) 40%,   transparent calc(40% + 1px)  );
        }
     ```
- `Labels` and `legends` can be added to describe to form elements. CSS can be used to make this text small or large and further customize it.
- The `:placeholder` pseudo-element is used to provide placeholder content on an input or text area element. This provides users with a visual of what type of info is being requested and its format. This is helpful to standardize input you want to collect from the form.
- In forms buttons are used to submit or reset. It is important to clearly distinguish these for users.
- Adding hover states, pointers, and adding/removing `text-decoration` on `button` link upon `hoover` to draw attention can help with this.
- The `:focus pseudo-class` can help the user to know what field they are currently working on.
- The `outline` property is used by browsers by default to indicate elements that have focus, but sometimes this isn’t noticeable enough or doesn’t work with other design aspects.
- Use outlines and/or box-shadows with `:focus` to create better indication that field or button is in use.
