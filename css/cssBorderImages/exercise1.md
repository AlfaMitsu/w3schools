Give the div element an image border. Use the short hand property to define the details of the image border.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        div {
          border: 10px solid transparent;
          border-image: url(border.png) 30 round;
        }
      </style>
    </head>
    <body>
      <div>This is a div element. It has some text.</div>
    </body>
    </html>
