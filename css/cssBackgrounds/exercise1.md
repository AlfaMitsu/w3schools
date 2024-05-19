Add two background images to the <body> element.

img1.gif and img2.gif.

Make sure that img2.gif is displayed on top of img1.gif.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        body {
          background-image: url('img2.gif'), url('img1.gif');
        }
      </style>
    </head>
    <body>
      <h1>This is a heading</h1>
      <p>This is a paragraph</p>
      <p>This is a paragraph</p>
    </body>
    </html>
