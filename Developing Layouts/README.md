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

# Explore Menu Section

## CSS Units

### Percentage

To define the size of a Child Element relative to its Parent Element, we can use Percentages.

## Bootstrap Sizing Utilities

### Percentage

You can use the below Bootstrap class names to specify the width of an HTML element in percentage.

| CSS property and value | Bootstrap class name |
| ---------------------- | -------------------- |
| width: 25%             | w-25                 |
| width: 50%             | w-50                 |
| width: 75%             | w-75                 |
| width: 100%            | w-100                |

```HTML
<img
  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/em-ginger-fried-img.png"
  class="menu-item-image w-100"
/>
```

<b>Note</b>

By default, the height of the image automatically adjusts when we alter the width.

## Bootstrap Icons

### How to add the Bootstrap Icons

- Go to https://icons.getbootstrap.com in your Web browser. You will find many icons.
- Click on the icon you need. For the icon used in this section, click on `arrow-right-short`.
- Copy the HTML code and paste it.
- Change the HTML attributes `width`, `height`, and `fill` of the HTML `svg` element as you need.

A piece of the code in the HTML body element is the Bootstrap arrow-right-short icon code in the below Code Playground.

```HTML
<svg width="1em" height="1em" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="currentColor" xmlns="http://www.w3.org/2000/svg">
      <path
        fill-rule="evenodd"
        d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z"
      />
    </svg>
```

<b>Note</b>

The HTML svg element is an HTML inline element. We can use it to add icons to our website.

## Bootstrap Utilities

### Shadow

To apply shadows to HTML elements, you can use the below Bootstrap class names.

| Bootstrap class name |
| -------------------- |
| shadow-none          |
| shadow-sm            |
| shadow               |
| shadow-lg            |

```HTML
<div class="shadow menu-item-card p-3 mb-3">
  <img
    src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-responsive-website/em-ginger-fried-img.png"
    class="menu-item-image w-100"
  />
  <h1 class="menu-card-title">Non-Veg Starters</h1>
  <a href="" class="menu-item-link">
    View All
    <svg width="16px" height="16px" viewBox="0 0 16 16" class="bi bi-arrow-right-short" fill="#d0b200" xmlns="http://www.w3.org/2000/svg">
      <path
        fill-rule="evenodd"
        d="M4 8a.5.5 0 0 1 .5-.5h5.793L8.146 5.354a.5.5 0 1 1 .708-.708l3 3a.5.5 0 0 1 0 .708l-3 3a.5.5 0 0 1-.708-.708L10.293 8.5H4.5A.5.5 0 0 1 4 8z"
      />
    </svg>
  </a>
</div>
```

# Healthy Food, Delivery and Payment, Thanking Customers Sections

## Bootstrap Flex Utilities

### Order

The Bootstrap Order class names are used to change the visual order of the flex items that appear inside the Flex Container.

For example, `order-1`, `order-2`, `order-3`, etc.

We can use any number in the range of `0` to `12` for a bootstrap `order` class name.

These class names are responsive. So, you can set the order by breakpoint.

For example, `order-1`, `order-md-2`, `order-lg-3`, etc.
