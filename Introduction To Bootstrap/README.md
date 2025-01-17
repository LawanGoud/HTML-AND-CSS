# Reusability of CSS Rulesets

If we want the same style for multiple HTML elements, we can write the CSS Ruleset once and use it for different HTML elements.

```CSS
.button {
  width: 138px;
  height: 36px;
  border-width: 0px;
  border-radius: 10px;
}
```

```HTML
<button class="button">Get Started</button>
<button class="button">Visit Now</button>
```

# Multiple class names as an HTML attribute value

We can provide multiple class names separated by space as a value to the HTML class attribute.

<b>Syntax</b>

`<tag class = "name1 name2 name3 name4 ...">Content</tag>`

HTML attribute value: `name1 name2 name3 name4 ...`

class names: `name1`, `name2`, `name3`, and `name4`

```CSS
.button {
  width: 138px;
  height: 36px;
  border-width: 0px;
  border-radius: 10px;
}
.button-green {
  background-color: #8cc63f;
}
```

```HTML
<button class="button button-green">Get Started</button>
```
