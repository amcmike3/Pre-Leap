## HTML Lab 4 - Exploring HTML Links

### Overview
In this lab, you will create an HTML file named `links.html` and practice creating different types of links, including basic links to external websites, links to local files, email links, and links to specific sections within a page.

### Instructions

1. **Create a New HTML File**:
   - Open git bash.
   - Navigate to your `~/Documents/PreLeap/HTML` directory using git bash.
   - Create a new file `links.html` using the `touch` command.
   - Open `links.html` using the `code` command.

2. **Write the HTML Structure**:
   - Inside `links.html`, create the basic structure of an HTML document with `<html>`, `<head>`, and `<body>` elements.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML Links Lab</title>
  </head>
  <body>
    
  </body>
</html>
```

3. **Create Basic Links**:
   - Within the `<body>` section, create at least three basic links to external websites. Use descriptive link text.

```html
<h2>Basic Links</h2>
<ul>
  <li><a href="https://www.google.com">Google</a></li>
  <li><a href="https://www.example.com">Example Website</a></li>
  <li><a href="https://www.github.com">GitHub</a></li>
</ul>
```

4. **Link to Local Files**:
   - Create a link to each of the other labs we have created so far. Ensure that it opens in the same browser window.

```html
<h2>Local File Link</h2>
<p><a href="basicFormatting.html">basic formatting (Local)</a></p>
```

5. **Create an Email Link**:
   - Create a link that opens the user's default email client to compose an email to your email address.

```html
<h2>Email Link</h2>
<p><a href="mailto:yourname@example.com">Email Us</a></p>
```

6. **Link to Specific Sections**:
   - Create a link that jumps to a specific section within the same page. Use an anchor with the `id` attribute.

```html
<h2 id="section2">Jump to Section</h2>
<ul>
  <li><a href="#section2">Jump to Section 2</a></li>
  <li><a href="#section3">Jump to Section 3</a></li>
</ul>
<h2 id="section3">Jump to Section</h2>
```

7. **Save Your HTML File**:
   - Save the `links.html` file after adding the content.

8. **View in a Web Browser**:
   - Right-click on the `links.html` file tab at the top of your VS Code editor.
   - Select 'Copy path.'
   - Open your favorite web browser (e.g., Google Chrome).
   - Paste the copied path into the browser's URL bar and press Enter.

9. **Test and Verify Links**:
   - Click on each link to ensure they navigate to the correct destinations, including external websites, local files, email, and specific sections within the page.

10. **Enjoy Exploring Links**:
    - Observe how different types of links function and how they can be used to connect web content.

### Example Output

When you open `links.html` in your web browser, you should see a webpage with various types of links, including basic links to external websites, a link to a local file, an email link, and links that jump to specific sections within the same page. Each link should work as expected, and you can explore their functionalities.

This lab helps you practice creating and using different types of HTML links for navigation and interaction on a web page.

[Prev](listsHTML.md) | [Up](README.md) | [Next](imagesHTML.md)