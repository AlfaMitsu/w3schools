Change the color of all <p> elements, that are descendants of <div> elements, to "red".

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        div p {
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
