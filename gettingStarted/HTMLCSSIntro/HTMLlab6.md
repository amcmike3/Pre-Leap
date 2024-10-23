## HTML Lab 6 - Creating and Styling a Table

### Overview
In this lab, you will create an HTML file named `tableLab.html` and practice creating and styling a table. You will include table headings, multiple rows and cells, and add a table caption for better understanding.

### Instructions

1. **Create a New HTML File**:
   - Open git bash.
   - Navigate to your `~/Documents/PreLeap/HTML` directory using git bash.
   - Create a new file `tableLab.html` using the `touch` command.
   - Open `tableLab.html` using the `code` command.

2. **Write the HTML Structure**:
   - Inside `tableLab.html`, create the basic structure of an HTML document with `<html>`, `<head>`, and `<body>` elements.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML Table Lab</title>
    <style>
      /* Add CSS styles here this will make you table better looking*/
    table {
        width: 100%;
    }

    th, td {
        border: 1px solid black;
        padding: 8px;
        text-align: left;
    }

    </style>
  </head>
  <body>
    <!-- Create your table here -->
  </body>
</html>
```

3. **Create a Table**:
   - Within the `<body>` section, create a table with the following specifications:
     - Add a table caption with the text "Student Grades."
     - Include table headings for "Student ID," "Student Name," "Math Score," "Science Score," and "Total Score."
     - Create a minimum of 3 rows with student data (you can use fictional data).

4. **Test in a Web Browser**:
   - Right-click on the `tableLab.html` file tab at the top of your VS Code editor.
   - Select 'Copy path.'
   - Open your favorite web browser (e.g., Google Chrome).
   - Paste the copied path into the browser's URL bar and press Enter to view your table.

5. **Review and Style**:
   - Ensure that your table contains the specified data, headings, and caption.

6. **Experiment with Styles**:
   - Feel free to experiment with different CSS styles to refine the appearance of your table. We will be learning about CSS next (:.

7. **Save Your HTML File**:
   - Save the `tableLab.html` file after adding the content.

8. **Enjoy Creating Tables**:
   - Gain practical experience in creating and styling tables within HTML documents.

### Example Output

When you open `tableLab.html` in your web browser, you should see a table titled "Student Grades" with multiple rows and columns containing student data. The table should be properly styled with borders and other CSS styles to make it visually appealing.

This lab allows you to practice creating and styling tables, which is a valuable skill for presenting data on web pages.

* When you're done don't forget to push your new code to github. 
    (`cd ~/Documents/PreLeap`, `git add .`, `git commit -m "some message",`, `git push origin master`)

[Prev](tablesHTML.md) | [Up](README.md) | [Next](introCSS.md)