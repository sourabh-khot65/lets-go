# Variables in Go

Variables are like containers that store data in your program. Let's learn how to use them in Go!

## Basic Variable Declaration

```go
// Declaring a variable
var name string = "John"

// Shorter way (Go will guess the type)
age := 25

// Multiple variables
var (
    city    = "New York"
    country = "USA"
)
```

## Common Variable Types

- `string` - for text
- `int` - for whole numbers
- `float64` - for decimal numbers
- `bool` - for true/false values

## Example

```go
package main

import "fmt"

func main() {
    // String variable
    name := "Alice"
    
    // Number variables
    age := 30
    height := 1.75
    
    // Boolean variable
    isStudent := true
    
    // Printing variables
    fmt.Println("Name:", name)
    fmt.Println("Age:", age)
    fmt.Println("Height:", height)
    fmt.Println("Is Student:", isStudent)
}
```

## Key Points to Remember

1. Go is statically typed - once you declare a variable's type, it can't change
2. Use `:=` for short variable declaration
3. Use `var` keyword for explicit declaration
4. Variables must be used after declaration (Go will give an error if you don't)

## Practice Exercise

Try creating a program that:
1. Declares variables for your name, age, and favorite color
2. Prints them in a nice format 