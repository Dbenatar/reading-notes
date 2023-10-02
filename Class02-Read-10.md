# Debugging

A syntax error is most often a typo, such as misspelled keywords, missing punctuation, missing bracket or closing parenthesis. These days most text editors such as Visual studio will detect these errors.

Logic errors are the kind of error which prevent your program from working correctly and working in the way you expect. The code may still run but the result is not the expected one. These are probably the hardest errors to detect. This requires the developer to thoroughly go through the code to determine where the error is.

My most common errors are typos, missing or putting an an "s" where it shouldnt be. Using a semi colon or colon the wrong way round. I am also quite bad at forgetting or misplacing a closing bracket especially when writing loops, functions or constructors with functions and or loops inside of them. This topic is teaching me to be more thorough with debugging my code and writing in a clearer way to begin with to help these mistakes easier to spot.

Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger. Built-in debuggers can be turned on and off, forcing errors to be reported to the user. With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing. Normally you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu. In the debugger window, you can set breakpoints in the JavaScript code. At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

> - W3schools.com

A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.

When a script calls a function, the interpreter adds it to the call stack and then starts carrying out the function.
Any functions that are called by that function are added to the call stack further up, and run where their calls are reached.
When the current function is finished, the interpreter takes it off the stack and resumes execution where it left off in the last code listing.
If the stack takes up more space than it was assigned, a "stack overflow" error is thrown.

> - MDN Web docs
