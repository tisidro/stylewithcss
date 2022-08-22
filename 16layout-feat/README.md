![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 16*](https://www.digitalocean.com/community/tutorials/how-to-create-layout-features-with-position-and-z-index-in-css) 
## How To Create Layout Features with Position and Z-Index in CSS

## What I learned and how it applies in my Github page example:
- Relative positioning defines the positioning in such a way that elements are offset from the previous element in the HTML code. This allows objects to be placed in relation to one another.
- Static positioning is the default. It defines the position of a given box essentially as an un-positioned element – it flows in the normal rendering sequence of the web page.
- For elements that have a position set to a value other than static, you can set 4 direction properties on that position: top, bottom, right, left. 
- Any unit based number (+ or -) or percentage will work, or use auto for default values.
- If you set a negative value it can pull an element up from the top edge of original placement and can overlay another element for interesting effects.
- Absolute Position, unlike relative, allows you to more precisely control and adjust how an element works with the content of the page
- Absolute elements need context from which to apply the direction property values. This context comes from the ancestor element w/ a position value (if none, the browser window is the default context)
- To set an absolute, you need to set parent to relative.
- For nav bars, it’s handy to set display: flex to have items line up in a row. 
- You can style the header element with align-items: center and justify-content: space-between: to evenly position contents within.
- You can give a main nav class display: flex and align-items:stretch to have list items stretch to fill the nav space.
- When working with sub-navigation items, set initial display to “none” to hide it, and add focus/hover effects on the links to change their color when user interacts w/ them. 
- Set sub navigation item styles to display: block so they show when users interact with them and if you give them a position of absolute and set top:100% it will set the sub-nav flush with the top nav.
- The position: fixed will make the element stay within the viewport no matter the scroll position. 
- Adding this to navigation keeps it accessible to the user as they scroll.
- This will no longer span the full width of window, so you can add left:0 and right:zero under position: fixed to fix it.
- If you have a position: fixed header and you have a position: relative photo in your page, the photo overlaps the fixed header. 
- The z-index property controls how position elements overlap each other and can fix this issue by defining the order in the z-axis stack the element will occupy.
- Using z-index will fix the issue. Set up z-index system with a 1-100 based system using css custom properties (css variables):
    - —z-1: 100; —z-2:200; etc.
- The 100-based incrementation is better than using just 1-9 incrementation because the larger scale gives more points for adjustment, plenty of space between each level of system.
- Setting whatever contains your nav to the highest z-element will show it above all other z-layers. 
- You can set z-index for other elements according to the order you want them to appear. Higher values will overlap lower values.
