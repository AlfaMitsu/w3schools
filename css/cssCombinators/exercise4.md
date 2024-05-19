Change the color of the <p> elements that are siblings of a <div> element, to "red".

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        div ~ p {
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
