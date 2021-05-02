# JavaScript & JQuery #
## Problem Domain ##

Understanding a problem domain is difficult. According to John Sonmez in his article *"Understanding The Problem Domain is The Hardest Part of Programming"* he explains to make the problem domain easier and to get better at understanding the problem domain. Cut the cases and narrow your focus on a particular part of the problem. 



## Chapter 3 ##

Objects gropu together a set of variables and functions to create a moddel. Within an object variables are known as properties. These properties tell us about the object with data such as name or type. Functions are known as methods, these are tasks for the object. 

An object literal houses all this information: 

`var kitten = {`<br>
    `name: 'spot',`<br>
    `age: 4,`<br>
    `available: true,`<br>
    `functionName: function() {`<br>
       ` return needed info;`<br>
    `}`<br>
`}`

Lets break some of these parts down. *Name*, *age* and *available* are called keys. The information after the colon is called the value. The word *kitten* after var is called the object. By using what is called the dot notation, you can access the information within the literal. This looks like *object.value*. In the example above, to call the age of the kitten, you'd write out kitten.age.

## Chapter 5 ##

Your model of a site is called a DOM tree and is stored in the browswers memory. They contain four types of nodes: Document, Element, Attribute and Text. 

Document nodes represent the entire page. You'd have to access the document element in order to go deeper into the other elements. Element nodes describe the structure of the page. The attribute nodes are part of the element. The text nodes are accessed through its element, text nodes cannot have children, if there is one it is the child of the containing element. 

Working the DOM tree has two steps:

1. Locate the node that represents the element you want to work with. 

    `getElementById()` or `querySelector()` are commonly used methods to access an individual element. If you are trying to access multiple elements you can replace "Id" with "ClassName", "TagName" for the getElement or you can use `querySelectorAll()`. You can also move from one element to a related one using `parentNode`, `previousSibling`, `nextSibling`, `firstChild` or `lastChild`.
    
2. Use it's text content, child elements and attributes. 

    
DOM queries are methods to find elements within a DOM tree. If you are working with multiple elements you should use a variable to store the result. 