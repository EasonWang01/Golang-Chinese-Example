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

結果如下圖：

{% file src=".gitbook/assets/screen-shot-2018-08-30-at-4.04.58-pm \(1\).png" %}

