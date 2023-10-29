# React and forms

1. Using React a form elements mutable state property is kept in the state property of componenets and updated using setstate(). This is different to an HTML form element where they maintain their own state and only update upon user input. Making Reacts state the single source of truth can combine these, this is know as a controlled component.

2. This would depend on whether we need multple responses from the user. Although it requires writing more code than using a single useState, using a controlled component means you can now pass the value to other UI elements or reset it from other event handlers.

3. To target what the user is intering into a form we can use a value attribute on the root of a select tag.

## The conditional (Ternary) operator explained.

1. Using a conditional (Ternary) operator allows us to yield the results of a an if else statement using just one short line of code.

2. if(x===y) {
   console.log(true);
   } else {
   console.log(false)
   }

Ternary operator.

x = y ? 'true' : 'false';
