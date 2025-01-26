# Specificity

Specificity is how browsers decide which CSS property values are the most relevant to an HTML element and, therefore, will be applied.

The following list of CSS Selectors is in the lowest to highest order by specificity.

- Type (tag name) Selector
- Class Selector
- ID Selector

## Type Selector & Class Selector

A Class Selector is **more specific** compared to Type (tag name) Selector as it selects only the HTML elements that have a **specific class attribute value** in the HTML document.

<b>Note</b>

It doesn't overwrite the entire CSS Ruleset but only overwrites the CSS properties that are the same.

## Class Selector & ID Selector

An ID Selector is more specific when compared to a Class Selector as we provide a unique ID within the HTML document and it selects only a single HTML Element.

    <h1>Heading 1</h1>
    <h1>Heading 2</h1>
    <h1 class="heading">Heading 3</h1>
    <h1 class="heading">Heading 4</h1>
    <h1 class="heading">Heading 5</h1>
    <h1 class="heading" id="heading5">Heading 5</h1>
