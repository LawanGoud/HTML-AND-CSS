# Bootstrap Navbar

A piece of code in the HTML body element in the below Code Playground is the Bootstrap Navbar without a list-based approach Code.

# Bootstrap Containers

## Container

The Bootstrap class name `container` provides us default left and right spacings starting from smaller devices for a better user experience. It has one fixed width for each breakpoint in Bootstrap (extra small, small, medium, large, and extra large).

| Device              | Device-Size (Width) | Container Max Width |
| ------------------- | ------------------- | ------------------- |
| Extra small devices | < 576px             | 100%                |
| Small devices       | >= 576px            | 540px               |
| Medium devices      | >= 768px            | 720px               |
| Large devices       | >= 992px            | 960px               |
| Extra large devices | >= 1200px           |

```HTML
<div class="container">
  <div class="row">
    <div class="col-12">
      <h1>Taj Mahal</h1>
      <p>
        The Taj Mahal is an ivory-white marble mausoleum on the southern
        bank of the river Yamuna in the Indian city of Agra.
      </p>
    </div>
  </div>
</div>
```

## Fluid Container

The Bootstrap class name `container-fluid` is a full width container, spanning the entire width of the viewport.

If we don’t need left and right spacings, we can use the Bootstrap class name `container-fluid` instead of `container`.

```HTML
<div class="container-fluid">
  <div class="row">
    <div class="col-12">
      <h1>Taj Mahal</h1>
      <p>
        The Taj Mahal is an ivory-white marble mausoleum on the southern
        bank of the river Yamuna in the Indian city of Agra.
      </p>
    </div>
  </div>
</div>
```

# CSS Colors

## Transparent

The CSS `transparent` keyword represents a fully transparent color. This makes the background behind the colored HTML element completely visible.

For example, to set a transparent background color,

```CSS
.custom-outline-button {
  background-color: transparent;
}
```

This allows you to set the background color of the HTML element to transparent so that any background HTML element will show through.

Bootstrap also provides you with a class name `bg-transparent` to set the background color to transparent.

# Why Choose Us? Section

## Bootstrap Spacing Utilities

### Padding

| CSS Padding property | Bootstrap class name |
| -------------------- | -------------------- |
| padding              | p-\*                 |
| padding-top          | pt-\*                |
| padding-right        | pr-\*                |
| padding-bottom       | pb-\*                |
| padding-left         | pl-\*                |

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

p-1 = 0.25 _ 16px = 4px
pt-4 = 1.5 _ 16px = 24px

### HTML Elements

#### HTML Span Element

The HTML `span` element is a generic inline container element which is mainly used for styling text in HTML Elements.

```HTML
<p class="wcu-card-description">
  Food Coupons & Offers upto
  <span class="offers">50% OFF</span>
  and Exclusive Promo Codes on All Online Food Orders.
</p>
```

```CSS
.offers {
  color: #323f4b;
  font-style: italic;
  font-weight: 600;
}
```
