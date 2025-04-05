# Introduction to CSS

## Objectives
Link an external CSS file to an HTML document.
Apply basic styling using selectors.
Use colors, fonts, and spacing effectively.

## Instructions

Create a style.css file.
Apply CSS to a HTML page.
Style elements using:
Classes and IDs.
Color and typography.
Margins, paddings, and borders.

>[!NOTE]
>  - Include at least:
>  - Use of 3 selectors
>  - Style an image
>  - Margin, Padding & Borders
>  - Different font

# Tasks
 - Link an external CSS file.
 - Apply at least 3 different selectors.
 - Improve readability and aesthetics.

Happy Coding! 💻✨


SOLUTION TO THE ABOVE ASSIGNMENT

!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="felix.css">
    <title>basic css styles</title>
</head>

<body>
    
  <div id="header">
    <h1>Welcome to CSS</h1>
  </div>
  <div class="container">
    <p>This is a paragraph of text.</p>
    <img src="image.jpg" alt="An image">
  </div>
</body>
</html>



EXTERNAL CSS

/* Style an element using a class */
.container {
    background-color: #f2f2f2;
    padding: 20px;
    margin: 20px;
  }
  
  /* Style an element using an ID */
  #header {
    background-color: #333;
    color: #fff;
    padding: 10px;
    text-align: center;
  }
  
  /* Style an image */
  img {
    width: 100%;
    height: auto;
    margin: 20px;
    border: 1px solid #ddd;
    padding: 10px;
  }

  /* Use a different font */
body {
    font-family: Arial, sans-serif;
  }
  
  /* Use colors */
  h1 {
    color: #00698f;
  }
  
  /* Use margins, paddings, and borders */
  p {
    margin-bottom: 20px;
    padding: 10px;
    border-bottom: 1px solid #ddd;
  }
  

