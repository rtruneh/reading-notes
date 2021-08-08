# REACT: Component Lifecycle Events #

In react you can define components as classes or functions with the methods being called lifecycle events. There are three phases of this cycle: 
1. Mounting - during this phase a component is created and inserted into the DOM. 

2. Updating - when a component is updated or state changes and is rerendered. 

3. Unmounting - the final phase when a component is being removed from DOM. 

### Methods ###

The constructor `constructor()` is called before it is mounted. If the component is a subclass, then call super(props) otherwise they will be undefined. Constructors can be used to assign a state via `this.state`. It's best practice to avoid `this.setState()`in the constructor because it will lead to unecessary side effects. 

`static getDerivedStateFromProps()` is only used when the state relies on changes in props over time. 

`render()` is the only required method in a class component. It examines `this.props` and `this.state` when called and shouldn't modify the component state or directly interact with the browser. 

`componentDidMount()` will be invoked immediately after a component is mounted. You would use this if you needed to load anything using a network request or when initializing the DOM. 