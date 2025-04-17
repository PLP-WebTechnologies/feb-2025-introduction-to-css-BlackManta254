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
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My CSS Practice</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <h1 class="main-heading">Welcome to My Web Page</h1>

  <p id="intro">This is a simple introduction to CSS styling.</p>

  <img src="https://via.placeholder.com/200" alt="Sample Image" class="styled-image" />

  <div class="content-box">
    <p>This is a styled content box using margin, padding, and border.</p>
  </div>

</body>
</html>

/* 1. Class selector */
.main-heading {
  font-family: 'Georgia', serif;
  color: #2c3e50;
  text-align: center;
}

/* 2. ID selector */
#intro {
  color: #34495e;
  font-size: 18px;
  margin: 20px;
}

/* 3. Element selector + styling an image */
img.styled-image {
  border: 3px solid #3498db;
  padding: 10px;
  margin: 20px auto;
  display: block;
  border-radius: 10px;
}

/* Styling a content box with margin, padding, border */
.content-box {
  background-color: #ecf0f1;
  border: 2px dashed #7f8c8d;
  padding: 20px;
  margin: 30px;
  font-family: Arial, sans-serif;
}

/* style.css */

/* Style the body of the page */
body {
    font-family: 'Arial', sans-serif; /* Apply a sans-serif font */
    background-color: #f4f4f9; /* Light background color */
    margin: 0;
    padding: 0;
}

/* Style the header */
#main-header {
    text-align: center; /* Center the header text */
    background-color: #333; /* Dark background */
    color: white; /* White text */
    padding: 20px; /* Add padding */
    margin-bottom: 20px; /* Add margin at the bottom */
}

/* Style paragraphs */
p {
    line-height: 1.6; /* Add space between lines of text */
    color: #555; /* Dark gray color */
    margin: 15px; /* Add margin around paragraphs */
}

/* Style the image */
img {
    width: 100%; /* Make the image responsive */
    max-width: 500px; /* Limit the image width */
    height: auto; /* Maintain aspect ratio */
    border-radius: 10px; /* Round the corners of the image */
    display: block;
    margin: 20px auto; /* Center the image */
}

/* Style a class for specific text styling */
.highlight {
    color: #e74c3c; /* Red color */
    font-weight: bold; /* Bold text */
}

/* Style a footer */
footer {
    text-align: center; /* Center the footer text */
    padding: 10px;
    background-color: #333;
    color: white;
    position: fixed;
    width: 100%;
    bottom: 0;
}

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Styled Page</title>
    <link rel="stylesheet" href="style.css"> <!-- Link the external CSS file -->
</head>
<body>

    <header id="main-header">
        <h1>Welcome to My Web Page</h1>
    </header>

    <p>This is a paragraph of text that will be styled using CSS. The font and color of this text have been customized for better readability.</p>

    <p class="highlight">This text is highlighted using a class selector. It's bold and red!</p>

    <img src="https://via.placeholder.com/500" alt="Example Image">

    <footer>
        <p>Copyright © 2025</p>
    </footer>

</body>
</html>

