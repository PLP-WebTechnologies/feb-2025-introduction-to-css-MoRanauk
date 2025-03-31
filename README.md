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





###ANSWER:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Page</title>
    <link rel="stylesheet" href="style.css"> <!-- Linking the external CSS -->
</head>
<body>
    <header id="main-header">
        <h1>Beauty in CSS</h1>
    </header>
    <section class="content">
        <p>In cascading hues, the page does gleam,<br>
            A canvas of beauty, a coder's dream.<br>
            With margins so soft, and borders that flow,<br>
            Typography whispers, as colors glow.<br></p>
        <img src="https://www.oddbird.net/assets/images/blog/2020/lynnandtonic-960w.webp" alt="Example Image" class="styled-image">
    </section>
    <footer>
        <p>&copy; 2025 Styled Page Example</p>
    </footer>
</body>
</html>



##style.css
/* General Page Styling */
body {
    font-family: 'Arial', sans-serif; /* Different font for the body text */
    background-color: #f4f4f4;
    color: #333;
    margin: 0;
    padding: 0;
}

/* Styling using an ID */
#main-header {
    background-color: #4CAF50;
    color: white;
    text-align: center;
    padding: 20px;
    border-bottom: 5px solid #3e8e41; /* Border */
}

/* Styling using a class */
.content {
    padding: 20px; /* Padding */
    margin: 20px; /* Margin */
    border: 2px dashed #ccc; /* Border */
    background-color: white;
    border-radius: 10px;
}

/* Styling an image */
.styled-image {
    display: block;
    margin: 0 auto;
    width: 300px;
    height: auto;
    border: 5px solid #4CAF50; /* Border */
    border-radius: 15px; /* Rounded corners */
}

/* Styling a tag (element selector) */
footer {
    background-color: #333;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}
