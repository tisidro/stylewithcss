![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 19*](https://www.digitalocean.com/community/tutorials/how-to-style-figure-and-image-html-elements-with-css) 
## How To Style Figure and Image HTML Elements with CSS

###What I learned and how it applies in my Github page example:
- The tutorial showed how to set fluid widths with the `<img />` element.
- Setting the `max-width` 100% keeps image scaled to window size.
- The tutorial showed how to put an image inside a `<figure>` element and add a `<figcaption>` containing descriptive text about the image.
- To overlay a `<figcaption>` on an image that is inside a ‘<figure>’ element, give the `figure` element a `position: relative` and give the `<figcaption>` a `<position: absolute>` 
- You can use responsive image swapping with an image to fit different screen sizes by using a `picture` element containing various `source` elements. The `source` elements point to a s`srcset` which is the location of the image you want and a media property specifying a `min-width`.
- With `object-fit: cover `you must set a `height` and `width` to give the `object-fit` property full control of resizing the image property.
- Use the `object-position` property to anchor an image to a specific area.
