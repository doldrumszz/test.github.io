<!DOCTYPE html>
<html>
  <head>
    <title>Cat Popup</title>
    <style>
      /* Style the button */
      button {
        padding: 10px;
        font-size: 20px;
      }
    </style>
  </head>
  <body>
    <button onclick="showCat()">Click me to see a cat!</button>

    <script>
      function showCat() {
        // Create a new image element
        var catImg = document.createElement("img");

        // Set the image source to a cat picture
        catImg.src = "https://placekitten.com/200/200";

        // Append the image to the body of the page
        document.body.appendChild(catImg);
      }
    </script>
  </body>
</html>
