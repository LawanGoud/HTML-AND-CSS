# HTML Elements

## Image Element

The HTML `img` element defines an Image

`Syntax : <img src="IMAGE_URL">`

## The `src` Attribute

The HTML Attribute `src` specifies the Path (URL) of the Image.

```HTML
<img
  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"
/>
```

## The `alt` Attribute

The HTML Attribute `alt` specifies an Alternate Text for the Image.

## How to get the path (URL) of an Image?

One of the ways to get the path (URL) of an Image from the internet.

- Open the Google Image search page: Go to `https://images.google.com/` in your Web browser. This will open the Google search page for images.

- Enter an image you want to search for: Type a word or phrase into the text box in the middle of the page.

- Click the Search icon: It's to the right of the text box. Doing so will search Google for images related to your search.

- Find your image: Scroll through the results until you find one which matches your needs.

- Open the image in a new tab: Click the Open image in new tab.

- Copy the image's URL: Copy the entire URL of the image from the address bar of the Web browser.

- Paste this URL in the HTML `src` Attribute of an HTML `img` element.

## How to apply Height and Width to an Image?

We can provide multiple HTML Attributes to the HTML `img` element. The HTML `src` and `class` Attributes are provided in the HTML `img` element given below.

```HTML
<img
  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"
  class="image"
/>
```

```CSS
.image {
  width: 80px;
  height: 100px;
}
```

# Void Elements

The HTML elements that only have a start tag and do not contain content or end tag are called as Void Elements.

`Syntax: <tag />`

For example, the HTML `img` element.

<img src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-img.png"/>

# CSS Box Model Properties

## Margin

The CSS `margin` property specifies the space around the four sides of an HTML element.

```CSS
.card-container {
  margin: 10px;
}
```

You can use the below CSS properties to apply a margin on the specific side of an HTML element,

| Property      |
| ------------- |
| margin-top    |
| margin-right  |
| margin-bottom |
| margin-left   |

Step by Step Process of achieving the Favourite Places Section:
Step1:

- Adding a Background Container
- Adding a Favourite Places Section Heading
- Adding Padding to the Favourite Places Section Heading
- Adding a Favourite Place Card
- Adding a Favourite Place Card Container
- Adding a Favourite Place Card Heading
- Adding a Favourite Place Card Description
- Adding padding to the Favourite Place Card
