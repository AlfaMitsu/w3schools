Using the transition shorthand property, specify width changes for the <div> element should have: "2" second duration, "ease-in-out" speed curve, and a "0.5" second delay before starting.

    div {
      width: 100px;
      height: 100px;
      background: red;
      transition: width 2s ease-in-out 0.5s; /* Transition for width changes */
    }
    
    div:hover {
      width: 400px;
    }
