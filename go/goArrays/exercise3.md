Change the value from "Volvo" to "Opel", in the cars array.

    package main
    
    import "fmt"
    
    func main() {
        var cars = [4]string{"Volvo", "BMW", "Ford", "Mazda"}
        cars[0] = "Opel"
    
        fmt.Println(cars)
    }
