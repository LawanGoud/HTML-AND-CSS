# Bootstrap Components

## Carousel

The Carousel is a slideshow for cycling through images, text, etc. Slides will change every few seconds.

To add the Carousel to our Favourite Place Detailed View Section Page, we used Bootstrap Carousel Component with the Indicators.

You can add the different images in the Carousel by changing the image URL in the value of the HTML `src` attribute.
`

```HTML
<img
  class="d-block w-100"
  src="https://d1tgh8fmlzexmh.cloudfront.net/ccbp-static-website/tajmahal-c1-img.png"
  alt="..."
/>
/>
```

# Bootstrap Utilities

## Embed

The given code snippet is the Youtube embed code provided by Bootstrap. You can add the different Youtube Videos by changing the Video ID in the value of the HTML `src` attribute.

The Video ID is in between the `https://www.youtube.com/embed/` and `?rel=0`.

```HTML
<div class="embed-responsive embed-responsive-16by9">
  <iframe
    class="embed-responsive-item"
    src="https://www.youtube.com/embed/49HTIoCccDY?rel=0"
    allowfullscreen
  ></iframe>
</div>
```

### How to add the Youtube video?

One of the ways to add the Youtube video.

Open the Youtube Home page: On the desktop, go to `https://www.youtube.com/` in your Web browser whereas on mobile, click on the Youtube application.

Enter a video you want to search for: Type a word or phrase into the text box.

Click the Search icon: It's to the right of the text box. Click it.

Select the video: Scroll through the results until you find one which matches your needs and click it.

Copy the video ID:
On the desktop, Copy the video ID after `v=`. If & is present after the `v=`, copy the video ID after `v=` and before &. For example, in the Youtube Video URL `https://www.youtube.com/watch?v=49HTIoCccDY&feature=youtu.be&ab_channel=theLuxuryTravelExpert`, the video ID is `49HTIoCccDY`.
Whereas on mobile, click on the share icon and select `Messages`, and copy the video ID after forward slash `/.`
Paste this video ID after the `embed/` and before the `?rel=0` in the value of the HTML `src` attribute.

<b>Note</b>

Be careful while pasting the video ID. The video ID must be in between the `https://www.youtube.com/embed/` and `?rel=0`. You won't get the video if any character is missed in the value of the HTML `src` attribute.
