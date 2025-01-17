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
