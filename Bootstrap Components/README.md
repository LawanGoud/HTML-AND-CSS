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
