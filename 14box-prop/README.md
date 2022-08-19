![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 14*](https://www.digitalocean.com/community/tutorials/how-to-use-the-display-property-to-manipulate-the-box-model-in-css) 
## How To Use the Display Property to Manipulate the Box Model in CSS

### What I learned and how it applies in my Github page example:

- The display property on a selector can be set to `display: block` or `display: inline`.

- *Block elements* create defined areas of content that take up the full width of the parent container. 

- They are usually rendered by themselves on a new line, so added block elements stack toward the end of the page. 

- For a top-to-bottom, left-to-right language like English, block elements stack toward the bottom of the browser window.

- *Block elements* define the meaning and group of content, like a paragraph.

- *Inline elements* exist within the flow of text content, do not take up the entire width of their parent, and are NOT rendered on their own lines.

- They are added in the direction of the text flow. For English, this is a left-to-right direction.

- *Inline elements* provide context about a word or group of words, such as an emphasis.

- Block elements break the current content flow, inline elements maintain it.

- If you add a width to an inline element it would not change the layout.

- When a block element disrupts the content flow it “stays broken” and  takes up the entire parent container width.

- The `inline-block` element condenses down to only the width of its content.

- To make tables more readable on small devices,  you can set td (table cells) to `display:block`. This causes each cell to stretch to width of parent container and makes it easy for users to just keep scrolling down to see more.

- When working with tables, upon shrinking you what works better than headings is adding label classes to specify headings and setting them to `display:none` for large screens and `display:inline` for small screens. This is an easy “small-screen” heading for tables technique!

- Another nice context element for small screen tables is to make them appear like their own small tables for readability. Some tips:

    - Use a `tbody th` descendant selector and distinguish it with color.

    - You can also define data sets (like Mercury, Venus, etc) with border by selecting table rows with parent of tbody and applying border all around

    - add some space to table body groupings with adjacent sibling combinator for `tr:  tbody > tr + tr`

    - Go for the striped effect by giving even td (data cells) a different color!  `td:nth-child(even)` and specify a background color.
