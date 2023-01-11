 # READING 02
 
## React lifecycle

1. When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. 
Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount 
all occur in this order during mounting.

2. What is the very first thing to happen in the lifecycle of React?
Mounting

3. Put the following things in the order that they happen: `componentDidMount`, `render`, `constructor`, `componentWillUnmount`, `React Updates`
  * `constructor`
  * `render`
  * `componentDidMount`
  * `React Updates`
  * `componentWillUnmount`

4. What does `<componentDidMount>` do?
This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, 
it should go here. This method is a good place to set up any subscriptions. If you do that, don’t forget to unsubscribe in componentWillUnmount().
