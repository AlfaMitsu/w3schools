Add a 2 second transition effect for background, and transform changes of the <div> element.

    div {
      width: 100px;
      height: 100px;
      background: red;
      transition: background 2s, transform 2s; /* Transition for background and transform changes */
    }
    
    div:hover {
      background: blue;
      transform: rotate(180deg);
    }
