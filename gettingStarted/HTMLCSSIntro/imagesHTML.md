Certainly! Here's a tutorial on using the `<img>` tag in HTML to display images on web pages.

### HTML Image (`<img>`) Tag Tutorial

The `<img>` tag is a self closing HTML tag. It is used to embed images in web pages. It's a fundamental element for presenting visual content to website visitors. Here's how to use it effectively:

#### 1. **Basic Image Tag**

To display an image on a web page, you need to use the `<img>` tag. The `src` attribute specifies the image file's source (URL or file path).

```html
<img src="image.jpg" alt="Image Description">
```

- `<img>`: This is the image tag.
- `src`: This attribute defines the image source. It can be a URL (e.g., `https://www.example.com/image.jpg`) or a relative file path (`images/image.jpg`).
- `alt`: This attribute provides alternative text for the image. It's important for accessibility and SEO. Include a brief description of the image.

#### 2. **Setting Image Dimensions**

You can specify the image's width and height using the `width` and `height` attributes. This helps browsers allocate space for the image before it loads.

```html
<img src="../../images/QuantumLeapAcademy.png" alt="Image Description" width="300" height="200">
```

- `width`: Defines the image's width in pixels.
- `height`: Defines the image's height in pixels.

#### 3. **Responsive Images**

For responsive web design, you can use the `width` attribute with a percentage value to make images adjust to different screen sizes.

```html
<img src="../../images/QuantumLeapAcademy.png" alt="Image Description" width="100%" height="auto">
```

- `width="100%"`: Makes the image width adapt to the container's width while maintaining its aspect ratio.
- `height="auto"`: Automatically adjusts the height proportionally.

#### 4. **Images in Different Formats**

The `<img>` tag supports various image formats, such as JPEG, PNG, GIF, and SVG. You should choose the format that suits your image content and quality requirements.

```html
<img src="image.png" alt="PNG Image">
<img src="image.gif" alt="GIF Image">
<img src="image.svg" alt="SVG Image">
```

#### 5. **Linking Images**

You can make images clickable by wrapping them in an `<a>` (anchor) tag. This is commonly used for image galleries or linking images to other pages or resources.

```html
<a href="page.html">
  <img src="image.jpg" alt="Linked Image">
</a>
```

#### 6. **Image Accessibility**

Always provide descriptive `alt` text for images. It assists screen readers for visually impaired users and improves SEO. Avoid using images for critical content; use text whenever possible.

#### 7. **Lazy Loading (HTML5)**

To improve page loading speed, you can use the `loading` attribute with the value `"lazy"` to load images only when they are visible in the user's viewport. This is beneficial for long web pages with many images.

```html
<img src="image.jpg" alt="Image Description" loading="lazy">
```

#### 8. **Images from External Sources**

When using images from external sources, make sure you have permission or the necessary rights to display them. Always provide the correct attribution if required.

#### Example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>HTML Image Tag</title>
  </head>
  <body>
    <h1>My Image Gallery</h1>
    <img src="image1.jpg" alt="Beautiful Sunset">
    <img src="image2.png" alt="Colorful Flowers" width="400" height="300">
    <a href="page.html">
      <img src="image3.jpg" alt="Linked Image">
    </a>
  </body>
</html>
```

In this tutorial, you've learned how to use the `<img>` tag in HTML to display images on web pages. You can control image dimensions, ensure accessibility, and link images to other resources. Images play a crucial role in web design, making content visually engaging and informative.


[prev](HTMLlab4.md) | [Up](README.md) | [Next](HTMLlab5.md)