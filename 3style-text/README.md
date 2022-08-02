![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 3*](https://www.digitalocean.com/community/tutorials/how-to-style-text-elements-with-font-size-and-color-in-css) 
## How To Style Text Elements with Font, Size, and Color in CSS.

## What I learned and how it applies in my Github page example:

In HTML there is a **clear content hierarchy** that is provided by heading tags. The h1 is by default largest, and there should only be one of these in a document. The h6 is much smaller than h1, but there may be many of these. A heading under a higher one can only be one lesser, equal, or any greater level than that previous heading. Default h5 and h6 text is smaller than p text. Color and space also provide a hierarchy of content.    

A font can have different **font weight and font style**, but still be a part of its family. A browser will look for a specific font, but  if it doesn't find it the **font stack** comes into play. The font stack is like a fallback system. It is a list of fonts that the browser uses to apply fonts to different elements. If a browser can't find any of the fonts in a font stack, it will use the last font on the list: sans serif (the browser default).

**Google Fonts** provides many fonts to download and load on your computer. When you select a font style, you can copy the "link" for the font family style and paste it in the head of the document under the stylesheet link. Next you can copy the "css rule" for the style and paste it into the CSS stylesheet to style an element.

The **font-weight property** allows you to control the thickness of the font (normal or bold). The text browser default is normal weight and the text default for the strong element is bold weight. The font-style property allows you to control text italics. 

The **font-size** property applies different sizes to text. Default text size is 16px. Default font sizes for elements are sized relative to the parent element. Use the **formula (target / base) * 100%** to obtain a percentage value that is relative to the base font size set on the desired target size. When using this formula you can either round or keep the full decimal values.

**Text color** is an important design consideration as color provides meaning and personality to text. Named colors are a list of predefined colors that match set color values (like hexadecimal).  You can add a color property to selectors like "body" that will specify color for that body text.
