# CSS Fundamentals

## 7. Understand CSS Layout with the Box Model

The box model is one of the most important aspects of understanding layouts and designs. It defines how elements will be affected by margins, borders, paddding, and actual content.

The CSS **box model** is the foundation of layout on the web. Each element is represented as a rectangular box with the box's content, `padding`, `border`, and `margin` built up around one another. As HTML is structured on the page, the browser will take this layering into effect when trying to piece together an overall layout.

`padding` and `border` affect the `height` and `width` of our element but `margin` is a little bit different. `margin` surrounds a CSS box and pushes up and against other CSS boxes around it in the layout, but it doesn't add to the `height` and `width`.

If we don't won't our `height` and `width` effected by `padding` and `border`, we can change the `border-box` property from it's default value of `content-box` to `border-box`. This will tell the browser not to add in `border` and `padding` to the overall `height` and `width`.

There is one caveat however. This box model only applies to block-level elements. If the `display` property's value is `inline` the `height` and `width` are ignored.
