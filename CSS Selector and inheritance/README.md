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

# Most fundamental concepts of CSS

In CSS, the styles that are applied to HTML elements depend on three fundamental concepts.

- Inheritance
- Specificity
- Cascade

## CSS Inheritance

The mechanism through which the value of certain CSS properties is passed on from parent elements to child elements is called Inheritance.

### Parent Element

If the HTML elements are placed inside the other HTML element, then the outer HTML element is called the parent element of the HTML elements inside it.

```HTML
<div>
  <h1>The seven wonders of the world</h1>
  <p>
    The <a href="https://en.wikipedia.org/wiki/Taj_Mahal">Taj Mahal</a>
    is one of the seven wonders of the world.
  </p>
</div>
```

From the above Code Snippet, we can say:

The HTML `div` element is the parent element of the HTML `h1` and `p` elements.
The HTML `p` element is the parent element of the HTML `a` element.

### Child Element

An HTML element that is directly inside the parent element is called the child element of that parent element.

```HTML
<div>
  <h1>The seven wonders of the world</h1>
  <p>
    The <a href="https://en.wikipedia.org/wiki/Taj_Mahal">Taj Mahal</a>
    is one of the seven wonders of the world.
  </p>
</div>
```

From the above Code Snippet, we can say:

1. The HTML `h1` and `p` elements are the child elements of the HTML div element.

2. The HTML `a` element is the child element of the HTML `p` element.

CSS properties can be categorized into two types:

- Inherited properties
- Non-inherited properties

### Inherited Properties

If the CSS properties applied to the parent element are inherited by the child elements, then they are called Inherited properties.

Some of the CSS Inherited Properties are:-

Text related Properties

- font-family
- font-style
- font-weight
- text-align

List related Properties

- list-style-type
- color property and many more.

### Non-inherited Properties

If the CSS properties applied to the parent element are not inherited by the child elements, then they are called Non-inherited properties.

Some of the CSS Non-inherited properties are:

- CSS Box Properties

  - width
  - height
  - margin
  - padding
  - border-style
  - border-width
  - border-color
  - border-radius

- CSS Background Properties
  - background-image
  - background-color
  - background-size
- text-decorationand many more.
