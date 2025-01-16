# Font Family

The CSS font-family property specifies the font for an element.

```CSS
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");
.main-heading {
  font-family: "Roboto";
}
.paragraph {
  font-family: "Roboto";
}
```

You can use one of the below values of the font-family property,

<b> Value </b>

<img src="https://nkb-backend-media-static-tenxiitian.s3.ap-south-1.amazonaws.com/tenxiitian_prod/programs/Tech+Programs/frontend-content/ccbp/cheatsheets/static-websites/images/font-families.png">

<b>Note</b>

1. To use font families, you need to import their style sheets into your CSS file.
2. There shouldn't be any spelling mistakes in the values of the `font-family` property.
3. There must be quotations around the value of the `font-family` property.

# Font Size

The CSS `font-size` property specifies the size of the font.

```CSS
.main-heading {
  font-size: 36px;
}
.paragraph {
  font-size: 28px;
}
```

<b>Note</b>

1. You must add px after the number in the value of the `font-size` property.
2. There shouldn't be any space between the number and `px`.
3. There shouldn't be any quotations around the value of the `font-size` property.

# Font Style

The CSS `font-style` property specifies the font style for a text.

You can use one of the below values of the `font-style` property,

| Value   |
| ------- |
| normal  |
| italic  |
| oblique |

```CSS
.main-heading {
  font-style: italic;
}
.paragraph {
  font-style: normal;
}
```

<b>Note</b>

1. There shouldn't be any spelling mistakes in the values of the `font-style` property.
2. There shouldn't be any quotations around the value of the `font-style` property.

# Font Weight

The CSS `font-weight` property specifies how thick or thin characters in text should be displayed.

```CSS
.main-heading {
  font-weight: bold;
}
.paragraph {
  font-weight: 200;
}
```

You can use one of the below values of the font-weight property,

| Value   |
| ------- |
| normal  |
| bold    |
| bolder  |
| lighter |
| 100     |
| 200     |
| 300     |
| 400     |
| 500     |
| 600     |
| 700     |
| 800     |
| 900     |

<b>Note</b>

1. There shouldn't be any spelling mistakes in the values of the `font-weight` property.
2. There shouldn't be any quotations around the value of the `font-weight` property.
3. The numerical values given to the `font-weight` property must be in the range from `100` to `900` and should be the multiples of `100`.

# Text Decoration

The CSS `text-decoration` property specifies the decoration added to the text.

```CSS
.main-heading {
  text-decoration: underline;
}
.paragraph {
  text-decoration: overline;
}
```

You can use one of the below values of the text-decoration property,

| Value         | Description             |
| ------------- | ----------------------- |
| underline     | Underline the text      |
| line-throught | Strike through the text |
| overline      | Overline the text       |

<b>Note</b>

1. There shouldn't be any spelling mistakes in the values of the `text-decoration` property.
2. There shouldn't be any quotations around the value of the `text-decoration` property.
3. Ensure that `text-decoration` and `line-throught` are hyphenated.
