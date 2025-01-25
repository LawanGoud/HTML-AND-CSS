# Bootstrap Grid System

## Column Wrapping

When we place more than 12 grid columns in a single row, the extra grid columns will wrap in a new line.

Try out the different combinations of Bootstrap class names like `col-4`, `col-4`, `col-6`, `col-6` and `col-6`, `col-4`, `col-6`, `col-4`, etc. in the below Code Playground.

## The Layout at different Breakpoints

Bootstrap provides different Bootstrap Grid Column class name prefixes for Five Responsive Tiers (Responsive Breakpoints).

| Device                  | Device Size (Width) | Class Name Prefix |
| ----------------------- | ------------------- | ----------------- |
| Extra Small             | 0-576px             | `col-`            |
| Small                   | 576-768px           | `col-sm-`         |
| Medium                  | 768-992px           | `col-md-`         |
| Large                   | 992-1200px          | `col-lg-`         |
| Extra Large             | 1200px and up       | `col-xl-`         |
| Extra Extra Large       | 1400px and up       | `col-xxl-`        |
| Extra Extra Extra Large | 1600px and up       | `col-xxxl-`       |

If we define the behaviour of the Bootstrap Grid Column in a particular device, similar behaviour is guaranteed in all devices with larger sizes.

```HTML
<div class="container">
  <div class="row">
    <div class="col-6">
      <h1 class="heading">Taj Mahal</h1>
      <p>The Taj Mahal is on the southern bank of the river Yamuna.</p>
    </div>
  </div>
</div>
```

### Class names in combination

We can use a combination of different Bootstrap class names for each Bootstrap Grid Column.

<b>Note</b>

Bootstrap follows Mobile First Approach.

First, design the Layout of a mobile version, and this will be adopted by devices with larger sizes.

# Bootstrap Grid System - 2

## CSS Box Properties

### Margin

We can get spacing between the two HTML elements with the CSS Box property margin.

To get space only on one particular side, we use Margin Variants.

- margin-top
- margin-right
- margin-bottom
- margin-left

## Bootstrap Spacing Utilities

### Margin

| CSS Margin Property | Bootstrap class name |
| ------------------- | -------------------- |
| margin-top          | `mt-*`               |
| margin-right        | `mr-*`               |
| margin-bottom       | `mb-*`               |
| margin-left         | `ml-*`               |

The asterisk (\*) symbol can be any number in the range of 0 to 5. For example, m-5, mr-2, mb-3, etc.

#### Margin Values

| Size | Value   |
| ---- | ------- |
| 0    | 0       |
| 1    | 0.25rem |
| 2    | 0.5rem  |
| 3    | 1rem    |
| 4    | 1.5rem  |
| 5    | 3rem    |

The spacer is a variable and has a value of 16 pixels by default.

For example,

- mb-3 = 1 \* 16px = 16px
- m-5 = 3 \* 16px = 48px

<b>Note</b>

Avoid using CSS `margin-left` and `margin-right` properties for Bootstrap Grid Columns. It disturbs the Bootstrap Grid System and gives unexpected results.

### Padding

| CSS Padding property | Bootstrap class name |
| -------------------- | -------------------- |
| padding-top          | `pt-*`               |
| padding-right        | `pr-*`               |
| padding-bottom       | `pb-*`               |
| padding-left         | `pl-*`               |

The asterisk (\*) symbol can be any number in the range of 0 to 5. For example, `p-3`, `pr-1`, `pb-5`, etc.

#### Padding Values

| Size | Value   |
| ---- | ------- |
| 0    | 0       |
| 1    | 0.25rem |
| 2    | 0.5rem  |
| 3    | 1rem    |
| 4    | 1.5rem  |
| 5    | 3rem    |

The spacer is a variable and has a value of 16 pixels by default.

For example,

- p-1 = 0.25 \_ 16px = 4px
- spt-4 = 1.5 \_ 16px = 24px

## Bootstrap background Color Utilities

You can use one of the below Bootstrap class names to apply a background color to an HTML element.

<b>Note</b>

In the above Code Playground, we used the bootstrap class name p-2 for padding.

## Developing Layouts for five Responsive Breakpoints

### Color Palette
