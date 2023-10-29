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



