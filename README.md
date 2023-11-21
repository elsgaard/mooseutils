# mooseutils

A library for general utillity functions


## PrettyPrint Usage

Pretty print structs

```go
package main

import (
	"github.com/elsgaard/mooseutils"
)

type User struct {
	Name string
}

func main() {

	user := &User{Name: "Frank"}
	mooseutils.PrettyPrint(user)

}
```

