# Intro to React #

### What is a Component? ###

A component is a well defined functionality that has implementation and exports it as a higher level interface. It's a software object that interacts with other components. ]]

A software component is a unit of composition with specified interface and explicit context dependencies. This means it can be deployed independently and is subject to composition by third parties. 

### What are the charactistics of a component? ###

Reusability − Components are usually designed to be reused in different situations in different applications. However, some components may be designed for a specific task.

Replaceable − Components may be freely substituted with other similar components.

Not context specific − Components are designed to operate in different environments and contexts.

Extensible − A component can be extended from existing components to provide new behavior.

Encapsulated − A A component depicts the interfaces, which allow the caller to use its functionality, and do not expose details of the internal processes or any internal variables or state.

Independent − Components are designed to have minimal dependencies on other components

### What are the advantages of using component based architecture? ###
It makes it easier to replace existing versions with no impact to other components. The independence of the components and their flexibility to connect components. Simple to make changes and update without affecting the rest of the system. 

### What is props short for? ###
It's short for properties that are used for passing data from one component to another.

### How are props used in React? ###

After the attribute and the value is defined, it's passed on to the child component(s) and then rendering the props data. 

### What is the flow of props? ###

The flow of props is uni-directional, which means it can only be passed down to the child component(s).