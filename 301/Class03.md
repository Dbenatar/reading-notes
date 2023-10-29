# Passing functions as props

1. Using .map() function can be used to create a new array populated with the results of calling a provided function.

2. When using React if you want to loop through an array and display each value you must use the .map() function. For example, this can be done be returning a li element for each item and then aggigning the resulting array of elemnets to a variable of the list items.

3. Using list items in React a special string attribute needs to be used along side called a key.

4. A Key helps react identify which items have changed, are added or are removed. Elements inside of an array should be given a key which gives elements outside of the array a stable identity.

## The Spread operator

1. Spread allows an iterable, such as an array or string to be expanded.

2. Spread can be used to replace apply() in function calls, create a shallow copy of an array, make more succinct syntax when combiniting array literals, finally spread is better way to concatenate arrays.

3. Using spread two arrays can be combined
   e.g
   let arr1 = [0, 1, 2];
   const arr2 = [3, 4 , 5];

arr1 = [...arr1, ...arr2];

4. Spread can be used to ad a new item into an array by

const isSummer = fales;
const fruits = ["apple", "banana", ...(isSummer ? ["watermelon"] : [])];

5. let arr1 = [0, 1 , 2];
   const arr2 = [3, 4, 5];

arr1 = [...arr2, ...arr1];
console.log(arr1);

## How to pass functions between components

**In the video, what is the first step that the developer does to pass functions between components?** The developer creates the increment function after the state containing the people array.

**In your own words, what does the increment function do?** The increment function in theis example increases the count be one increment per click of the button.

**How can you pass a method from a parent component into a child component?** To pass a componenet from the parent to the child component you can use {this.name of function}.

**How does the child component invoke a method that was passed to it from a parent component?** To call this method you call in the child by using this.props.nameOfFunction().
