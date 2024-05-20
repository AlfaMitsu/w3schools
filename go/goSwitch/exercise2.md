Complete the switch statement, and add the correct keyword at the end to specify some code to run if there is no case match in the switch statement.

    package main
    
    import "fmt"
    
    func main() {
        var day = 4
        switch day {
        case 1:
            fmt.Print("Saturday")
        case 2:
            fmt.Print("Sunday")
        default:
            fmt.Print("Weekday")
        }
    }
