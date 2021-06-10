# HTML & CSS #
## Chapter 15: Layout ##

Each element is considered to have it's own box, this can be inline or block level. Remember: *block level* starts on a new line and acts as the main building blocks of the layouts, *inline* flows between surrounding text. 



If one block level sits inside of another then the bigger container is considered the the containing or parent element. CSS offers you the ability to position the different working parts of your element to control the layout using "normal flow", "relative positioning" and "absolute positioning". 

*Normal FLow* is the basic layout where paragraphs appear one after the other. *Relative positioning* will move an element from it's normal flow and can shift it to the top, right, bottom or left. *Absolute positioning* takes your element out of normal position and doesn't affect the position of the elements around it. 

The box offset property can help your code know where the box should be positioned. Use *fixed positioning*, which is similar to absolute positioning that will place the elemnent in relation to the browsing window instead of the containing element. *Floating elements* allow you to take it out of normal flow and position it as far left or right of the containing box. 

The default flow or "natural" flow is where each block level element sits on top of the next one. With this flow an example of the syntax would be `position: static;`. Relative position is moving the element in relation to where it would have been in normal flow. Absolute positioning it's removed from the natrual flow so that it doesn't affect the positions of the other elements. Lastly, a fixed position positions elements in relation to the browser so that when you scroll down it'll stay in place.

When using any of the above mentioned elements, they will overlap. In order to control which element is on top you would use the z-index property with a number value. The higher the number the closer it is to the front. 

Float properties paired with the width property allow you to take an element within a normal flow and place it to the left or right of it's container. Clear properties allow you to say that no element within the same container should touch the left or right side of the box. To get the multi column design on your page you achieve this by dividing each element within its own `<div>`. When you are ready to design in CSS you add the width(to set the width of the column), float (to position the columns next to each other) and margin (to create gaps between them). 
If a containing element only has floated elements the browser will collapse the css border. The work around for this is to add `overflow: auto;` and set width to 100%

#### Multi-Column layouts with Floats ####

Make sure to set each column within it's own `<div>` and give it it a class name. You can then begin to set each column with it's own css properties using the class name. 

#### Screen Sizes and Resolutions ####

Resolution refers to the number of dots a screen shows per inch. This will differ by size and type of tech used. You'll have the fun job of trying to appeal to all sizes and resolutions. Most designers try and create pages around 960-1000 pixels wide. 

Fixed width layouts do not change sizes if the user increases or decreases the size of their browser window. There are advantages and disadvantages to this. Where you're pixel value is accurate and you have control of the appearance and position of the items, if a users page is larger than anticipated this can make the page difficult to read or create a lot of empty space. 

Liquid layouts streth and contract as the user increases or decreases the browser. This means the page will always fill the entire screen and it's a tolerant design if users set font to large. However, without set width's the page can be extremely stretched and in turn difficult to read, images can overflow and a narrow window will squish all the content. 

Layout grids are helpful. It essentially breaks the page down into parts that help designers position items on the page. 

If you plan on using multiple style sheets you'll be needing to use the `@import` value. Some designers use separate css sheets to help separate what each one does, whether it's to control layout or font or colors etc. It's a couple of ways to do this. You can either link one style sheet to your HTML and then use the `@import` rule to import other sheets. Or you can use separate links for each style sheet in your HTML. 