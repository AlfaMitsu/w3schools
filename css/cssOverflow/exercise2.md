Specify that the overflowing text in the <div> element should not be visible, not even with a scroll bar.

    <!DOCTYPE html>
    <html>
    <head>
      <style>
        .intro {
          width: 200px;
          height: 70px;
          overflow: hidden; /* Hide overflowing content */
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
