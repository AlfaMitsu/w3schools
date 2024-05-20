Print "1" if x is equal to y, print "2" if x is greater than y, otherwise print "3".

    package main
    
    import "fmt"
    
    func main() {
        var x = 50
        var y = 50
        
        if x == y {
            fmt.Print("1")
        } else if x > y {
            fmt.Print("2")
        } else {
            fmt.Print("3")
        }
    }
