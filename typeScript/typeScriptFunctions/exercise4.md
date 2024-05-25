Create a function with 2 parameters (myVar1 and myVar2,in that order), that are both strings.

    function myFunc(myVar1: string, myVar2?: string) {
      return myVar1 + (myVar2 || "");
    }
