Insert the image "smiley.gif" before, and after any <p>element, using the ::before and ::after pseudo-elements.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        p::before {
          content: url('smiley.gif');
        }
        p::after {
          content: url('smiley.gif');
        }
      </style>
    </head>
    <body>
    
    <p>This is a paragraph.</p>
    <p>This is a paragraph.</p>
    
    </body>
    </html>
