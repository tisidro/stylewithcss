![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 6*](https://www.digitalocean.com/community/tutorials/how-to-lay-out-text-with-css) 
## How to Lay Out Text With CSS.
## What I learned and how it applies in my Github page example:

*These notes are a bit longer, but I intend to refer back to them for projects!* :)

You can make line lengths more readable with width/max-width properties. By setting **width to 90% and adding margin: 0 auto you can center the content block** in the middle of the page which is better on the eye.

To control the line length --optimum length is 45-75 characters so go with about 70-- you use the **character or ch unit** for the **max-width**. That specifies the **maximum number of characters to which a line can grow**.

Setting the **line-height property** in text elements like the .body selector provides a default distance between lines for the entire document. A comfortable value for readers is 1.5. You can **use a smaller line height like 1.15 to help readability** of long headers (keep text more together). If you give line-height no units, the default behavior is to multiply the value by the font-size (responsive!).

The **margin property** can be used to apply different vertical spacing between content elements. For example, if you add margin values in em to an h3, it applies spacing relative to the context font size. If you have margin: 2em 0 0.5em it will provide double the font-size for top margin, 0 for right and left margins, and half the font size for the bottom margin. Remember that p elements have a default top margin you  may need to set to 0 when working with headers.

You can set **text-align** to center text, but it's better to have it set to default for user customization. Use with discretion.

Two properties can really help with legibility: **text transform** controls how capitalization is formatted (uppercase, lowercase, capitalize), and **letter spacing** controls space between characters.


