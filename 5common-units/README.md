![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 5*](https://www.digitalocean.com/community/tutorials/how-to-use-common-units-in-css) 
## How to Use Common Units in CSS.
## What I learned and how it applies in my Github page example:

**Pixels (px)** are physically based units whose size is determined by physical size of a single pixel on the device’s display.  They can be applied to margins, padding, and other element properties. They are not very responsive, and create issues of pixel doubling (small/blurry) and sub-pixel rendering (blurry edges). Better to use  % or em.

**Percent units (%)** are relative. They don't rely on physical screen attributes. It can scale based on different factors (ie, user browser settings). It's better for accessibility and user engagement with content.

The **width** property is more responsive with the percent unit. To determine which percentage to use in a situation, use the formula:  size / context = result. Size is desired size, context is the surrounding relevant container to which we want to make the element proportional.

**Font sizes** are also more responsive with the use of % as opposed to pixels. The default browser font size if 16, so that becomes the context. Users can set their own font size to assist with visibility. Relative units allow font-sizes to scale proportionally based on the user preference.


The **em** unit is responsive and also has a common base unlike the % unit. The em is relative to the font-size of the element. The browser default font is 16px, hence 1em = 16 px.  

Since em is relative to font size, it can be used on more properties than % (margin, padding, border, and max-width). Also, there is no need to multiply the result of the size / context = result by 100 as ems are not percentages.

In the last example it was interesting that even though the font-size property was specified at the end of the .citation class block, it still provided the context for all the properties. Since a font-size was specified, that would be the context (not the default browser font of 16px).

The **rem** unit is a "root" element unit referring to the topmost element of the web page (html or body). The rem has a consistent size based on the root element's font size (16 by default). This differs from em which can change based on its context. The benefit of rem is that it is not affected when font sizes of parent containers change.

You can change the basis for the rem unit by specifying a different font size in styles.css applied to **:root**. This is a way to easily increase/decrease overall font size in your document for accessibility or visual aesthetics. 




