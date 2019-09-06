# CSS Fundamentals

## 14. Customize CSS Selectors with Pseudo Classes

**Pseudo Classes** are special keywords that can be used to affect specific selectors in customized ways. For example, when links enter a "hover" state, meaning a user has positioned their mouse over the element, we can apply a new set of styles using the :hover pseudo class. Another great example is styling inputs when a user clicks into it with the :focus pseudo class.

A CSS pseudo-class is a keyword added to a selector that specifies a specific state of the selected element.

`:hover` - As the name suggests all of the styles within this block will apply to the selector when the element is hovered over.

```CSS
p:hover {
  background-color: yellow;
  font-weight: bold;
}
```

Now when the `p` element is hovered over the text will have a background color of yellow and the text will be bold.

`<input type="text">`

```CSS
input:focus {
  outline-color: green;
}
```

Now when you click on the inside of the input box the outline will be green.

The `:focus` pseudo-class represents an element, such as a form input, that has received focus, but you usually see this when a user clicks or taps on an element or selects it with the keyboard's tab key. A few other pseudo-classes are `:nth-child`, which allows us to target specific children,by passing a number here.

Finally, there is also the `:visited` pseudo-class, which represents links that the user has already visited.

These pseudo-classes barely scratch the surface. [Mozilla](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) shows us many more options of classes that can be used to style elements.
