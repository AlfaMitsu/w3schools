Use the correct background property to make the background image NOT scroll with the rest of the page.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        body {
          background-image: url("img_tree.png");
          background-attachment: fixed;
        }
      </style>
    </head>
    <body>
      <h1>This is a heading</h1>
      <p>This is a paragraph</p>
      <p>This is a paragraph</p>
    </body>
    </html>
