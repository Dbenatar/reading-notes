# Pulling it all together

1. The single responsibility principle is a technique that a componenet should only do one thing.

To build a static version of an app means build componenets that reuse other componenets and pass data using props. A static version has little interactivity so it is often easier to start with this version and add intereactivity later.

You can determine whether some is state if it is adding interactivity, if it is data that changes over time, such as the value of checkboxes, or if it isnt passing in from a parent via props.

How can you identify where state needs to live?
Often you can put the state directly into their common parent. You can also put the state into some component above their parent. Create a new component for holding state and add it somewhere in the hierarchy above the common parent component.

A higher-order-function are functions that operate on other functions.

function greaterThan(n) {
return m => m > n;
}
let greaterThan10 = greaterThan(10);
console.log(greaterThan10(11));
// → true
The second line of the function is a variable with the value of the greaterThan function.

In a higer-order function map operates by transforming an array by applying its elements and building a new array from the returned values.
