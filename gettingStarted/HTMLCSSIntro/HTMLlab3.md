## HTML Lab 3 - Working with Lists

### Overview
In this lab, you will create an HTML file named `lists.html` and use various HTML list tags to organize and structure content. You will create ordered lists, unordered lists, nested lists, and definition lists.

### Instructions

1. **Create a New HTML File**:
   - Open git bash.
   - Navigate to your `~/Documents/PreLeap/HTML` directory using git bash.
   - Create a new file `lists.html` using the `touch` command.
   - Open `lists.html` using the `code` command.

2. **Write the HTML Structure**:
   - Inside `lists.html`, create the basic structure of an HTML document with `<html>`, `<head>`, and `<body>` elements.
   
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Lists HTML</title>
  </head>
  <body>
    
  </body>
</html>
```

3. **Create an Ordered List**:
   - Within the `<body>` section, create an ordered list with at least three list items. Write these out yourself to ensure they are commited to memory.

```html
<h2>Ordered List</h2>
<ol>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ol>
```

4. **Create an Unordered List**:
   - Create an unordered list with at least three list items.

```html
<h2>Unordered List</h2>
<ul>
  <li>Item A</li>
  <li>Item B</li>
  <li>Item C</li>
</ul>
```

5. **Create a Nested List**:
   - Create a nested list by placing an unordered list within an ordered list or vice versa. Ensure that the nested list has at least two levels of indentation.

```html
<h2>Nested List</h2>
<ol>
  <li>Item 1</li>
  <li>Item 2
    <ul>
      <li>Subitem A</li>
      <li>Subitem B</li>
    </ul>
  </li>
</ol>
```

6. **Create a Definition List**:
   - Create a definition list with at least two term and definition pairs.

```html
<h2>Definition List</h2>
<dl>
  <dt>Term 1</dt>
  <dd>Definition 1</dd>
  <dt>Term 2</dt>
  <dd>Definition 2</dd>
</dl>
```

7. **Save Your HTML File**:
   - Save the `lists.html` file after adding the content.

8. **View in a Web Browser**:
   - Right-click on the `lists.html` file tab at the top of your VS Code editor.
   - Select 'Copy path.'
   - Open your favorite web browser (e.g., Google Chrome).
   - Paste the copied path into the browser's URL bar and press Enter.

9. **Verify Lists**:
   - Check that the HTML file correctly displays the ordered list, unordered list, nested list, and definition list with the respective formatting and indentation.

10. **Enjoy Working with Lists**:
    - Observe how different list types are displayed and structured within the web page.

### Example Output

When you open `lists.html` in your web browser, you should see the various lists correctly displayed, including ordered lists, unordered lists, nested lists, and definition lists. Each list type should be structured and formatted as expected.

This lab helps you practice using different types of HTML lists to organize and structure content on a web page.

[Prev](listsHTML.md) | [Up](README.md) | [Next](linksHTML.md)