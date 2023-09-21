# Basics of HTML, CSS, JS

## HTML

The use of semantic elements in HTML is important becuase they clearly describe the content inside of the tags. This also helps make it easier for SEO bots to parse. Semantic elements improve accessibility in a couple of ways. They firstly use less memory than non-semantic HTML so this is easier for mobile applcations. The browser also has an easier time interpreting the code. Semantic HTML is a lot more beneficial to those using screen readers. The use of semantic elements is also easier for developers to read, especially when it is a large team of developers reading the same code.

Headings in HTML have 6 different levels, h1 being the largest and reserved for the main heading of the page. It is commomn practice to only use one of these per page. Heading sizes decrease in size all the way to h6. Unlike the H1 tag, you can use multiple headings on a page of the other five sizes.

HTML can make use of two typographical elements called **sup** and **sub**, **superscript** and **subscript** respectively.

The abbreviation tag **abbr** must be used in conjunvction with the global <title> attribute to show the description of the abbreviation.

## CSS

There are three ways of inserting a CSS stylesheet to an HTML index. External CSS style sheets can be linked via a <link> element in the head of a HTML file. Internal CSS can be used bey adding a <style> attribute inside the head section of the HTML. Inline CSS may be used to apply style to a single element. However, Inline CSS loses advantages of a style sheet but mixing content with presentation.

In the example below the selector is the h2 heading. The color and padding components are properties while color:black; and padding:5px; are CSS declarations.

h2 {
color: black;
padding: 5px;
}

## JS

If you write HTML inside of Javascript an argument it should be instide of single quotes.

There are number of different Javascript operators, such as Arithmetic, comparison, assignment and string operators.

As a **Function** is a block of code designed to perform a particular task, it is a great for task that need to be repeated. Using funtions you can also use the same code but using different arguments to produce different results. A real life example of using a function would be if you needed to convert a unit of measeurment from metric to imperial or vice versa.

An if statement checks a condition and if it evaluates to true, then the code block will execute. A way to chain extra choices or outcomes to a block of code we can use the **else if** condition. This can specify a new condition to test if the initial condition is false.

Comparison operators are used along with Logical operators to test for true or false. Examples of Comparison operators are **==** = equal to, **!=** = not equal to, < = less than and > greater than. The difference between Logical operators are && = **and** while || means **or**.
