# Respostas

1. O que é um espaço em branco?
    R: Espaço em branco é o espaço entre caracteres, composto de caracteres de espaço, tabulação e quebra de linha.
2. O que é um comentário? Quais são as duas maneiras de escrever um comentário?
    R: Um comentário é uma seção de código ignorada pelo compilador, que pode ser usada como uma nota para qualquer pessoa que leia o código. Os dois tipos de comentários são: `//` (que vai até o final da linha) e `/* */`.
3. Nosso programa começou com `package main`. Os arquivos do pacote `fmt` devem começar com qual instrução?
    R: Os arquvios do pacote `fmt` devem começar com `package fmt`.
4. Usamos a função `Println` definida no pacote `fmt`. Se quiséssemos usar a função `Exit` do pacote `os`, o que você deveria fazer?
    R: Para usar a função `Exit` do pacote `os`, seria necessário importar o pacote `os`: `import: "os"` e, então chamá-la com .: `os.Exit()`
5. Modifique o programa que escrevemos de modo que, em vez de exibir `Hello, World`, ele apresente `Hello, my name is`, seguido de seu nome.
    R: ```
       package main

       import "fmt"

       func main() {
          fmt.Println("Hello, my name is Pery!")
       }
       ```
