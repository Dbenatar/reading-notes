# State and props.

1. Going by the diagram provided, the render happens first and after that the componenetDidMount.

2. When using React the first thing to happen in the lifecycle is creation of the constructor.

3.

- Constructor
- Render
- React updates
- componentDidMount
- componenetWillMount

4. ComponentDidMount is the commit phase and the component can now be worked with DOM, run side effects and schedule updates.

## State vs props

1. Props are like arguments to a function, when you create a component in React you will pass an intitial value into the props.

2. The biggest difference between props and state are that props are a value passed into a component whereas a State is a value handled inside of the component.

3. If we make a change to a componenet via props we will need to rerender our application.

4. State is used to rerender an application based on what the user has done. So if you want to change something based on the users interaction, you need to store this data in state. An example of this would be the use of a form.
