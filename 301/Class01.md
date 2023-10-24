# Introduction to React and Components

## Componenet-based architecture

A componenet in short is a software object, a small piece of code which makes up part of the interface you are building with React.

The main characteristics of components are its **reuseability**, componenets are designed to be reused in different situations in different applications. Some componenets however may be designed for a specific task. Componnets are **replaceable** and may be freely sustituted with other similar components. On top of being replaceable componenets are also designed to operate in different environments and are not context specific. A componenet is **extensible** and can be extended from existing components to provide new behaviour.
A componenet is **encapsulated**, it depicts the interfaces, which when called allow its functionality to be used. Components are designed to have minimal dependecies on other componenets.

Using componenet-based architecture has many advantages. On top of the their characteristics of being reusable and independent, they are reliable, easy to deploy and can reduce cost of development and maintenance with the use of third-party componenets. This makes system maintenance and evolution easier as you can update the implementation without affecting the rest of the system.

## Props and how to use it in React

Props or **properties** are objects that are used in React. They are used to pass data between components in a unidirectional flow, meaning the data flows down form the parent elements to the child elements. To make use of props you first need to define an attribute and its value, the pass this data (or value) to its child compenents, which then finally needs to be rendered.
