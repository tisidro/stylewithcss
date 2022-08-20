![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 15*](https://www.digitalocean.com/community/tutorials/how-to-load-and-use-custom-fonts-with-css) 
## How To Load and Use Custom Fonts with CSS

## What I learned and how it applies in my Github page example:

- The the font stack provided an order of fonts that the browser could attempt to find and load. 

- The browser will sequentially attempt to load the local fonts in the font stack until it is successful. 

- Hosted services can provide cool fonts to your project.
    - Go to Google fonts
    - Find your font
    - Copy link and place after stylesheet link in HTML head
    - Add the font name in quotes before the first font in the font-family property of the selector you want to style followed by a comma

- You can also load fonts on to your project directory and access those with the @font-face.
    - Unzip the file
    - Drag the folder to your project directory
    - Write an @font-face rule. Example:  see example in section “Loading a Self-Hosted Font with @font-face” on [this page](https://www.digitalocean.com/community/tutorials/how-to-load-and-use-custom-fonts-with-css). Scroll down and you will see it!

    - Add font name to the selector’s font-family you want to specify in CSS file.
    - Remember, you don’t need to link anything in the head section under the stylesheet link if you are hosting your own font.

- Variable fonts look the same as an @font-face rule, but it’s a bit shorter and easier to write. Again refer to [this page](https://www.digitalocean.com/community/tutorials/how-to-load-and-use-custom-fonts-with-css). Scroll down to the “Working With Variable Fonts” and you’ll have an example to follow!

- Again, add font name to the selector’s font-family you want to specify in CSS file.
