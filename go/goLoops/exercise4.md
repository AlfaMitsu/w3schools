In the following loop, when the value is "4", jump directly to the next value.

    package main
    
    import "fmt"
    
    func main() {
        for i := 0; i < 10; i++ {
            if i == 4 {
                continue
            }
            fmt.Println(i)
        }
    }
