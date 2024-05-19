Specify that the animation of the <div> element should have a "1" second delay before starting.

    div {
      width: 100px;
      height: 100px;
      position: relative;
      background-color: red;
      animation-name: example;
      animation-duration: 2s;
      animation-delay: 1s; /* Add a 1-second delay */
    }
    
    @keyframes example {
      0%   { background-color: red; left: 0px; }
      50%  { background-color: yellow; left: 200px; }
      100% { background-color: red; left: 0px; }
    }
