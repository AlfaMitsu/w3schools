Position the two background images in each top corner.

img1.gif at the left and img2.gif at the right.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        body {
          background-image: url('img1.gif'), url('img2.gif');
          background-repeat: no-repeat, no-repeat;
          background-position: top left, top right;
        }
      </style>
    </head>
    <body>
      <h1>This is a heading</h1>
      <p>This is a paragraph</p>
      <p>This is a paragraph</p>
    </body>
    </html>
