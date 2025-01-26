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
