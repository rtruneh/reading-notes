# HTML & CSS #
## Chapter 16: Images ##

Humans are visual beings. It's why we enjoy watching movies and looking at photos. It's also what draws our attention to websites and keeps us on them. Being able to control how your images look on the site is very important. 

*Width* and *height* properties are used in CSS to work on the size of an image. Doing so will help the page to load smoothly because it tells the browser how much space to leave for the image, as it's one of the last things to load.

Once you have a control on the size of the image you will want to be able to align it on the page to fit around any text or content or other images. *Float* is usually the property used for this. You can align an image left or right and then add a margin so that your content is spaced correctly and not overlapping each other. Images are inline elements, in order to center an image you have to turn it into a block element by using `display: block;` within your CSS code for the image followed by `margin: 0px auto;`. 

You can also make an image a background for your site by using `background-image: url("enter image location");` within your body element in CSS. By default the photo will do it's best to fill or repeat until filled. If you want the image only on a particular section you just specify which element you wnat the image applied to...ie `p`, `li` etc. Getting fancy with your background colors is always fun. CSS allows the option to make your background image or color gradient by applying it after `background-image`. `background-attachment` is used to tell the image whether it needs to stay put or move as the user scrolls by using `fixed` or `scroll`.Repeating images is as easy as using the `background-repeat:`. There are four values that can be used: 
>`repeat`: just goes to default and repeats horizontally and vertically<br>
>`repeat-x`: repeats horizontally <br>
>`repeat-y`: repeats vertically<br>
>`no-repeat`: image only shows once<br>

When not repeating an image you should use `background-position` to tell it where on the page you want it to populate. Each option is basically specifying the location, ie: left top or left bottom. 

You can set a second style to an item such as rollover to allow for a button to change colors when a cursor moves over it. *Sprite* is when a single image is used for several different parts of the site, these are useful for logo images or even buttons and allows for the site to load faster because it only hs to request one image. 

## Chapter 19: Practical Information ##

When you search terms in google to find a local shop or informaiton on a topic, it's using something called Search Engine Optimization, SEO. This is basically taking terms that people are more likely to use and appling them in the right places on your site to increase the chances of it showing up as a search result. 

The book gives us 6 steps that help identify right keyword and phrases for your site: 
1. Brainstorm. Think about words you or others around you would use, don't limit yourself to one word...think of phrases as well. 
2. Organize the words you thought of into categories for your site. 
3. Research sites such as **adwords.google.co.uk/select/KeywordToolExternal** to help suggest additional words to those you've already thought of. 
4. Compare your site and keywords. There are millions of sites that have been optimized for a particular keyword. 
5. Refine your list to what you will focus on. The ones you've determined to be relevant to your page. 
6. Pick a few words or phrases that map out each page of your site and use them as the keyword. Don't repeat keywords across each page. 

SEO uses two techniques to determine what comes first in search results: On-Page and Off-Page techniques.

*On-Page* techniques looks at the text and code for terms commonly used in searches. There are seven places where you should apply keywords. 
1. The page title: what appears at the top of the browser
2. The URL: the web address
3. Headings: text that is within your `<h1-6>` elements
4. Text: within your main body, try not to over use the terms
5. Link text: don't just use 'click here' for your links
6. Image alt text: utilize this space for descriptions
7. Page description: This is usually within the `<head>` element under `<meta>`

The *Off-Page* techniques looks at links to your site from other sites as well as taking into consideration the relevance of the site that has your site linked. 
 
You'll also want to learn about the people coming across your site. Informaiton like how they found your site, who sent them and at what point they left are vital to improving and maintaining your sheet. You can sign up for google analytics that will in turn give you data analytics of the traffic to your site and answers questions like the ones above. 