# HTML lists, Control flow with JS and the CSS Box model

## Learn HTML

An Unordered list tag is used in HTML for a list of items with no numerical ordering, most often using bullet points. There are a couple of different styles of bullet point which can be used. This can be done by ustilising the **list-style-property** property inside of the opnening tag and choosing from the value, disc, circle, square or none. The fourth bullet type of triangle is not supported by all browsers. If the user has a list of numerical value to display the Ordered list tag should be used which lists the items with numbers instead of bullet points. An ordered list can list items using letters as well as numbers or can start a list at a particular number, either by using **type="i"** inside of the opening Ol tag or **start="5"**, for example.

## The CSS Box model

The margin property is a transparent space which clears an area outside of the border. The padding, like the margin, is also transparent and clears area around the content.

The other parts of the box model are the content of the box, this is where the text or image appears. Inbetween the padding and the margin is the border of the box, this goes around the outside of the padding and has a few diffent style options. The border can be given custom sizes, colours and styles such as dotted lines, dash lines or a solid line.

## Arrays, Operators and Expressions, Conditionals and Loops

Arrays can contain a mixture of data types, however it is best practice to create seperate arrays for strings or numbers, for example.

The example array is not a valid Javascript. It is possible to have more than one array, however the example has multiple indexes some of which are not valid. Such as [['pete', 32, 'libraian', null]]. Null, is not declared. I think inner arrays should use {} instead of [].

1. Assignment shorthand operator. x = f()
2. Addition assingment. x += f()
3. Subtraction assingment. x -=f()
4. Multiplication assingment. x\*= f()
5. Division assingment. x /= f()

6. This example has really stumped me to be honest. Im reading it as 10 plus false plus dog. The code runs false 10 times plus the string of dog? Once the code has finished running false ten times it will add dog?

A real world example for using a conditional statement in Javascript could be to check a users age and see if they are old enough to buy alcohol.

> const age = 26;
> const beverage = age >= 21 ? "Beer" : "Juice";
> console.log(beverage); // "Beer"

Example taken from [MDN](https://developer.mopwzilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Conditional_operator).

Loops are great for running the same code repeatedly and get different values.
