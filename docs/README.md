# Overview of HTML

<!-- Think about the components of this [web page](). You have major components like the navigation bar,  -->

#### Learning Objectives

- Understand what is HTML
- How to create and render an HTML page on your browser

HTML (HyperText Markup Language) is a markup language that the web browser can render. 



```html
<html>
    <body>
        <h1>Main Heading</h1>
        <p>This body of text represents a paragraph</p>
        <h2>Here's a sub-heading</h2>
        <p>Here's the paragraph for the sub-heading</p>
    </body>
</html>
```

Each line within `<body>` represents an HTML element. Each HTML element contains an opening tag, some content, and an ending tag. Take `<h1>Main Heading</h1>` for example. The opening tag is `<h1>`, the content is `Main Heading`, and the closing tag is `</h1>`.

## Creating Your First Webpage

You'll need a text editor to create your first webpage. If you are on Windows or Mac, I personally recommend installing an editor such as [Visual Studio Code](https://code.visualstudio.com/). Otherwise, you can use Notepad **(Windows)** or TextEdit **(Mac)** as your text editor.

Open a new file and type (or copy): 
```html
<!DOCTYPE html>
<html> 
    <body>
        <h1>My First Webpage</h1>
        <p>I am creating my very first webpage</p>
    </body>
</html>
```

All HTML documents must include `<!DOCTYPE html>` at the very top to tell the browser it should render an HTML document. According to the HTML specification, this is necessary to ensure your web page is rendered correctly.

All documents also begin with an `<html>` element as a container for all other elements.

The `<body>` element contains all content that the user can see on the page.

#### Opening Your Webpage

Save your file using `CTRL-S` or "File" -> "Save As," then name it `index.html` Then in your file explorer, double-click on `index.html` and your browser will render your web page.
