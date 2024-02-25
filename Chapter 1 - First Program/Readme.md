# GoLang First Program - Hello, World

In this tutorial, we will write a simple "Hello, World!" program in GoLang.

## Explanation of the Code

- **`package main`**: This line defines the package name. Every Go file starts with a package declaration. Packages are Go's way of organizing and reusing code. The `main` package is special because it tells Go that this file will be the entry point of the program. Only the `main` package can contain the `main` function, which is where execution of the program starts.
- **`import "fmt"`**: This line imports the `fmt` package, which contains functions for formatted I/O (Input/Output) operations. Here, you're using it to print text to the console.
- **`func main() { ... }`**: This defines the `main` function. As mentioned, the `main` function is the entry point of your Go program. The braces `{ }` enclose the body of the function.
- **`fmt.Println("Hello, World!")`**: Inside the `main` function, this line calls the Println function from the fmt package. Println stands for "print line", and it outputs the string "Hello, World!" to the console, followed by a newline character.

## Run the Program

Save your file with a `.go` extension, for example, `hello.go`. Open a terminal or command prompt, navigate to the directory where your file is saved, and run the program by typing `go run hello.go`. You should see the output `Hello, World!` printed to the console.

## Process

When you run the program using `go run`, the Go compiler compiles the code into an executable binary, and then immediately runs that binary.
