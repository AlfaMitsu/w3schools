Declare an object kindPerson from the Person interface, where all the properties are optional:

    interface Person {
        age?: number;
        firstName?: string;
        lastName?: string;
    }
    
    let kindPerson: Partial<Person> = {};
