# Introduction to JavaScript and DOM Manipulation

## Objectives

Write basic JavaScript functions.
Manipulate the DOM dynamically.
Respond to user interactions.

## Instructions

- Create a script.js file and link it to a HTML.
- Structure the document using DOCTYPE, html, head, and body.

>[!NOTE]
>  - Write JavaScript that:
>  - Changes text content dynamically.
>  - Modifies CSS styles via JavaScript.
>  - Adds or removes an element when a button is clicked.


# Tasks
- Create a well-structured HTML5 document.
- Use at least 5 different HTML elements.
- Ensure semantic correctness.

<!DOCTYPE html>
<html>
  <head>
    <title>Dynamic Content</title>
    <style>
      /* Add some basic styling to the page */
      body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
      }
      h1 {
        color: #333;
      }
      button {
        margin: 10px;
      }
    </style>
  </head>
  <body>
    <h1 id="content">Welcome page1>
    <button id="changeContent">Change Content</button>
    <button id="addElement">Add Element</button>
    <button id="removeElement">Remove Element</button>
    <p id="output"></p>

    <script src="script.js"></script>
  </body>
</html>
In this example, i created a well-structured HTML5 document with a <!DOCTYPE html> declaration, <html>, <head>, and <body> elements. We have used different HTML elements such as <h1>, <button>, and <p> to create a semantic structure.
We have also added some basic styling to the page using the <style> element in the <head> section. We have defined the font family, margin, and padding for the body element, as well as the color for the <h1> element and the margin for the buttons.
In the <body> section, we have added three buttons with different functions: “Change Content”, “Add Element”, and “Remove Element”. We have also added a <p> element with an id of “output” to display any output from the JavaScript code.
Finally, we have linked the script.js file to the HTML document using the <script> element in the <body> section. This will allow us to add JavaScript code to the page that can modify the content dynamically, change CSS styles via JavaScript, and add or remove elements when the buttons are clicked.
Happy Coding! 💻✨
