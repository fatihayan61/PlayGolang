# Play with Golang


```go
package main

import (
	"golang.org/x/tour/pic"
)

func Pic(dx, dy int) [][]uint8 {
	res := make([][]uint8, dy)

	for i := 0; i < dy; i++ {
		res[i] = make([]uint8, dx)
		for j := range a[i] {
			res[i][j] = uint8((i*j*i*j/2)*(j*i*j*i/2))
		}

	}
	return res
}

func main() {
	pic.Show(Pic)
}
```
[Playground](https://go.dev/play/p/4yOqNoZbp_7)
