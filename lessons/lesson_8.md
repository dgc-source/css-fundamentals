# CSS Fundamentals

## 8. Contorl HTML Elements with Different CSS Units

When working in CSS it's important to understand the difference between absolute units like pixels (`px`) and relative units like `em`, percentages (`%`), and `rem`.

**Pixels** are referred to as **absolute units**, because they'll always be the same size regardless of any other related settings.

`em` is referred to as a **relative unit**, becuase it depends on the font size of the element which it is assigned to. So if we gave `p` element a `padding` of 2em:

```CSS
p {
  font-size: 18px;
  padding: 2em;
}
```

It's associated pixels will be `36px`. That's because in the case of the `p` element it's font size is set to 18px, so `1 em` is equivalent to `18px` hence the reason we got `36px` above.

If we change the em to rem:

```CSS
p {
  font-size: 18px;
  padding: 2em;
}
```

We see now that our computed padding is going to be `32px`. This is because `rem`s work exactly the same way as `em`s except for, it will go off the default base `font-size` of the browser and the not the `font-size` that's applied to the current element. The default `font-size` of the browser is `16px`. So `1 rem` is the equivalent of `16px` and `2 rem` is `32px`.

We can also use percentages inside of our CSS. We change our the font-size of our `p` element to `200%`. And now our font size is now `32px`. That's because percentages are calcuated based on the parent size. So for our font size, that's going to be the default size of the browser, `16px`, and 200% of 16 is going to be 32. If we use the percentage on `width` or `height`, it would calculate the `width` and `height` based off the size of the parent's `height` and `width`.
