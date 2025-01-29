# Bootstrap Components

## Modal

Try out changing the content and the styles of the Modal Header, Modal Body and Modal Footer in the Bootstrap Modal Code in the below Code Playground.

# Thanking Customers Section with the Bootstrap Modal

# Gradients

A special type of Background Image formed by the transition between two or more colors.

There are mainly two types of gradients:

- Linear Gradient
- Radial Gradient

## Linear Gradient

To create the most basic type of gradient, all you need is to specify two colors. You must have at least two colors, but you can have as many as you want.

```HTML
<div class="linear-gradient-background"></div>
```

```CSS
.linear-gradient-background {
  height: 100vh;
  background-image: linear-gradient(#2196f3, #f44336);
}
```

### Changing Direction

By default, linear gradients run from top to bottom. You can change their transition by specifying a direction.

| Direction |     | Description                                                          |
| --------- | --- | -------------------------------------------------------------------- |
| to bottom |     | The gradient runs from top to bottom. This is the default direction. |
| to top    |     | The gradient runs from bottom to top.                                |
| to right  |     | The gradient runs from left to right.                                |
| to left   |     | The gradient runs from right to left.                                |

```CSS
.linear-gradient-background {
  background-image: linear-gradient(to right, #2196f3, #f44336);
}
```

### Using more than two colors

You don't have to limit yourself to two colors. You may use as many as you like! By default, colors are evenly spaced along the gradient.

```CSS
.linear-gradient-background-with-more-colors {
  height: 100vh;
  background-image: linear-gradient(red, blue, yellow, orange);
}
```

## Radial Gradient

```HTMl
<div class="radial-gradient-background"></div>
```

```CSS
.radial-gradient-background {
  height: 100vh;
  background-image: radial-gradient(#2196f3, #f44336);
}
```

### Using more than two colors

You don't have to limit yourself to two colors. You may use as many as you like! By default, colors are evenly spaced along the gradient.

```CSS
.radial-gradient-background-with-more-colors {
  height: 100vh;
  background-image: radial-gradient(red, blue, yellow, orange);
}
```

# Food Munch Website Code
