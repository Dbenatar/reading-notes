# Basics of HTML, CSS, JS

## HTML

The use of semantic elements in HTML is important becuase they clearly describe the content inside of the tags. This also helps make it easier for SEO bots to parse. Semantic elements improve accessibility in a couple of ways. They firstly use less memory than non-semantic HTML so this is easier for mobile applcations. The browser also has an easier time interpreting the code. Semantic HTML is a lot more beneficial to those using screen readers. The use of semantic elements is also easier for developers to read, especially when it is a large team of developers reading the same code.

Headings in HTML have 6 different levels, <h1> being the largest and reserved for the main heading of the page. It is commomn practice to only use one of these per page. Heading sizes decrease in size all the way to <h6>. Unlike the H1 tag, you can use multiple headings on a page of the other five sizes.

HTML can make use of two typographical elements called <sup> and <sub>, **superscript** and **subscript** respectively.

The abbreviation tag <abbr> must be used in conjunvction with the global <title> attribute to show the description of the abbreviation.

## CSS

There are three ways of inserting a CSS stylesheet to an HTML index. External CSS style sheets can be linked via a <link> element in the head of a HTML file. Internal CSS can be used bey adding a <style> attribute inside the head section of the HTML. Inline CSS may be used to apply style to a single element. However, Inline CSS loses advantages of a style sheet but mixing content with presentation.

In the example below the selector is the h2 heading. The color and padding components are properties while color:black; and padding:5px; are CSS declarations.

h2 {
color: black;
padding: 5px;
}

## JS
