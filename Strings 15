package main

import (
	"bufio"
	"fmt"
	"os"
	"strings"
)

func main() {
	scanner := bufio.NewScanner(os.Stdin)
	fmt.Println("Digite uma string em letra minúscula e sem acentos ")
	scanner.Scan()
	frase1 := scanner.Text()
	frase1 = strings.ReplaceAll(frase1, "a", "*")
	frase1 = strings.ReplaceAll(frase1, "e", "*")
	frase1 = strings.ReplaceAll(frase1, "i", "*")
	frase1 = strings.ReplaceAll(frase1, "o", "*")
	frase1 = strings.ReplaceAll(frase1, "u", "*")
	fmt.Println(frase1)
}
