package main

import (
	"bufio"
	"fmt"
	"os"
	"strings"
)

func main() {
	scanner := bufio.NewScanner(os.Stdin)

	fmt.Println("Digite uma frase ")
	scanner.Scan()
	frase1 := scanner.Text()
	fmt.Println(strings.Count(frase1, " ") + 1)
}
