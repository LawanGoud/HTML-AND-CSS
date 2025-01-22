# CCBP UI Kit

It is a collection of reusable code snippets similar to Bootstrap. It is specially designed for CCBP training.

## Adding CCBP UI Kit to the Web Page

```HTML
<!DOCTYPE html>
<html>
  <head>
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
      integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z"
      crossorigin="anonymous"
    />
    <script
      src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
      integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"
      integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV"
      crossorigin="anonymous"
    ></script>
  </head>
  <body>
    <script
      type="text/javascript"
      src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"
    ></script>
  </body>
</html>
```

The CCBP UI Kit Script Code should be placed just before the HTML body end tag.

## Display Utility

It is a reusable code snippet to display or hide Section Containers based on user actions.

```HTML
<!DOCTYPE html>
<html>
  <head>
    <link
      rel="stylesheet"
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
      integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z"
      crossorigin="anonymous"
    />
    <script
      src="https://code.jquery.com/jquery-3.5.1.slim.min.js"
      integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js"
      integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN"
      crossorigin="anonymous"
    ></script>
    <script
      src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"
      integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV"
      crossorigin="anonymous"
    ></script>
  </head>
  <body>
    <div id="section1">
      <p>This is Section One</p>
      <button class="btn btn-primary" onclick="display('section2')">
        Go to Section 2
      </button>
    </div>
    <div id="section2">
      <p>This is Section Two</p>
      <button class="btn btn-primary" onclick="display('section3')">
        Go to Section 3
      </button>
    </div>
    <div id="section3">
      <p>This is Section Three</p>
      <button class="btn btn-primary" onclick="display('section1')">
        Go to Section 1
      </button>
    </div>
    <script
      type="text/javascript"
      src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/js/ccbp-ui-kit.js"
    ></script>
  </body>
</html>
```

# Sections in Tourism Website

## Home Section

## Favourite Places Section

<b>Note</b>

To occupy the background image to the entire content in the above output, remove the height specified to the `favourite-places-bg-container`.

The background image takes the height of the content of an HTML element if you don't specify the height to it.

## Detailed View Section

# HTML Attributes

## The HTML id Attribute

The HTML `id` attribute specifies a unique id for an HTML element. The value of the `id` attribute must be unique within the HTML document.

```HTML
<div id="section1">Section 1</div>
```

<b>Warning</b>

The CCBP UI kit works only if the value of the HTML `id` attribute of the container section has the prefix as `section`.

So, the id which we specify for any section should always contain its prefix as `section` if you are using CCBP UI Kit.

## The HTML onclick Attribute

The `onclick` event occurs when the user clicks on an HTML Element.

```HTML
<button class="btn btn-primary" onclick="display('section3')">
  Go to Section 3
</button>
```

The value of an HTML `onclick` attribute should be enclosed in double-quotes and the value inside the brackets of `display()` should be enclosed in single quotes.

# Website Integration

## Integration of Home and Favourite Places Sections

To display Favourite Places Section when we are in the Home Section:

`Step-1`: Change ids of Section Containers. All the ids must start with `section`
`Step-2`: Add HTML code of Home Section and corresponding CSS styles to Display Utility
`Step-3`: Add HTML code of Favourite Places Section and corresponding CSS styles to Display Utility
`Step-4`: Add an HTML `onclick` attribute to the HTML `button` element in the Home Section

To display the Home Section when we are in the Favourite Places Section:

`Step-5`: Add an HTML `button` element in Favourite places Section
`Step-6`: Add an HTML `onclick` attribute to it

<b>Note</b>

While Integrating the sections with CCBP UI Kit, the ids of the section container must have a prefix section. Otherwise it doesn't work.

## Integration of Favourite Places and Detailed View Sections

To display the Detailed View Section when we click on Taj Mahal Card:

`Step-1`: Add HTML code of Detailed View Section code to the Display Utility
`Step-2`: Add corresponding styles to the CSS file
`Step-3`: Add an HTML onclick attribute to the Taj Mahal Card in the Favourite Places Section

To display the Favourite Places Section when we are in the Detailed View Section:

`Step-4`: Add an HTML button element in the Detailed View Section
`Step-5`: Add an HTML onclick attribute to the HTML button element

---

# Detailed View Section

## Golden Temple Detailed View Section

## Mysore Palace Detailed View Section

## Varanasi Temple Detailed View Section

<b>Note</b>

The ids of the Carousels are changed in the above Detailed View Sections code.

The ids used in the above code are unique throughout the HTML document.

# Website Integration

## Integration of Favourite Places and Detailed View Sections

To display the Detailed View Section when we click on the <b>Golden Temple Card</b> in the Favourite Places Section:

`Step-1`: Add the Section Container with the unique id
`Step-2`: Add HTML Code of Golden Temple Detailed View Section
`Step-3`: Add an HTML `onclick` attribute to the Golden Temple Card in the Favourite Places Section

To display the Favourite Places Section when we are in the Detailed View Section:

`Step-4`: Add an HTML `button` element in the Detailed View Section
`Step-5`: Add an HTML `onclick` attribute to the HTML `button` element

Try out adding the Mysore Palace and Varanasi Temple Detailed View Sections and integrate them similar to the Golden Temple and TajMahal Detailed View Sections in the below Code Playground.

<b>Note</b>

To use multiple Carousels in the same HTML document, we have to provide a unique id to each Carousel.

So while adding a new Carousel, you need to change the id of the Carousel. Else, the Carousel controls don’t work.

# HTML Lists

The List is a way to group related pieces of information so that they are easy to read and understand.

For example, Shopping list, Todo list, etc.

There are mainly two types of Lists available in HTML.

- Unordered List
- Ordered List

## Unordered List

It is a collection of related items that have no special order or sequence.

For example, List of Hobbies

- Painting
- Reading Books
- Playing the Guitar

The Unordered List starts with <ul> tag. It wraps around all the list items and each list item starts with the <li> tag.

```HTML
<ul>
  <li>Painting</li>
  <li>Reading Books</li>
  <li>Playing the Guitar</li>
</ul>
```

By default, list items in the Unordered List are marked with bullets.

### Styling Unordered List

The CSS `list-style-type` property is used to style the List.

```CSS
.unordered-square-list {
  list-style-type: square;
}
```

You can use one of the below values of the CSS `list-style-type` property to style the Unordered List.

| Value  |
| ------ |
| square |
| circle |
| disc   |
| none   |
