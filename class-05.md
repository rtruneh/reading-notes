# HTML & CSS #
## CHAPTER 5 ##

No one wants a text only site. As much as we are adults, we have inner children that need a break from words via images. When including images into your site, it's best to stay as organized as possible by creating a separate IMG folder within your repo to house all the images you'll be using for your site. 

The `<img src="image title" />` element to add an image to your site. So let's break it down, `img` lets the page know that you want an image added, the `src` tells it where to find the image and the `title` lets it know specifically what image within the source to select and show. By adding `alt="description"` after the image title, it gives the picture a text description in case the image is broken and can't be seen. This is helpful to those who visit your site with visual impariments. 

When you copy in or save an image, sometimes the original size doesn't quite fit how you want. Adjusting the size is as easy as adding a `height` and `width` element within your `img` tag. Placement of the photo within your code is important. If you place it before a block element, like `<p>` or `<h>`, it'll place it in a different line. If you place it within your inline elements the picture will be wrapped around the image.