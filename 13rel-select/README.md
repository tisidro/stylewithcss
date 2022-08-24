![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 13*](https://www.digitalocean.com/community/tutorials/how-to-use-relationships-to-select-html-elements-with-css) 
## How To Use Relationships to Select HTML Elements with CSS

### What I learned and how it applies in my Github page example:

- Descendant combinators are space-separated lists of selectors that matches the HTML structure in order to apply styles to elements with a particular ancestor.

- The last selector is the one that receives the style.

- The easiest way to scope a style is with a descendant combinator.

- Scoping a style provides additional details to increase the specificity of a selector.

- Example: the descendent combinator “header a” will select only a tags that are found in a header element.

- You can select more than one descendant combinator by separating them with a comma: .descendant `p, .child p.` Usually additional descendant combinators go on a separate line.

- Child combinator selectors style only the children of a given parent.

- To select only the direct child of a class, the parent selector is followed by the greater-than sign (>) and then the child selector.

- Example:  `.child > p`  selects only p elements that are a direct child of the .child class.

- The general sibling combinator scopes styling to elements following a specific element and having the same parent element, but which may not be next to each other.

- You can write styles for the sibling `<p>` elements that come after another `<p>` element of the same parent by writing a selector followed by a tilde (~) and the selector of the sibling you wish to style.

- Examples: `.general-sibling p ~ p` or `.general-sibling div ~ p`.

- To apply a style when two elements are adjacent in the html use the adjacent sibling combinator.

- A first-child pseudo-class selector is indicated by appending :first-child directly after the element. For example,  `li:first-child`.

- A last-child pseudo-class selector is indicated by appending :last-child directly after the element. For example,  `li:last-child`.

- The only-child pseudo-class selector applies styles when there is only one child element. If you have first and last child, those styles can over-write each other with an only child element. Example: `li:only-child`.

- You can set patterns for selecting child elements with the nth-child pseudo-class selector.

- This selector targets HTML elements by a given numerical position within their parent. 

- The nth-child pseudo-class is useful for creating stripe effects.  You can specify an odd or even input and style an element using this pseudo-class. Example: `li:nth-child(even)`.

- Similarly you can specify an actual number and apply that effect one to that `child: li:nth-child(4)`. This is good for highlighting effects.
