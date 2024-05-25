Specify that Person.name can only be accessed within the class, but that the method Person.getName() can be accessed anywhere:

    class Person {
      private name: string;
    
      public constructor(name: string) {
        this.name = name;
      }
    
      public getName(): string {
        return this.name;
      }
    }
