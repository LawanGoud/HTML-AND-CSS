# CSS Box Properties

## Height

The CSS `height` property specifies the height of an HTML element.

```CSS
.card {
  height: 200px;
}
```

## Width

The CSS `width` property specifies the width of an HTML element.

```CSS
.card {
  width: 250px;
}
```

# CSS Background Properties

## Background Image

The CSS `background-image` property specifies the background image of an HTML element.

```CSS
.card {
  background-image: url("https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/ocean.jpg");
}
```

| Value | Description           |
| ----- | --------------------- |
| url   | The URL to the image. |

<b>Warning</b>

1.  The background image takes the height of the content of an HTML element if you don't specify the height to it.
2.  The URL given to the background-image must be a valid URL to display the image.

## Background Size

The CSS `background-size` property specifies the size of the background image of an HTML element.

```CSS
.card {
  background-size: cover;
}
```

| Value | Description                                                                                                                                                       |
| ----- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| cover | Scales the image to the smallest size while maintaining the same aspect ratio (width/height) and covers the entire width and height even if the image is cropped. |
|       |

<b>Note</b>
Aspect Ratio is the ratio of the width and height (width/height) of an image.

# Viewport

The browser's viewport is the area of the window in which web content can be seen.

## Viewport Height

The CSS Viewport Height `vh` Unit equals to 1% of the height of the Viewport (browser window size).

```CSS
.card {
  height: 50vh;
}
```

<b>Note</b>
The height `100vh` sets an HTML element to the entire height of the Viewport (browser window size).

## Viewport Width

The CSS Viewport Width `vw` Unit equals to 1% of the width of the Viewport (browser window size).

```CSS
.card {
  width: 100vw;
}
```

<b>Note</b>
The width `100vw` sets an HTML element to the entire width of the Viewport (browser window size).
