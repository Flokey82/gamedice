# gamedice: Simple dice rolling

This package implements a simple dice roller for games like Dungeons & Dragons and other RPGs that use all kinds of dice (D4, D8, ..., D20, etc.).

## TODO

* add lexical parser for dice notation (maybe)
* custom rand source

## Usage

```go
package main

import (
	"fmt"

	"github.com/Flokey82/gamedice"
)

func main() {
	fmt.Println(gamedice.Roll(3, gamedice.D4, gamedice.D12))
}
```
