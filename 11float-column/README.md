![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 11*](https://www.digitalocean.com/community/tutorials/how-to-use-float-and-columns-to-lay-out-content-with-css) 
## How To Use Float and Columns to Lay Out Content with CSS

- Applying a float property to an element causes content to wrap around it. Adjusting the width will allow the content to wrap (floating elements still expand to natural wide of content, so you have to specify).

- If a floating item is large enough that it is causing the heading of the next section to wrap as well, this can be corrected by placing the *clear* property on the affected element in the next section. You can clear left, right, or both. Here, we did an example with a horizontal rule and by adding clear it appeared under the blockquote.

- Once you float elements, you can fine tune how they look by tweaking padding,  margins, and width.

- You can make your design responsive by using flexible width, resizable images, and media queries.

- Our example cause an image to float to the right at a specific screen width, and then at a larger screen size pull the image into the right side margin.

- It's important to set max-width to 100% on images so they can shrink into more restrictive spaces but not grow past actual size.

- You can pull images into white space by using negative margins on the image. This will pull it into the white space by the designated amount (which is the parent element's width, not the image width!).

- It's easy to set up columns with the column property. You can also specify column-gap and column-rule.

- Eliminating competing margins above a column requires you to address the column selector and the content selector...then set margin to zero.

- You can remove breaks inside column content by targeting the column class, content selector, and using the break-inside: avoid.

- You can create ordered lists in columns as you would anywhere.  You can style ordered lists with border, background color, etc. You can also add columns, column-gap, and margin within the ordered list!

- You may want to increase the number of columns for wider screen media queries to improve readability.
