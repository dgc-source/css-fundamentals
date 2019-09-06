# CSS Fundamentals

## 9. Manipulate Colors with CSS

Defining colors can be done in **hexadecimal**, `hsl`, and `rgb` values. Each one works by telling browsers how to blend colors and lightness together.

```CSS
p {
color: #ff0000;
}
```

This is the hexadecimal representation of red. The `#` here in the color value is telling us that this is the hex value where the firt two values represent red, the second two represent green, and the last two represent blue.

| red | green | blue |
| :-: | :---: | :--: |
| ff  |  00   |  00  |

This is red because red is set to the highest value `FF` and the other is the lowest `00`.

Whenever you use the `color` propery, not only is it going to change the text color, but it's also going to affect text decorations and also be the default color for any borders that are applied.

```CSS
p {
  color: rgb(255, 0, 0)
}
```

This is also red. When we use the `rgb` value here, this is indicating red, green, and blue. We define the intenisty of each color between the values of 0 and 255. red is still 255 and our other two colors are 0 giving us red.

```CSS
p {
  color: hsl(0, 100%, 50%);
}
```

This color is also red. This stands for **hue**, **satuartion**, and **lightness**. This is another way we can define our colors in CSS.

**Hue** is the first value and its degree on the color wheel is from 0 to 360, **0** is red, **120** is green, and **240** is blue.

**Saturation** is the second value and it is a percentage value. **0** means a shade of grey and **100%** is the full color.

**Lightness** is also perecentage. **0** is black, **50%** is neither light or dark, and **100%** is white.
