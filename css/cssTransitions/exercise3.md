Specify that the transition of the <div> element should have a "0.5" second delay before starting.

    div {
      width: 100px;
      height: 100px;
      background: red;
      transition: width 2s;
      transition-delay: 0.5s; /* Delay the transition by 0.5 seconds */
    }
    
    div:hover {
      width: 300px;
    }
