# HTML Anchor Element

The HTML `a` element defines a Hyperlink.

We use Hyperlinks to navigate to other web resources or a specific element within the HTML document. They are also called links.

```HTML
<a href="URL">Content</a>
```

## HTML `href` Attribute

The HTML `href` Attribute specifies the URL/ path of the page where the link goes to.

```HTML
<a href="https://www.ccbp.in/">Explore CCBP 4.0 Certification Programs</a>
```

## HTML `target` Attribute

The HTML target Attribute specifies where to open the linked web resource.

# Navigate within the same HTML document

The HTML `a` element can also be used to navigate to different sections within the same HTML document.

Add an HTML `id` attribute to the section that you want to navigate to. Provide the hash symbol `#,` and the value of the `id` attribute of that section as a value to the link's HTML `href` attribute.

<b>Note</b>

While navigating to a particular section within the same HTML document, the content of that section doesn't start from the starting of a page when

- It has less content to fill the Viewport height and there are no sections after it.
- The content of that section and the content of the sections after it has less content to fill the Viewport height.
