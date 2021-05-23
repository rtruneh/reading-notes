# HTML & CSS #
## Chapter 16: Images ##

Humans are visual beings. It's why we enjoy watching movies and looking at photos. It's also what draws our attention to websites and keeps us on them. Being able to control how your images look on the site is very important. 

*Width* and *height* properties are used in CSS to work on the size of an image. Doing so will help the page to load smoothly because it tells the browser how much space to leave for the image, as it's one of the last things to load.

Once you have a control on the size of the image you will want to be able to align it on the page to fit around any text or content or other images. *Float* is usually the property used for this. You can align an image left or right and then add a margin so that your content is spaced correctly and not overlapping each other. Images are inline elements, in order to center an image you have to turn it into a block element by using `display: block;` within your CSS code for the image followed by `margin: 0px auto;`. 

You can also make an image a background for your site by using `background-image: url("enter image location");` within your body element in CSS. By default the photo will do it's best to fill or repeat until filled. If you want the image only on a particular section you just specify which element you wnat the image applied to...ie `p`, `li` etc. `background-attachment` is used to tell the image whether it needs to stay put or move as the user scrolls by using `fixed` or `scroll`.Repeating images is as easy as using the `background-repeat:`. There are four values that can be used: 
>`repeat`: just goes to default and repeats horizontally and vertically<br>
>`repeat-x`: repeats horizontally <br>
>`repeat-y`: repeats vertically<br>
>`no-repeat`: image only shows once<br>

When not repeating an image you should use `background-position` to tell it where on the page you want it to populate. Each option is basically specifying the location, ie: left top or left bottom. 



 