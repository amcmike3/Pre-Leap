## HTML for starters

HTML elements (also known as HTML tags) are fundamental components of Hypertext Markup Language (HTML), which is the standard markup language used to create web pages. HTML elements are used to structure and define the content of a web page, specifying how different parts of the page should be displayed in a web browser. Each HTML element is enclosed within angle brackets (< >) and consists of a start tag, content, and an optional end tag.

Here's a breakdown of the key components of HTML elements:

1. **Start Tag**: The start tag, also known as the opening tag, is the first part of an HTML element. It consists of the element name enclosed within angle brackets. For example, `<p>` is the start tag for a paragraph element.

2. **End Tag**: The end tag, also known as the closing tag, is the second part of an HTML element. It has the same element name as the start tag but with a forward slash (/) before the element name. For example, `</p>` is the end tag for a paragraph element.

3. **Content**: The content of an HTML element is the information or text that falls between the start and end tags. It defines what is displayed or rendered on the web page. For example, in `<p>Hello, World!</p>`, "Hello, World!" is the content of the paragraph element.

4. **Attributes**: Some HTML elements can have attributes, which are additional information or settings that modify the behavior or appearance of the element. Attributes are specified within the start tag and are written as name-value pairs. For example, `<img src="image.jpg" alt="Image Description">` includes `src` and `alt` attributes for an image element.

HTML elements serve various purposes and can include headings, paragraphs, links, images, forms, tables, and more. They provide structure and semantics to web content, enabling web browsers to render the content as intended. Additionally, HTML elements can be styled and formatted using CSS (Cascading Style Sheets) to control their appearance and layout on the web page.

basically, HTML elements are the building blocks of web pages, defining the structure and content of a document. They are essential for creating structured and well-organized web content that can be displayed and interacted with by users in web browsers. Lets look at an example:


```html
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    <h1>Hello World</h1>
  </body>
</html>
```

**HTML Overview:**

- `<!DOCTYPE html>`: This declaration defines the document type as HTML5, which is the latest version of HTML.

- `<html>`: The opening and closing `<html>` tags enclose the entire HTML document, indicating the beginning and end of the HTML content.

- `<head>`: The `<head>` section contains metadata about the document, such as the document title, character encoding, and links to external resources like stylesheets and scripts. In the provided code, the `<head>` section is empty.

- `<body>`: The `<body>` section contains the visible content of the web page. It includes elements like text, images, headings, links, and more. In this example, there's an `<h1>` (header 1) element with the text "Hello World" enclosed within it.

- `<h1>`: The `<h1>` element represents a top-level heading and is used to display a large, bold headline on the web page. In this case, it displays "Hello World" as the main heading. There are several variations of this which you will see on the next page.

This HTML code creates a simple web page with the title "Hello World" displayed as a heading. You can further enhance and customize the content and appearance of your web page by adding more HTML elements and CSS styles.

[prev](README.md) | [Up](../README.md) | [Next](HTMLlab1.md)