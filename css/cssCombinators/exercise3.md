Change the color of the first <p> element that is directly after a <div> element, to "red".

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        div + p {
          color: red;
        }
      </style>
    </head>
    <body>
      <div>
        <p>This is a paragraph.</p>
        <p>This is a paragraph.</p>
      </div>
      <p>This is a paragraph.</p>
      <p>This is a paragraph.</p>
    </body>
    </html>
