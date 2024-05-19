Set the background color to "red" for <a> elements that have a target attribute with the value "_blank".

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        a[target="_blank"] {
          background-color: red;
        }
      </style>
    </head>
    <body>
      <a href="https://w3schools.com">w3schools.com</a>
      <a href="http://disney.com" target="_blank">Disney.com</a>
      <a href="http://wikipedia.org" target="_top">wikipedia.org</a>
    </body>
    </html>
