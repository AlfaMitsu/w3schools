The image border needs a border-image-repeat value, insert one of the legal values.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        div {
          border-image-source: url(border.png);
          border-image-repeat: round;
          border-image-slice: 30;
        }
      </style>
    </head>
    <body>
      <div>This is a div element. It has some text.</div>
    </body>
    </html>
