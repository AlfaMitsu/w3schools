Add a 2 second animation for the <div> element, which changes the color from red to blue. Call the animation "example".

    div {
      width: 100px;
      height: 100px;
      background-color: red;
      animation-name: example;
      animation-duration: 2s;
    }
    
    @keyframes example {
      from {
        background-color: red;
      }
      to {
        background-color: blue;
      }
    }
