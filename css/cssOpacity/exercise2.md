Use CSS to "remove" the transparency of the image when the user mouse over the image.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        img {
          opacity: 0.4;
        }
        img:hover {
          opacity: 1;
        }
      </style>
    </head>
    <body>
      <img src="klematis.jpg" width="150" height="113">
    </body>
    </html>
