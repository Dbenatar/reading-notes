# HTML Forms

Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage. The data entered is also used on the clients interface.

> Designing a quick mockup will help you to define the right set of data you want to ask your user to enter. From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

MDN Web docs.

Forms utilise a number of specific structures as well as some standard HTML elements such as **ordered** and **unordered lists** and **list items**. The p and div elements are also commonly used. Specific form structures are fieldset, legend and label structures. **Fieldset** element is a way to create groups that share the same purpose, for styling and semantic purposes.
**Legend** formally describes the purpose of the fieldset it is inside of. The **Label** element is the formal way to define a label for an HTML form.

## JS Events

Events are things that happen in the system you are programming, which the system tells you about so your code can react to them. For example, if the user clicks a button on a webpage, you might want to react to that action by displaying an information box.

When using the _addEventListener_ method you will need to provide 2 arguments. The type of event, such as "click" or "mousedown". The second argument is the function that is wanted to be called when the event occurs.

All event objects in the HTML DOM are based on the Event Object. All event objects (like MouseEvent and KeyboardEvent) has access to the Event Object's properties and methods. The _target_ within the event object is helpful becuase it returns the element that triggered the element.

The _bubbling_ principle is simple. When an event happens on an element, it first runs the handlers on it, then on its parent, then all the way up on other ancestor. There’s another phase of event processing called _capturing_. It is rarely used in real code, but sometimes can be useful. The standard DOM Events describes 3 phases of event propagation:Capturing phase – the event goes down to the element.
Target phase – the event reached the target element.
Bubbling phase – the event bubbles up from the element.

> - javascript.info
