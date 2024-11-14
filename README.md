# go-modules
----
# go-aes
```go
package main

import (
	"fmt"
	. "github.com/not-filepile/go-util/aes"
)

func main() {
	K = []byte("testkeytestkey12")
	fmt.Println(Enc("test")) // "XNOfQ++jLxXnjQDiiXPuUrXYPSdk3ABJfOOxp60aJ+E="
	fmt.Println(Dec("XNOfQ++jLxXnjQDiiXPuUrXYPSdk3ABJfOOxp60aJ+E=")) // "test"
}
```
