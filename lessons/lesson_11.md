# CSS Fundamentals

## 11. Hide and Show HTML Elements with CSS

CSS gives us control over the visibility of elements on a website. For example when dealing with transitions, understanding how to show and hide elements is essential.

CSS gives us the ability to show and hide elements on a page.

`opacity` specifies the level of transparency of an element. In other words, the degree to which the content behind the element is visible.

`opacity: 0;` - causes the element to be hidden, but it still takes up space on the page. This can be useful when adding transitions and animations.

`visibility: hidden` - will also hide the element, and will also still take up space on the page. But unlike `opacity`, there is only a `hidden` and `visible` option. There's no in-between option. Transtions would not work with visibility.

`display: none` - causes the element to be removed from the layout of the page. Just like `visibility`, there is no in-between option so transitions won't work. `display:none` is a great option when hiding HTML from a page when you don't want it to take up space.
