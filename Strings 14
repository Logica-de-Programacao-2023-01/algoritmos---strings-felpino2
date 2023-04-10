package main

import (
	"bufio"
	"fmt"
	"os"
	"strconv"
)

func main() {
	scanner := bufio.NewScanner(os.Stdin)
	fmt.Println("Digite uma string ")
	scanner.Scan()
	frase1 := scanner.Text()
	i, err := strconv.Atoi(frase1)
	cresc := true
	if err != nil {
		fmt.Println("A string não é uma sequência. ")
	}
	for i = 0; i < len(frase1)-1; i++ {
		if frase1[i+1] > frase1[i] {
			cresc = false
		}
	}
	if cresc == true {
		fmt.Println("A string é uma sequência decrescente. ")
	} else {
		fmt.Println("A string n é uma sequência decrescente")
	}
}
