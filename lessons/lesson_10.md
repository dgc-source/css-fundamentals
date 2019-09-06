# CSS Fundamentals

## 10. Add Backgrounds to HTML Elements

Backgrounds are very flexible. We can use images, gradients, or plain colors to create colorful backgrounds.

When we use the `background` property, it's important to understand that it's a shorthand property, which means it applies a whole bunch of styles with a single declaration. By default background comes with a lot of initial styles with the shorthand property.

`background: url()` - this allows us to set a background image for our element. the `url` can be the relative location of an image or the url to an online image.

`backgrounnd-size: cover` - this is going to scale the image as much as possible without actually stretching it.

`background: url(...)center/cover no-repeat;` - this is going make the values for `background-postion-x` and `background-position-y` `center` which will center the background image in the browser, the `background-size` is cover, and `background-repeat-x` and `background-repeat-y` is set to `no-repeat` which means that the background image will not be repeated.

This `background` property also accpets gradients, so we can use the `radial-gradient` for our background which is applied as an image.

`background: radial-gradient( crimson, skyblue);` - blends together to create a gradient

We can give this gradient a parallax field, meaning when we scroll up and down the center will follow our view. This is accomplished by add a shorthand property of `fixed`.

`background: radial-gradient( crimson, skyblue)fixed;`
