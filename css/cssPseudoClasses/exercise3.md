Set the background-color to red, of any <p> element that are the first child of any element.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        p:first-child {
          background-color: red;
        }
      </style>
    </head>
    <body>
      <p>This is a paragraph.</p>
      <p>This is a paragraph.</p>
    </body>
    </html>
