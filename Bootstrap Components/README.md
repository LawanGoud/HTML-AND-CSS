# Bootstrap Components

## Navbar

A Navbar is a navigation header that is placed at the top of the page. With Bootstrap, a Navbar can extend or collapse, depending on the device size.

### HTML Nav element

The HTML `nav` element is a container element similar to the HTML `div` element. We use the HTML `nav` element to add a Navbar to our website.

```HTML
<nav class="navbar navbar-expand-lg navbar-light bg-light"></nav>
```

### Nav Items inside Navbar

```HTML
<a class="nav-link active" href="#">
  Home
  <span class="sr-only">(current)</span>
</a>
<a class="nav-link" href="#">Features</a>
<a class="nav-link" href="#">Pricing</a>
<a class="nav-link disabled" href="#" tabindex="-1" aria-disabled="true">
  Disabled
</a>
```

### Nav link

```HTML
<a class="nav-link" href="#">Features</a>
```

# HTML Elements

In general, HTML elements can be divided into two categories.

- Block-level Elements
- Inline Elements

## Block-level Elements

These elements always start in a new line and take up the full width available. So, an HTML Block-level element occupies the entire horizontal space of its parent element.

For example, the HTML `h1` element, `p` element, `div` element, etc.

```HTML
<h1 class="heading">The seven wonders of the world</h1>
<p class="paragraph">The Taj Mahal is one of the seven wonders of the world</p>
```

## Inline Elements

These elements do not start in a new line and only take up as much width as necessary.

For example, the HTML button element, img element, a element, etc.

```HTML
<img
  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/mysore-palace2-img.png"
  class="image"
/>
<img
  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/varanasi1-img.png"
  class="image"
/>
```

```HTML
<p class="paragraph">
  The <a class="link-text" href="https://en.wikipedia.org/wiki/Taj_Mahal">Taj Mahal</a>
  is one of the seven wonders of the world.
</p>
```

# CSS Box Properties

## Margin

We can align HTML Block-level elements horizontally using CSS `margin` property.

Apart from values that are specified in pixels, it also accepts `auto` keyword as a value.

<b>Note</b>

If we specify the CSS `text-align` property to the HTML Block-level element, it aligns the text or HTML Inline elements inside it.

### Auto Value

The child element will be horizontally centred inside the HTML container element.

```HTML
<div class="navbar-nav nav-items-center">
  <a class="nav-link active" href="#">
    Home
    <span class="sr-only">(current)</span>
  </a>
  <a class="nav-link" href="#">About Me</a>
  <a class="nav-link" href="#">Projects</a>
  <a class="nav-link" href="#">Testimonials</a>
</div>
```

```CSS
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");

.nav-items-center {
  margin: auto;
}
```

### Auto Value with Margin Variants

- Using auto as a value for the CSS margin-right property takes up all the available space, and the element gets aligned to the left.

- Using auto as a value for the CSS margin-left property takes up all the available space, and the element gets aligned to the right.

```HTML
<div class="navbar-nav nav-items-right">
  <a class="nav-link active" href="#">
    Home <span class="sr-only">(current)</span>
  </a>
  <a class="nav-link" href="#">About Me</a>
  <a class="nav-link" href="#">Projects</a>
  <a class="nav-link" href="#">Testimonials</a>
</div>
```

```CSS
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");

.nav-items-right {
  margin-left: auto;
}
```

# Bootstrap Utilities

## Margin

Apart from the numbers 0-5, the margin also has the below Bootstrap class names.

- m-auto
- ml-auto
- mr-auto
