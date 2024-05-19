Add the following 5 steps to the animation "example" (using 0%, 25%, 50%, 75%, and 100%):

0% - Set left position to "0px", top position to: "0px"
25% - Set left position to "0px", top position to: "200px"
50% - Set left position to "200px", top position to: "200px"
75% - Set left position to "200px", top position to: "0px"
100% - Set left position to "0px", top position to: "0px"

    div {
      width: 100px;
      height: 100px;
      position: relative;
      background-color: red;
      animation-name: example;
      animation-duration: 4s;
      animation-iteration-count: infinite; /* Optional: Repeat the animation infinitely */
    }
    
    @keyframes example {
      0%   {
        left: 0px;
        top: 0px;
      }
      25%  {
        left: 0px;
        top: 200px;
      }
      50%  {
        left: 200px;
        top: 200px;
      }
      75%  {
        left: 200px;
        top: 0px;
      }
      100% {
        left: 0px;
        top: 0px;
      }
    }
