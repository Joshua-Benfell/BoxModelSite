# BoxModelSite

## The Box Model
The CSS box model is the main way of describing every element on a webpage. 

Each element contains 4 boxes:
- The Content
- The Padding
- The Border
- The Margin

From these boxes, the content box is where all the items such as text and images are contained. Surrounding the content is the padding, which allows you to make the overall box larger. Following that is the border and then the margin which is used to provide space between elements.
The total width or height of a single element can be found by adding the two padding, border and margin measurements (top and bottom, or left and right) to the height/width of the content region. Alternatively, the CSS Rule box-sizing: border-box; can be used to make the width and height of the content region and padding determined by just defining the width or height of the content region, as the this resizes the actualy content region around the selected padding sizes.
