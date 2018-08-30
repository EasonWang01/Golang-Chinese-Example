# Fmt 模組

```go
package main

import (
	"fmt"
)

type person struct {
	height int
	weight int
}

func main() {
	Jason := person{178, 72}

	fmt.Print(Jason)
	fmt.Println(Jason)        // 不換行
	fmt.Printf("%v\n", Jason) // 可選擇使用什麼格式來印
	fmt.Printf("%+v\n", Jason)
}

```

