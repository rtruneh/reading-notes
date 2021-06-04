# CSS Transform, Transitions and Animations #

## Transforms ##
###### [](learn.shayhowe.com/advanced-html-css/css-transforms) ######

There is a new property called "transform" that allows you to use new ways to position or alter elements. It comes in two different settings: 2 and 3 dimensional. Assuming the browsers accept the transform property, let's dive into them. 

The 2D aspect takes into consideration the x(horizontal) and y(vertical) axes. Let's go through some of the acceptable values. 
>*Rotate* allows the object to rotate from 0 to 360 degrees. <br>
>*Scale* allows you to change the size of the objects' height or width or the whole thing. <br>
>*Translate* works on the positioning of the object without messing with the flow of the other elements. Much like the *scale* value, you can translate only x or only y or both. <br>
>*Skew* is used to distort elements to give it and parallelogram look.<br>

You are allowed to combine any of the above transforms but they would have to be listed within the transform property without any commas. If you were to list them out in their own declaration it wouldn't work because each new one would overwrite the one above it. 

For any of the above changes there is an understanding that the origin is located at the halfway point horizontally and vertically. This is called the *transform origin*. If you want to move this point you just have to adjust the property. If you only specify one value it will apply it to both horizontal and vertical. If you do place two values, the first one will apply to the horizontal and second one for the vertical. 

3D aspect needs perspective and there are two ways of applying this. You can either add the perspective value within the transform property (this will be good for one element) or apply the perspective property on the parent element (this is good for a group of elements.). Depth value allows an item to seem close or far away depending on the value given to it. You can start with none, which will change nothing and the larger the number the further away it seems. 