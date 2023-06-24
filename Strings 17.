package main

import (
	"fmt"
	"strings"
)

func main() {
	var value string
	fmt.Print("Escreva algo: ")
	fmt.Scan(&value)

	for _, x := range value {
		count := strings.Count(value, string(x))
		if count == 1 {
			fmt.Println(string(x))
		}
	}
}
