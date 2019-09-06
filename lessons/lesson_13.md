# CSS Fundamentals

## 13. Positioning HTML Elements using CSS

Elements flow along the page depending on their display values, however we can customize them to be placed literally anywhere. We can position elements absolute or relative to a certain location, as well as fixed to the top of a page.

The `position` property can help us manipulate the location of an element. When we use `relative` as the value, it's going to keep the element's original position in the flow of the HTML document, which gives us the ability to use `left`, `right`, `top`, `bottom`, and `z-index`.

If we change `position` to `absolute`, it breaks out of the flow of the page. absolute positioning will change depending on which of its parent elements is positioned relative and even there is no parent element with a relative position the element will be positioned at the very top-level HTML element.

Similar to `absolute` is the `fixed` value. However, fixed elements are always relative to the document and not any parent element. Also, scrolling does not affect it. This is handy when working with navigations that stay at the top of a website.
