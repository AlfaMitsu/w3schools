Set the background-color to red, of any <input> element that are in focus.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        input:focus {
          background-color: red;
        }
      </style>
    </head>
    <body>
    
    <form>
      Name:
      <input type="text" name="fname">
      Age:
      <input type="text" name="age">
    </form>
    
    </body>
    </html>
