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

# Inline Styles

The Inline styles are applied directly to an HTML element. They use the HTML `style` attribute, with CSS property values defined within it.

**Syntax:**

`<tag style = "property1: value1; property2: value2; ...">Content</tag>`

A HTML `style` attribute value can consist of one or more CSS property values.

<b>Note</b>

Inline Styles have the highest specificity. They overwrite any other styles specified using CSS Selectors.

Using Inline Styles is not recommended because

- Inline Styles are not reusable.
- Writing HTML and CSS separately increases code readability.

# CSS Cascade

The source order of CSS Rulesets matters. When two CSS Rulesets have equal specificity, the one that comes last in the CSS is applied.
