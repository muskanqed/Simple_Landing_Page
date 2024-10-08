
# Simple Landing Page

## To create this Landing page we will use HTML and CSS

### HTML

HTML stands for hyper text markup language. It is the foundation of building unstyled websites.

Step 1: Creating a simple HTML file locally

* Create a folder on your machine called website
* Add a index.html file inside it.
* Write the code in given in the index.html file.

Step 2: Lets learn some of the tags used in the above code

* `<div>` : A block-level container used to group other elements for styling or layout purposes.
Example: 

`<div style="background-color: lightblue; padding: 10px;">
    This is a div container.  </div>`

* `<span>` : An inline container used to group text or other inline elements without adding line breaks.

Example: 

`<p>This is a paragraph with a <span style="color: red;">highlighted</span> word.</p>
`

* `<head>` : Contains metadata and links to resources like stylesheets and scripts; it's not visible on the webpage.

Example: 

`<head>
    <title>My Webpage</title>
    <link rel="stylesheet" href="styles.css"></head>`

* `<body>` : Encloses the content of the webpage that is visible to users, including text, images, and links.

Example:

`<body>
    <h1>Welcome to My Webpage</h1>
    <p>This is the main content of the page.</p><body>`

* `<h1> to <h6>` : Define HTML headings, with <h1> being the highest (or most important) level and <h6> the lowest.

Example:

`<h1>Heading 1</h1>`

`<h2>Heading 2</h2>`

`<h3>Heading 3</h3>`

`<h4>Heading 4</h4>`

`<h5>Heading 5</h5>`

`<h6>Heading 6</h6>`


* `<b>` : Makes the enclosed text bold for emphasis, without adding any extra importance.

Example:

`<p>This is <b>bold</b> text.</p>`


* <i>: Italicizes the enclosed text, often used to denote a term or phrase in another language.

Example:

`<p>This is <i>italicized</i> text.</p>`

* <u>: Underlines the enclosed text, typically used for emphasis or to denote hyperlinks in some designs.

Example:

`<p>This is <u>underlined</u> text.</p>`

* <a>: Creates hyperlinks to other webpages, parts of the same page, or files.

Example:

`<a href="https://www.example.com">Visit Example</a>`

* <img>: Embeds images in the webpage, with the source specified by the src attribute.

Example:

`<img src="image.jpg" alt="A beautiful scenery" width="300">`

* <input>: Defines an input field where users can enter data, like text boxes, radio buttons, or checkboxes.

Example:

`<input type="text" placeholder="Enter your name">`

* <button>: Creates a clickable button that users can interact with to submit forms or trigger scripts.

Example:

`<button type="button" onclick="alert('Button clicked!')">Click Me</button>
`

* <br>: Inserts a line break, moving the following content to a new line.

Example:

`<p>First line of text.<br>Second line of text.</p>`


### CSS

* CSS stands for Cascading Style Sheets. It is used to style our applications.

* You can add CSS to your HTML app by using the  style attribute inline styles, internal styles external css file.

Approach #1 - Inline styles

`<body style="background-color: black;">
... rest of the code</body>`

Approach #2 - Internal styles

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0;
            padding: 20px;
        }
        
        h1 {
            color: #333;
            text-align: center;
        }
        
        p {
            color: #666;
            line-height: 1.6;
        }
        
        .highlight {
            background-color: yellow;
            font-weight: bold;
        }
    </style>

Approach #3 - External styles

* Add a new file called index.css
* Add the following code in it

`body {
    background-color: black;
}`

### Common style attributes

* color: Sets the text color.
* background-color: Sets the background color.
* font-size: Sets the size of the text.
* margin: Sets the outer space around an element.
* padding: Sets the inner space within an element.
* border: Sets the border around an element.
* Flexbox: Flexbox is a CSS layout model designed to help with the arrangement of items within a container.
* Classes and ids: In CSS, classes and IDs are used as selectors to apply styles to HTML elements. They help in targeting specific elements for styling and can be used to enhance the modularity and reusability of CSS code.