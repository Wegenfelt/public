## fishandchips

### Instructions

Write a function called `FishAndChips()` that takes an `int` and returns a `string`.

- If the number is divisible by 2, print `fish` followed by a newline `\n`.
- If the number is divisible by 3, print `chips` followed by a newline `\n`.
- If the number is divisible by 2 and 3, print `fish and chips` followed by a newline `\n`.

### Expected function

```go
func FishAndChips(n int) string {

}
```

### Usage

Here is a possible program to test your function:

```go
package main

import (
        "fmt"
        "piscine"
)

func main() {
        fmt.Println(piscine.FishAndChips(4))
        fmt.Println(piscine.FishAndChips(9))
        fmt.Println(piscine.FishAndChips(6))
}
```

And its output:

```go
fish$
$
chips$
$
fish and chips$
$
```