# Bootstrap Grid System

Bootstrap Grid System is a collection of reusable code snippets to create responsive layouts. It is made up of containers, rows, and columns.

It uses a 12 column system for layouting. We can create up to 12 columns across the page.

## Container

The purpose of a container is to hold rows and columns.

```HTML
<div class="container"></div>
```

Here, the container is a `div` element with the Bootstrap class name `container`.

## Row

The purpose of a row is to wrap all the columns.

```HTML
<div class="container">
  <div class="row"></div>
</div>
```

Here, the row is a `div` element with the Bootstrap class name `row`.

## Column

We should place the columns inside a row and the content inside a column.

We can specify the number of columns our content should occupy in any device. The number of columns we specify should be a number in the range of 1 to 12.

```HTML
<div class="container">
  <div class="row">
    <div class="col-12">
      I'm your content inside the grid!
    </div>
  </div>
</div>
```

<b>Note</b>

If Bootstrap class name is `col-12`, it occupies the entire width available inside the row.

The Bootstrap class names `col-*` indicates the number of columns you would like to use out of the possible 12 columns per row. For example, `col-1`, `col-5`, etc.

# Creating Multiple Column Layouts

The Layout in the below Code Playground is a Two Column Layout. Similarly try out multiple column layouts like One Column Layout, Three Column Layout, etc. in the below Code Playground.
