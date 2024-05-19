Remove the default underline style for links, but add a underline when you mouse over a link (hover).

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        /* unvisited link */
        a:link {
          text-decoration: none;
        }
    
        /* visited link */
        a:visited {
          text-decoration: none;
        }
    
        /* mouse over link */
        a:hover {
          text-decoration: underline;
        }
      </style>
    </head>
    <body>
      <h1>This is a heading</h1>
      <p>This is a paragraph</p>
      <a href="http://w3schools.com">This is a link</a>
    </body>
    </html>
