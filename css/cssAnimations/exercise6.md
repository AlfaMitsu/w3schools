Specify that the animation of the <div> element should have a "ease-in-out" speed curve.

    div {
      width: 100px;
      height: 100px;
      position: relative;
      background-color: red;
      animation-name: example;
      animation-duration: 4s;
      animation-timing-function: ease-in-out; /* Ease in and out */
    }
    
    @keyframes example {
      0%   { background-color: red; left: 0px; }
      50%  { background-color: yellow; left: 200px; }
      100% { background-color: red; left: 0px; }
    }
