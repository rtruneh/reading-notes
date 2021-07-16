# Domain Modeling #

According to codefellows' github, domain modeling is the process of creating a model in code for a specific problem to describe the entities, attributes, behaviors and constraints that govern the problem. It's a great communication tool among group members as it helps to define vocabulary to be used between technical and business teams.

Codefellows continues describing domain modeling by giving an example of attempting to guage popularity of epic fail videos. A constructor function to declare and then assign a function with two parameters. This allows you to store data when calling the function. You can then add a method to the constructor functions prototype, also considered the objects stunt double. 

Tips provided when building a domain model: 
1. Build self-contained objects with same attirbutes when modeling a single entity with several instances. 
2. Model the attribute with a constructor funciton. 
3. Model the behavior with small methods that focus on doing one job well. 
4. Create instances using `new ` keyword 
5. Store new objects in a varibale to access it from outside of the function
6. Use `this` variable to access properties from within the funciton. 

# HTML #
## Chapter 6 ##
### Tables ###

A table represents informaiton in a grid format. The basic table structure consists of a few elements: 
>`<table>` is the container for your entire table <br>
>`<thead>`which is where your headings `<th>` should sit inside<br>
>`<tbody>` is where the body of the table should sit. You can apply the  `<td>`, `<tr>` and `<th>` can be used here. <br>
>`<tfoot>` is the footer, or the last row of the table. <br>

The `<tr>` which indicates each row and then the `<td>` which holds the data. The `<th>` element which is used for the header of either the column or row this can be indicated using the `scope` attribute and telling it to apply the header to either the `row` or `col`. It's a good thing to note that even if a cell doesn't have any data, you should still represent it, otherwise the table won't render correctly. 

You can span informaiton accross multiple columns using the `colspan` or the `rowspan` followed by a number to let it know how many cells to span accross.  

# JavaScript #
## Chapter 3 ##
### Functions, Methods, and Objects ###

In order to create an object you use the `new` keyword and the name of the constructor then add the properties. This can be done by making it a varibale like so: 

`var hotel = new Object();`

You can add new properties like this: 

`hotel.name = 'Inn'`

Or add a method: 

`hotel.checkAvailability = function(){`<br>
`return this.rooms - this.booked;`<br>
`};`<br>

There are two ways to update a property. You can either use the dot notation or square brackets. 

`hotel.name = 'new name';`<br>

`hotel['name'] = 'new name';<br>

To delete a property just add the keyword delete before the property: 
`delete hotel.name;`<br>

To clear the value of a property just set the string blank: 
`hotel.name = '';`<br>

You can create a function to use as a template for creating several objects with similar things, it'll still look somewhat similar to the objects above: 
`function Hotel(name, rooms){`<br>
`this.name = name;`<br>
`this.rooms = rooms;`<br>
`}`<br

So when creating new instances you'd create the variable with a new object name and then add the cosntructor function: 
`var innHotel = new Hotel ('Inn', 40);`<br>

An array can also be an object. With an array you can store related set of key/value pairs where the index number is the key for each value. When you combine arrays and objects, you create complex data structures.

Things like the DOM or JS objects like strings, booleans and numbers are considered built in objects. These are objects you didn't create but that a hardwired into the language and can be used to create and build your site.


