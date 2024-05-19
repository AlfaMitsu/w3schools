Force a scroll bar to the <div> element with class="intro".

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        .intro {
          width: 200px;
          height: 70px;
          overflow: scroll; /* Add a scrollbar when content overflows */
        }
      </style>
    </head>
    <body>
      <div class="intro">
        Lorem ipsum dolor sit amet,
        consectetur adipiscing elit.
        Phasellus imperdiet, nulla et dictum interdum,
        nisi lorem egestas odio,
        vitae scelerisque enim ligula venenatis dolor.
      </div>
    </body>
    </html>
