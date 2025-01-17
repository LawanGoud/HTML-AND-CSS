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

# Bootstrap

Bootstrap is a large collection of predefined reusable Code Snippets written in HTML, CSS, and Javascript. The Code Snippets include Buttons, Cards, Carousels, etc.

## How to use Bootstrap?

To use the Code Snippets provided by Bootstrap, we need to add the below piece of code within the HTML `head` element. We call it BootstrapCDN.

```HTML
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
<script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
```

## Predefined Styles in Bootstrap

### Button

The Bootstrap class name `btn` is used to style the HTML `button` element.

```HTML
<button class="btn">Submit</button>
```

Bootstrap provides us with different types of buttons. One of them is outline buttons, which don't have a background color.

To add the outline buttons in our HTML document, just replace `btn` in the above class names with the `btn-outline`.

To achieve the different outline button styles, Bootstrap has the following class names:

<b>Note</b>

By default, Bootstrap class name `btn` has no background color.

### Text colors

To apply different colors to the text, Bootstrap has the following class names:

### Text Transform

To apply different cases like upper case, lower case, etc. to the text, Bootstrap has the following class names:

### Background colors

To apply different background colors to an HTML element, Bootstrap has the following class names:

Bootstrap provides us with many predefined class names. Some of them are:

- card
- carousel
- alert
- alert-success
- alert-link
- bg-danger
- card-body and many more...

<b>Note</b>

Using predefined bootstrap class names as a selector in our CSS Ruleset may give unexpected results.

<b>DO's</b>

```CSS
.button {
  border-radius: 5px;
  height: 50px;
  width: 138px;
  background-color: blue;
  color:white;
}
```

```HTML
<button class="button">Get Started</button>
```

<b>DON'T's</b>

```CSS
.btn {
  border-radius: 5px;
  height: 50px;
  width: 138px;
  background-color: blue;
  color:white;
}
```

```HTML
<button class="btn">Get Started</button>
```
