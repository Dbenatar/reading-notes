# Functional Programming

What is functional programming?
Functional programming is a style of building the structure and elements of computer programs.

What is a pure function and how do we know if something is a pure function?
A pure function is a function that returns the same results if given the same arguments and it does not cause any observable side effects.

What are the benefits of a pure function?
A pure function is easier to test and doesnt require making a mock up. If a function recieves a collection of numbers it would expect it to increment each element of this collection.

What is immutability?
Immutability data, once created it's state cannot change. If you want to make changes you would have to create a new object with the new value.

What is Referential transparency?
If a function consistently yields the same result for the same input, it is referentially transparent.

## Node.js modules and require()

What is a module?
A Node.js modle is somewhat similar to a React component. It is created in its own seperate file and expoted and imported into the file where we want to call the object.

What does the word ‘require’ do?
Require() is used in a Node.js module when an object written in another file is needed to be called.

How do we bring another module into the file the we are working in?
To bring another module ino a file we would use the _require()_ command as a path to that other file. Not dissimilar to importing a component in React.

What do we have to do to make a module available?
To make a module available to use outside of the module is using _.exports_ in the original file.
