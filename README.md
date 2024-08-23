[zlink to codecademy lesson](https://www.codecademy.com/courses/react-101/lessons/react-programming-patterns/exercises/reactive-programming-patterns-review)

### React Programming Patterns

**Review**

Congrats! You’ve learned your first programming pattern to help organize your React code. You divided a complex React component into a container component and a couple of presentational components.

Here are the steps we took:

- Identified that the original component needed to be refactored: it handled calculations/logic and presentation/rendering.
- Created a container component containing all the stateful logic.
- Created a function that calls the state setter method provided by useState().
- Created and exported presentational components containing only JSX.
- Imported the presentational components into the container component.
- Used the presentational components in the return statement of the container component.
- Passed state and functions used to change state as props to the rendered presentational components.

In this programming pattern, the container component does the work of figuring out what to display using state. The presentational component does the work of actually displaying the state through props. If a component does a significant amount of work in both areas, then that’s a sign that you should use this pattern!
