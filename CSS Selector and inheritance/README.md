# CSS Selectors

The CSS Selectors are used to select the HTML Elements that we want to style.

The different types of CSS Selectors are:

- Simple Selectors
  - Class Selector
  - ID Selector
  - Type (tag name) Selector
  - Attribute Selector
  - Universal Selector
  - Pseudo-class
- Compound Selectors
- Complex Selectors and many more.

## Class Selector

The CSS Class Selector selects all the HTML elements that have a given CSS class selector as their class attribute value. It consists of a dot (.), followed by the class name of the HTML element.

```HTML
<p class="paragraph">The population of India is around 138 crores.</p>
```

```CSS
.paragraph {
  color: blue;
}
```

Here, the CSS class selector is `.paragraph`. So, it selects all the HTML elements that have an HTML attribute name `class`, and it's value `paragraph`.

<b>Note</b>

There can be more than one HTML element with the same class name in the HTML document.

## ID Selector

The CSS ID selector selects an HTML element based on its ID attribute value. It consists of a hash `(#)`, followed by the ID of the HTML element.

```HTML
<p id="populationParagraph">The population of India is around 138 crores.</p>
```

```CSS
#populationParagraph {
  color: blue;
}
```

Here, the CSS ID selector is `#populationParagraph`. So, it selects the HTML element that has an HTML attribute name `id` and it's value `populationParagraph`.

<b>Note</b>

There should be only one HTML element with a given ID in the entire HTML document. The HTML `id` attribute value doesn't need to have the prefix `section` as CCBP UI Kit is not used.

## Type (tag name) Selector

The CSS Type Selector selects all the HTML elements based on their tag names (`h1`, `p`, `div`, etc.)

```HTML
<p>The population of India is around 138 crores.</p>
```

```CSS
p {
  color: blue;
}
```

Here, the CSS Type selector is `p`. So, it selects all the HTML elements that have a tag name p.
