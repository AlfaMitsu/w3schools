Stop the loop if for is 5.

    package main
    
    import "fmt"
    
    func main() {
        for i := 0; i < 10; i++ {
            if i == 5 {
                break
            }
            fmt.Println(i)
        }
    }
