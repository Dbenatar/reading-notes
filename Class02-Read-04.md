# HTML Links, Js Functions and CSS Layout

To create a basic link on an HTML page we must first create an anchor tag(<a>) and within this achor using an href attribute (Hypertext Reference) to contain the link. The href can link to a URL anywhere on the internet or a remote file on the developers computer, such as an image.

To ensure our links are accesible to all readers it is good practice to include key words in your link text that effectively describes what is being linked to.

## CSS Layout: Normal flow CSS layout: Poistioning.

Normal flow refers to the default layout of elements on a webpage if no CSS has been applied to change the way it behaves or its appearance. Normal flow ensures that the content is readable regardless of the the browser orif the user is using a screen reader.

Depending on the type of element, each HTML element will have a default display value. Either **Block** or **Inline**. Block-level elements always start a new line and have a margin added automatically by the browser. Block elements will also take up the full width available to them. The opposite in these regards is the inline element, which does not start a new line and takes up as much width as necassary. By default every HTML element is given the static positioning element. Which simply means each element is placed in its normal position in the document flow. So for languages such as Arabic or English, static will position things on the left going to the right.

An **absolute** positioned element does not exist in the normal flow of a document. It will instead sit on its own layer seperate to everything else. This can be very useful in creating isolated UI features which do not interfere wit the layout of other element on the page. For example, pop-up notifications, menus, cookie settings etc. The key difference between the absolute position and the fixed position is that unlike aboslute position, where the element is fixed in place relative to its nearest positioned ancestor, the **fixed** position is placed realative to the viewport, meaning the element stays in place even if the page is scrolled.

## JS Functions

Js functions are not executed once they are declared. Once written the declaration creates a binding of a new function to a given name. They are written and stored until they are invoked.

A functions parameters are the names listed in the function definition. Function arguments are the values passed to the function.
