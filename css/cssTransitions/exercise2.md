Specify that the transition of the <div> element should have a "ease-in-out" speed curve.

    div {
      width: 100px;
      height: 100px;
      background: red;
      transition: width 2s 
      transition-timing-function: ease-in-out; /* Transition with ease-in-out speed curve */
    }
    
    div:hover {
      width: 300px;
    }
