Set a border for <img> elements that have a title attribute starting with blue.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        img[title^="blue"] {
          border: 5px solid red;
        }
      </style>
    </head>
    <body>
      <img src="klematis.jpg" title="blue flower">
      <img src="klematis2.jpg" title="purple flowers">
      <img src="klematis3.jpg" title="two blue flowers">  
    </body>
    </html>
