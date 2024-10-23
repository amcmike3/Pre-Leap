## HTML Lab 5 - Working with `<img>` Tags

### Overview
In this lab, you will create an HTML file named `imgTagsLab.html` and practice using the `<img>` tag to display multiple images on a webpage. You will include various images with different dimensions and attributes to gain hands-on experience with HTML image tags.

### Instructions

0. **Get your images**
    - For our images to display properly we need to add some images to your HTML directory. 
    - Right click on the picture below and select save image as.
    - in file explorer navigate to your `~/Documents/PreLeap/HTML` directory and save the file named image1.png

    <img src="../../images/QuantumLeapAcademy.png" alt="Quantum Leap Logo" width="300" height="300">

1. **Create a New HTML File**:
   - Open git bash.
   - Navigate to your `~/Documents/PreLeap/HTML` directory using git bash.
   - Create a new file `imgTagsLab.html` using the `touch` command.
   - Open `imgTagsLab.html` using the `code` command.

2. **Write the HTML Structure**:
   - Inside `imgTagsLab.html`, create the basic structure of an HTML document with `<html>`, `<head>`, and `<body>` elements.

```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML Image Tags Lab</title>
  </head>
  <body>
    
  </body>
</html>
```

3. **Add Images**:
   - Within the `<body>` section, use the `<img>` tag to add an image to the webpage. You can use both local image files and external image URLs if you can find some.

```html
<h1>Image Gallery</h1>

<img src="image1.png" alt="Quantum Leap" width="300" height="200">
<img src="image2.jpg" alt="This image contains the secret to unimaginable wealth but Oops this image didn't load properly." width="400" height="300">
<img src="https://www.example.com/image3.jpg" alt="This link doesn't work. Try to find a different image on the interwebs!!" width="350" height="250">
```

4. **Set Alternative Text**:
   - Make sure to include descriptive `alt` text for each image to ensure accessibility.

5. **Adjust Image Dimensions**:
   - Experiment with different `width` and `height` values for each image to see how they affect the image display.

6. **Link Images**:
   - Create a link around one of the images that leads to an external webpage when clicked.

```html
<a href="https://www.example.com">
  <img src="image1.png" alt="Linked Image" width="250" height="150">
</a>
```

7. **Save Your HTML File**:
   - Save the `imgTagsLab.html` file after adding the content.

8. **View in a Web Browser**:
   - Right-click on the `imgTagsLab.html` file tab at the top of your VS Code editor.
   - Select 'Copy path.'
   - Open your favorite web browser (e.g., Google Chrome).
   - Paste the copied path into the browser's URL bar and press Enter.

9. **Test and Observe**:
   - Examine how each image is displayed with different dimensions and attributes.
   - Click on the linked image to verify that it navigates to the external webpage.

10. **Enjoy Working with Images**:
    - Gain practical experience in using the `<img>` tag to incorporate images into web content.

### Example Output

When you open `imgTagsLab.html` in your web browser, you should see a webpage containing multiple images, each with different dimensions and attributes. Additionally, one of the images should be a clickable link to an external webpage. This lab allows you to explore and practice working with HTML image tags.

[Prev](formsHTML.md) | [Up](README.md) | [Next](tablesHTML.md)