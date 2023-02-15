# 201 class 8 notes

**Why this matters**: This information matters because because it provides another tool for page layouts with more functionality than `floats` and `positioning`, which can lead to better and more accessible coding.

------------------------------------

## Learn CSS - Flexbox

Source: [https://web.dev/learn/css/flexbox/](https://web.dev/learn/css/flexbox/)

**1. Flexbox is designed for one-dimensional content. Explain what this means.**

Flexbox layout is designed for layout in one dimension, meaning either a row or a column, as opposed to, for example, Grid layout which was designed for two-dimensional layout meaning rows and columns at the same time.


**2. Explain the difference between the main axis and cross axis.**

- main axis is set by the `flex-direction` property, so if it's `row`, the main axis will be along the row, and if it's `column`, the main axis will be along the column.

- cross axis runs the other direction, so if `flex-direction` is `row`, the cross axis is the `column`.


**3. How can using certain properties of flexbox negatively impact accessibility?**

- Accessibility can be negatively impacted when using properties that reorder the visual display away from how things are ordered in the HTML document. For example, the `row-reverse` and `column-reverse` values - because the rendering only happens in the visual order and not the logical order, which is the content that the screen reader will read out.

-----------------------------


## CSS Layout - Flexbox

Source: [https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

**1. What are some advantages of using flexbox over float?**

The following layout designs are difficult or impossible to achieve with float, but are made much easier with flexbox:

- Vertically centering a block of content inside its parent.

- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.

- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

(from this [source](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox))


**2. How does this topic connect with your long term goals?**

I think this topic connects to my long term goals because it provides another tool for page layouts with more functionality than `floats` and `positioning`. Knowing more approaches can lead to better and more accessible coding in the long term.


------------------------------------
### Things I Want To Know More About:
If flexbox is one dimensional and Grid is two dimensional, is there anything beyond that? Or other two dimensional layout tools?