Complete the Generic:

    function createPair<typeX, typeY>(x: typeX, y: typeY): [typeX, typeY] {
      return [x, y];
    }
    
    console.log(createPair<string, number>('Meaning', 42));
