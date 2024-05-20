Add a fname parameter of type string to myFunction.

    package main
    
    import "fmt"
    
    func myFunction(fname string) {
        fmt.Printf("%v Doe", fname)
    }
    
    func main() {
        myFunction("John")
    }
