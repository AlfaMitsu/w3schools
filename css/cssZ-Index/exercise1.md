Both the header and the paragraph are positioned at the top of the page.

Make sure that the header is placed on top of the paragraph.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        #mytitle {
          position: absolute;
          top: 0;
          z-index: 1;  /* Ensure the header is on top */
        }
        #myintro {
          position: absolute;
          top: 50px;   /* Adjust as needed */
          z-index: 0:
        }
      </style>
    </head>
    <body>
      <h1 id="mytitle">This is a heading</h1>
      <p id="myintro">This is a paragraph</p>
    </body>
    </html>
