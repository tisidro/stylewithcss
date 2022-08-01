![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 2*](https://www.digitalocean.com/community/tutorials/how-to-select-html-elements-to-style-with-css) 
## How To Select HTML Elements to Style with CSS.

## What I learned and how it applies in my Github page example:

Through this tutorial I learned how to set up the HTML for a page with elements to style it. There are relationships between elements such as parent-child or siblings.  

An **element selector** (also called 'type selector')  finds elements on a page by their tag names (body, h2, strong, etc.), and has the broadest specificity. 

**Combinator selectors** find more specific selections than an element selector. The combinator selector uses the nested relationships of HTML elements to select a designated element.  In our example, we saw two elements separated by a space.  The element farthest to the right is the intended target of the specified style. 

**Selector groups** allow for use of the DRY (Don't Repeat Yourself) principle that makes code easier to maintain.

 Using a **selector group**, you can consolidate selectors that have the same property and value in a selector block. This is done by placing a comma between selectors (i.e--  h2, h3) indicating that the style is to be applied to all listed. It is more clear if you write each selector on its own line.

**Selectors and combinators** can even be combined. For example, you can have a style applied to h1, h2 ol strong. This applies it to both the heading elements as well as any strong tags found in ordered lists.
