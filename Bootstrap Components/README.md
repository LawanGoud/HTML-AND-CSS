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
