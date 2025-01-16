- CSS Box Properties
  - Border Width
  - Border Radius
  - Border Color
  - Border-style
  - Padding
- CSS Colors
  - HEX Code

# CSS Box Properties

## Border Width

The CSS `border-width` property specifies the width of the border for all four sides of an HTML element.

```CSS
.button {
  border-width: 2px;
}
```

The CSS Property and value pair `border-width: 0px;` removes the border of an HTML element.

<b>Warning</b>
Specifying the CSS `border-style` property for an HTML element is mandatory. Otherwise, the CSS properties like `border-color`, `border-width` will not appear in the browser. The HTML `button` element is an exception as it appears with a border in the browser by default.

## Border Radius

The CSS `border-radius` property specifies the roundness of the corners of an HTML element.

```CSS
.button {
  border-radius: 20px;
}
```

You can use the below CSS properties to round a specific corner of an HTML element.

| Property                   |
| -------------------------- |
| border-top-left-radius     |
| border-top-right-radius    |
| border-bottom-left-radius  |
| border-bottom-right-radius |

<b>Quick Tip</b>
Specifying the background color for an HTML element makes the border radius more visible.

## Border Color

The CSS `border-color` property specifies the color of the border for all four sides of an HTML element.

```CSS
.button {
  border-color: orange;
}
```

<b>Warning</b>
Specifying the CSS `border-style` property for an HTML element is mandatory. Otherwise, the CSS properties like `border-color`, `border-width` will not appear in the browser. The HTML `button` element is an exception as it appears with a border in the browser by default.

## Border-style

The CSS `border-style` property specifies the style of the border for all four sides of an HTML element.

```CSS
.button {
  border-style: dashed;
}
```

You can use one of the below values of the CSS `border-style` property.

| Values        |
| ------------- |
| solid         |
| dashed        |
| dotted        |
| none(default) |

## Padding

The CSS `padding` property specifies the space around the content of an HTML element.

```CSS
.card {
  padding: 10px;
}
```

# CSS Colors

## Hex Code

CSS Colors can be represented in multiple ways:

- Color names
- Hex Code
- HSL
- RGB and many more...

Since few colors have the Color names, Hex Codes make a good alternative to pick a wide variety of colors.

Some of the Color names and their Hex Codes are:

- Red: #FF0000
- Green: #008000
- Blue: #0000FF
- Yellow: #FFFF00
- Purple: #800080
- Orange: #FFA500
- Pink: #FFC0CB
- Black: #000000
- White: #FFFFFF
- Gray: #808080
- Brown: #964B00
- Turquoise: #1ABC9C
- Teal: #0097A7
- Silver: #B1B1B1
- Maroon: #800000

```CSS
.button {
  background-color: #25b1cc;
}
```

<b>How to pick a color using Hex Code
</b>

The color picker lets you pick a color among the approximately 16,777,216 colors available.

One of the simplest ways to access a color picker is:

_Type color picker in the Google Search bar and search it._

<img src="https://nkb-backend-media-static-tenxiitian.s3.ap-south-1.amazonaws.com/tenxiitian_prod/programs/Tech+Programs/frontend-content/ccbp/cheatsheets/static-websites/images/color-picker.png">

<b>Note</b>
In the preview of the above code playground, you can't see the blue border around the HTML `button` element when you click inspect because the HTML `button` element already has borders.
