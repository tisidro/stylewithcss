![phillip zastrow logo](https://pbs.twimg.com/profile_images/1452633114044403715/d3liT5vd_400x400.jpg)
# [*Tutorial 9*](https://www.digitalocean.com/community/tutorials/how-to-select-html-elements-using-id-class-and-attribute-selectors-in-css) 
## How To Select HTML Elements Using ID, Class, and Attribute Selectors in CSS
## What I learned and how it applies in my Github page example:

- The *ID Selector or attribute* is a unique identifier. There can only be one unique idea on a page. You add an ID in the html following the element name as id=“my-id” and in the css it is #my-id

- The *Class Selector or attribute* creates a specific target-able value to which styles can be applied. There can be many classes on a page (unlike ID, which can only be used once in a page because it’s unique).You add a class in the html following the element name as class=“some-class” and in the css it is .some-class.

- You can *combine class selectors* which allows you to apply multiple class values to the same html element. Class selectors can also be combined to target more specific elements.

- Combined class selectors take precedence over set styles for each individual classes. The combined class selector selects a more specific element than the individual class selectors.

- An *attribute selector* format is the name of the attribute wrapped in a pair of square brackets: [ attr ]. 

- Attribute selectors can be used with any attribute, including id and class and other elements. URLs can also be used [ href=“https://cats.com” ].

- One condition modifier an attribute can look for is ^. This condition indicates that an attribute will look for a value starting with a given string.

- Example: [ href^="https://" ] looks for only secure URLS (those starting with https).
