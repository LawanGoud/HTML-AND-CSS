# Adding Icons

There are a limited number of Icon choices in Bootstrap icons. Since we don’t have the desired icons in Bootstrap Icons, we use Font Awesome Icons.

## Font Awesome Icons

To use the Font Awesome Icons, you need to add the below Font Awesome Icons Kit Code in the HTML head element.

```HTML
<script src="https://kit.fontawesome.com/fac54f0bd8.js" crossorigin="anonymous"></script>
```

```HTML
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous"/>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
    <script src="https://kit.fontawesome.com/fac54f0bd8.js" crossorigin="anonymous"></script>
  </head>
  <body>
    <i class="fab fa-twitter icon"></i>
  </body>
</html>
```

```CSS
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");

.icon {
  color: #d0b200;
  font-size: 35px;
}
```

# Follow Us Section

<b>Note</b>

The CSS Property border-radius allows you to add circular corners to an HTML element. We need to provide the same height and width to get circular corners else we will get elliptical corners.

# Adding Links to the Sections

- Adding id to the section to which we want to navigate.

```HTML
<div class="wcu-section pt-5 pb-5" id="wcuSection">...</div>
```

- Providing id as `href` Attribute value to the Nav Item

```HTML

<a class="nav-link active" id="navItem1" href="#wcuSection">
  Why Choose Us?
  <span class="sr-only">(current)</span>
</a>
```
