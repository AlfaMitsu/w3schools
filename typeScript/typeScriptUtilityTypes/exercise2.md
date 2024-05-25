Declare an object kindPerson from the Person interface, where all the properties are required.

    interface Person {
        age: number;
        firstName: string;
        lastName: string;
    }
    
    let kindPerson: Required<Person> = {
        age: 1800,
        firstName: "Santa",
        lastName: "Claus"
    };
