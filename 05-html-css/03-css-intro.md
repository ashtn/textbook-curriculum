# CSS {  display: intro; }

## 📚 Learning Goals 📚
- Identify parts of CSS Syntax
- Link a stylesheet to an HTML File
- Can use selectors to target specific elements to add custom style

## CSS adds the style to a website

CSS stands for Cascading Style Sheets. It is the language for specifying how documents (such as HTML) are presented to users. Use CSS to define styles for your documents, including the design, layout and variations in display for different devices and screen sizes.


**Note:** if you want to make a front-end developer cringe, tell them how CSS makes a website 'pretty'. They'll love it.

## CSS Syntax Structure

This is a CSS rule-set with a declaration block. The declaration block has two declarations (lines 2 & 3):
```css
  selector {
    property: value;
    property: value;
   }
```
- The __selector__ is *what* you want to change
- The __property__ is *what part* you want to change
- The __value__ is *how* you want to change it.

- A __declaration__ is the property and value
- A __declaration block__ are all declarations between a set of curly braces.
- The __rule-set__ is the selector *with* the declaration block.


#### Example:
```css
  h1 {
    color: orange;
    font-family: helvetica;
   }

   h2 {
     text-align: center;
   }

   p {
     color: gray;
     text-align: justify;
   }
```
What does the above code do?

**Note** After coming from backend programming, HTML and CSS can be difficult as it never throws errors if there is a syntax error. Instead it just won't do what you want it to. We will learn some debugging strategies throughout the week.

## Adding CSS to a Website
There are a few different ways to include CSS in your website. We are only going to use external style sheets in order to maintain an organized code base.

Other, __unadvisable__, ways of adding CSS include:
- Inline CSS, with the style attribute inside of an HTML tag
- Embedding a CSS block into an HTML file


Using an external style sheet has many advantages, such as:  
- Keeps styles separate from your HTML content
- Maintains readable code
- Helps avoid duplication
- Makes maintenance easier
- Allows you to make a site-wide change in one place


### Create a new CSS Style Sheet Document
In your project's directory, create a new directory called 'styles'. Inside of your new directory, create a new file called 'main.css'.

Add a new rule-set, changing all the h1 elements in your html and refresh your html page in the browser to see that style!

But wait. When I previewed my site in the browser, it didn't change any of the h1's on my web page...

That's because we didn't *link* the CSS to the HTML document. Right now the two files have no idea each other exist.

### Link CSS to HTML
For CSS to be applied on HTML element, we will need to go back to our HTML document and link our CSS.

In the head of our html document, use a [link](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link) tag to provide the relative path to your stylesheet.
```html
  <head>
    <meta charset="UTF-8">
    <title> Style Queen 👑 </title>

    <!-- Link to Style Sheet -->
    <link href="styles/main.css" rel="stylesheet">
  </head>
```

Now preview you webpage, and voila! 🎉

### Explore all the Styles!

To get started, we will use MDN's documentation on Fundamental Font and Text styling to learn common properties and values. [Click here](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals) to get started!

**Note** CSS has _A LOT_ of properties and even more values. It is not at all practical to memorize them all. Instead, google the style aesthetic you want to achieve. That will yield some code examples with properties and values to try out .  

For example, I want more spacing between lines of text in my p tags. I could google 'css change line spacing in paragraphs'.

## Best Practices
- CSS should be in it's own .css document
- Declaration blocks should have a line break between declarations
- Keep all styles for a selector in one rule-set


## Vocab ✅
- Markup language
- Element
- Declaration
- Selector
- Property
- Rule-set

## 🔑 Key Takeaway
Use CSS to define styles for your documents, including the design, layout and variations in display for different devices and screen sizes.

### Additional Resources
[MDN CSS Syntax](https://developer.mozilla.org/en-US/docs/Web/CSS/Syntax)
