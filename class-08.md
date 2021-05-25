# HTML & CSS #
## Chapter 15: Layout ##

Each element is considered to have it's own box, this can be inline or block level. Remember: *block level* starts on a new line and acts as the main building blocks of the layouts, *inline* flows between surrounding text. 

If one block level sits inside of another then the bigger container is considered the the containing or parent element. CSS offers you the ability to position the different working parts of your element to control the layout using "normal flow", "relative positioning" and "absolute positioning". 

*Normal FLow* is the basic layout where paragraphs appear one after the other. *Relative positioning* will move an element from it's normal flow and can shift it to the top, right, bottom or left. *Absolute positioning* takes your element out of normal position and doesn't affect the position of the elements around it. 

The box offset property can help your code know where the box should be positioned. Use *fixed positioning*, which is similar to absolute positioning that will place the elemnent in relation to the browsing window instead of the containing element. *Floating elements* allow you to take it out of normal flow and position it as far left or right of the containing box. 