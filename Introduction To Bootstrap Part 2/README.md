- Flexbox Properties
  - Flexbox Container
  - Flex Direction
    - flex-row
    - flex-column
  - Justify Content
    - justify-content-start
    - justify-content-center
    - justify-content-end

# Flexbox Properties

## Flexbox Container

The Bootstrap class name `d-flex` defines a Flexbox Container. The direct HTML elements in the Flexbox Container are called flex items.

- The HTML container element with the class="d-flex" is a Flexbox Container.
- The HTML container element div in Flexbox Container is a flex item. Because it is directly inside the Flexbox Container.
- The HTML main heading, paragraph, and button elements are not flex items. Because these elements are not directly inside the Flexbox Container.

<b>Note</b>

Wrapping HTML elements in the Flexbox Container is mandatory to apply other flex properties.

## Flex Direction

The Flex Direction specifies the direction of the flex items in the Flexbox Container.

| Class Name  | Direction of the flex items in a Flexbox Container |
| ----------- | -------------------------------------------------- |
| flex-row    | The flex items are arranged horizontally.          |
| flex-column | The flex items are arranged vertically.            |

### flex-row

The Bootstrap class name `flex-row` is used to move the flex items horizontally in the Flexbox Container.

### flex-column

The Bootstrap class name `flex-column` is used to move the flex items vertically in the Flexbox Container.

<b>Note</b>

The Bootstrap class name `flex-row` is the default Flex Direction for the Flexbox Container. So, once `d-flex` is specified, all the flex items in the Flexbox Container display horizontally.

## Justify Content

The Justify Content specifies the alignment of flex items along the Flex Direction in a Flexbox Container.

### justify-content-start

The Bootstrap class name `justify-content-start` is used to align the flex items at the start of the Flexbox Container either horizontally or vertically based on the Flex Direction.

| Flex Direction | Alignment of flex items in a Flexbox Container |
| -------------- | ---------------------------------------------- |
| flex-row       | Align flex items horizontally to the left      |
| flex-column    | Align flex items vertically to the top         |

### justify-content-center

The Bootstrap class name `justify-content-center` is used to align the flex items at the center of the Flexbox Container either horizontally or vertically based on the Flex Direction.

| Flex Direction | Alignment of flex items in a Flexbox Container |
| -------------- | ---------------------------------------------- |
| flex-row       | Align flex items horizontally to the center    |
| flex-column    | Align flex items vertically to the middle      |

### justify-content-end

The Bootstrap class name `justify-content-end` is used to align the flex items at the end of the Flexbox Container either horizontally or vertically based on the Flex Direction.

| Flex Direction | Alignment of flex items in a Flexbox Container |
| -------------- | ---------------------------------------------- |
| flex-row       | Align flex items horizontally to the center    |
| flex-column    | Align flex items vertically to the middle      |

### justify-content-between

The Bootstrap class name `justify-content-between` is used to provide equal space between the flex items within the Flexbox Container, aligning them either horizontally or vertically based on the Flex Direction.

| Flex Direction | Alignment of flex items in a Flexbox Container |
| -------------- | ---------------------------------------------- |
| flex-row       | Align flex items horizontally to the center    |
| flex-column    | Align flex items vertically to the middle      |

```HTML
<div class="d-flex flex-column justify-content-between">
  <div>
    <h1>Tourism</h1>
    <p>Plan your trip.</p>
    <button>Get Started</button>
  </div>
</div>
```

```HTML
<!DOCTYPE html>
<html>
  <head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
  </head>
  <body>
    <div class="d-flex flex-column justify-content-between box-container">
      <div class="box box-orange"><p>Box 1</p></div>
      <div class="box box-green"><p>Box 2</p></div>
    </div>
  </body>
</html>
```

```CSS
@import url("https://fonts.googleapis.com/css2?family=Bree+Serif&family=Caveat:wght@400;700&family=Lobster&family=Monoton&family=Open+Sans:ital,wght@0,400;0,700;1,400;1,700&family=Playfair+Display+SC:ital,wght@0,400;0,700;1,700&family=Playfair+Display:ital,wght@0,400;0,700;1,700&family=Roboto:ital,wght@0,400;0,700;1,400;1,700&family=Source+Sans+Pro:ital,wght@0,400;0,700;1,700&family=Work+Sans:ital,wght@0,400;0,700;1,700&display=swap");

.box{
  width: 100px;
  height: 100px;
  color: white;
}
.box-orange{
  background-color: orange;
}
.box-green{
  background-color: green;
}
.box-container{
  width: 100vw;
  height: 100vh;
}
```
