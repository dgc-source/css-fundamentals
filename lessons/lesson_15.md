# CSS Fundamentals

## Use CSS Media Queries to Dynamically Apply Styles

Today the majority of internet traffic comes from mobile devices. So it is essential to understand how to make styles dynamic to different viewport sizes.

`Flex` is a powerful and simple way of dynamically positioning our elements. When used with `justify-content: space-between`, it evenly spreads out our elements.

Using media queries are useful when we want to modify our site or app, depending on devices general type such as the viewport width. Whenever all of the media feature expressions which are defined inside parentheses compute to true, the CSS defined within the blocks will apply to the website.

```CSS
@media (max-width: 700px) {
  ...
}
```

What `max-width` is saying here, if our viewport is 700 pixels or less, apply the following styles.

We can accomplish this same functionality by switching to `min-width`.

```CSS
@media (min-width: 700px) {
  ...
}
```

Now we're saying if the `min-width` of the viewport is 700 pixels or greater, apply the following styling.

Logical operators such as `and` can be used to compose a complex media query:

```CSS
@media (min-width: 700px) and (max-width: 1000px) {
  ...
}
```

Here we're saying only apply the styling when the viewport is between 700 and 1000 pixels.

A couple of other media features you can test on is `min-height` and `max-height`.

You can also check for `orientation`, whether the website is in `portrait` or `landscape` mode.
