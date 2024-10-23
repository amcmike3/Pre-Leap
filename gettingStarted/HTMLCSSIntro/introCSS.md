# CSS (Cascading Style Sheets) Lesson

## What is CSS?

CSS, which stands for Cascading Style Sheets, is a styling language used to describe how web documents (HTML and XML) should be presented to users. It allows you to control the layout, design, and appearance of web pages, making them visually appealing and user-friendly.

CSS serves three primary purposes:

1. **Separation of Content and Presentation**: CSS separates the content of a web page (HTML) from its presentation (styling). This separation simplifies the maintenance of websites and allows for consistent design across multiple pages.

2. **Styling**: CSS defines how elements on a web page should be styled. You can set properties like colors, fonts, margins, padding, borders, and more to control the visual aspects of your page.

3. **Layout**: CSS enables you to control the layout of web page elements. You can specify how elements are positioned, sized, and aligned within the page layout.

## Where to Write CSS

CSS can be written in three different ways:

1. **Inline CSS**: You can add CSS directly to HTML elements using the `style` attribute. Inline CSS is specific to individual elements and overrides other styles. Although this can work in a pinch it is highly frowned upon. Using inline CSS makes webpages awful to maintain in the long run.

   ```html
   <p style="color: blue; font-size: 16px;">This is a blue paragraph.</p>
   ```

2. **Internal CSS**: You can include CSS within an HTML document's `<style>` element in the `<head>` section. Internal CSS applies to the entire page. This is better than inline CSS but again can eventually lead to longterm maintenance difficulty.

   ```html
   <!DOCTYPE html>
   <html>
     <head>
       <style>
         p {
           color: green;
           font-size: 18px;
         }
       </style>
     </head>
     <body>
       <p>This is a green paragraph.</p>
     </body>
   </html>
   ```

3. **External CSS**: The best and most recommended way to write CSS is in an external stylesheet file with a `.css` extension. You link this file to your HTML document using the `<link>` element in the `<head>` section. External CSS allows you to maintain styles separately and apply them to multiple HTML pages.

   ```html
   <!-- In HTML -->
   <!DOCTYPE html>
   <html>
     <head>
        <!-- the following link tag is how the page knows where to get its styling from -->
       <link rel="stylesheet" type="text/css" href="styles.css">
     </head>
     <body>
       <p>This is a styled paragraph.</p>
     </body>
   </html>
   ```

   ```css
   /* In styles.css */
   p {
     color: purple;
     font-size: 20px;
   }
   ```

## CSS Selectors

CSS selectors are patterns used to select and style HTML elements. They define which elements on a web page should receive specific styles. Here are some common CSS selectors:

- **Element Selector**: Selects elements based on their HTML tag name.

  ```css
  p {
    color: blue;
  }
  ```

- **Class Selector**: Selects elements with a specific `class` attribute value. Class selectors are denoted by a period `.` followed by the class name.

  ```css
  .highlight {
    background-color: yellow;
  }
  ```

   ```html
   <!-- In HTML -->
     <body>
       <p class="highlight">This is a highlighted paragraph.</p>
     </body>
   ```

- **ID Selector**: Selects a single element with a specific `id` attribute value. ID selectors are denoted by a hash `#` followed by the ID name.

  ```css
  #bigFont {
    font-size: 24px;
  }
  ```

  ```html
   <!-- In HTML -->
     <body>
       <p id="bigFont">This is a bigFont paragraph.</p>
     </body>
   ```

- **Descendant Selector**: Selects elements that are descendants of another element. It uses whitespace to separate elements.

  ```css
  ul li {
    list-style-type: square;
  }
  ```
  ```html
   <!-- In HTML -->
     <body>
       <ul>
        <li>This gets styled, an li tag thats a descendant of ul</li>
       </ul>
     </body>
   ```

- **Child Selector**: Selects elements that are direct children of another element. It uses `>` to denote the relationship.

  ```css
  .menu > li {
    font-weight: bold;
  }
  ```
  ```html
   <!-- In HTML -->
     <body>
       <ul class="menu">
        <li>This gets styled, an li tag thats a descendant of menu class</li>
       </ul>
     </body>
   ```

   

- **Attribute Selector**: Selects elements with a specific attribute or attribute value.

  ```css
  input[type="text"] {
    border: 1px solid #ccc;
  }
  ```

  ```html
   <!-- In HTML -->
     <body>
       <input type="text">
     </body>
   ```

- **Pseudo-class Selector**: Selects elements based on their state or position, such as `:hover` for mouse-over effects or `:first-child` for the first child of an element. This is more complex. CSS can get really intricate so don't sweat it if this isn't totally clear.

  ```css
  a:hover {
    color: red;
  }
  ```

Understanding CSS selectors is essential for targeting specific elements and applying styles effectively to create visually appealing web pages. By combining selectors, you can create complex and precisely styled layouts.

CSS plays a crucial role in web development, allowing developers to transform plain HTML documents into visually stunning and user-friendly websites. Learning CSS is essential for anyone looking to become a proficient web developer.

[Prev](README.md) | [Up](README.md)