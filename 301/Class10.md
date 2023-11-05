# In memory storage

What is a ‘call’?
A call or "function invocation" is a single functionx execution and is done one at a time from the top to the bottom. Meaning the call stack is synchronous.
How many ‘calls’ can happen at once?
One call happens at a time.

What does LIFO mean?
_LIFO_ stands for "Last in, first out." Which basicalyl means that the last function that gets pushed into the call stack is the first one to come out when the function returns.

Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

function thirdFunction() {
secondFunction();
}

function secondFunction(){
firstFunction();
}

firstFunction();

What causes a Stack Overflow?
A stack overflow occurs when a function calls itself without an exit point.

## JavaScript error messages

What is a ‘reference error’?
A reference error occurs when a varialbe is used that has not yet been declared.
What is a ‘syntax error’?
A syntax error occurs when something cannot be parsed in terms of syntax. Such as when you try and parse an invalid object using JSON.parse.
What is a ‘range error’?
A range error occurs when an object is manipulated with a length and given and invalid length.
What is a ‘type error’?
A type error occurs when the data type yo uare trying to use is incompatible.
What is a breakpoint?
A breakpoint is used in debugging and can be added to your program to make it stop running at a certain point when a condition is met.
What does the word ‘debugger’ do in your code?
Adds a breakpoint to your code where you wish to later examine your code via the developer tools in your browser.
