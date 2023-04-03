<!DOCTYPE html>
<html>
  <head>
    <title>Change Button Color</title>
    <style>
      /* Style the button */
      button {
        padding: 10px;
        font-size: 20px;
        background-color: blue;
        color: white;
        border: none;
      }
      
      /* Style the button when it's clicked */
      button.clicked {
        background-color: green;
      }
    </style>
  </head>
  <body>
    <button onclick="changeColor()">Click me to change color!</button>

    <script>
      function changeColor() {
        // Get the button element
        var button = document.getElementsByTagName("button")[0];
        
        // Add the "clicked" class to the button
        button.classList.add("clicked");
      }
    </script>
  </body>
</html>
