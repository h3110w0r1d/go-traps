1.
```go
package main

func main() {
    b := make([]int, 3)

    b = append(b, 1)

    c := append(b, 1, 2)

    d := append(b, 2, 3)
    
    /**
     * Questions:
     *
     * 1. What is the capacity of b?
     * 2. What is c?
     * 3. What is d?
     */
}
```
